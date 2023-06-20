---
title: Breast Cancer
---

<img src="https://www.yourhealth.net.au/wp-content/uploads/2017/09/pink-ribbon-for-breast-cancer-awareness.jpg" width="300" alt="Breast Cancer">  
*pink ribbon*

For this project, I decided to take a different approach. Instead of creating a classification model, I implemented a K Means Clustering (KMC).

This is so as to visualize the causes of breast cancer in women.

<img src="{{site.baseurl}}/assets/images/3D plot.jpg">
*3D Breast cancer distibution using Plotly*

From the above diagram, it is obvious that the mean breast texture and perimeter are good indicators of malignant tumors.

**Other improvements**:
- use of PCA to get meaningful features before performing KMC
- use of cross-validation (Grid Search CV) to improve clustering

**Improvements to be made**:
- cross validating with classification methods to see how well clustering did
- cross-comparison with other clustering methods (e.g. Hirearchical Clustering, DBSCAN etc.)  
[github notebook](https://github.com/manish-cr/data-science-projects/tree/master/Breast%20Cancer)