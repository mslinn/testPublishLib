# TestPublishLib #

Sample library for testing sbt publishing.
Companion app is [testPublishApp](https://github.com/mslinn/testPublishApp)
Read my [blog posting](http://mikeslinn.blogspot.com/2013/07/publishing-maven-artifacts-to-aws-s3.html) on how to use this project.

1. This project is configured to publish to the local ivy repo at `~/.ivy2/local`.
2. Create directory on a web server or an AWS S3 bucket to hold the published files.
If you use an S3 bucket, be sure to enable the web site feature.
3. Copy the `com/micronautics` directory and all of its contents from `~/.ivy2/local` to the repo directory.
4. Ensure that that all the files are readable from a web browser.
