# phantomjs-lambda

Provides a version of phantomjs that is compatible with AWS Lambda. This has
not been tested with other FaaS providers like Azure Functions.

To use, simply fetch the latest version from 'releases' and unzip to
/opt.

# Example

```shell
$> curl -o phantomjs_lambda.zip https://github.com/carlosonunez/phantomjs-lambda/raw/${VERSION}/phantomjs_lambda.zip
$> unzip -d /opt phantomjs_lambda.zip
```
