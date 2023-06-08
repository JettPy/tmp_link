# tmp_link
https://drive.google.com/drive/u/1/folders/16u5-aGb3MpbVeOy6hA-E9NLcT8C4TqZ4

https://disk.yandex.ru/d/_3fYIFdw-QKIZA

https://disk.yandex.ru/d/SMvXi1ywzDxSsQ


Mean Absolute Error (MAE):
$MAE = \frac{1}{n} \sum_{i=1}^{n} |y_i - \hat{y_i}|$

Mean Squared Error (MSE):
$MSE = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y_i})^2$

Root Mean Squared Error (RMSE):
$RMSE = \sqrt{\frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y_i})^2}$

R-squared:
$R^2 = 1 - \frac{\sum_{i=1}^{n}(y_i - \hat{y_i})^2}{\sum_{i=1}^{n}(y_i - \bar{y})^2}$

где $\bar{y}$ - среднее значение зависимой переменной

Mean Absolute Percentage Error (MAPE):
$MAPE = \frac{1}{n} \sum_{i=1}^{n} \frac{|y_i - \hat{y_i}|}{|y_i|}$

Symmetric Mean Absolute Percentage Error (SMAPE):
$SMAPE = \frac{1}{n} \sum_{i=1}^{n} \frac{|y_i - \hat{y_i}|}{(|y_i| + |\hat{y_i}|)/2}$

Accuracy:
$Accuracy = \frac{TP + TN}{TP + FP + TN + FN}$

Precision:
$Precision = \frac{TP}{TP + FP}$

Recall:
$Recall = \frac{TP}{TP + FN}$

F1-score:
$F1 = 2 * \frac{Precision * Recall}{Precision + Recall}$

ROC-AUC:
ROC-кривая строится путем варьирования порога для принятия решения и вычисления False Positive Rate (FPR) и True Positive Rate (TPR) для каждого порога. Затем площадь под ROC-кривой вычисляется с помощью интеграла:

$AUC = \int_{0}^{1} TPR(FPR^{-1}(t)) dt$

где $FPR^{-1}(t)$ - обратная функция к функции FPR(t)

Confusion matrix:
Confusion matrix - это матрица, которая показывает, сколько объектов было классифицировано правильно, а сколько ошибочно. Она имеет вид:

| | Predicted Positive | Predicted Negative |
| --- | --- | --- |
| Actual Positive | True Positive (TP) | False Negative (FN) |
| Actual Negative | False Positive (FP) | True Negative (TN) |

где TP - количество истинно положительных результатов, TN - количество истинно отрицательных результатов, FP - количество ложно положительных результатов, FN - количество ложно отрицательных результатов.
