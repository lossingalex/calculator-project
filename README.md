# Calculator Project

## Pre-requisite

- Nodejs: version 10.x
- Serverless.com framework
- AWS Account

## Local Install Setup

### Nodejs

- Official: <https://nodejs.org/en/download/>
- RECOMMENDED - To avoid permission error: <https://docs.npmjs.com/resolving-eacces-permissions-errors-when-installing-packages-globally>

### Setup your AWS CLI and credential

#### Install AWS CLI

- Instructions to follow: [AWS CLI install](http://docs.aws.amazon.com/cli/latest/userguide/installing.html)
- Or directly for MacOs user: [AWS CLI install MacOS](http://docs.aws.amazon.com/cli/latest/userguide/cli-install-macos.html)

#### Configure AWS CLI and credentials

- Instructions to follow: [AWS cli configuration](http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html)

```bash
$ aws configure
AWS Access Key ID [None]: your_access_key
AWS Secret Access Key [None]: your_secret_key
Default region name [None]: ap-southeast-1
Default output format [None]:
```

This command line will create a credentials file at :

- `~/.aws/credentials` on `Mac/Linux` 
- `C:\Users\USERNAME\.aws\credentials` on `Windows`

This file will be used by the serverless framework when deploying to AWS.

### Setup Serverless Framework

- Install serverles globally

```bash
npm install -g serverless
```

More Info: <https://serverless.com/framework/docs/getting-started/>
