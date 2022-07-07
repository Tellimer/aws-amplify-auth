<img src="https://user-images.githubusercontent.com/352761/177859520-99a278f1-9ca4-4587-9feb-90ee376230b1.png" alt="Open Source Fork" width="100" > <img src="https://s3.amazonaws.com/aws-mobile-hub-images/aws-amplify-logo.png" alt="AWS Amplify" width="550" >


<a href="https://nodei.co/npm/@tellimer/aws-amplify-auth/">
  <img src="https://nodei.co/npm/@tellimer/aws-amplify-auth.svg?downloads=true&downloadRank=true&stars=true">
</a>
<p>
  <a href="https://discord.gg/jWVbPfC" target="_blank">
    <img src="https://img.shields.io/discord/308323056592486420?logo=discord"" alt="Discord Chat" />
  </a>
  <a href="https://codecov.io/gh/Tellimer/aws-amplify-auth">
    <img src="https://codecov.io/gh/Tellimer/aws-amplify-auth/branch/main/graph/badge.svg" />
  </a>
  <a href="https://lgtm.com/projects/g/Tellimer/aws-amplify-auth/context:javascript"><img alt="Language grade: JavaScript" src="https://img.shields.io/lgtm/grade/javascript/g/Tellimer/aws-amplify-auth.svg?logo=lgtm&logoWidth=18"/>
  </a>
  <a href="https://circleci.com/gh/Tellimer/aws-amplify-auth">
    <img src="https://img.shields.io/circleci/project/github/Tellimer/aws-amplify-auth/main.svg" alt="build:started">
  </a>
</p>

### Reporting Bugs / Feature Requests

[![Open Bugs](https://img.shields.io/github/issues/Tellimer/aws-amplify-auth/bug?color=d73a4a&label=bugs)](https://github.com/Tellimer/aws-amplify-auth/issues?q=is%3Aissue+is%3Aopen+label%3Abug)
[![Feature Requests](https://img.shields.io/github/issues/Tellimer/aws-amplify-auth/feature-request?color=ff9001&label=feature%20requests)](https://github.com/Tellimer/aws-amplify-auth/issues?q=is%3Aissue+label%3Afeature-request+is%3Aopen)
[![Closed Issues](https://img.shields.io/github/issues-closed/Tellimer/aws-amplify-auth?color=%2325CC00&label=issues%20closed)](https://github.com/Tellimer/aws-amplify-auth/issues?q=is%3Aissue+is%3Aclosed+)

### AWS Amplify Auth is a TypeScript library for frontend developers building cloud-enabled applications

We forked AWS Amplify and decided to implement Tellimer specific flows in particular due to a split in approach as we used authentication accross multiple subdomains, as well as trying to get the library closer to Typescript native and away from web and mobile parity.

#### Visit AWS Amplify [Documentation site](https://docs.amplify.aws/) to learn more about AWS Amplify as we tried and maintained parity with most of the old functionality.

- [Demo Applications](https://github.com/aws-amplify/amplify-js-samples)
- [Contributing](https://github.com/Tellimer/aws-amplify-auth/blob/main/CONTRIBUTING.md)

### Features

| Category                                                                                                          | AWS Provider                                                | Description                                                                                                            |
| ----------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| [**Authentication**](https://docs.amplify.aws/lib/auth/getting-started/q/platform/js)                             | [Amazon Cognito](https://aws.amazon.com/cognito/)           | APIs and Building blocks to create Authentication experiences.                                                         |

## Getting Started

AWS Amplify Auth is available as `@tellimer/aws-amplify-auth` package on [npm](https://www.npmjs.com/package/@tellimer/aws-amplify-auth).

  ```ts
  import { Auth } from '@tellimer/aws-amplify-auth';
  ```


