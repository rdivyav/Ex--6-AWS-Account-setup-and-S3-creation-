# Ex--6-AWS-Account-setup-and-S3-creation-
## Introduction
In this lab, we are going to be introduced to one of the famous Cloud Service providers, Amazon Web Services (AWS). We will work on Amazon Simple Storage Service (S3), which provides storage through web service interfaces (REST, SOAP, and BitTorrent). In S3, the data is stored in the form of buckets. Buckets serve as root folders where we can add, create, or upload files and folders. We can create multiple buckets for different purposes, and each bucket can have different access control policies.

## Objectives
1. Create a Bucket in Amazon S3.
2. Add Objects (files and folders) to the bucket.
3. Access, move, download, and delete the objects.
4. Delete the Bucket.
## Illustration
Step 1: Choose S3 Service
Choose the S3 service from the list of services provided by AWS.

![image](https://github.com/user-attachments/assets/e1a2ec67-f811-417c-ba92-8c2240b76ef0)

Step 2: Create a Unique Bucket
After selecting the S3 service, click on the "Create Bucket" button on the page. The bucket name must be unique, contain no uppercase letters, and have no special characters. If you enter any of these, an error will display, preventing the bucket from being created.

![image](https://github.com/user-attachments/assets/6edcf49d-1751-494b-9cd9-713b302b19ed)

![image](https://github.com/user-attachments/assets/e1128680-bbd6-4e69-a7ee-5ff8764a39eb)

![image](https://github.com/user-attachments/assets/e042b4ba-84aa-44b2-b9b2-b626f7dfb856)

![image](https://github.com/user-attachments/assets/8dad0c37-1fa7-4754-bf3d-7ca643f8fb11)


For region selection, choose a region from the available list. It is recommended to select a region nearby your location for higher availability. In this lab, I selected Sydney, as it is near my country, New Zealand. Remember to provide a unique bucket name with no special characters or uppercase letters.

Step 3: Upload Files to the Bucket
Now, I have uploaded some files into the bucket I just created. There are no restrictions on uploading file types, but the size of each file must be less than 5 terabytes.

![image](https://github.com/user-attachments/assets/c48c1853-f1f3-4923-8c23-4be20e6786dd)

![image](https://github.com/user-attachments/assets/cfb366d5-3f62-4ce7-98ae-2d5145127f39)




You can upload files of any extension, folders, and subfolders. The images below explain that you can drag and drop files or select them from your computer. After uploading a file, you can download, cut, copy, make it public, rename, or delete it. Making a file public means everyone can access it, and you will receive a link (e.g., https://s3-ap-southeast-2.amazonaws.com/...) to share it.



Step 4: Upload a Folder
You can also upload a folder to the bucket. If your local folder contains subfolders and data, all data inside the parent folder will be uploaded. The images below show how to upload a folder by dragging and dropping or browsing.

![image](https://github.com/user-attachments/assets/df50fdb2-8d16-4965-be88-e66fa05ccafe)


Step 5: Delete the Bucket
To delete a bucket, you must retype the bucket name. This policy is implemented by Amazon to confirm your action because deleting a bucket can remove large amounts of data.

![image](https://github.com/user-attachments/assets/3184b018-ec05-4cde-a597-1f45e694dbf4)

## Result
Successfully created, managed, and deleted an S3 bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon S3.
