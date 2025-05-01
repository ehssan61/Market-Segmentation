# Market-Segmentation
The Online retail dataset was one of the ones that we used in our first group problem set project.
I included some parts of our prior analysis in this report.
Preprocessing:
In the preprocessing phase, the dataset was cleaned and transformed to compute RFM (Recency,
Frequency, Monetary) features for customer segmentation. Missing values in key fields like
CustomerID and Description were removed, and canceled transactions were filtered out using
invoice numbers that start with 'C'. Additionally, transactions with non-positive Quantity or
UnitPrice were excluded to ensure meaningful purchase data.