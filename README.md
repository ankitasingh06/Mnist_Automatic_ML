# Mnist_Automatic_ML

Hello Reader!!

As in this fast and growing IT world , we want everything to be available in just one click.And in MlOps world, The hardest part of machine learning today is deploying and maintaining accurate models, as it requires constant access to new data to update them and improve their accuracy.Human error in continuous checking and maintaining may cause huge loss.

MLOps is a practice for collaboration and communication between data scientists and operations professionals to help manage production ML lifecycle.

Using Human mind(in creating model) and then Train the model so that they will work same as humans (the way human use their intelligence) is Machine Learning.

And when we integrate ML with DevOps so that continuous integration and continuous development will work automatically is the examlpe of MlOps.

Here is one Project based on this MlOps problem, and I have taken Mnist dataset. and tried to automate its training and get the accuracy upto 95%.

Aim:- After training model , Our model should automatically learn and increase its accuracy.

Problem Statement :-

1. Create container image that’s has Python3 and Keras or numpy installed using dockerfile .

2. When we launch this image, it should automatically starts train the model in the container.

3. Create a job chain of job1, job2, job3, job4 and job5 using build pipeline plugin in Jenkins .

4. Job1 : Pull the Github repo automatically when some developers push repo to Github.

5. Job2 : Jenkins should launch the container with the help of our customized image.

6. Job3 : Train your model and predict accuracy or metrics.

7. Job4 : if metrics accuracy is less than 80% , then tweak the machine learning model architecture.

8. Job5: Retrain the model or notify that the best model is being created

9. Create One extra job job6 for monitor : If container where app is running. fails due to any reason then this job should automatically start the container again from where the last trained model left.



"FOR  DETAILED SOLUTION , Please visit my linkedin Article."
