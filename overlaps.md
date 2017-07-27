# Overlaps
If you do any ChIP-seq analysis, it's just a matter of time before someone asks you for a Venn diagram showing the overlap between two or more sets. I dislike Venn diagrams, so here are the quickest ways to produce them so you can move onto more interesting analyses. These instructions use `R`, assuming you have already done your peakcalling.

## Gene List Overlaps

Coming soon.

## Peak Overlaps

Here, `Vennerable` is not as useful, since each peak does not have a unique character representation (and if you assign one, overlapping peaks will not have the same value). So we turn another package, `ChIPpeakAnno`.

Firstly, combine your peak files (as `GenomicRanges` objects) into a list, then pass this straight to `makeVennDiagram`:

```r
makeVennDiagram(list(peakset1, peakset2))
```