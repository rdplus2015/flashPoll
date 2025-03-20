# FlashPoll
This project aims to create a **fast feedback system** where users can respond to a **question** in one of the following formats:

1. **True or False**
2. **Yes or No**
3. **Choice between two images**

The system automatically generates the **survey interface** and a **unique code** to access it.

This code allows users to **share the poll** with their audience, who can **vote without authentication**.

At the end of the specified duration (maximum **24 hours**), a **PDF report of the results** is generated and made available to the poll creator.

The website also displays the **remaining time** before the poll closes.

Once the time has expired, **all poll data is automatically deleted**.

---

## **Tech Stack**

- **HTML, CSS, JavaScript (**Frontend**)**
- **Express.js** (Serverless API running on AWS Lambda)
- This project is built on a **serverless architecture** using the following AWS services:
    - **S3** – For storing static files
    - **IAM** – For managing AWS permissions
    - **Lambda** – To run the backend logic (Express.js in a serverless environment)
    - **API Gateway** – To expose the API
    - **DynamoDB** – To store polls and others datas
    - **Others**: AWS CLI, AWS SDK
    

---

## **Features**

✅ Generate the poll and a unique shareable code for each poll

✅ Allow users to vote without authentication

✅ Display the remaining time before poll expiration

✅ Automatically generate a PDF summary after poll completion

✅ Automatically delete poll data

---
