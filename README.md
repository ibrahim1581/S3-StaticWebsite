# Simple Static Website with AWS S3

## Overview

This documentation will guide you through creating a basic static website hosted on Amazon S3.

## Table of Contents

- [1. Prerequisites](#1-prerequisites)
- [2. Create an S3 Bucket](#2-create-an-s3-bucket)
- [3. Upload HTML and Image Files](#3-upload-html-and-image-files)
- [4. Configure Bucket for Website Hosting](#4-configure-bucket-for-website-hosting)
- [5. Access Your Website](#5-access-your-website)

## 1. Prerequisites

Before you begin, make sure you have an AWS account.

## 2. Create an S3 Bucket

1. Go to the [Amazon S3 Console](https://s3.console.aws.amazon.com/s3/).
2. Click on the "Create bucket" button.
3. Choose a globally unique name for your bucket (e.g., `my-static-website-bucket`).
4. Click through the default settings and click "Create bucket."

## 3. Upload HTML and Image Files

1. Select your bucket.
2. Click on the "Upload" button.
3. Upload your HTML file (e.g., `index.html`) and any image files.
4. Ensure that your images are in the same folder as your HTML file.

## 4. Configure Bucket for Website Hosting

1. Go to the "Properties" tab.
2. Click on "Static website hosting."
3. Choose "Use this bucket to host a website."
4. Set the index document to your HTML file (e.g., `index.html`).
5. Optionally, set an error document.
6. Click "Save changes."

## 5. Access Your Website

1. In the "Static website hosting" section, note the "Endpoint" URL.
   - It will look like: `http://loginpages3project.s3-website-us-east-1.amazonaws.com/?username=asd&password=asd`
2. Open this URL in a web browser to view your static website.
