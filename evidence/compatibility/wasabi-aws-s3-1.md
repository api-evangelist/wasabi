<!-- fetched 2026-10-13 from https://docs.wasabi.com/docs/wasabi-api by sweep-shape-compat.py; text extracted from the provider's own page -->

Wasabi S3 API Reference ` instead of inline ` Open in ChatGPT Ask ChatGPT about this page Open in Claude Ask Claude about this page 
 Prev Next Wasabi’s object storage service is built to be 100% bit-compatible with the Amazon Web Services Simple Storage Service (AWS S3) and Identity and Access Management (AWS IAM) APIs.
 The Wasabi S3 API Reference describes variations in functionality when comparing the Wasabi S3 to AWS S3 and AWS IAM APIs. In certain cases, Wasabi provides additional functionality relative to AWS S3 (or implements functionality in a different manner than AWS S3).
 What is Wasabi S3?
 Wasabi is a cloud-based object storage service for a broad range of applications and use cases. Wasabi is designed for individuals and organizations that require a high-performance, reliable, and secure data storage infrastructure at minimal cost.
 Wasabi’s object storage service is built to be 100% bit-compatible with AWS S3 and Identity and Access Management (AWS IAM) APIs. This means that any existing AWS S3-compatible application or gateway device will work seamlessly with Wasabi.
 In certain cases, Wasabi provides additional functionality relative to AWS S3 (or implements functionality in a different manner than AWS S3). The primary purpose of this guide is to describe these variations in functionality as they pertain to using Wasabi S3 relative to the AWS S3 and IAM APIs.
 Given that Wasabi is built to be 100% bit-compatible with AWS S3, the AWS documentation for S3 and IAM is a complementary resource to the information provided in this guide. The following AWS documents apply to the Wasabi S3 design:
 AWS S3 capabilities referenced in this Guide are based on API version 2006-03-01, described in the Amazon Simple Storage Service API Reference: http://docs.aws.amazon.com/AmazonS3/latest/API/s3-api.pdf 
 AWS IAM capabilities referenced in this Guide are based on API version 2010-05-08, described in the AWS Identity and Access Management API Reference: http://docs.aws.amazon.com/IAM/latest/APIReference/iam-api.pdf 
 Throughout this guide, for the sake of brevity, Wasabi S3 functionality is designated as “Wasabi” and the AWS S3 API functionality is designated as “AWS S3.”
 In addition, examples indicate access to buckets created in the East Coast region. Note, however, that you must use URLs based on the region to access buckets. Refer to the Service URLs for Wasabi Storage Regions . Using the incorrect URL will enable you to do a GET, but not a PUT or DELETE function. 
 Copyright © 2025 by Wasabi Technologies LLC
75 Arlington Street, Suite 810, Boston, MA 02116 USA
All Rights Reserved
Visit us at https://wasabi.com .
 WASABI and the WASABI logo are trademarks of Wasabi Technologies LLC and may not be used without permission of Wasabi Technologies. All other names are used for identification purposes only and are trademarks or registered trademarks of their respective companies. 
Information presented herein is subject to change without notice. Companies, names, and data used in examples are fictitious unless otherwise noted. No part of this information may be reproduced or transmitted in any form by means electronic or mechanical, for any purpose, without express written permission of Wasabi Technologies.
