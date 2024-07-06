# This filre records the questions that I have asked GPT and other AI helper services to help me with the setup.

## Query 1 - General Structure of the Project

What steps should be followed to create a new website designed for deployment to AWS? The website should be equipped
with the Cloud Development Kit (CDK) using TypeScript for Infrastructure as Code. The design implements the use of an S3
bucket to store the project's HTML, CSS, and JavaScript files - are there any other options, like a CDN? It must also
utilize HTTPS for secure communication, be scalable to manage variable loads, and have cachability for static content.

## Query 2 - S3 and SDN

If I use CND, I still have to use s3 to store static content for the web-site? I guess answers is yes and no? Then would
it be simpler if I go with both S3 and CDN?

## Query 3

Ok, I go with CDN and S3, lets generate the cdk stack that would incroparate it. But let's start small, adding s3
support first.

## Query 3 - Logo

Let's generate a logo for Locus Esse.
The web-site about human values, will contain stories
and such. Locus Esse - you
know how it translates. So take it into account.
And adding the Locus Esse under the logo

## Query 4

Ok, now I as have the stack with s3 bucket and in index.html with the rest in website folder, how I can make it be
connected, be deployed to s3 ?

## Query 5

How to try to deploy it now? How would It know to what aws account to deploy?
... TODO:

## Query 6

Ok, to save money (and waste a bit of time...)
I would like to go with localstack setup, test things locally before deploying.
TODO:

