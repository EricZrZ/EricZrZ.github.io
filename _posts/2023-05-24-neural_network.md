# This is the title

Here's the table of contents:

1. TOC
{:toc}

## Neural Network

Some features of neural network
- Neural network is a particular kind of machine learning model
- Highly flexible and can solve wide range of the problems by adjusting the weights
- Stochastic gradient descent can provides a way to find weight parameter automatically



## The difference between loss and metric

**Loss:**

- Loss is to measure the model performance and then improve the model by adjusting the weights
- loss depends on the prediction and the correct labels
- Good choice of loss is easy for stochastic gradient descent to use.

<img src="/images/detailed_loop.jpg" width = "800" height = "280" alt="" align=center />

**Metric:**
 
- Human consumption
- To show the differece between prediction and actual value

## Confusion matrix

Confusion matrix is a popular method used to measure the performance of classification problem. 
The confusion matrix conposes four parts: true positive, false positive, false negative, and true negative, which is shown in the table below.

<table style="border-collapse: collapse; border: none; border-spacing: 0px;">
	<tr>
		<td style="padding-right: 3pt; padding-left: 3pt;">
		</td>
		<td colspan="2" style="text-align: center; vertical-align: top; padding-right: 3pt; padding-left: 3pt;">
			<b>Predicted Class </b>
		</td>
	</tr>
	<tr>
		<td rowspan="2" style="text-align: center; padding-right: 3pt; padding-left: 3pt;">
			<b>Ture Class</b>
		</td>
		<td style="text-align: center; padding-right: 3pt; padding-left: 3pt;">
			Ture Positive (TP)
		</td>
		<td style="text-align: center; padding-right: 3pt; padding-left: 3pt;">
			False Negative (FN)
		</td>
	</tr>
	<tr>
		<td style="text-align: center; padding-right: 3pt; padding-left: 3pt;">
			False Positive (FP)
		</td>
		<td style="text-align: center; padding-right: 3pt; padding-left: 3pt;">
			Ture Negative (TN)
		</td>
	</tr>
</table>

In addition, from the confusion matrix, we also can calculate the accuracy, precision, recall, and F1-Score.

Accuracy = (TP+TN)/(TP+TN+FP+FN)

Precision = TP/(TP+FP)

Recall = TP/(TP+FN)

F1-Score = 2*Precision*Recall/(Precision+Recall)

[Click here](https://www.geeksforgeeks.org/confusion-matrix-machine-learning/) for more details
