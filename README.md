> my webpage :D

# wat

    $ git submodule update --init
    $ gem install jekyll # jekyll? still, fil? geez
    $ jekyll build

# Architecture

Leveraging all AWS.

## DNS

> AWS Route53

## CDN

> AWS Cloudfront

## Static Site Hosting

> AWS S3

- There's a filmaj.ca bucket configured for static hosting, with public GET permissions on it.

# Automation

Leveraging Travis to build and upload the site to S3. Post-upload it also invalidates changed files in CloudFront.

For details see the `.travis.yml` file.
