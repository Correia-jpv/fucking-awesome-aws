<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/data-science-ipython-notebooks/master/images/aws.png">
</p>
<br/>

# Awesome AWS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome AWS libraries, open source repos, guides, blogs, and other resources.

Inspired by the <b><code>441666⭐</code></b> <b><code>&nbsp;33347🍴</code></b> [awesome](https://github.com/sindresorhus/awesome)) list.

## The Fiery Meter of AWSome

* Repo with 0100+ Stars: :fire:
* Repo with 0200+ Stars: :fire::fire:
* Repo with 0500+ Stars: :fire::fire::fire:
* Repo with 1000+ Stars: :fire::fire::fire::fire:
* Repo with 2000+ Stars: :fire::fire::fire::fire::fire:

Repos not on `The Fiery Meter of AWSome` can still be awesome, see [A Note on Repo AWSomeness](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md#a-note-on-repo-awsomeness).

### `awesome-aws` Python Module

[![Build Status](https://travis-ci.org/donnemartin/awesome-aws.svg?branch=master)](https://travis-ci.org/donnemartin/awesome-aws) [![Codecov](https://img.shields.io/codecov/c/github/donnemartin/awesome-aws.svg)](https://codecov.io/github/donnemartin/awesome-aws) [![PyPI version](https://badge.fury.io/py/awesome-aws.svg)](http://badge.fury.io/py/awesome-aws)

The Python module [`awesome-aws`](https://github.com/correia-jpv/fucking-awesome-aws/tree/master/awesome) regularly scans repos on [Awesome AWS](https://github.com/correia-jpv/fucking-awesome-aws) to maintain the accuracy of the `Fiery Meter of AWSome`.

## Contributing

Contributions are welcome!

Review the [Contributing Guidelines](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md).

Also check out the [Watch List](https://github.com/correia-jpv/fucking-awesome-aws/issues/34).

## Index

* [SDKs and Samples](#sdks-and-samples)
    * [Android](#android-sdk)
    * [C++](#c-sdk)
    * [Clojure](#clojure-sdk)
    * [Go](#go-sdk)
    * [iOS](#ios-sdk)
    * [IoT](#iot-sdk)
    * [Java](#java-sdk)
    * [JavaScript](#javascript-sdk)
    * [Haskell](#haskell-sdk)
    * [Perl](#perl-sdk)
    * [PHP](#php-sdk)
    * [Python](#python-sdk)
    * [Ruby](#ruby-sdk)
    * [Rust](#rust-sdk)
    * [Scala](#scala-sdk)
    * [Xamarin](#xamarin-sdk)
    * [Unity](#unity-sdk)
    * [.NET](#net-sdk)
* [Command Line Tools](#command-line-tools)
    * [Universal Command Line Interface](#universal-command-line-interface)
    * [Windows PowerShell](#windows-powershell)
* [IDE Toolkits](#ide-toolkits)
    * [Eclipse Toolkit](#eclipse-toolkit)
    * [Visual Studio Toolkit](#visual-studio-toolkit)
* [Open Source Repos](#open-source-repos)
    * [API Gateway](#api-gateway)
    * [CLI](#cli)
    * [CloudFormation](#cloudformation)
    * [CloudSearch](#cloudsearch)
    * [CloudTrail](#cloudtrail)
    * [CloudWatch](#cloudwatch)
    * [Code Deploy](#code-deploy)
    * [Code Pipeline](#code-pipeline)
    * [Cognito](#cognito)
    * [Data Pipeline](#data-pipeline)
    * [Device Farm](#device-farm)
    * [DynamoDB](#dynamodb)
    * [Elastic Beanstalk](#elastic-beanstalk)
    * [Elastic Container Service](#elastic-container-service)
    * [Elastic File System](#elastic-file-system)
    * [Elastic MapReduce](#elastic-mapreduce)
    * [Elastic Search](#elastic-search)
    * [Elasticache](#elasticache)
    * [Glacier](#glacier)
    * [Kinesis](#kinesis)
    * [Lambda](#lambda)
    * [Machine Learning](#machine-learning)
    * [Mobile Analytics](#mobile-analytics)
    * [OpsWorks](#opsworks)
    * [Redshift](#redshift)
    * [Route 53](#route-53)
    * [S3](#s3)
    * [SNS](#sns)
    * [SQS](#sqs)
    * [Data](#data)
    * [DevOps](#devops)
    * [Security](#security)
    * [Accompanying](#accompanying-repos)
    * [Miscellaneous](#miscellaneous-repos)
* [Guides, Books, Documentation, and Training](#guides-books-documentation-and-training)
    * [Getting Started Guides](#getting-started-guides)
    * [General Guides](#general-guides)
    * [Books](#books)
    * [Whitepapers](#whitepapers)
    * [Documentation](#documentation)
    * [Training](#training)
    * [Case Studies: Powered by AWS](#case-studies-powered-by-aws)
* [Social](#social)
    * [Blogs](#blogs)
    * [Twitter Influencers](#twitter-influencers)
    * [Facebook Pages](#facebook-pages)
    * [YouTube Channels](#youtube-channels)
    * [LinkedIn Groups](#linkedin-groups)
    * [Subreddits](#subreddits)
    * [Conferences](#conferences)
* [Latest KPIs and Stats](#latest-kpis-and-stats)
* [Appendix of Core Services](#appendix-of-core-services)
    * [Services in Plain English](#services-in-plain-english)
    * [Compute](#compute-services)
    * [Networking](#networking-services)
    * [Enterprise Applications](#enterprise-applications)
    * [Analytics](#analytics-services)
    * [Artificial Intelligence](#artificial-intelligence)
    * [Management Tools](#management-tools)
    * [Security and Identity](#security-and-identity-services)
    * [Internet of Things](#internet-of-things-service)
    * [Mobile Services](#mobile-services)
    * [Storage and Content Delivery](#storage-and-content-delivery-services)
    * [Databases](#databases)
    * [Application Services](#application-services)
    * [Developer Tools](#developer-tools)
    * [Miscellaneous Services](#miscellaneous-services)
* [Contributing](#contributing)
* [Credits](#credits)
* [Other Awesome Lists](#other-awesome-lists)
* [Contact Info](#contact-info)
* [License](#license)

## SDKs and Samples

*AWS and community SDKs with samples and docs, grouped by language.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/TK96G8T.png">
</p>
<br/>

### Android SDK

* <b><code>&nbsp;&nbsp;1069⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;548🍴</code></b> [Repo :fire::fire::fire:](https://github.com/aws/aws-sdk-android))
* <b><code>&nbsp;&nbsp;1053⭐</code></b> <b><code>&nbsp;&nbsp;1035🍴</code></b> [Repo with Samples :fire::fire::fire:](https://github.com/awslabs/aws-sdk-android-samples))
* [Install](http://sdk-for-android.amazonwebservices.com/latest/aws-android-sdk.zip)
* 🌎 [Docs](aws.amazon.com/documentation/sdk-for-android/)
* 🌎 [Learn More](aws.amazon.com/mobile/sdk/)

### C++ SDK

* <b><code>&nbsp;&nbsp;2176⭐</code></b> <b><code>&nbsp;&nbsp;1145🍴</code></b> [Repo :fire::fire::fire::fire:](https://github.com/awslabs/aws-sdk-cpp))
* 🌎 [Blog with Samples](aws.amazon.com/blogs/aws/introducing-the-aws-sdk-for-c/)

*The C++ SDK is a labs project with limited docs and/or samples.*

### Clojure SDK

* <b><code>&nbsp;&nbsp;1005⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;202🍴</code></b> [Repo :fire::fire::fire:](https://github.com/mcohen01/amazonica))
* <b><code>&nbsp;&nbsp;1005⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;202🍴</code></b> [Install](https://github.com/mcohen01/amazonica#installation))
* <b><code>&nbsp;&nbsp;1005⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;202🍴</code></b> [Docs](https://github.com/mcohen01/amazonica#documentation))

*The Clojure SDK is a community project with limited docs and/or samples.*)

### Go SDK

* <b><code>&nbsp;&nbsp;8711⭐</code></b> <b><code>&nbsp;&nbsp;2055🍴</code></b> [Repo :fire::fire::fire::fire::fire:](https://github.com/aws/aws-sdk-go))
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Install](https://github.com/aws/aws-sdk-go/wiki))
* [Docs](http://docs.aws.amazon.com/sdk-for-go/api/)
* 🌎 [Learn More](aws.amazon.com/sdk-for-go/)

Related Repos:

* <b><code>&nbsp;&nbsp;&nbsp;372⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [goamz/goamz :fire::fire:](https://github.com/goamz/goamz))

### iOS SDK

* <b><code>&nbsp;&nbsp;1706⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;900🍴</code></b> [Repo :fire::fire::fire::fire:](https://github.com/aws/aws-sdk-ios))
* <b><code>&nbsp;&nbsp;1055⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;744🍴</code></b> [Repo with Samples :fire::fire::fire::fire:](https://github.com/awslabs/aws-sdk-ios-samples))
* [Install](http://sdk-for-ios.amazonwebservices.com/latest/aws-ios-sdk.zip)
* 🌎 [Docs](aws.amazon.com/documentation/sdk-for-ios/)
* 🌎 [Learn More](aws.amazon.com/mobile/sdk/)

### IoT SDK

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;113🍴</code></b> [Repo for Arduino](https://github.com/awslabs/aws-sdk-arduino))
* <b><code>&nbsp;&nbsp;1047⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;639🍴</code></b> [Repo for C :fire::fire::fire:](https://github.com/aws/aws-iot-device-sdk-embedded-C))
* <b><code>&nbsp;&nbsp;&nbsp;967⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;378🍴</code></b> [Repo for JavaScript :fire::fire::fire:](https://github.com/aws/aws-iot-device-sdk-js))
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Repo for Arduino Yun :fire:](https://github.com/aws/aws-iot-device-sdk-arduino-yun/))
* [Docs](http://docs.aws.amazon.com/iot/latest/developerguide/what-is-aws-iot.html)

*The IoT SDK is a labs project with limited docs and/or samples.*

### Java SDK

* <b><code>&nbsp;&nbsp;4197⭐</code></b> <b><code>&nbsp;&nbsp;2806🍴</code></b> [Repo :fire::fire::fire::fire::fire:](https://github.com/aws/aws-sdk-java))
* <b><code>&nbsp;&nbsp;&nbsp;240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;344🍴</code></b> [Repo with Samples :fire::fire:](https://github.com/awslabs/aws-java-sample))
* [Install](http://sdk-for-java.amazonwebservices.com/latest/aws-java-sdk.zip)
* 🌎 [Docs](aws.amazon.com/documentation/sdk-for-java/)
* 🌎 [Learn More](aws.amazon.com/sdk-for-java/)

### JavaScript SDK

* <b><code>&nbsp;&nbsp;7645⭐</code></b> <b><code>&nbsp;&nbsp;1535🍴</code></b> [Repo :fire::fire::fire::fire::fire:](https://github.com/aws/aws-sdk-js))
* <b><code>&nbsp;&nbsp;&nbsp;308⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;169🍴</code></b> [Repo with Samples :fire::fire:](https://github.com/awslabs/aws-nodejs-sample))
* [Install](http://docs.aws.amazon.com/AWSJavaScriptSDK/guide/node-intro.html)
* 🌎 [Docs](aws.amazon.com/documentation/sdk-for-javascript/)
* 🌎 [Learn More](aws.amazon.com/sdk-for-node-js/)

Related Repos:

* <b><code>&nbsp;&nbsp;9593⭐</code></b> <b><code>&nbsp;&nbsp;2169🍴</code></b> [aws/aws-amplify :fire::fire::fire::fire::fire:](https://github.com/aws/aws-amplify))
* <b><code>&nbsp;&nbsp;&nbsp;458⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [chilts/awssum :fire::fire:](https://github.com/chilts/awssum))
* <b><code>&nbsp;&nbsp;&nbsp;681⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;165🍴</code></b> [mirkokiefer/aws-lib :fire::fire::fire:](https://github.com/mirkokiefer/aws-lib))
* <b><code>&nbsp;&nbsp;&nbsp;240⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [SaltwaterC/aws2js :fire::fire:](https://github.com/SaltwaterC/aws2js))

### Haskell SDK

* <b><code>&nbsp;&nbsp;&nbsp;612⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;239🍴</code></b> [Repo :fire::fire::fire:](https://github.com/brendanhay/amazonka))
* [Docs](http://hackage.haskell.org/packages/#cat:AWS)

Related Repos:

* <b><code>&nbsp;&nbsp;&nbsp;246⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [aristidb/aws :fire::fire:](https://github.com/aristidb/aws))

*The Haskell SDK is a community project with limited docs and/or samples.*

### Perl SDK

* <b><code>&nbsp;&nbsp;&nbsp;173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [Repo :fire:](https://github.com/pplu/aws-sdk-perl))
* <b><code>&nbsp;&nbsp;&nbsp;173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [Repo with Samples :fire:](https://github.com/pplu/aws-sdk-perl/tree/master/examples))
* <b><code>&nbsp;&nbsp;&nbsp;173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [Install](https://github.com/pplu/aws-sdk-perl#installation))
* 🌎 [Docs](metacpan.org/pod/Paws)
* 🌎 [Learn More](metacpan.org/pod/Paws)

*The Perl SDK is a community project.*

### PHP SDK

* <b><code>&nbsp;&nbsp;6179⭐</code></b> <b><code>&nbsp;&nbsp;1239🍴</code></b> [Repo :fire::fire::fire::fire::fire:](https://github.com/aws/aws-sdk-php))
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74🍴</code></b> [Repo with Samples](https://github.com/awslabs/aws-php-sample))
* [Install](http://docs.aws.amazon.com/aws-sdk-php/v3/guide/getting-started/installation.html)
* 🌎 [Docs](aws.amazon.com/documentation/sdk-for-php/)
* 🌎 [Learn More](aws.amazon.com/sdk-for-php/)

Related Repos:

* <b><code>&nbsp;&nbsp;1716⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;250🍴</code></b> [aws-sdk-php-laravel :fire::fire::fire::fire:](https://github.com/aws/aws-sdk-php-laravel))
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;81⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [aws-sdk-php-silex](https://github.com/aws/aws-sdk-php-silex))
* <b><code>&nbsp;&nbsp;&nbsp;104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [aws-sdk-php-zf2 :fire:](https://github.com/aws/aws-sdk-php-zf2))

### Python SDK

* <b><code>&nbsp;&nbsp;9708⭐</code></b> <b><code>&nbsp;&nbsp;1954🍴</code></b> [Repo :fire::fire::fire::fire::fire:](https://github.com/boto/boto3))
* <b><code>&nbsp;&nbsp;&nbsp;207⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [Repo with Samples :fire:](https://github.com/awslabs/aws-python-sample))
* [Install](http://github.com/boto/boto#installation)
* 🌎 [Docs](boto3.amazonaws.com/v1/documentation/api/latest/index.html)
* [Learn More](http://github.com/boto/boto/blob/develop/README.rst#boto)

Related Repos:

* <b><code>&nbsp;&nbsp;9708⭐</code></b> <b><code>&nbsp;&nbsp;1954🍴</code></b> [boto3 :fire::fire::fire::fire::fire:](https://github.com/boto/boto3))
* <b><code>&nbsp;&nbsp;1606⭐</code></b> <b><code>&nbsp;&nbsp;1139🍴</code></b> [botocore :fire::fire::fire::fire:](https://github.com/boto/botocore))

### Ruby SDK

* <b><code>&nbsp;&nbsp;3643⭐</code></b> <b><code>&nbsp;&nbsp;1232🍴</code></b> [Repo :fire::fire::fire::fire::fire:](https://github.com/aws/aws-sdk-ruby))
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [Repo with S3 Sample](https://github.com/awslabs/aws-ruby-sample))
* [Install](http://docs.aws.amazon.com/sdk-for-ruby/v3/developer-guide/setup-install.html)
* 🌎 [Docs](aws.amazon.com/documentation/sdk-for-ruby/)
* <b><code>&nbsp;10369⭐</code></b> <b><code>&nbsp;&nbsp;5847🍴</code></b> [Samples :fire::fire::fire::fire::fire:](https://github.com/awsdocs/aws-doc-sdk-examples/tree/master/ruby/example_code/))

Related Repos:

* <b><code>&nbsp;&nbsp;&nbsp;615⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [aws-sdk-rails :fire::fire::fire:](https://github.com/aws/aws-sdk-rails))
* <b><code>&nbsp;&nbsp;&nbsp;235⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [appoxy/aws :fire::fire:](https://github.com/appoxy/aws))
* <b><code>&nbsp;&nbsp;&nbsp;450⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [rightscale/right_aws :fire::fire:](https://github.com/rightscale/right_aws))

### Rust SDK

* <b><code>&nbsp;&nbsp;2730⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;441🍴</code></b> [Repo :fire::fire::fire::fire::fire:](https://github.com/rusoto/rusoto))
* <b><code>&nbsp;&nbsp;2730⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;441🍴</code></b> [Install](https://github.com/rusoto/rusoto#installation))
* 🌎 [Docs](docs.rs/rusoto_core/)

*The Rust SDK is a community project with limited docs and/or samples.*

### Scala SDK

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Repo](https://github.com/awslabs/aws-scala-sdk))

Related Repos:

* 🌎 [atlassian/aws-scala](bitbucket.org/atlassian/aws-scala)
* <b><code>&nbsp;&nbsp;&nbsp;731⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;220🍴</code></b> [seratch/AWScala :fire::fire::fire:](https://github.com/seratch/AWScala))

*The Scala SDK is a labs project with limited docs and/or samples.*

### Unity SDK

* <b><code>&nbsp;&nbsp;&nbsp;104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [Repo :fire:](https://github.com/aws/aws-sdk-unity))
* <b><code>&nbsp;&nbsp;&nbsp;164⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;108🍴</code></b> [Repo with Samples :fire:](https://github.com/awslabs/aws-sdk-unity-samples))
* 🌎 [Install](s3.amazonaws.com/aws-unity-sdk/latest/aws-unity-sdk.zip)
* [Docs](http://docs.aws.amazon.com/mobile/sdkforunity/developerguide/)

### Xamarin SDK

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Repo](https://github.com/awslabs/aws-sdk-xamarin))
* 🌎 [Blog with Samples](blog.xamarin.com/amazon-web-services-aws-mobile-sdks-for-xamarin-now-available/)

*The Xamarin SDK is a labs project with limited docs and/or samples.*

### .NET SDK

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;878🍴</code></b> [Repo :fire::fire::fire::fire:](https://github.com/aws/aws-sdk-net))
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [Repo with Samples](https://github.com/awslabs/aws-auto-scaling-console-sample))
* [Install](http://sdk-for-net.amazonwebservices.com/latest/AWSToolsAndSDKForNet.msi)
* 🌎 [Docs](aws.amazon.com/documentation/sdk-for-net/)
* 🌎 [Learn More](aws.amazon.com/sdk-for-net/)
* <b><code>&nbsp;&nbsp;&nbsp;195⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;174🍴</code></b> [Samples :fire:](https://github.com/awslabs/aws-sdk-net-samples))

## Command Line Tools

*AWS and community command line tools with samples and docs.*

<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/data-science-ipython-notebooks/master/images/commands.png">
</p>
<br/>

### Universal Command Line Interface

* <b><code>&nbsp;16785⭐</code></b> <b><code>&nbsp;&nbsp;4483🍴</code></b> [Repo :fire::fire::fire::fire::fire:](https://github.com/aws/aws-cli))
* [Install](http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-set-up.html)
* 🌎 [Docs](aws.amazon.com/documentation/cli/)
* 🌎 [Learn More](aws.amazon.com/cli/)

Related Repos:

* <b><code>&nbsp;&nbsp;7359⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;784🍴</code></b> [awslabs/aws-shell :fire::fire::fire::fire::fire:](https://github.com/awslabs/aws-shell))
* <b><code>&nbsp;&nbsp;5308⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;284🍴</code></b> [donnemartin/saws :fire::fire::fire::fire::fire:](https://github.com/donnemartin/saws))

### Windows PowerShell

* [Install](http://sdk-for-net.amazonwebservices.com/latest/AWSToolsAndSDKForNet.msi)
* 🌎 [Docs](aws.amazon.com/documentation/powershell/)
* 🌎 [Learn More](aws.amazon.com/powershell/)

## IDE Toolkits

*Official IDE toolkits with samples and docs.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/x4nu914.png">
</p>
<br/>

### Eclipse Toolkit

* [Install](http://docs.aws.amazon.com/AWSToolkitEclipse/latest/ug/tke_setup.html)
* 🌎 [Docs](aws.amazon.com/documentation/awstoolkiteclipse/)
* 🌎 [Learn More](aws.amazon.com/eclipse/)

### Visual Studio Toolkit

* [Install](http://sdk-for-net.amazonwebservices.com/latest/AWSToolsAndSDKForNet.msi)
* 🌎 [Docs](aws.amazon.com/documentation/aws-toolkit-visual-studio/)
* 🌎 [Learn More](aws.amazon.com/visualstudio/)

## Open Source Repos

*AWS and community open source projects, grouped by service.  See [A Note on Repo AWSomeness](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md#a-note-on-repo-awsomeness) for more details.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/wbhTgga.png">
</p>
<br/>

### API Gateway

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;308⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [api-gateway-secure-pet-store :fire::fire:](https://github.com/awslabs/api-gateway-secure-pet-store)) - Cognito credentials through Lambda.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [aws-apigateway-sdk-java](https://github.com/awslabs/aws-apigateway-sdk-java)) - SDK for Java.
* <b><code>&nbsp;&nbsp;&nbsp;520⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;138🍴</code></b> [aws-apigateway-swagger-importer :fire::fire::fire:](https://github.com/awslabs/aws-apigateway-importer)) - Tools to work with Swagger.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### CLI

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;484⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [awscli-aliases :fire::fire:](https://github.com/awslabs/awscli-aliases)) - Repository for AWS CLI aliases.
* <b><code>&nbsp;&nbsp;1807⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;298🍴</code></b> [amazon-ecs-cli :fire::fire::fire::fire:](https://github.com/aws/amazon-ecs-cli)) - ECS CLI using the same Docker Compose file format and familiar Compose commands.
* <b><code>&nbsp;16785⭐</code></b> <b><code>&nbsp;&nbsp;4483🍴</code></b> [aws-cli :fire::fire::fire::fire::fire:](https://github.com/aws/aws-cli)) - Universal Command Line Interface.
* <b><code>&nbsp;&nbsp;7359⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;784🍴</code></b> [aws-shell :fire::fire::fire::fire::fire:](https://github.com/awslabs/aws-shell))
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [awscli-cookbook](https://github.com/awslabs/awscli-cookbook)) - Installs the CLI tools and provides a set of LWRPs for use within chef cookbooks.
* <b><code>&nbsp;&nbsp;&nbsp;142⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [awsmobile-cli :fire:](https://github.com/aws/awsmobile-cli)) - CLI experience for Frontend developers in the JavaScript ecosystem.

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;843⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [achiku/jungle :fire::fire::fire:](https://github.com/achiku/jungle)) - Operations by EC2 and ELB cli should be simpler.
* <b><code>&nbsp;&nbsp;&nbsp;226⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [dbcli/athenacli :fire:](https://github.com/dbcli/athenacli)) - a CLI tool for AWS Athena service that can do auto-completion and syntax highlighting.
* <b><code>&nbsp;&nbsp;5308⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;284🍴</code></b> [donnemartin/saws :fire::fire::fire::fire::fire:](https://github.com/donnemartin/saws)) - A Supercharged AWS Command Line Interface.
* <b><code>&nbsp;&nbsp;&nbsp;435⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;130🍴</code></b> [timkay/aws :fire::fire:](https://github.com/timkay/aws)) - Easy command line access to Amazon EC2, S3, SQS, ELB, and SDB.
* <b><code>&nbsp;&nbsp;4983⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;259🍴</code></b> [wallix/awless :fire::fire::fire::fire::fire:](https://github.com/wallix/awless)) - a Powerful CLI for EC2, IAM and S3 in Go.
* <b><code>&nbsp;&nbsp;8963⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;841🍴</code></b> [99designs/aws-vault :fire::fire::fire::fire::fire:](https://github.com/99designs/aws-vault)) - A tool for securely storing AWS credentials, written in Go.

### CloudFormation

AWS Repos:

* <b><code>&nbsp;12673⭐</code></b> <b><code>&nbsp;&nbsp;4417🍴</code></b> [aws-cdk :fire::fire::fire::fire::fire:](https://github.com/aws/aws-cdk)) - Framework for defining cloud infrastructure in code.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [aws-cfn-custom-resource-examples](https://github.com/awslabs/aws-cfn-custom-resource-examples)) - Custom resource examples.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [aws-cfn-resource-bridge](https://github.com/aws/aws-cfn-resource-bridge)) - Custom resource framework.
* <b><code>&nbsp;&nbsp;2608⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;625🍴</code></b> [cfn-python-lint :fire::fire::fire::fire::fire:](https://github.com/awslabs/cfn-python-lint)) - A tool for linting/validating CloudFormation.
* <b><code>&nbsp;&nbsp;&nbsp;112⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [cfncluster-cookbook](https://github.com/awslabs/cfncluster-cookbook)) - Sample Cookbook.
* <b><code>&nbsp;&nbsp;&nbsp;886⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;319🍴</code></b> [cfncluster :fire::fire::fire:](https://github.com/awslabs/cfncluster)) - Framework that deploys and maintains HPC clusters.

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Appliscale/perun](https://github.com/Appliscale/perun)) - A CLI tool for linting/validation and managing CloudFormation templates and stacks.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [bazaarvoice/cloudformation-ruby-dsl :fire::fire:](https://github.com/bazaarvoice/cloudformation-ruby-dsl)) - Ruby DSL for creating templates.
* <b><code>&nbsp;&nbsp;&nbsp;101⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [beaknit/cform :fire:](https://github.com/beaknit/cform)) - SublimeText plugin.
* <b><code>&nbsp;&nbsp;1527⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;307🍴</code></b> [cloudreach/sceptre :fire::fire::fire::fire:](https://github.com/cloudreach/sceptre)) - A CLI tool for automating CloudFormation.
* <b><code>&nbsp;&nbsp;4950⭐</code></b> <b><code>&nbsp;&nbsp;1419🍴</code></b> [cloudtools/troposphere :fire::fire::fire::fire::fire:](https://github.com/cloudtools/troposphere)) - Python library to create descriptions.
* <b><code>&nbsp;&nbsp;&nbsp;205⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [peterkh/cumulus :fire::fire:](https://github.com/peterkh/cumulus)) - Manages stacks.
* <b><code>&nbsp;&nbsp;&nbsp;294⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [envato/stack_master :fire::fire:](https://github.com/envato/stack_master)) - A CLI tool to manage CloudFormation stacks.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [sparkleformation/sfn](https://github.com/sparkleformation/sfn)) - CLI for stack management.
* <b><code>&nbsp;&nbsp;&nbsp;221⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [sparkleformation/sparkle_formation :fire::fire:](https://github.com/sparkleformation/sparkle_formation)) - Ruby DSL for template creation.
* <b><code>&nbsp;&nbsp;1304⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;209🍴</code></b> [Stelligent/cfn_nag :fire::fire::fire::fire:](https://github.com/stelligent/cfn_nag)) - Linting tool for CloudFormation templates

### CloudSearch

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [cloudsearchable](https://github.com/awslabs/cloudsearchable)) - An ActiveRecord-style ORM query interface.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### CloudTrail

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [aws-cloudtrail-processing-library](https://github.com/aws/aws-cloudtrail-processing-library)) - Easily consume and process log files.

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;358⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [AppliedTrust/traildash :fire::fire:](https://github.com/AppliedTrust/traildash)) - Slick dashboard.
* <b><code>&nbsp;&nbsp;&nbsp;464⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;165🍴</code></b> [GorillaStack/auto-tag :fire::fire:](https://github.com/GorillaStack/auto-tag)) - Automatically tag AWS resources on creation, for cost assignment.

### CloudWatch

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;399⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [cloudwatch-logs-subscription-consumer :fire::fire:](https://github.com/awslabs/cloudwatch-logs-subscription-consumer)) - Kinesis stream reader.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [ecs-cloudwatch-logs](https://github.com/awslabs/ecs-cloudwatch-logs)) - Assets in the blog post on using Amazon ECS and Amazon CloudWatch logs.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [logstash-output-cloudwatchlogs](https://github.com/awslabs/logstash-output-cloudwatchlogs)) - A logstash plugin that sends logs to CloudWatch.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [opsworks-cloudwatch-logs-cookbooks](https://github.com/awslabs/opsworks-cloudwatch-logs-cookbooks)) - OpsWorks sample cookbook.

Community Repos:

* <b><code>&nbsp;&nbsp;4978⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;339🍴</code></b> [jorgebastida/awslogs :fire::fire::fire::fire::fire:](https://github.com/jorgebastida/awslogs)) - Simple CLI for querying groups, streams and events.
* <b><code>&nbsp;&nbsp;&nbsp;152⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [newrelic-platform/newrelic_aws_cloudwatch_plugin :fire:](https://github.com/newrelic-platform/newrelic_aws_cloudwatch_plugin)) - New Relic plugin.

### Code Deploy

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;336⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;189🍴</code></b> [aws-codedeploy-agent :fire::fire:](https://github.com/aws/aws-codedeploy-agent)) - Sample agent.
* <b><code>&nbsp;&nbsp;&nbsp;156⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [aws-codedeploy-plugin :fire:](https://github.com/awslabs/aws-codedeploy-plugin)) - Jenkins plugin.
* <b><code>&nbsp;&nbsp;&nbsp;638⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;784🍴</code></b> [aws-codedeploy-samples :fire::fire::fire:](https://github.com/awslabs/aws-codedeploy-samples)) - Samples and template scenarios.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### Code Pipeline

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [aws-codepipeline-custom-job-worker](https://github.com/awslabs/aws-codepipeline-custom-job-worker)) - Develop your own job worker when creating a custom action.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;1447🍴</code></b> [aws-codepipeline-jenkins-aws-codedeploy_linux](https://github.com/awslabs/aws-codepipeline-jenkins-aws-codedeploy_linux)) - Four-stage pipeline for Linux.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70🍴</code></b> [aws-codepipeline-plugin-for-jenkins](https://github.com/awslabs/aws-codepipeline-plugin-for-jenkins)) - Jenkins plugin.
* <b><code>&nbsp;&nbsp;&nbsp;166⭐</code></b> <b><code>&nbsp;&nbsp;6001🍴</code></b> [aws-codepipeline-s3-aws-codedeploy_linux :fire:](https://github.com/awslabs/aws-codepipeline-s3-aws-codedeploy_linux)) - Simple pipeline for Linux.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;283🍴</code></b> [AWSCodePipeline-Jenkins-AWSCodeDeploy_Windows](https://github.com/awslabs/AWSCodePipeline-Jenkins-AWSCodeDeploy_Windows)) - Four-stage pipeline for Windows.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [AWSCodePipeline-S3-AWSCodeDeploy_Windows](https://github.com/awslabs/AWSCodePipeline-S3-AWSCodeDeploy_Windows)) - Simple pipeline for Windows.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### Cognito

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [amazon-cognito-android](https://github.com/aws/amazon-cognito-android)) - Sync SDK for Android.
* <b><code>&nbsp;&nbsp;&nbsp;101⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [amazon-cognito-developer-authentication-sample](https://github.com/awslabs/amazon-cognito-developer-authentication-sample)) - Authentication sample.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [amazon-cognito-dotnet](https://github.com/aws/amazon-cognito-dotnet)) - Sync SDK for .NET.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [amazon-cognito-ios](https://github.com/aws/amazon-cognito-ios)) - Sync SDK for iOS.
* <b><code>&nbsp;&nbsp;&nbsp;199⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [amazon-cognito-js :fire::fire:](https://github.com/aws/amazon-cognito-js)) - Sync SDK for JavaScript.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [amazon-cognito-streams-sample](https://github.com/awslabs/amazon-cognito-streams-sample)) - Consuming Streams sample.
* <b><code>&nbsp;&nbsp;&nbsp;122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [cognito-sample-nodejs :fire:](https://github.com/awslabs/cognito-sample-nodejs)) - Sample App for Node.js.

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;474⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [capeless/warrant :fire::fire:](https://github.com/capless/warrant)) - Python library for using Cognito.
* <b><code>&nbsp;&nbsp;&nbsp;201⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [rahulpsd18/cognito-backup-restore :fire:](https://github.com/rahulpsd18/cognito-backup-restore)) - Tool for backing up and restoring Cognito user pools.

### Data Pipeline

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;470⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;262🍴</code></b> [data-pipeline-samples :fire::fire:](https://github.com/awslabs/data-pipeline-samples)) - Sample pipelines.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### Device Farm

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;78🍴</code></b> [aws-device-farm-appium-tests-for-sample-app](https://github.com/awslabs/aws-device-farm-appium-tests-for-sample-app)) - Appium TestNG Android tests.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [aws-device-farm-calabash-tests-for-sample-app](https://github.com/awslabs/aws-device-farm-calabash-tests-for-sample-app)) - Calabash Android tests.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [aws-device-farm-gradle-plugin](https://github.com/awslabs/aws-device-farm-gradle-plugin)) - Gradle plugin.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [aws-device-farm-jenkins-plugin](https://github.com/awslabs/aws-device-farm-jenkins-plugin)) - Jenkins plugin.
* <b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;206🍴</code></b> [aws-device-farm-sample-app-for-android :fire:](https://github.com/awslabs/aws-device-farm-sample-app-for-android)) - Sample Android app.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### DynamoDB

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [aws-dotnet-session-provider](https://github.com/aws/aws-dotnet-session-provider)) - A session state provider for ASP.NET apps.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [aws-dotnet-trace-listener](https://github.com/aws/aws-dotnet-trace-listener)) - A trace listener for System.Diagnostics that can be used to log events.
* <b><code>&nbsp;&nbsp;&nbsp;138⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;71🍴</code></b> [aws-dynamodb-encryption-java :fire:](https://github.com/awslabs/aws-dynamodb-encryption-java)) - Encryption Client for Java.
* <b><code>&nbsp;&nbsp;&nbsp;593⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;237🍴</code></b> [aws-dynamodb-examples :fire::fire:](https://github.com/awslabs/aws-dynamodb-examples)) - Samples using the Java SDK.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [aws-dynamodb-mars-json-demo](https://github.com/awslabs/aws-dynamodb-mars-json-demo)) - Stores and indexes NASA JPL Mars images.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [aws-dynamodb-session-tomcat](https://github.com/aws/aws-dynamodb-session-tomcat)) - Session store for Apache Tomcat.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [aws-sessionstore-dynamodb-ruby](https://github.com/aws/aws-sessionstore-dynamodb-ruby)) - Handles sessions for Ruby web apps.
* <b><code>&nbsp;&nbsp;&nbsp;275⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [dynamodb-cross-region-library :fire::fire:](https://github.com/awslabs/dynamodb-cross-region-library)) - Cross-region replication.
* <b><code>&nbsp;&nbsp;&nbsp;276⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95🍴</code></b> [dynamodb-geo :fire::fire:](https://github.com/awslabs/dynamodb-geo)) - Library to create and query geospatial data.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [dynamodb-import-export-tool](https://github.com/awslabs/dynamodb-import-export-tool)) - Import and export examples.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [dynamodb-online-index-violation-detector](https://github.com/awslabs/dynamodb-online-index-violation-detector)) - Finds violations on an online GSI's hash key and range key.
* <b><code>&nbsp;&nbsp;&nbsp;104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [dynamodb-streams-kinesis-adapter](https://github.com/awslabs/dynamodb-streams-kinesis-adapter)) - Kinesis interface to consume and process data from a DynamoDB stream.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [dynamodb-tictactoe-example-app](https://github.com/awslabs/dynamodb-tictactoe-example-app)) - Lightweight python app.
* <b><code>&nbsp;&nbsp;&nbsp;446⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [dynamodb-titan-storage-backend :fire::fire:](https://github.com/awslabs/dynamodb-titan-storage-backend)) - Storage Backend for Titan.
* <b><code>&nbsp;&nbsp;&nbsp;358⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88🍴</code></b> [dynamodb-transactions :fire::fire:](https://github.com/awslabs/dynamodb-transactions)) - Performs atomic writes and isolated reads across multiple items and tables.
* <b><code>&nbsp;&nbsp;&nbsp;104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [logstash-input-dynamodb :fire:](https://github.com/awslabs/logstash-input-dynamodb)) - Logstash input plugin.

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;310⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82🍴</code></b> [channl/dynamodb-lambda-autoscale :fire::fire:](https://github.com/channl/dynamodb-lambda-autoscale)) - Autoscale DynamoDB provisioned capacity using Lambda.
* <b><code>&nbsp;&nbsp;1858⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [lyft/confidant :fire::fire::fire::fire:](https://github.com/lyft/confidant)) - Stores secrets, encrypted at rest.
* <b><code>&nbsp;&nbsp;&nbsp;618⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [sebdah/dynamic-dynamodb :fire::fire::fire:](https://github.com/sebdah/dynamic-dynamodb)) - Provides auto-scaling.
* <b><code>&nbsp;&nbsp;&nbsp;716⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [sensedeep/dynamodb-onetable :fire::fire::fire:](https://github.com/sensedeep/dynamodb-onetable)) - DynamoDB library for single table designs using NodeJS.

### Elastic Beanstalk

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [aws-eb-glassfish-dockerfiles](https://github.com/aws/aws-eb-glassfish-dockerfiles)) - GlassFish docker files.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [aws-eb-python-dockerfiles](https://github.com/aws/aws-eb-python-dockerfiles)) - Python docker files.
* <b><code>&nbsp;&nbsp;&nbsp;147⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;181🍴</code></b> [eb-demo-php-simple-app :fire:](https://github.com/awslabs/eb-demo-php-simple-app)) - Simple PHP app.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [eb-docker-multiple-ports](https://github.com/awslabs/eb-docker-multiple-ports)) - Simple Node.js and Tomcat apps using Docker images.
* <b><code>&nbsp;&nbsp;&nbsp;145⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [eb-docker-nginx-proxy :fire:](https://github.com/awslabs/eb-docker-nginx-proxy)) - Simple PHP app using the PHP-FPM and Nginx Docker images.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [eb-docker-virtual-hosting](https://github.com/awslabs/eb-docker-virtual-hosting)) - Simple PHP, Tomcat, and Nginx applications using Docker images.
* <b><code>&nbsp;&nbsp;&nbsp;281⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;248🍴</code></b> [eb-node-express-sample :fire::fire:](https://github.com/awslabs/eb-node-express-sample)) - Sample express app.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [eb-node-express-signup](https://github.com/awslabs/eb-node-express-signup)) - Express framework and Bootstrap Node.js sample app.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [eb-node-express](https://github.com/awslabs/eb-node-express)) - Sample app referenced in the Developer Guide.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [eb-py-flask-signup-worker](https://github.com/awslabs/eb-py-flask-signup-worker)) - Python app that illustrates worker roles.
* <b><code>&nbsp;&nbsp;&nbsp;265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;159🍴</code></b> [eb-py-flask-signup :fire::fire:](https://github.com/awslabs/eb-py-flask-signup)) - Python signup form app with Flask and Bootstrap.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69🍴</code></b> [eb-python-flask](https://github.com/awslabs/eb-python-flask)) - Simple Python and Flask app.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [eb-wif-sample](https://github.com/awslabs/eb-wif-sample)) - Sample login app with Web Identity Federation.

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;189⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [alienfast/elastic-beanstalk :fire:](https://github.com/alienfast/elastic-beanstalk)) - Gem with rake configuration and deployment for rails apps.
* <b><code>&nbsp;&nbsp;&nbsp;394⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [ThoughtWorksStudios/eb_deployer :fire::fire:](https://github.com/ThoughtWorksStudios/eb_deployer)) - Blue-green deployment automation.

### Elastic Compute Cloud

AWS Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;437⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;106🍴</code></b> [alestic/ec2-consistent-snapshot :fire::fire:](https://github.com/alestic/ec2-consistent-snapshot)) - Initiate consistent EBS snapshots in EC2.
* <b><code>&nbsp;&nbsp;&nbsp;561⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [ConradIrwin/aws-name-server :fire::fire::fire:](https://github.com/ConradIrwin/aws-name-server)) - DNS server that lets you look up instances by name.
* <b><code>&nbsp;&nbsp;2362⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;312🍴</code></b> [cristim/autospotting :fire::fire::fire::fire::fire:](https://github.com/autospotting/autospotting)) - Automatically rolling-replace on-demand EC2 instances in AutoScaling groups with compatible spot instances.
* <b><code>&nbsp;&nbsp;&nbsp;208⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;122🍴</code></b> [evannuil/aws-snapshot-tool :fire::fire:](https://github.com/evannuil/aws-snapshot-tool)) - Automates EBS snapshots and rotation.
* <b><code>&nbsp;47611⭐</code></b> <b><code>&nbsp;15539🍴</code></b> [kelseyhightower/kubernetes-the-hard-way :fire::fire::fire::fire::fire:](https://github.com/kelseyhightower/kubernetes-the-hard-way)) - Bootstrap Kubernetes the hard way on EC2. No scripts.
* <b><code>&nbsp;&nbsp;&nbsp;252⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [mirakui/ec2ssh :fire::fire:](https://github.com/mirakui/ec2ssh)) - SSH config manager.
* <b><code>&nbsp;&nbsp;9636⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;978🍴</code></b> [openebs/openebs :fire::fire::fire::fire::fire:](https://github.com/openebs/openebs)) - Containerized block storage QoS SLAs, tiering and replica policies across AZs and environments, and predictable and scalable performance.
* <b><code>&nbsp;&nbsp;&nbsp;429⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [skavanagh/EC2Box :fire::fire:](https://github.com/skavanagh/EC2Box)) - A web-based SSH console to manage multiple instances simultaneously.
* <b><code>&nbsp;&nbsp;&nbsp;164⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [wbailey/claws :fire:](https://github.com/wbailey/claws)) - CLI-driven console with capistrano integration.

### Elastic Container Service

AWS Repos:

* <b><code>&nbsp;&nbsp;2144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;648🍴</code></b> [amazon-ecs-agent :fire::fire::fire::fire:](https://github.com/aws/amazon-ecs-agent)) - Agent that runs on and starts containers.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [amazon-ecs-amazon-efs](https://github.com/awslabs/amazon-ecs-amazon-efs)) - Persists Data from containers.
* <b><code>&nbsp;&nbsp;&nbsp;197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;112🍴</code></b> [amazon-ecs-init :fire:](https://github.com/aws/amazon-ecs-init)) - RPM developed to support the Amazon ECS Container Agent.
* <b><code>&nbsp;&nbsp;&nbsp;938⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [blox :fire::fire::fire:](https://github.com/blox/blox)) - Open source tools for building custom schedulers on ECS.
* <b><code>&nbsp;&nbsp;&nbsp;461⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;463🍴</code></b> [ecs-blue-green-deployment :fire::fire:](https://github.com/awslabs/ecs-blue-green-deployment)) - Blue-green deployment on ECS.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [ecs-cloudwatch-logs](https://github.com/awslabs/ecs-cloudwatch-logs)) - Assets from the blog using Amazon ECS and Amazon CloudWatch logs.
* <b><code>&nbsp;&nbsp;&nbsp;173⭐</code></b> <b><code>&nbsp;&nbsp;3306🍴</code></b> [ecs-demo-php-simple-app :fire:](https://github.com/awslabs/ecs-demo-php-simple-app)) - Simple PHP app.
* <b><code>&nbsp;&nbsp;&nbsp;170⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [ecs-mesos-scheduler-driver :fire:](https://github.com/awslabs/ecs-mesos-scheduler-driver)) - Integrates Apache Mesos.
* <b><code>&nbsp;&nbsp;&nbsp;854⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;981🍴</code></b> [ecs-refarch-continuous-deployment :fire::fire::fire:](https://github.com/awslabs/ecs-refarch-continuous-deployment)) - Reference Architecture for continuous deployment to ECS using CodePipeline.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [ecs-task-kite](https://github.com/awslabs/ecs-task-kite)) - Simple ambassador container for inter-task communication.
* <b><code>&nbsp;&nbsp;&nbsp;293⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [lambda-ecs-worker-pattern :fire::fire:](https://github.com/awslabs/lambda-ecs-worker-pattern)) - Extends Lambda using SQS and ECS.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;504🍴</code></b> [py-flask-signup-docker](https://github.com/awslabs/py-flask-signup-docker)) - Python sample app.
* <b><code>&nbsp;&nbsp;&nbsp;106⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [service-discovery-ecs-consul :fire:](https://github.com/awslabs/service-discovery-ecs-consul)) - Assets from the blog Service Discovery via Consul with Amazon ECS.

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Lumoslabs/broadside](https://github.com/lumoslabs/broadside)) - Command line tool for deploying revisions of containerized applications.
* <b><code>&nbsp;&nbsp;&nbsp;965⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;133🍴</code></b> [Stelligent/mu :fire::fire::fire:](https://github.com/stelligent/mu)) - Command line tool to simplify ECS deployments via CodeBuild and CodePipeline.

### Elastic File System

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [amazon-ecs-amazon-efs](https://github.com/awslabs/amazon-ecs-amazon-efs)) - Persist data from ECS.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### Elastic MapReduce

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;613⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;303🍴</code></b> [emr-bootstrap-actions :fire::fire::fire:](https://github.com/awslabs/emr-bootstrap-actions)) - Sample bootstrap actions.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [emr-sample-apps](https://github.com/awslabs/emr-sample-apps)) - Sample apps.

Community Repos:

* <b><code>&nbsp;&nbsp;2617⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;586🍴</code></b> [Yelp/mrjob :fire::fire::fire::fire::fire:](https://github.com/Yelp/mrjob)) - Run MapReduce jobs on Hadoop or EMR.

### Elastic Search

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;374⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [logstash-output-amazon_es :fire::fire:](https://github.com/awslabs/logstash-output-amazon_es)) - Logstash output plugin to sign and export events.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [opsworks-elasticsearch-cookbook](https://github.com/awslabs/opsworks-elasticsearch-cookbook)) - OpsWorks Elasticsearch sample cookbook.

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;575⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;179🍴</code></b> [elastic/elasticsearch-cloud-aws :fire::fire::fire:](https://github.com/elastic/elasticsearch-cloud-aws)) - Plugin for Elasticsearch.

### Elasticache

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [aws-elasticache-cluster-client-libmemcached](https://github.com/awslabs/aws-elasticache-cluster-client-libmemcached)) - Libmemcached library support.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [aws-elasticache-cluster-client-memcached-for-java](https://github.com/awslabs/aws-elasticache-cluster-client-memcached-for-java)) - Client for Java.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [aws-elasticache-cluster-client-memcached-for-php](https://github.com/awslabs/aws-elasticache-cluster-client-memcached-for-php)) - Enhanced PHP library connecting to ElastiCache.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [elasticache-cluster-config-net](https://github.com/awslabs/elasticache-cluster-config-net)) - Config object for Enyim's MemcachedClient to enable auto discovery.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### Glacier

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;538⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55🍴</code></b> [vsespb/mt-aws-glacier :fire::fire::fire:](https://github.com/vsespb/mt-aws-glacier)) - Perl Multithreaded Multipart sync to Glacier.

### Kinesis

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;152⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [amazon-kinesis-aggregators :fire:](https://github.com/awslabs/amazon-kinesis-aggregators)) - Provides a simple way to create real time aggregations.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [amazon-kinesis-client-net](https://github.com/awslabs/amazon-kinesis-client-net)) - Client Library for .NET.
* <b><code>&nbsp;&nbsp;&nbsp;306⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;199🍴</code></b> [amazon-kinesis-client-nodejs :fire::fire:](https://github.com/awslabs/amazon-kinesis-client-nodejs)) - Client Library for Node.js.
* <b><code>&nbsp;&nbsp;&nbsp;376⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;227🍴</code></b> [amazon-kinesis-client-python :fire::fire:](https://github.com/awslabs/amazon-kinesis-client-python)) - Client Library for Python.
* <b><code>&nbsp;&nbsp;&nbsp;148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [amazon-kinesis-client-ruby :fire:](https://github.com/awslabs/amazon-kinesis-client-ruby)) - Client Library for Ruby.
* <b><code>&nbsp;&nbsp;&nbsp;660⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;481🍴</code></b> [amazon-kinesis-client :fire::fire::fire:](https://github.com/awslabs/amazon-kinesis-client)) Client library for Amazon Kinesis.
* <b><code>&nbsp;&nbsp;&nbsp;328⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;188🍴</code></b> [amazon-kinesis-connectors :fire::fire:](https://github.com/awslabs/amazon-kinesis-connectors)) - Libary to integrate with other AWS and non-AWS services.
* <b><code>&nbsp;&nbsp;&nbsp;171⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [amazon-kinesis-data-visualization-sample :fire:](https://github.com/awslabs/amazon-kinesis-data-visualization-sample)) - Sample data visualization app.
* <b><code>&nbsp;&nbsp;&nbsp;110⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;138🍴</code></b> [amazon-kinesis-learning](https://github.com/awslabs/amazon-kinesis-learning)) - Learning Kinesis Development.
* <b><code>&nbsp;&nbsp;&nbsp;413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;341🍴</code></b> [amazon-kinesis-producer :fire::fire:](https://github.com/awslabs/amazon-kinesis-producer)) - Producer Library.
* <b><code>&nbsp;&nbsp;&nbsp;335⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [amazon-kinesis-scaling-utils :fire::fire:](https://github.com/awslabs/amazon-kinesis-scaling-utils)) - Provides the ability to scale streams.
* <b><code>&nbsp;&nbsp;&nbsp;289⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [aws-fluent-plugin-kinesis :fire::fire:](https://github.com/awslabs/aws-fluent-plugin-kinesis)) - Fluent Plugin.
* <b><code>&nbsp;&nbsp;&nbsp;104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [dynamodb-streams-kinesis-adapter](https://github.com/awslabs/dynamodb-streams-kinesis-adapter)) - DynamoDB Streams Adapter.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [kinesis-log4j-appender](https://github.com/awslabs/kinesis-log4j-appender)) - Log4J Appender.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [kinesis-poster-worker](https://github.com/awslabs/kinesis-poster-worker)) - Simple multi-threaded Python Poster and Worker.
* <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61🍴</code></b> [kinesis-storm-spout :fire:](https://github.com/awslabs/kinesis-storm-spout)) - Spout for Storm.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [mqtt-kinesis-bridge](https://github.com/awslabs/mqtt-kinesis-bridge)) - Simple MQTT bridge in Python.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### Lambda

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;386⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;172🍴</code></b> [amazon-elasticsearch-lambda-samples :fire::fire:](https://github.com/awslabs/amazon-elasticsearch-lambda-samples)) - Data ingestion for Elasticsearch from S3 and Kinesis.
* <b><code>&nbsp;&nbsp;6699⭐</code></b> <b><code>&nbsp;&nbsp;1209🍴</code></b> [awslabs/aws-sam-local :fire::fire::fire::fire::fire:](https://github.com/awslabs/aws-sam-local)) - CLI tool for local development and testing of Serverless applications.
* <b><code>&nbsp;&nbsp;3796⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;573🍴</code></b> [aws-lambda-go :fire::fire::fire::fire::fire:](https://github.com/aws/aws-lambda-go)) - Libraries, samples and tools to help Go developers develop Lambda functions.
* <b><code>&nbsp;&nbsp;&nbsp;545⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;240🍴</code></b> [aws-lambda-java-libs :fire::fire:](https://github.com/aws/aws-lambda-java-libs)) - Official mirror for interface definitions and helper classes.
* <b><code>&nbsp;&nbsp;&nbsp;596⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;161🍴</code></b> [aws-lambda-redshift-loader :fire::fire::fire:](https://github.com/awslabs/aws-lambda-redshift-loader)) - Redshift loader.
* <b><code>&nbsp;11060⭐</code></b> <b><code>&nbsp;&nbsp;1005🍴</code></b> [chalice :fire::fire::fire::fire::fire:](https://github.com/awslabs/chalice)) - Python Serverless Microframework.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [create-thumbnails-lambda](https://github.com/awslabs/create-thumbnails-lambda)) - Uses the grunt-aws-lambda plugin to help you develop and test.
* <b><code>&nbsp;&nbsp;&nbsp;293⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [lambda-ecs-worker-pattern :fire::fire:](https://github.com/awslabs/lambda-ecs-worker-pattern)) - Extends Lambda using SQS and ECS.
* <b><code>&nbsp;&nbsp;&nbsp;470⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;178🍴</code></b> [lambda-refarch-fileprocessing :fire::fire:](https://github.com/awslabs/lambda-refarch-fileprocessing)) - Reference Architecture for Real-time File Processing.
* <b><code>&nbsp;&nbsp;&nbsp;253⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [lambda-refarch-iotbackend :fire::fire:](https://github.com/awslabs/lambda-refarch-iotbackend)) - Reference Architecture for creating an IoT Backend.
* <b><code>&nbsp;&nbsp;&nbsp;587⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [lambda-refarch-mobilebackend :fire::fire::fire:](https://github.com/awslabs/lambda-refarch-mobilebackend)) - Reference Architecture for creating a Mobile Backend.
* <b><code>&nbsp;&nbsp;1597⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;913🍴</code></b> [lambda-refarch-webapp :fire::fire::fire::fire:](https://github.com/awslabs/lambda-refarch-webapp)) - Reference Architecture for creating a Web Application.

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;533⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [alestic/lambdash :fire::fire::fire:](https://github.com/alestic/lambdash)) - Lambda shell - Run sh commands inside the Lambda environment.
* <b><code>&nbsp;&nbsp;&nbsp;227⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Alephbet/gimel :fire::fire:](https://github.com/Alephbet/gimel)) - Run your own A/B testing backend using Lambda.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [apex/apex ](https://github.com/apex/apex)) - Minimal AWS Lambda function manager with Go support.
* <b><code>&nbsp;&nbsp;3888⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;277🍴</code></b> [claudiajs/claudia :fire::fire::fire::fire::fire:](https://github.com/claudiajs/claudia)) - Deploy Node.js projects to Lambda and API Gateway easily.
* <b><code>&nbsp;&nbsp;&nbsp;389⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [cloudnative/lambda-chat :fire::fire:](https://github.com/cloudnative/lambda-chat)) - A chat application without servers.
* <b><code>&nbsp;&nbsp;1372⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;229🍴</code></b> [danilop/LambdAuth :fire::fire::fire::fire:](https://github.com/danilop/LambdAuth)) - Sample authentication service.
* <b><code>&nbsp;&nbsp;&nbsp;698⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [eawsy/aws-lambda-go :fire::fire::fire:](https://github.com/eawsy/aws-lambda-go)) - A fast and clean way to execute Go on Lambda.
* <b><code>&nbsp;&nbsp;&nbsp;900⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86🍴</code></b> [garnaat/kappa :fire::fire::fire:](https://github.com/garnaat/kappa)) - Kappa is a CLI tool that makes it easier to deploy, update, and test functions for AWS Lambda.
* <b><code>&nbsp;&nbsp;1878⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;184🍴</code></b> [goadapp/goad :fire::fire::fire::fire:](https://github.com/goadapp/goad)) - Lambda powered, highly distributed, load testing tool.
* <b><code>&nbsp;13247⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;570🍴</code></b> [graphcool/chromeless :fire::fire::fire::fire::fire:](https://github.com/graphcool/chromeless)) - Automate Chrome through Lambda.
* <b><code>&nbsp;&nbsp;&nbsp;600⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [grycap/scar :fire::fire::fire:](https://github.com/grycap/scar)) - Transparently execute containers out of Docker images in AWS Lambda.
* <b><code>&nbsp;&nbsp;1468⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [jeremydaly/lambda-api :fire::fire::fire::fire:](https://github.com/jeremydaly/lambda-api)) - Lightweight web framework for your serverless applications.
* <b><code>&nbsp;&nbsp;&nbsp;620⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [jimpick/lambda-comments :fire::fire::fire:](https://github.com/jimpick/lambda-comments)) - Blog commenting system built with Lambda.
* <b><code>&nbsp;&nbsp;2030⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;135🍴</code></b> [jorgebastida/gordon :fire::fire::fire::fire::fire:](https://github.com/jorgebastida/gordon)) - λ Gordon is a tool to create, wire and deploy AWS Lambdas using CloudFormation.
* <b><code>&nbsp;&nbsp;1293⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [ks888/LambStatus :fire::fire::fire::fire:](https://github.com/ks888/LambStatus)) - A status page system inspired by StatusPage.io, built on AWS Lambda.
* <b><code>&nbsp;&nbsp;&nbsp;567⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [kubek2k/lambdoku :fire::fire::fire:](https://github.com/kubek2k/lambdoku)) - Heroku-like experience when using Lambda.
* <b><code>&nbsp;&nbsp;3974⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;186🍴</code></b> [lambci/lambci :fire::fire::fire::fire::fire:](https://github.com/lambci/lambci)) - A continuous integration system built on Lambda.
* <b><code>&nbsp;&nbsp;1060⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [littlstar/s3-lambda :fire::fire::fire::fire:](https://github.com/littlstar/s3-lambda)) - Lambda functions over S3 objects with concurrency control (each, map, reduce, filter).
* <b><code>&nbsp;&nbsp;1273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [mentum/lambdaws :fire::fire::fire::fire:](https://github.com/mentum/lambdaws)) - Deploy, run and get results in a breeze.
* <b><code>&nbsp;11852⭐</code></b> <b><code>&nbsp;&nbsp;1183🍴</code></b> [Miserlou/Zappa :fire::fire::fire::fire::fire:](https://github.com/Miserlou/Zappa)) - Serverless WSGI Python Web Apps with AWS Lambda + API Gateway.
* <b><code>&nbsp;&nbsp;1521⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;225🍴</code></b> [nficano/python-lambda :fire::fire::fire::fire:](https://github.com/nficano/python-lambda)) - A toolkit for developing and deploying serverless Python code in Lambda.
* <b><code>&nbsp;46949⭐</code></b> <b><code>&nbsp;&nbsp;5735🍴</code></b> [serverless/serverless :fire::fire::fire::fire::fire:](https://github.com/serverless/serverless)) The Serverless Application Framework (formerly JAWS).
* <b><code>&nbsp;&nbsp;&nbsp;244⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99🍴</code></b> [Tim-B/grunt-aws-lambda :fire::fire:](https://github.com/Tim-B/grunt-aws-lambda)) - Grunt plugin.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [trek10inc/aws-lambda-debugger :fire::fire:](https://github.com/trek10inc/aws-lambda-debugger)) - Remote debugging tool for Lambda functions running on Node 6.10

### Machine Learning

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;883⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;387🍴</code></b> [machine-learning-samples :fire::fire::fire:](https://github.com/awslabs/machine-learning-samples)) - Sample apps.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### Mobile Analytics

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [aws-sdk-mobile-analytics-js](https://github.com/aws/aws-sdk-mobile-analytics-js)) - JavaScript SDK.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### OpsWorks

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [opsworks-attribute-customization](https://github.com/awslabs/opsworks-attribute-customization)) - Attribute customization example.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [opsworks-capistrano](https://github.com/awslabs/opsworks-capistrano)) - Capistrano with instances.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [opsworks-cloudwatch-logs-cookbooks](https://github.com/awslabs/opsworks-cloudwatch-logs-cookbooks)) - CloudWatch sample cookbook.
* <b><code>&nbsp;&nbsp;1046⭐</code></b> <b><code>&nbsp;&nbsp;1203🍴</code></b> [opsworks-cookbooks :fire::fire::fire::fire:](https://github.com/aws/opsworks-cookbooks)) - Chef Cookbooks.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [opsworks-demo-php-photo-share-app](https://github.com/awslabs/opsworks-demo-php-photo-share-app)) - Simple PHP photo share app.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;193🍴</code></b> [opsworks-demo-php-simple-app](https://github.com/awslabs/opsworks-demo-php-simple-app)) - Simple PHP app.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39🍴</code></b> [opsworks-demo-rails-photo-share-app](https://github.com/awslabs/opsworks-demo-rails-photo-share-app)) - A sample Rails app.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;116🍴</code></b> [opsworks-elasticsearch-cookbook](https://github.com/awslabs/opsworks-elasticsearch-cookbook)) - Elasticsearch sample cookbook.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;141🍴</code></b> [opsworks-example-cookbooks :fire:](https://github.com/awslabs/opsworks-example-cookbooks)) - Cookbooks used with the sample apps.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [opsworks-first-cookbook](https://github.com/awslabs/opsworks-first-cookbook)) - Cookbook used to demonstrate simple recipes.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;396🍴</code></b> [opsworks-windows-demo-](https://github.com/awslabs/opsworks-windows-demo-nodejs)) - A sample Node.JS app.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [opsworks-windows-demo-cookbooks](https://github.com/awslabs/opsworks-windows-demo-cookbooks)) - Cookbooks for Windows.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [todo-sample-app-cookbooks](https://github.com/awslabs/todo-sample-app-cookbooks)) - Custom cookbooks associated with the todo-sample-app.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### Redshift

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;596⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;161🍴</code></b> [aws-lambda-redshift-loader :fire::fire::fire:](https://github.com/awslabs/aws-lambda-redshift-loader)) - Lambda database loader.
* <b><code>&nbsp;&nbsp;2811⭐</code></b> <b><code>&nbsp;&nbsp;1247🍴</code></b> [amazon-redshift-utils :fire::fire::fire::fire::fire:](https://github.com/awslabs/amazon-redshift-utils)) - Applies optimal Column Encoding to existing Tables.

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Lumoslabs/aleph](https://github.com/lumoslabs/aleph)) - A full featured web application for writing and running Redshift
queries. Supports revision tracking of queries and has basic visualization support.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [getredash/redash :fire::fire::fire::fire::fire:](https://github.com/getredash/redash/)) - A web application that allows to easily query an existing database, share the dataset and visualize it in different ways. Initially was developed to work with Redshift, and has great support for it.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [everythingMe/redshift_console](https://github.com/EverythingMe/redshift_console)) -  A simple tool to monitor and manage a Redshift cluster. The first release has basic tools to monitor running queries, WLM queue and your tables/schemas.

### Route 53

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;361⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26🍴</code></b> [route53-infima :fire::fire:](https://github.com/awslabs/route53-infima)) - Manages service-level fault isolation.

Community Repos:

* <b><code>&nbsp;&nbsp;2128⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;268🍴</code></b> [barnybug/cli53 :fire::fire::fire::fire:](https://github.com/barnybug/cli53)) - cli53 is a command line tool for Amazon Route 53 which provides import and export from BIND format and simple command line management of Route 53 domains.
* <b><code>&nbsp;&nbsp;&nbsp;325⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [winebarrel/roadworker :fire::fire:](https://github.com/winebarrel/roadworker)) - Roadworker is a tool to manage Route53. It defines the state of Route53 using DSL, and updates Route53 according to DSL.

### S3

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;474⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [anomalizer/ngx_aws_auth :fire::fire:](https://github.com/anomalizer/ngx_aws_auth)) - Implements proxying of authenticated requests.
* <b><code>&nbsp;&nbsp;1399⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;211🍴</code></b> [bloomreach/s4cmd :fire::fire::fire::fire:](https://github.com/bloomreach/s4cmd)) - S3 command line tool, faster than S3cmd for large files.
* <b><code>&nbsp;&nbsp;&nbsp;593⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [CulturalMe/meteor-slingshot :fire::fire::fire:](https://github.com/CulturalMe/meteor-slingshot)) - Upload files in meteor.
* <b><code>&nbsp;&nbsp;&nbsp;657⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [danilop/yas3fs :fire::fire::fire:](https://github.com/danilop/yas3fs)) - Yet Another S3-backed File System, inspired by s3fs.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [grippy/node-s3](https://github.com/grippy/node-s3)) - Node.js app to manage buckets.
* <b><code>&nbsp;&nbsp;2930⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;352🍴</code></b> [jubos/fake-s3 :fire::fire::fire::fire::fire:](https://github.com/jubos/fake-s3)) - Lightweight S3 clone that simulates most commands.
* <b><code>&nbsp;&nbsp;5514⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;531🍴</code></b> [kahing/goofys :fire::fire::fire::fire::fire:](https://github.com/kahing/goofys)) -  a Filey System for Amazon S3 written in Go.
* <b><code>&nbsp;&nbsp;1060⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47🍴</code></b> [littlstar/s3renity :fire::fire::fire::fire:](https://github.com/littlstar/s3renity)) - Batch functions with concurrency control (each, map, reduce, filter, join)
* <b><code>&nbsp;&nbsp;&nbsp;773⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;458🍴</code></b> [marcel/aws-s3 :fire::fire::fire:](https://github.com/marcel/aws-s3)) - Ruby implementation of Amazon's S3 REST API.
* <b><code>&nbsp;&nbsp;&nbsp;245⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [mardix/flask-cloudy :fire::fire:](https://github.com/mardix/flask-cloudy)) - Flask extension.
* <b><code>&nbsp;&nbsp;&nbsp;292⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;89🍴</code></b> [MathieuLoutre/grunt-aws-s3 :fire::fire:](https://github.com/MathieuLoutre/grunt-aws-s3)) - Grunt plugin.
* <b><code>&nbsp;13687⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;963🍴</code></b> [mickael-kerjean/filestash :fire::fire::fire::fire::fire:](https://github.com/mickael-kerjean/filestash)) - A modern web client for S3.
* <b><code>&nbsp;&nbsp;3401⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;658🍴</code></b> [minio/mc :fire::fire::fire::fire::fire:](https://github.com/minio/mc)) -  Minio Client for filesystem and cloud storage.
* <b><code>&nbsp;60403⭐</code></b> <b><code>&nbsp;&nbsp;7156🍴</code></b> [minio/minio :fire::fire::fire::fire::fire:](https://github.com/minio/minio)) - Object storage server compatible with S3.
* <b><code>&nbsp;&nbsp;&nbsp;163⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75🍴</code></b> [mumrah/s3-multipart :fire:](https://github.com/mumrah/s3-multipart)) - Parallel upload/download to S3 via Python.
* <b><code>&nbsp;55800⭐</code></b> <b><code>&nbsp;&nbsp;4939🍴</code></b> [ncw/rclone :fire::fire::fire::fire::fire:](https://github.com/ncw/rclone)) - Rsync for various cloud storage providers such as S3.
* <b><code>&nbsp;&nbsp;&nbsp;168⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [owocki/s3_disk_util :fire:](https://github.com/owocki/s3_disk_util)) - S3 Disk usage (du) utility.
* <b><code>&nbsp;&nbsp;3933⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;334🍴</code></b> [peak/s5cmd :fire::fire::fire:](https://github.com/peak/s5cmd)) - Fast S3 and local filesystem execution tool with wildcard and batch command support.
* <b><code>&nbsp;&nbsp;&nbsp;396⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;84🍴</code></b> [pgherveou/gulp-awspublish :fire::fire:](https://github.com/pgherveou/gulp-awspublish)) - Gulp plugin.
* <b><code>&nbsp;&nbsp;1144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;183🍴</code></b> [rlmcpherson/s3gof3r :fire::fire::fire::fire:](https://github.com/rlmcpherson/s3gof3r)) - Fast, concurrent, streaming access, includes a CLI.
* <b><code>&nbsp;&nbsp;1462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [s3git/s3git :fire::fire::fire::fire:](https://github.com/s3git/s3git)) - CLI tool that allows you to create a distributed, decentralized and versioned repository.
* <b><code>&nbsp;&nbsp;9726⭐</code></b> <b><code>&nbsp;&nbsp;1073🍴</code></b> [s3fs-fuse/s3fs-fuse :fire::fire::fire::fire::fire:](https://github.com/s3fs-fuse/s3fs-fuse)) - Allows Linux and Mac OS X to mount an S3 bucket via FUSE.
* <b><code>&nbsp;&nbsp;4867⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;909🍴</code></b> [s3tools/s3cmd :fire::fire::fire::fire::fire:](https://github.com/s3tools/s3cmd)) - CLI for managing S3 and CloudFront.
* <b><code>&nbsp;&nbsp;&nbsp;233⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [schickling/git-s3 :fire::fire:](https://github.com/schickling/git-s3)) - Deploy your git repo to a bucket.
* <b><code>&nbsp;&nbsp;&nbsp;413⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;107🍴</code></b> [sorentwo/carrierwave-aws :fire::fire:](https://github.com/sorentwo/carrierwave-aws)) - Adapter for CarrierWave.
* <b><code>&nbsp;&nbsp;&nbsp;216⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;172🍴</code></b> [spring-projects/aws-maven :fire::fire:](https://github.com/spring-projects/aws-maven)) -  Maven Wagon for S3.
* <b><code>&nbsp;&nbsp;&nbsp;136⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [tongwang/s3fs-c :fire:](https://github.com/tongwang/s3fs-c)) - Mounts buckets for use on a local file system.
* <b><code>&nbsp;&nbsp;&nbsp;316⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;102🍴</code></b> [mishudark/s3-parallel-put :fire::fire:](https://github.com/mishudark/s3-parallel-put)) - CLI that supports parallel uploads.
* <b><code>&nbsp;&nbsp;&nbsp;653⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;329🍴</code></b> [waynehoover/s3_direct_upload :fire::fire::fire:](https://github.com/waynehoover/s3_direct_upload)) - Direct Upload to Amazon S3 With CORS
* <b><code>&nbsp;&nbsp;&nbsp;200⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;104🍴</code></b> [weavejester/clj-aws-s3 :fire:](https://github.com/weavejester/clj-aws-s3)) - Client library for Clojure.

### SES

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;545⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [drewblas/aws-ses :fire::fire::fire:](https://github.com/drewblas/aws-ses)) - Provides an easy ruby DSL & interface.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [microapps/MoonMail :fire::fire::fire::fire:](https://github.com/microapps/MoonMail)) - Shoot billions of emails using SES and Lambda.

### Simple Workflow

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [aws-flow-ruby :fire:](https://github.com/aws/aws-flow-ruby)) - Creates background jobs and multistep workflows.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [aws-flow-ruby-samples](https://github.com/awslabs/aws-flow-ruby-samples)) - AWS Flow Framework for Ruby samples.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [aws-flow-ruby-opsworks-helloworld](https://github.com/awslabs/aws-flow-ruby-opsworks-helloworld)) - Hello World sample.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### SimpleDB

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;134⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [rjrodger/simpledb :fire:](https://github.com/rjrodger/simpledb)) - Node.js library.

### SNS

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;214⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [aws-php-sns-message-validator :fire:](https://github.com/aws/aws-php-sns-message-validator)) - Message validation for PHP.

Community Repos:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### SQS

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;182⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;149🍴</code></b> [amazon-sqs-java-messaging-lib :fire:](https://github.com/awslabs/amazon-sqs-java-messaging-lib)) - Holds the Java Message Service to communicate with SQS.

Community Repos:

* <b><code>&nbsp;&nbsp;2111⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;290🍴</code></b> [phstc/shoryuken :fire::fire::fire::fire:](https://github.com/phstc/shoryuken)) - A super efficient SQS thread based message processor for Ruby.

### Data

AWS Repos:

* <b><code>&nbsp;&nbsp;4107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;721🍴</code></b> [aws-data-wrangler :fire::fire::fire::fire::fire:](https://github.com/awslabs/aws-data-wrangler)) - Connects Pandas DataFrames and AWS data related services.

Community Repos:

* <b><code>&nbsp;28899⭐</code></b> <b><code>&nbsp;&nbsp;8034🍴</code></b> [donnemartin/data-science-ipython-notebooks :fire::fire::fire::fire::fire:](https://github.com/donnemartin/data-science-ipython-notebooks)) - Big data/data science notebooks.
* <b><code>&nbsp;&nbsp;&nbsp;430⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [everpeace/vagrant-mesos :fire::fire:](https://github.com/everpeace/vagrant-mesos)) - Spin up your Mesos Cluster with Vagrant.
* <b><code>&nbsp;&nbsp;&nbsp;254⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [jhorey/ferry :fire::fire:](https://github.com/jhorey/ferry)) -  Define, run, and deploy big data apps using Docker.
* <b><code>&nbsp;&nbsp;&nbsp;515⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;146🍴</code></b> [nathanmarz/storm-deploy :fire::fire::fire:](https://github.com/nathanmarz/storm-deploy)) - One click deploy for Storm clusters.

### DevOps

Community Repos:

* <b><code>&nbsp;&nbsp;5937⭐</code></b> <b><code>&nbsp;&nbsp;1596🍴</code></b> [cloud-custodian/cloud-custodian :fire::fire::fire::fire::fire:](https://github.com/cloud-custodian/cloud-custodian)) - Rules engine for management, DSL in yaml for query, filter, and actions on resources.
* <b><code>&nbsp;&nbsp;&nbsp;649⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;557🍴</code></b> [chef-cookbooks/aws :fire::fire:](https://github.com/chef-cookbooks/aws)) - Development repository for aws Chef cookbook.
* <b><code>&nbsp;&nbsp;1340⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;401🍴</code></b> [colinbjohnson/aws-missing-tools :fire::fire::fire::fire:](https://github.com/colinbjohnson/aws-missing-tools)) - Tools for managing resources including EC2, EBS, RDS and Route53.
* <b><code>&nbsp;&nbsp;1179⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;190🍴</code></b> [k1LoW/awspec :fire::fire::fire::fire:](https://github.com/k1LoW/awspec)) - RSpec tests your resources.
* <b><code>&nbsp;&nbsp;2595⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;571🍴</code></b> [mitchellh/vagrant-aws :fire::fire::fire::fire::fire:](https://github.com/mitchellh/vagrant-aws)) - Use Vagrant to manage your EC2 and VPC instances.
* <b><code>&nbsp;&nbsp;2124⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;366🍴</code></b> [NixOS/nixops :fire::fire::fire::fire:](https://github.com/NixOS/nixops)) - Use NixOS to provision EC2 instances, S3 buckets, and other resources.

### Security

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [aws-sha256-agentcs](https://github.com/awslabs/aws-sha256-agentcs)) - SHA256 Agent Compatibility Ccanner.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [aws-tvm-anonymous](https://github.com/awslabs/aws-tvm-anonymous)) - Token Vending Machine for Anonymous Registration.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [aws-tvm-identity](https://github.com/awslabs/aws-tvm-identity)) - Token Vending Machine for Identity Registration.
* <b><code>&nbsp;&nbsp;4691⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;763🍴</code></b> [s2n :fire::fire::fire::fire::fire:](https://github.com/awslabs/s2n)) - An implementation of the TLS/SSL protocols.

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;809⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [AdRoll/hologram :fire::fire::fire:](https://github.com/AdRoll/hologram)) - Easy, painless credentials on developer laptops.
* <b><code>&nbsp;&nbsp;&nbsp;727⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [alex/letsencrypt-aws :fire::fire::fire:](https://github.com/alex/letsencrypt-aws)) - Automatically provision and update certificates.
* <b><code>&nbsp;&nbsp;8491⭐</code></b> <b><code>&nbsp;&nbsp;1305🍴</code></b> [bridgecrewio/checkov :fire::fire::fire::fire::fire:](https://github.com/bridgecrewio/checkov)) - Terraform static analysis, verifies security best practices.
* <b><code>&nbsp;&nbsp;3708⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;736🍴</code></b> [cloudsploit/scans :fire::fire::fire::fire:](https://github.com/cloudsploit/scans)) - Detects security risks.
* <b><code>&nbsp;&nbsp;1724⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;292🍴</code></b> [iSECPartners/Scout2 :fire::fire::fire::fire:](https://github.com/iSECPartners/Scout2)) - Security auditing tool.
* <b><code>&nbsp;&nbsp;1456⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;245🍴</code></b> [jordanpotti/AWSBucketDump :fire::fire::fire::fire:](https://github.com/jordanpotti/AWSBucketDump)) - Security Tool to Look For Interesting Files in S3 Buckets.
* <b><code>&nbsp;&nbsp;2759⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;228🍴</code></b> [Netflix/bless :fire::fire::fire::fire::fire:](https://github.com/Netflix/bless)) - SSH Certificate Authority that runs as a Lambda function.
* <b><code>&nbsp;&nbsp;4372⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;784🍴</code></b> [Netflix/security_monkey :fire::fire::fire::fire::fire:](https://github.com/Netflix/security_monkey)) - Monitors policy changes and alerts on insecure configurations.
* <b><code>&nbsp;&nbsp;&nbsp;446⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37🍴</code></b> [RiotGames/cloud-inquisitor :fire::fire:](https://github.com/RiotGames/cloud-inquisitor)) - Tool to enforce ownership and data security.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [salesforce/policy_sentry :fire::fire::fire::fire:](https://github.com/salesforce/policy_sentry/)) - IAM Least Privilege Policy Generator.
* <b><code>&nbsp;&nbsp;&nbsp;182⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [sebsto/AWSVPN :fire:](https://github.com/sebsto/AWSVPN)) - Start a private VPN server in the cloud.
* <b><code>&nbsp;30320⭐</code></b> <b><code>&nbsp;&nbsp;2364🍴</code></b> [trailofbits/algo :fire::fire::fire::fire::fire:](https://github.com/trailofbits/algo)) - Set up a personal IPSEC VPN on EC2 and other cloud services.
* <b><code>&nbsp;&nbsp;2015⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;136🍴</code></b> [ttlequals0/autovpn :fire::fire::fire::fire:](https://github.com/ttlequals0/autovpn)) - Create On Demand Disposable OpenVPN Endpoints.

### Accompanying Repos

AWS Repos:

*Repos Accompanying Blogs, Training Events, and Conferences.*

* <b><code>&nbsp;&nbsp;&nbsp;256⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [aws-arch-backoff-simulator :fire:](https://github.com/awslabs/aws-arch-backoff-simulator)) - Jitter and backoff Simulator for AWS architecture blog.
* <b><code>&nbsp;&nbsp;&nbsp;895⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;619🍴</code></b> [aws-big-data-blog :fire::fire::fire:](https://github.com/awslabs/aws-big-data-blog)) - Samples from the AWS Big Data Blog.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53🍴</code></b> [aws-demo-php-simple-app](https://github.com/awslabs/aws-demo-php-simple-app)) - PHP apps from the AWS Blogs.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [aws-mobile-sample-wif](https://github.com/awslabs/aws-mobile-sample-wif)) - Samples from the AWS Mobile SDK blog.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [aws-mobile-self-paced-labs-samples](https://github.com/awslabs/aws-mobile-self-paced-labs-samples)) - Android Snake Game from a self-paced lab.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [aws-quickstart](https://github.com/aws-quickstart/)) - Official repository for AWS Quick Start.
* <b><code>&nbsp;&nbsp;&nbsp;978⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;316🍴</code></b> [aws-spot-labs :fire::fire::fire:](https://github.com/awslabs/aws-spot-labs)) - Best practices using AWS Spot Instances.
* <b><code>&nbsp;&nbsp;&nbsp;129⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79🍴</code></b> [aws-training-demo :fire:](https://github.com/awslabs/aws-training-demo)) - Demos from the Technical Trainers community.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [java-meme-generator-sample](https://github.com/awslabs/java-meme-generator-sample)) - Meme generation app from re:Invent 2012.
* <b><code>&nbsp;&nbsp;&nbsp;165⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [railsconf2013-tech-demo :fire:](https://github.com/awslabs/railsconf2013-tech-demo)) - Seahorse demo from RailsConf 2013.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [reinvent2013-js-blog-demo](https://github.com/awslabs/reinvent2013-js-blog-demo)) - Demo blogging app from re:Invent 2013.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [reinvent2013-mobile-photo-share](https://github.com/awslabs/reinvent2013-mobile-photo-share)) - Mobile photo share app from re:Invent 2014.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [reinvent2014-scalable-site-management](https://github.com/awslabs/reinvent2014-scalable-site-management)) - Scalable site management sample from re:Invent 2014.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [reinvent2015-dev309](https://github.com/awslabs/reinvent2015-dev309)) - Large Scale Metrics Analysis from re:Invent 2015.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [timely-security-analytics](https://github.com/awslabs/timely-security-analytics)) - Security analytics sample from 2015 re:Invent 2015.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [todo-sample-app](https://github.com/awslabs/todo-sample-app)) - Simple "Todo" app from RailsConf 2014.

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;297⭐</code></b> <b><code>&nbsp;&nbsp;1250🍴</code></b> [startup-class/setup :fire::fire:](https://github.com/startup-class/setup)) -  EC2 setup files for Startup Engineering MOOC.

### Miscellaneous Repos

AWS Repos:

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [amediamanager](https://github.com/awslabs/amediamanager)) - Media manager.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [aws-hal-client-java](https://github.com/awslabs/aws-hal-client-java)) - Java client for the Hypertext Application Language.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [aws-model-validators](https://github.com/awslabs/aws-model-validators)) - Tools for validating the AWS service JSON model files.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [aws-sdk-js-sample-video-transcoder](https://github.com/awslabs/aws-sdk-js-sample-video-transcoder)) - Sample cross-platform video transcoder app.
* <b><code>&nbsp;&nbsp;&nbsp;319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [simplebeerservice :fire::fire:](https://github.com/awslabs/simplebeerservice)) - Cloud-connected kegerator that streams live sensor data to AWS.

Community Repos:

* <b><code>&nbsp;&nbsp;&nbsp;440⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [bcoe/thumbd :fire::fire:](https://github.com/bcoe/thumbd)) - Node.js/ImageMagick-based image thumbnailing service.
* <b><code>&nbsp;&nbsp;2348⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;271🍴</code></b> [cdkpatterns/serverless :fire::fire::fire::fire:](https://github.com/cdk-patterns/serverless)) - Deployable serverless architecture patterns built in AWS CDK.
* <b><code>&nbsp;&nbsp;&nbsp;275⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [Comcast/cmb :fire::fire:](https://github.com/Comcast/cmb)) - Highly available, horizontally scalable queuing and notification service.
* <b><code>&nbsp;&nbsp;1892⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;177🍴</code></b> [convox/rack :fire::fire::fire::fire:](https://github.com/convox/rack)) - Open-source PaaS on AWS.
* <b><code>&nbsp;&nbsp;&nbsp;387⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;119🍴</code></b> [devops-israel/aws-inventory :fire::fire:](https://github.com/devops-israel/aws-inventory)) - Display all your AWS resources on a single web page.
* <b><code>&nbsp;&nbsp;6266⭐</code></b> <b><code>&nbsp;&nbsp;1151🍴</code></b> [donnemartin/dev-setup :fire::fire::fire::fire:](https://github.com/donnemartin/dev-setup)) - Mac setup of various developer tools and AWS services.
* <b><code>&nbsp;&nbsp;4266⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;644🍴</code></b> [dtan4/terraforming :fire::fire::fire::fire::fire:](https://github.com/dtan4/terraforming)) - Export existing resources to Terraform style (tf, tfstate).
* <b><code>&nbsp;&nbsp;2102⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;413🍴</code></b> [segmentio/stack :fire::fire::fire::fire::fire:](https://github.com/segmentio/stack)) - A set of Terraform modules for configuring production infrastructure.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [j2labs/microarmy ](https://github.com/j2labs/microarmy)) - Deploy micro instances to launch a coordinated siege.
* <b><code>&nbsp;&nbsp;&nbsp;171⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [jpillora/grunt-aws :fire:](https://github.com/jpillora/grunt-aws)) - Grunt interface into the Node.JS SDK.
* <b><code>&nbsp;&nbsp;&nbsp;280⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63🍴</code></b> [jvehent/haproxy-aws :fire::fire:](https://github.com/jvehent/haproxy-aws)) - Documentation on building a HTTPS stack with HAProxy.
* <b><code>&nbsp;64518⭐</code></b> <b><code>&nbsp;&nbsp;4579🍴</code></b> [localstack/localstack :fire::fire::fire::fire::fire:](https://github.com/localstack/localstack)) - A fully functional local AWS cloud stack. Develop and test your cloud apps offline!
* <b><code>&nbsp;&nbsp;&nbsp;314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [meducation/propono :fire::fire:](https://github.com/meducation/propono)) - Easy-to-use pub/sub in Ruby.
* <b><code>&nbsp;&nbsp;&nbsp;807⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76🍴</code></b> [mozilla/awsbox :fire::fire::fire:](https://github.com/mozilla/awsbox)) - A featherweight PaaS on top of EC2 for deploying node apps.
* <b><code>&nbsp;&nbsp;&nbsp;957⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;167🍴</code></b> [Netflix/aminator :fire::fire::fire:](https://github.com/Netflix/aminator)) - A tool for creating EBS AMIs.
* <b><code>&nbsp;&nbsp;2493⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;478🍴</code></b> [Netflix/archaius :fire::fire::fire::fire::fire:](https://github.com/Netflix/archaius)) - Library for configuration management API.
* <b><code>&nbsp;&nbsp;2224⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;397🍴</code></b> [Netflix/asgard :fire::fire::fire::fire::fire:](https://github.com/Netflix/asgard)) - Web interface for application deployments and cloud management.
* <b><code>&nbsp;&nbsp;&nbsp;419⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [Netflix/aws-autoscaling :fire::fire:](https://github.com/Netflix/aws-autoscaling)) - Tools for using auto scaling and documentation best practices.
* <b><code>&nbsp;16613⭐</code></b> <b><code>&nbsp;&nbsp;1273🍴</code></b> [Netflix/chaosmonkey :fire::fire::fire::fire::fire:](https://github.com/Netflix/chaosmonkey)) - Resiliency tool that helps applications tolerate random instance failures.
* <b><code>&nbsp;12699⭐</code></b> <b><code>&nbsp;&nbsp;3783🍴</code></b> [Netflix/eureka :fire::fire::fire::fire::fire:](https://github.com/Netflix/eureka)) - Service registry for resilient mid-tier load balancing and failover.
* <b><code>&nbsp;&nbsp;2177⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;252🍴</code></b> [Netflix/EVCache :fire::fire::fire::fire:](https://github.com/Netflix/EVCache)) - A distributed in-memory data store.
* <b><code>&nbsp;&nbsp;&nbsp;698⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;114🍴</code></b> [Netflix/Fenzo :fire::fire::fire:](https://github.com/Netflix/Fenzo)) - Extensible Scheduler for Mesos Frameworks.
* <b><code>&nbsp;&nbsp;2879⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;430🍴</code></b> [Netflix/ice :fire::fire::fire::fire::fire:](https://github.com/Netflix/ice)) - Usage and cost monitoring tool.
* <b><code>&nbsp;&nbsp;4619⭐</code></b> <b><code>&nbsp;&nbsp;1237🍴</code></b> [Netflix/ribbon :fire::fire::fire::fire::fire:](https://github.com/Netflix/ribbon)) - Remote procedure call library with built in software load balancers.
* <b><code>&nbsp;&nbsp;7981⭐</code></b> <b><code>&nbsp;&nbsp;1125🍴</code></b> [Netflix/SimianArmy :fire::fire::fire::fire::fire:](https://github.com/Netflix/SimianArmy)) - Tools to keep your cloud operating in top form.
* <b><code>&nbsp;13993⭐</code></b> <b><code>&nbsp;&nbsp;2432🍴</code></b> [Netflix/zuul :fire::fire::fire::fire::fire:](https://github.com/Netflix/zuul)) - Edge service that provides dynamic routing, monitoring, resiliency, security, and more.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [niftylettuce/gulp-aws-splash :fire::fire:](https://github.com/niftylettuce/gulp-aws-splash)) - Open-source LaunchRock alternative. Build beautiful splash pages.
* <b><code>&nbsp;&nbsp;&nbsp;186⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;215🍴</code></b> [puppetlabs/puppetlabs-aws :fire:](https://github.com/puppetlabs/puppetlabs-aws)) - Puppet module for managing resources to build out infrastructure.
* <b><code>&nbsp;&nbsp;&nbsp;297⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [mhart/react-server-routing-example :fire::fire:](https://github.com/mhart/react-server-routing-example)) - Sample universal client/server routing and data in React.
* <b><code>&nbsp;&nbsp;&nbsp;733⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60🍴</code></b> [Similarweb/finala :fire::fire::fire:](https://github.com/similarweb/finala)) - A resource cloud scanner that analyzes and reports wasteful and unused resources to cut unwanted expenses.
* <b><code>&nbsp;&nbsp;7004⭐</code></b> <b><code>&nbsp;&nbsp;1183🍴</code></b> [snowplow/snowplow :fire::fire::fire::fire::fire:](https://github.com/snowplow/snowplow)) - Enterprise-strength web, mobile and event analytics, powered by Hadoop, Kafka, Kinesis, Redshift and Elasticsearch.
* <b><code>&nbsp;&nbsp;9690⭐</code></b> <b><code>&nbsp;&nbsp;1257🍴</code></b> [Spinnaker/spinnaker :fire::fire::fire::fire::fire:](https://github.com/Spinnaker/spinnaker)) - Successor to asgard supporting pipelines and more.
* <b><code>&nbsp;&nbsp;8236⭐</code></b> <b><code>&nbsp;&nbsp;2177🍴</code></b> [spulec/moto :fire::fire::fire::fire::fire:](https://github.com/spulec/moto)) - Allows your python tests to easily mock out the boto library.

## Guides, Books, Documentation, and Training

*How-to's, training, whitepapers, docs, and case studies.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/LxYDN5K.png">
</p>
<br/>

### Getting Started Guides

AWS Guides:

* [Getting Started with AWS](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-intro.html)
* [Getting Started Tutorials](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html)
    * [Run a Virtual Server](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2614)
    * [Store Files](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2683)
    * [Share Digital Media](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2755)
    * [Deploy a Website](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2767)
    * [Host a Website (Linux)](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2836)
    * [Host a Website (Windows)](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2908)
    * [Run a Database](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2980)
    * [Analyze Your Data](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e3065)

Community Guides:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### General Guides

AWS Guides:

* 🌎 [Analyzing Big Data](docs.aws.amazon.com/emr/latest/ManagementGuide/emr-gs.html)
* [Working with the AWS Management Console](http://docs.aws.amazon.com/awsconsolehelpdocs/latest/gsg/getting-started.html)
* [Deploying a Web App Using Elastic Beanstalk](http://docs.aws.amazon.com/gettingstarted/latest/deploy/overview.html)
* [Hosting a Web App](http://docs.aws.amazon.com/gettingstarted/latest/wah-linux/web-app-hosting-intro.html)
* [Hosting a .NET Web App](http://docs.aws.amazon.com/gettingstarted/latest/wah/web-app-hosting-intro.html)
* [Hosting a Static Website](http://docs.aws.amazon.com/gettingstarted/latest/swh/website-hosting-intro.html)
* 🌎 [Quick Start Deployment Guides](aws.amazon.com/documentation/quickstart/)

Community Guides:

* <b><code>&nbsp;36595⭐</code></b> <b><code>&nbsp;&nbsp;3910🍴</code></b> [Open Guide to AWS :fire::fire::fire::fire::fire:](https://github.com/open-guides/og-aws))

### Books

* Amazon Web Services in Action 🌎 [Manning](www.manning.com/books/amazon-web-services-in-action) or [Amazon.com](http://amzn.com/1617292885)
* AWS Lambda in Action 🌎 [Manning](www.manning.com/books/aws-lambda-in-action) or [Amazon.com](http://amzn.com/1617293717) - <b><code>&nbsp;&nbsp;&nbsp;288⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;121🍴</code></b> [Code Repo :fire::fire:](https://github.com/danilop/AWS_Lambda_in_Action))

### Whitepapers

* 🌎 [AWS Well-Architected Framework](d0.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf)
* 🌎 [Whitepapers](aws.amazon.com/whitepapers/)

### Documentation

* 🌎 [Documentation](aws.amazon.com/documentation/)
* 🌎 [AWS Billing and Cost Management](aws.amazon.com/documentation/account-billing/)
* 🌎 [AWS Marketplace](aws.amazon.com/documentation/marketplace/)
* 🌎 [AWS Support](aws.amazon.com/documentation/aws-support/)
* [AWS General Reference](http://docs.aws.amazon.com/general/latest/gr/)
* [AWS Glossary](http://docs.aws.amazon.com/general/latest/gr/glos-chap.html)

### Training

* 🌎 [Training and Certification](aws.amazon.com/training/)
* 🌎 [Webinars](aws.amazon.com/about-aws/events/)

### Case Studies: Powered by AWS

* 🌎 [Adobe](aws.amazon.com/solutions/case-studies/adobe/)
* 🌎 [AdRoll](aws.amazon.com/solutions/case-studies/adroll/)
* 🌎 [Airbnb](aws.amazon.com/solutions/case-studies/airbnb/)
* 🌎 [Autodesk](aws.amazon.com/solutions/case-studies/autodesk/)
* 🌎 [Citrix](aws.amazon.com/solutions/case-studies/citrix/)
* 🌎 [Comcast](aws.amazon.com/solutions/case-studies/comcast/)
* 🌎 [Coursera](aws.amazon.com/solutions/case-studies/coursera/)
* 🌎 [Docker](aws.amazon.com/solutions/case-studies/docker/)
* 🌎 [Dow Jones](aws.amazon.com/solutions/case-studies/dow-jones/)
* 🌎 [Dropbox](www.dropbox.com/)
* 🌎 [Dropcam](aws.amazon.com/solutions/case-studies/dropcam/)
* 🌎 [Expedia](aws.amazon.com/solutions/case-studies/expedia/)
* 🌎 [Foursquare](aws.amazon.com/solutions/case-studies/foursquare/)
* 🌎 [IMDb](aws.amazon.com/solutions/case-studies/imdb/)
* 🌎 [Instrumental](instrumentalapp.com/blog/aws-kinesis/)
* 🌎 [Intuit](aws.amazon.com/solutions/case-studies/soasta-intuit/)
* 🌎 [Johnson & Johnson](aws.amazon.com/solutions/case-studies/johnson-and-johnson/)
* 🌎 [Lionsgate](aws.amazon.com/solutions/case-studies/lionsgate/)
* 🌎 [mlbam](aws.amazon.com/solutions/case-studies/major-league-baseball-mlbam/)
* 🌎 [NASA](aws.amazon.com/solutions/case-studies/nasa-jpl-curiosity/)
* 🌎 [Netflix](aws.amazon.com/solutions/case-studies/netflix/)
* 🌎 [Nike](web.archive.org/web/20150910200649/http://aws.amazon.com/solutions/case-studies/nike/)
* 🌎 [Nokia](web.archive.org/web/20161210062336/https://aws.amazon.com/solutions/case-studies/nokia/)
* 🌎 [PBS](aws.amazon.com/solutions/case-studies/pbs/)
* 🌎 [Pfizer](web.archive.org/web/20161210034734/https://aws.amazon.com/solutions/case-studies/pfizer/)
* 🌎 [Philips](aws.amazon.com/solutions/case-studies/philips/)
* 🌎 [Reddit](web.archive.org/web/20150905070945/https://aws.amazon.com/solutions/case-studies/reddit/)
* 🌎 [Samsung](aws.amazon.com/solutions/case-studies/samsung/)
* 🌎 [Siemens](aws.amazon.com/solutions/case-studies/siemens/)
* 🌎 [Slack](aws.amazon.com/solutions/case-studies/slack/)
* 🌎 [Spotify](web.archive.org/web/20180608043124/https://aws.amazon.com/solutions/case-studies/spotify/)
* 🌎 [Swiftkey](web.archive.org/web/20160410051253/https://aws.amazon.com/solutions/case-studies/swiftkey/)
* 🌎 [The Weather Company](aws.amazon.com/solutions/case-studies/the-weather-company/)
* 🌎 [Ticketmaster](aws.amazon.com/solutions/case-studies/ticketmaster/)
* 🌎 [Time Inc](aws.amazon.com/solutions/case-studies/time-inc/)
* 🌎 [Twilio](aws.amazon.com/solutions/case-studies/twilio/)
* 🌎 [U.S. Department of State](aws.amazon.com/solutions/case-studies/exchangesconnect/)
* 🌎 [Ubisoft](aws.amazon.com/solutions/case-studies/ubisoft/)
* 🌎 [Yelp](aws.amazon.com/solutions/case-studies/yelp-docker/)
* 🌎 [Zillow](aws.amazon.com/solutions/case-studies/zillow/)

## Social

*Blogs, discussion groups, conferences, and social media.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/kRRBa1e.png">
</p>
<br/>

### Blogs

AWS Blogs:

* 🌎 [Official Blog](aws.amazon.com/blogs/aws/)
    * 🌎 [Brasil](aws.amazon.com/pt/blogs/aws-brasil/)
    * 🌎 [China](aws.amazon.com/cn/blogs/china/)
    * 🌎 [Germany](aws.amazon.com/de/blogs/germany/)
    * 🌎 [Japan](aws.amazon.com/jp/blogs/news/)
    * [Korea](http://aws.amazon.com/ko/blogs/korea/)
* 🌎 [DevOps](aws.amazon.com/blogs/devops/)
* 🌎 [Architecture](aws.amazon.com/blogs/architecture/)
* 🌎 [Big Data](aws.amazon.com/blogs/big-data/)
* 🌎 [Compute](aws.amazon.com/blogs/compute/)
* 🌎 [Mobile](aws.amazon.com/blogs/mobile/)
* 🌎 [Messaging](aws.amazon.com/blogs/messaging-and-targeting/)
* 🌎 [Java](aws.amazon.com/blogs/developer/category/programing-language/java/)
* 🌎 [PHP](aws.amazon.com/blogs/developer/category/programing-language/php/)
* 🌎 [Ruby](aws.amazon.com/blogs/developer/category/programing-language/ruby/)
* 🌎 [.NET](aws.amazon.com/blogs/developer/category/programing-language/dot-net/)
* 🌎 [Security](aws.amazon.com/blogs/security/)
* 🌎 [Startup](medium.com/aws-activate-startup-blog)
* 🌎 [Partner Network](aws.amazon.com/blogs/apn/)
* 🌎 [SAP](aws.amazon.com/blogs/awsforsap/)

Community Blogs:

* [All Things Distributed](http://www.allthingsdistributed.com/) - Werner Vogels, AWS CTO.
* [Things I Like...](http://jeff-barr.com/) - Jeff Barr, AWS Chief Evangelist.
* [Netflix Tech Blog](http://techblog.netflix.com/)
* <b><code>&nbsp;37195⭐</code></b> <b><code>&nbsp;&nbsp;1951🍴</code></b> [A Curated List of Engineering Blogs](https://github.com/kilimchoi/engineering-blogs))
* 🌎 [AWS Geek](www.awsgeek.com/)

### Twitter Influencers

AWS Tweeps:

* 🌎 [@awscloud](twitter.com/awscloud) - Official Twitter feed.
* 🌎 [@AWS_Partners](twitter.com/AWS_Partners)
* 🌎 [@AWSIdentity](twitter.com/AWSIdentity)
* 🌎 [@AWSMarketplace](twitter.com/AWSMarketplace)
* 🌎 [@AWSreInvent](twitter.com/AWSreInvent) - Official Twitter account for re:Invent.
* 🌎 [@AWSStartups](twitter.com/AWSStartups)
* 🌎 [@ajassy](twitter.com/ajassy) - Andy Jassy: Senior Vice-President.
* 🌎 [@Ianmmmm](twitter.com/Ianmmmm) - Ian Massingham - Technical Evangelist.
* 🌎 [@jeffbarr](twitter.com/jeffbarr) - Jeff Barr: Chief Evangelist.
* 🌎 [@mndoci](twitter.com/mndoci) - Deepak Singh: GM EC2.
* 🌎 [@mza](twitter.com/mza) - Matt Wood: Product Strategy.
* 🌎 [@Werner](twitter.com/Werner) - Werner Vogels: CTO.
* 🌎 [Community heroes, Evangelists, etc](twitter.com/awscloud/lists)

Community Tweeps:

* 🌎 [@kennwhite](twitter.com/kennwhite)
* 🌎 [@esh](twitter.com/esh)
* 🌎 [@garnaat](twitter.com/garnaat)
* 🌎 [@quinnypig](twitter.com/quinnypig)
* 🌎 [@awsgeek](twitter.com/awsgeek)

### Facebook Pages

AWS Pages:

* 🌎 [amazonwebservices](www.facebook.com/amazonwebservices) - Official Facebook page.
* 🌎 [awsreinvent](www.facebook.com/awsreinvent) - Official Facebook page for re:Invent.

Community Pages:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

### YouTube Channels

AWS Channels:

* 🌎 [AmazonWebServices](www.youtube.com/user/AmazonWebServices)
* 🌎 [AWSDeutsch](www.youtube.com/user/AWSAktuell)
* 🌎 [AWSJapan](www.youtube.com/user/AmazonWebServicesJP)
* 🌎 [AWSKorea](www.youtube.com/user/AWSKorea)
* 🌎 [AWSLatinAmerica](www.youtube.com/channel/UCvaUAVzIIGsRNlUDWkQFCeA)
* 🌎 [AWSTutorialSeries](www.youtube.com/user/awstutorialseries)
* 🌎 [AWSWebinars](www.youtube.com/user/AWSwebinars)

Community Channels:

* 🌎 [Backspace Academy](www.youtube.com/channel/UCav3fsasRc5VOqvZiT5avgw)
* 🌎 [Cloud Academy](www.youtube.com/channel/UCeRY0LppLWdxWAymRANTb0g/videos)
* 🌎 [Linux Academy](www.youtube.com/user/pineheadtv/playlists)

### LinkedIn Groups

AWS Page:

* 🌎 [Amazon Web Services](www.linkedin.com/company/amazon-web-services)

Community Groups:

* 🌎 [Amazon AWS Architects](www.linkedin.com/grp/home?gid=4387417)
* 🌎 [Amazon AWS Architects, Engineers, Developers, Consultants, Entrepreneurs Experts](www.linkedin.com/grps?gid=3748455)
* 🌎 [Amazon Web Services (AWS) for Business](www.linkedin.com/grps?gid=5122002)
* 🌎 [Amazon Web Services Architects](www.linkedin.com/grps?gid=4233997)
* 🌎 [Amazon Web Services Community Network](www.linkedin.com/grp/home?gid=49531)
* 🌎 [Amazon Web Services Enthusiasts](www.linkedin.com/grps?gid=2485626)
* 🌎 [Amazon Web Services Users](www.linkedin.com/grps?gid=86137)

### Subreddits

* 🌎 [/r/aws/](www.reddit.com/r/aws/)
* 🌎 [/r/AWS_cloud/](www.reddit.com/r/AWS_cloud/)

### Conferences

AWS Conferences:

* 🌎 [re:Invent](reinvent.awsevents.com/) - Annual user conference. The event features keynote announcements, training and certification opportunities, over 250 technical sessions, a partner expo, after hours activities, and more.
* 🌎 [Summits](aws.amazon.com/summits/) - Global one-day events that are designed to educate new customers about the AWS platform and offer existing customers deep technical content to be more successful with AWS.
* 🌎 [AWSome Day](aws.amazon.com/events/awsome-day/awsome-day-online/) - Global one-day events are delivered by AWS Education's technical instructors and are ideal for IT pros, developers and technical managers who would like to learn about how to get started in the AWS Cloud.

Community Conferences:

* [Contribute](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CONTRIBUTING.md)

## Latest KPIs and Stats

*Latest key performance indicators and other interesting stats.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/KP2TmJv.png">
</p>
<br/>

* Over 1 million customers active in past 30 days.<sup 🌎 [1](www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
* $7B+ annual revenue run-rate business.<sup 🌎 [1](www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
    * 81% year over year revenue growth.<sup 🌎 [1](www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
* EC2 usage up 95% year over year.<sup 🌎 [1](www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
* S3 data transfer up 120% year over year.<sup 🌎 [1](www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
    * S3 holds trillions of objects and regularly peaks at 1.5 million requests per second.<sup>[2](http://highscalability.com/blog/2015/1/12/the-stunning-scale-of-aws-and-what-it-means-for-the-future-o.html)</sup>
* Database services usage up 127% year over year.<sup 🌎 [1](www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
    * $1B annual revenue run-rate business.<sup 🌎 [1](www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
* 2 million new EBS volumes created per day.<sup 🌎 [4](www.youtube.com/watch?v=OuyUbvtgfDk)</sup>
* Customers have launched more than 15 million Hadoop clusters.<sup>[3](http://www.forbes.com/sites/benkepes/2014/11/25/scale-beyond-comprehension-some-aws-numbers/)</sup>
* 102Tbps network capacity into a data center.<sup>[2](http://highscalability.com/blog/2015/1/12/the-stunning-scale-of-aws-and-what-it-means-for-the-future-o.html)</sup>
* 500+ major new features and services launched since 2014.<sup 🌎 [1](www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
* All 14 other cloud providers combined have 1/5th the aggregate capacity of AWS.<sup>[2](http://highscalability.com/blog/2015/1/12/the-stunning-scale-of-aws-and-what-it-means-for-the-future-o.html)</sup>
* Every day, AWS adds enough new server capacity to support all of Amazon's global infrastructure when it was a $7B annual revenue enterprise (in 2004).<sup>[2](http://highscalability.com/blog/2015/1/12/the-stunning-scale-of-aws-and-what-it-means-for-the-future-o.html)</sup>

## Appendix of Core Services

*Appendix of official services, grouped by service category.*

### Services in Plain English

* 🌎 [Amazon Web Services in Plain English](www.expeditedssl.com/aws-in-plain-english) - Entertaining and educational, a community contribution.

### Compute Services

* 🌎 [Auto Scaling](aws.amazon.com/autoscaling/) - Launches or terminates EC2 instances based on policies, schedules, and health checks.
* 🌎 [Batch](aws.amazon.com/batch/) - Run batch jobs at scale.
* 🌎 [Blox](blox.github.io/) - Open source projects for building custom schedulers on ECS.
* 🌎 [EC2 Container Service (ECS)](aws.amazon.com/ecs/) - Supports Docker containers on EC2 instances.
* 🌎 [EC2 Systems Manager](aws.amazon.com/ec2/systems-manager/) - Easily configure and manage EC2 and on-premises systems.
* 🌎 [Elastic Beanstalk](aws.amazon.com/elasticbeanstalk/) - Provides quick deployment and management of applications in the cloud.
* [Elastic Compute Cloud (EC2)](http://aws.amazon.com/ec2/) - Provides scalable virtual private servers using Xen.
* 🌎 [Elastic GPUs](aws.amazon.com/ec2/Elastic-GPUs/) - Attach low-cost GPUs to EC2 instances for graphics acceleration.
* 🌎 [Elastic Load Balancing (ELB)](aws.amazon.com/elasticloadbalancing/) - Automatically distributes incoming traffic across multiple EC2 instances.
* 🌎 [Lambda](aws.amazon.com/lambda/) - Runs code in response to events and automatically manages EC2 instances.
* 🌎 [Lightsail](amazonlightsail.com/) - Launch and manage simple virtual private servers.
* 🌎 [Virtual Private Cloud (VPC)](aws.amazon.com/vpc/) - Creates a logically isolated set of EC2 instances which can be connected to an existing network using a VPN connection.

### Networking Services

* 🌎 [Direct Connect](aws.amazon.com/directconnect/) - Provides dedicated connections to AWS for faster and cheaper data throughput.
* 🌎 [Elastic Load Balancing (ELB)](aws.amazon.com/elasticloadbalancing/) - Automatically distributes incoming traffic across multiple EC2 instances.
* 🌎 [Route 53](aws.amazon.com/route53/) - Provides a highly available and scalable Domain Name System (DNS) web service.
* 🌎 [Virtual Private Cloud (VPC)](aws.amazon.com/vpc/) - Creates a logically isolated set of EC2 instances which can be connected to an existing network using a VPN connection.

### Enterprise Applications

* 🌎 [WorkDocs](aws.amazon.com/workdocs/) - Provides a fully managed, secure enterprise storage and sharing service.
* 🌎 [WorkMail](aws.amazon.com/workmail/) - Provides managed email and calendaring service.
* 🌎 [WorkSpaces](aws.amazon.com/workspaces/) - Provides a cloud-based desktop experience to end-users.
* [Workspaces Application Manager (WAM)](http://aws.amazon.com/workspaces/applicationmanager/) - Simplifies deployment and management of WorkSpaces.

### Analytics Services

* 🌎 [Athena](aws.amazon.com/athena/) - Query data on S3 instantly.
* 🌎 [Data Pipeline](aws.amazon.com/datapipeline/) - Provides workload management by processing and moving data between services.
* [Elastic MapReduce (EMR)](http://aws.amazon.com/elasticmapreduce/) - Hosts a Hadoop and Spark framework running on EC2 and S3.
* 🌎 [Elasticsearch Service (ES)](aws.amazon.com/elasticsearch-service/) - Managed Elasticsearch, a popular open-source search and analytics engine.
* 🌎 [Glue](aws.amazon.com/glue/) - Prepare and load data to data stores.
* 🌎 [Kinesis](aws.amazon.com/kinesis/) - Provides real-time data processing over large, distributed data streams.
* 🌎 [Kinesis Analytics](aws.amazon.com/kinesis/analytics/) - Write standard SQL queries on streaming data without having to learn any new programming skills.
* 🌎 [Kinesis Firehose](aws.amazon.com/kinesis/firehose/) - Captures and automatically loads streaming data into S3 and Redshift.
* 🌎 [Quicksight](aws.amazon.com/quicksight/) - Provides cloud-powered business intelligence for 1/10th the cost of traditional BI solutions.
* 🌎 [Redshift](aws.amazon.com/redshift/) - Provides petabyte-scale data warehousing with columnar storage and multi-node compute.

### Artificial Intelligence

* 🌎 [Lex](aws.amazon.com/lex/) - Build conversational interfaces through voice or text.
* 🌎 [Machine Learning](aws.amazon.com/machine-learning/) - Provides managed machine learning technology.
* 🌎 [Polly](aws.amazon.com/polly/) - Turn text into lifelike speech.
* 🌎 [Rekognition](aws.amazon.com/rekognition/) - Deep learning-based image analysis.

### Management Tools

* 🌎 [CloudFormation](aws.amazon.com/cloudformation/) - Provides a file-based interface for provisioning other resources.
* 🌎 [CloudTrail](aws.amazon.com/cloudtrail/) - Provides logs of all activity.
* 🌎 [CloudWatch](aws.amazon.com/cloudwatch/) - Provides monitoring for AWS cloud resources and applications, starting with EC2.
* 🌎 [Command Line Interface (CLI)](aws.amazon.com/cli/) - Provides a CLI to manage all services.
* 🌎 [Config](aws.amazon.com/config/) - Provides a detailed view of all resources.
* 🌎 [Management Console (AWS Console)](aws.amazon.com/console/) - A web-based interface to manage all services.
* 🌎 [OpsWorks](aws.amazon.com/opsworks/) - Provides configuration of EC2 services using Chef.
* 🌎 [Personal Health Dashboard](aws.amazon.com/premiumsupport/phd/) - Your personalized view of service health.
* 🌎 [Service Catalog](aws.amazon.com/servicecatalog/) - Service Catalog allows IT administrators to create, manage, and distribute portfolios of approved products to end users, who can then access the products they need in a personalized portal.

### Security and Identity Services

* 🌎 [Certificate Manager](aws.amazon.com/certificate-manager/) - Lets you easily provision, manage, and deploy SSL/TLS certificates for use with AWS services.
* 🌎 [CloudHSM](aws.amazon.com/cloudhsm/) - Helps meet corporate, contractual and regulatory compliance requirements for data security by using dedicated Hardware Security Module (HSM) appliances within the AWS cloud.
* 🌎 [Directory Service](aws.amazon.com/directoryservice/) - A managed service that allows you to connect your resources with an existing on-premises Microsoft Active Directory or to set up a new, stand-alone directory in the AWS Cloud.
* 🌎 [Identity and Access Management (IAM)](aws.amazon.com/iam/) - An implicit service, the authentication infrastructure used to authenticate access to the various services.
* 🌎 [Inspector](aws.amazon.com/inspector/) - An automated security assessment service that helps improve the security and compliance of applications deployed on AWS.
* 🌎 [Key Management Service (KMS)](aws.amazon.com/kms/) - A managed service that makes it easy for you to create and control the encryption keys used to encrypt your data.
* 🌎 [Shield](aws.amazon.com/shield/) - Managed DDoS Protection.
* 🌎 [WAF](aws.amazon.com/waf/) - A web application firewall service that monitors and manages CloudFront distributions.

### Internet of Things Service

* 🌎 [IoT](aws.amazon.com/iot/) - Enables secure, bi-directional communication between internet-connected things (such as sensors, actuators, embedded devices, or smart appliances) and the AWS cloud over MQTT and HTTP.

### Mobile Services

* 🌎 [API Gateway](aws.amazon.com/api-gateway/) - Service for publishing, maintaining and securing web service APIs.
* 🌎 [Cognito](aws.amazon.com/cognito/) - Provides user identity and data synchronization.
* 🌎 [Device Farm](aws.amazon.com/device-farm/) - App testing service for iOS, Android and Fire OS apps on physical devices.
* 🌎 [Mobile Analytics](aws.amazon.com/mobileanalytics/) - Service for collecting, visualizing, and understanding app usage data.
* 🌎 [Mobile Hub](aws.amazon.com/mobile/) - Provides an integrated console that helps you build, test, and monitor your mobile apps.
* 🌎 [Pinpoint](aws.amazon.com/pinpoint/) - Targeted push notifications for mobile apps.
* 🌎 [Simple Notification Service (SNS)](aws.amazon.com/sns/) - Provides a hosted multi-protocol "push" messaging for applications.

### Storage and Content Delivery Services

* 🌎 [CloudFront](aws.amazon.com/cloudfront/) - A content delivery network (CDN) for distributing objects to locations near the requester.
* 🌎 [Elastic Block Store (EBS)](aws.amazon.com/ebs/) - Provides persistent block-level storage volumes for EC2.
* 🌎 [Elastic File System (EFS)](aws.amazon.com/efs/) - A file storage service for EC2 instances.
* 🌎 [Glacier](aws.amazon.com/glacier/) - Provides a low-cost, long-term storage option, intended for archiving data.
* 🌎 [Import/Export](aws.amazon.com/importexport/) - Accelerates moving large amounts of data into and out of AWS using portable storage devices for transport.
* 🌎 [Simple Storage Service (S3)](aws.amazon.com/s3/) - Provides Web Service based storage.
* 🌎 [Storage Gateway](aws.amazon.com/storagegateway/) - An iSCSI block storage virtual appliance with cloud-based backup.

### Databases

* 🌎 [Aurora](aws.amazon.com/rds/aurora/) - MySQL and PostgreSQL compatible relational database with improved performance.
* 🌎 [DynamoDB](aws.amazon.com/dynamodb/) - Provides a scalable, low-latency NoSQL online Database Service backed by SSDs.
* 🌎 [ElastiCache](aws.amazon.com/elasticache/) - Provides in-memory caching for web apps (Memcached, Redis).
* 🌎 [Redshift](aws.amazon.com/redshift/) - Provides petabyte-scale data warehousing with columnar storage and multi-node compute.
* 🌎 [Relational Database Service (RDS)](aws.amazon.com/rds/) - Provides a scalable database server with MySQL, Oracle, SQL Server, PostgreSQL, and MariaDB support.
* 🌎 [Schema Conversion Tool](aws.amazon.com/documentation/SchemaConversionTool/) - App that helps you convert your database schema from an Oracle or Microsoft SQL Server database, to an RDS MySQL DB instance or an Aurora DB cluster.
* 🌎 [SimpleDB](aws.amazon.com/simpledb/) - Allows developers to run queries on structured data.

### Application Services

* 🌎 [API Gateway](aws.amazon.com/api-gateway/) - Service for publishing, maintaining and securing web service APIs.
* 🌎 [AppStream](aws.amazon.com/appstream/) - Flexible, low-latency streaming service for apps and games.
* 🌎 [CloudSearch](aws.amazon.com/cloudsearch/) - Provides basic full-text search and indexing of textual content.
* 🌎 [DevPay](aws.amazon.com/devpay/) - Provides billing and account management.
* 🌎 [Elastic Transcoder (ETS)](aws.amazon.com/elastictranscoder/) - Provides video transcoding of S3 hosted videos.
* 🌎 [Flexible Payments Service (FPS)](payments.amazon.com/developer) - Provides an interface for micropayments.
* 🌎 [Simple Email Service (SES)](aws.amazon.com/ses/) - Provides bulk and transactional email sending.
* 🌎 [Simple Notification Service (SNS)](aws.amazon.com/sns/) - Provides a hosted multi-protocol "push" messaging for applications.
* 🌎 [Simple Queue Service (SQS)](aws.amazon.com/sqs/) - Provides a hosted message queue for web applications.
* 🌎 [Simple Workflow (SWF)](aws.amazon.com/swf/) - A workflow service for building scalable, resilient applications.
* 🌎 [Step Functions](aws.amazon.com/step-functions/) - Coordinate components of distributed applications.

### Developer Tools

* 🌎 [CodeBuild](aws.amazon.com/codebuild/) - Build and test code.
* 🌎 [CodeCommit](aws.amazon.com/documentation/codecommit/) - Hosted Git version control service.
* 🌎 [CodeDeploy](aws.amazon.com/codedeploy/) - Provides automated code deployment to EC2 instances.
* 🌎 [CodePipeline](aws.amazon.com/documentation/codepipeline/) - Continuous delivery service.
* 🌎 [Command Line Interface (CLI)](aws.amazon.com/cli/) - Provides a CLI to manage all services.
* 🌎 [X-Ray](aws.amazon.com/xray/) - Analyze and debug your applications.

### Miscellaneous Services

* 🌎 [Fulfillment Web Service](aws.amazon.com/about-aws/whats-new/2008/03/19/announcing-amazon-fulfillment-web-service/) - Provides a programmatic web service for sellers to ship items to and from Amazon using Fulfillment by Amazon.
* 🌎 [Mechanical Turk](www.mturk.com/mturk/welcome) - Manages small units of work distributed among many persons.
* 🌎 [Partner Network (APN)](aws.amazon.com/partners/) - Provides partners with the technical information and sales and marketing support to increase business opportunities.
* [Product Advertising API](http://docs.aws.amazon.com/AWSECommerceService/latest/GSG/Welcome.html) - Provides access to product data and electronic commerce functionality.

## Credits

Check out the [Credits page](https://github.com/correia-jpv/fucking-awesome-aws/blob/master/CREDITS.md).

## Other Awesome Lists

Other awesome lists can be found in <b><code>441667⭐</code></b> <b><code>&nbsp;33347🍴</code></b> [awesome](https://github.com/sindresorhus/awesome)) and <b><code>&nbsp;33257⭐</code></b> <b><code>&nbsp;&nbsp;3588🍴</code></b> [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)).

## Contact Info

Feel free to contact me to discuss any issues, questions, or comments.

My contact info can be found on my [GitHub page](https://github.com/donnemartin).

## License

*I am providing code and resources in this repository to you under an open source license.  Because this is my personal repository, the license you receive to my code and resources is from me and not my employer (Facebook).*

    Copyright 2017 Donne Martin

    Creative Commons Attribution 4.0 International License (CC BY 4.0)

    http://creativecommons.org/licenses/by/4.0/

## Source
<b><code>&nbsp;13934⭐</code></b> <b><code>&nbsp;&nbsp;1884🍴</code></b> [donnemartin/awesome-aws](https://github.com/donnemartin/awesome-aws))