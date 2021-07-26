# Lambda


**When an image is uploaded to your S3 bucket, it should trigger a Lambda function which must:**


- *Download a file called “images.json” from the S3 Bucket if it exists*

- *The images.json should be an array of objects, each representing an image. Create an empty array if this file is not present*

- *Create a metadata object describing the image Name, Size, Type, etc.*

- *Append the data for this image to the array.*
