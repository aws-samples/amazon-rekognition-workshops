# Amazon Rekognition Custom Labels Workshop - Detect Woodpecker Holes in Utility Poles


## Step 1. 
From the [Rekognition Immersion day Pre-requisite](https://rekognition-immersionday.workshop.aws/rek_apis.html) launch the Cloudformation stack in the "Launch Amazon SageMaker Notebook Instance" section. 

**Note:** You don't need to do the "Download necessary notebooks" section on that page. 

## Step 2. 
Next we will Create a s3 bucket. 

As you create a model training job, you will save the following in an Amazon S3 bucket:
- The model training data
- Model artifacts, which Amazon SageMaker generates during model training

You can store the training data and artifacts in a single bucket or in two separate buckets. For exercises in this guide, one bucket is sufficient. You can use existing buckets or create new ones.

Follow the instructions in [Create a Bucket](https://docs.aws.amazon.com/AmazonS3/latest/userguide/create-bucket-overview.html) in the Amazon Simple Storage Service Console User Guide. Include sagemaker in the bucket name; for example, sagemaker-datetime.

## Step 3. 

Click on "Open JupyterLab"

![Open Instance](readme-images/Notebook_Status.png)

## Step 4. 
Select Git > Clone Repository
![Git Termial](readme-images/CloneRepo.png)

## Step 5. 
Enter git url "https://github.com/aws-samples/amazon-rekognition-workshops" in the dialog box and click "Clone"

![Git Termial](readme-images/CloneDialog.png)

## Step 6. 
After cloning is complete, verify that directory named "amazon-rekognition-workshops" is created

![source code](readme-images/RepoFolder.png)

## Step 7. 
Click on 'Open Jupyter' 

![Open Notebook](readme-images/Open_Notebook.png)

## Step 8. 
Click "amazon-rekognition-workshops" to open the folder

![Open Notebook](readme-images/37.png)

## Step 9. 
Click "ObjectDetection" to open the folder

![Open Notebook](readme-images/objectdetection.png)

## Step 10. 
Click on **'ground_truth_object_detection_tutorial.ipynb'** to open the notebook in the browser

![Open Notebook](readme-images/Notebook.png)

## Step 11. 
Open the **'ground_truth_object_detection_turtorial.ipynb'** and follow the instructions in the Notebook.


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

