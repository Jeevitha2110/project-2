Task 2: Generate and Store Pre-Signed URLs
Objective: Implement a system to generate pre-signed URLs to allow temporary access to images in the S3 bucket.

Steps:

Write a Lambda function or backend API (e.g., using Node.js with AWS SDK) to generate pre-signed URLs.
Set a configurable expiration time for each URL.
Store the pre-signed URL, expiration time, and image metadata (e.g., file name, user ID) in a database (e.g., MongoDB).
Ensure the pre-signed URLs are accessible only when valid (before expiration).
Deliverable: Functionality that generates, returns, and stores pre-signed URLs in a database.

https://github.com/user-attachments/assets/c1db1681-05e1-49aa-b648-b117e32e5cd1

