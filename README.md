# ML final project
---
Use model: SVM

total 1692 images

Preprocessing: gray scale => Resize to 64*64

Build 5 classifiers for each attributes.

Validation method:
* Holdout validation (HV)
* Cross validation (CV)

---
## take HP attribute for example

### kernel: linear

| validation method| HV(train) | HV(test) | CV |
| -------- | -------- | -------- | -------- |
| Score     | .830 | .167 | .162 |
| confusion matrix | |![](https://i.imgur.com/1VvOuad.png)  | ![](https://i.imgur.com/Zin8G2v.png) |

---

### kernel: poly

| validation method| HV(train) | HV(test) | CV |
| -------- | -------- | -------- | -------- |
| Score     | .649 | .191 | .173 |
| confusion matrix | | ![](https://i.imgur.com/eeoj6Ug.png)  | ![](https://i.imgur.com/e6qzaWq.png) |

---

### kernel: rbf

| validation method| HV(train) | HV(test) | CV |
| -------- | -------- | -------- | -------- |
| Score     | .364 | .177 | .189 |
|  confusion matrix | |![](https://i.imgur.com/VCFe0V1.png)  | ![](https://i.imgur.com/wqsBHRQ.png) |

---

### kernel: sigmoid

| validation method| HV(train) | HV(test) | CV |
| -------- | -------- | -------- | -------- |
| Score     | .188 | .169 | .172 |
|  confusion matrix | |![](https://i.imgur.com/HLzYuNd.png) | ![](https://i.imgur.com/PBEVmIB.png) |
