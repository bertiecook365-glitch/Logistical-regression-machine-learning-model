# Logistical-regression-machine-learning-model
Constructing a logistical regression model to classify breast cancer cells

My goal here was to construct a logistical regression model from the ground up that could classify breast cancer cells to a high degree of accuracy. And compare this accuracy with other models.
I began by constructing simple 2 paramater, 4 instance set of data to build my model around and was debugging throughout. From there i upscaled to 3 dimension and adjusted code as needed. Then applied to the breast cancer data set which cause overflow issues. So i introduced clipping into the model to avoid dividing by 0 and overflow. The accuracy is measured on all of its training data so doesn't take into acount any extrapolating classifications.
