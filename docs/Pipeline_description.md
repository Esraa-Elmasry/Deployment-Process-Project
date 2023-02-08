Pipeline process:

1. we update our code in local env
1. we push it to our github 
1. circleci triggers the following actions:
   - install node, aws cli, eb cli
   - install front-end dependencies
   - install back-end dependencies 
   - run front-end lint 
   - build the front-end app
   - build the back-end API 
   - update back-end code in elastic-beanstalk
   - update front-end code in its S3 bucket

   Pipeline Infrastructure diagram:

   