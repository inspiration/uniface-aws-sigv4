# uniface-aws-sigv4
Uniface code for AWS Signature V4 - used for signing requests to send to API Gateway

## UT01 - Unit Test 1 
This unit test uses the AWS documented sig v4 example to confirm the code is creating the same signature

## UT02 - Unit Test 2
This unit test uses <my> secret keys in #define trigger to validate a correct signature with Postman's AWS sig v4 signature
  
## UT03 - Unit Test 3
This unit test creates a signature and calls the AWS API gateway endpoint, which will return OK if successful

# The code contains a Uniface form component for unit testing, but the LPMX code is portable.

There are some todo's such as URI encoding.

