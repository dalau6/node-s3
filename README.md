# node-s3

A simple web server that pulls an image from an AWS S3 bucket and displayed it without having to use the file system to store the image.

There are two options to read images from a private s3 bucket. One is to establish a signed URL to your S3 bucket. The other is to access images as a stream. The latter is the app's our approach.
