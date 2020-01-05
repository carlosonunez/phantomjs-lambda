# poltergeist-lambda

Provides a version of Poltergeist that is compatible with AWS Lambda. This has
not been tested with other FaaS providers like Azure Functions.

To use, simply fetch the latest version from 'releases' and unzip to
/opt.

# Example

```shell
$> curl -o poltergeist_lambda.zip https://github.com/carlosonunez/poltergeist-lambda/raw/${VERSION}/phantomjs_lambda.zip
$> unzip -d /opt poltergeist_lambda.zip
```
