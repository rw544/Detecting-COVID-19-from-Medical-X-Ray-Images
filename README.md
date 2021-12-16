# Detecting-COVID-19-from-Medical-X-Ray-Images
Detecting COVID-19 from Medical X-Ray Images (CS 4701 - Practicum in AI - Project)
-------------------------------------------------------------------------------------------------------------------------------

Since we are living in a time with an ongoing COVID-19 pandemic, I decided to work on this project because
I thought this was the most relevant to the current state of our society, and wanted to choose an AI tool
that could potentially improve efficiency in medical practice.

Without AI, to detect COVID-19, radiologists have to scan through each 2-D chest X-ray of all patients and classify each one. 
First, this process could be very time consuming, as it is critical that patients get their test results back immediately or 
within a reasonable timeframe so they can take action based on the result. Second, this process could lead to radiologists 
producing inaccurate predictions.

As my AI solution, I developed a deep learning model in Python that takes in a patient’s chest X-ray image and predicts whether
that patient is positive or negative for COVID-19, a binary classification problem. I constructed a web application using HTML 
and Flask that allows radiologists to input a patient’s chest X-ray image. As soon as they have uploaded an image and have hit 
the submit button, the image gets sent over to the trained machine learning model, and the prediction is then outputted
back to the radiologist.

For this project, I experimented with different hyperparameter values, such as the learning rate, the number of epochs
of the training process, and the optimizer type. With an optimally-chosen combination of hyperparameters, I was able 
to achieve an accuracy of approximately 95% on a held-out validation set of medical X-ray images.
