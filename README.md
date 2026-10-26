# AWS-S3-Bucket

## INTRODUCTION TO AWS S3
Amazon S3 service gives anyone access to the very high scalable, fast and reliable data storage infra which Amazon also uses it to run their own global n/w of websites.
Here we create a bucket and then we start storing data inside our buckets.

<img width="810" height="277" alt="Screenshot 2026-10-26 144913" src="https://github.com/user-attachments/assets/a56b84a4-9116-4503-8c3e-63f394edd5d9" />

The data that we store in buckets are called Objects.

<img width="807" height="420" alt="Screenshot 2026-10-26 144942" src="https://github.com/user-attachments/assets/5bf762c5-0e66-407f-8b6a-8c1a9def2731" />

So we can understand the creation process as per the diagram depicted above.
If we create an EC2 instance and the S3 bucket in the same region, then the data retrieval will be very fast.
If both the EC2 instance and S3 buckets are in different regions then there will be a little more latency but still, the objects will be accessible.

<img width="797" height="516" alt="Screenshot 2026-10-26 145007" src="https://github.com/user-attachments/assets/5a329971-5787-48d3-aa43-a643d4543ad4" />


## AWS S3 practical using the AWS Console

* Sign in to the AWS Management Console.
* Search for S3.
* Click Create bucket.
* Enter a globally unique bucket name.
* Select your AWS Region.
* Keep Block all public access enabled.
* Click Create bucket.
* Open the bucket and select Upload to upload a file.

## CREATING BUCKETS IN S3 

Login to AWS management console and search for S3 and click on S3 Scalable Storage in the Cloud option.

<img width="1723" height="846" alt="Screenshot 2026-10-26 152642" src="https://github.com/user-attachments/assets/2d015003-9251-4b4a-a9bd-049d16abd345" />

As I don’t have any buckets created already, so just click on Create Bucket.

<img width="1857" height="845" alt="Screenshot 2026-10-26 152203" src="https://github.com/user-attachments/assets/8122ca98-ec49-4ad8-84be-19af14551028" />

Now let’s give a unique name to our bucket.

<img width="1863" height="847" alt="Screenshot 2026-10-26 153044" src="https://github.com/user-attachments/assets/a4b9d02a-a0a4-45b4-8d4f-4d29a078a2e5" />

Keep block public access.

<img width="1820" height="748" alt="Screenshot 2026-10-26 161101" src="https://github.com/user-attachments/assets/2fffd916-60f3-46ac-90c0-7bdcc0d34f81" />

After click (I acknowledge that the current settings might result in this bucket and the objects within becoming public).

<img width="1911" height="830" alt="image" src="https://github.com/user-attachments/assets/953c0d84-163f-4e5f-8551-1cc4b1ffe416" />

Enable default encryption.

<img width="957" height="486" alt="Screenshot 2026-10-26 161313" src="https://github.com/user-attachments/assets/4142152e-5ea9-4518-86e1-257c58f671bf" />

Create the bucket.

<img width="1896" height="846" alt="Screenshot 2026-10-26 161352" src="https://github.com/user-attachments/assets/b25a54bc-a201-447a-9dc4-6042b8f82983" />

Open the bucket and upload a sample file.

<img width="1903" height="791" alt="Screenshot 2026-10-26 162639" src="https://github.com/user-attachments/assets/4d0ab819-0d37-4ec2-8fa0-579f6bb4eed2" />

After Click On upload.

<img width="1915" height="851" alt="image" src="https://github.com/user-attachments/assets/c6c92ff8-b938-4cba-adf0-886c6cd47621" />

After On Index.html and open

<img width="1906" height="827" alt="image" src="https://github.com/user-attachments/assets/4cca6eba-869f-40df-9ce8-de7dad0fc43a" />

And Click on open and look uploaded file.
<img width="1868" height="833" alt="Screenshot 2026-10-26 163401" src="https://github.com/user-attachments/assets/6b54ff8d-fcba-42fb-8c3f-9e1092178090" />

## SUMMARY

So, in this article, we have learned what is S3, what is the purpose of using it, different storage types, lifecycle policies, and how we can actually create a bucket using the graphical user interface. In the coming article, we will see how we can actually host a static website using S3.









  

