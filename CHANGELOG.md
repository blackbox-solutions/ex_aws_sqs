v3.0.0
- ***BREAKING CHANGE***: Changed queue specific functions to take the QueueUrl instead of the QueueName. Previously the name was used to build the path for the request. This is an anti-pattern according to aws docs and prevents this library from being used with alternative SQS compatible services, like localstack.

v2.0.1
- Relaxed `:ex_aws` version constraint from `v2.0.0` to `v2.0`

v2.0

- Major Project Split. Please see the main ExAws repository for previous changelogs.
