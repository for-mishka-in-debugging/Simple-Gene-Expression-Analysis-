# Simple-Gene-Expression-Analysis-
used public gene dataset to draw some conclusions 

What I tried & what I found:
I chose a publicly available RNA-Seq gene expression dataset with different cancer types. Because there were many (~20,000) genes, I reduced the dimensionality by selecting the 50 genes with highest variance across samples, assuming that genes that vary more are more likely to show differences between cancer types. I plotted expression distributions of one of the top genes across cancer types (e.g. BRCA and COAD), performed a t-test to check if the difference is statistically significant, and trained a simple logistic regression classifier to see how well the reduced data can predict the cancer type.
