# Amazon Cognito

---

## What is Amazon Cognito?

> Amazon Cognito 可讓您快速輕鬆地將使用者註冊、登入和存取控制新增到 Web 和行動應用程式 - Amazon Cognito

---

## What can Amazon Cognito do?

* 安全且可擴展的使用者目錄
* 社交與企業聯合身分
* 標準身份驗證
  * 如 Oauth 2.0、[SAML 2.0](https://aws.amazon.com/tw/identity/saml/) 和 OpenID Connect
* 應用程式和使用者的安全
  * 多重因素認證(Multi-Factor Authentication, MFA)
* AWS 資源的存取控制
* 輕鬆與您的應用程式整合

---

## Features of Amazon Cognito

---

### User pools

使用者的帳號集合

> A user pool is a user directory in Amazon Cognito.

+++

### Identity pools

使用者的 AWS 授權中心

> With an identity pool, your users can obtain temporary AWS credentials to access AWS services, such as Amazon S3 and DynamoDB.

---

## Authenticate with a User Pool

![Authenticate with a User Pool](https://docs.aws.amazon.com/zh_tw/cognito/latest/developerguide/images/scenario-authentication-cup.png)

---

## Access Control with User Pool

+++

### Access Your Own Resources

![Access Your Own Resources with a User Pool](https://docs.aws.amazon.com/zh_tw/cognito/latest/developerguide/images/scenario-standalone.png)

+++

### Access API Gateway and Lambda

![Access API Gateway and Lambda with a User Pool](https://docs.aws.amazon.com/zh_tw/cognito/latest/developerguide/images/scenario-api-gateway.png)

+++

### Access AWS Services with an Identity Pool

![Authenticate with a User Pool and Access AWS Services with an Identity Pool](https://docs.aws.amazon.com/zh_tw/cognito/latest/developerguide/images/scenario-cup-cib.png)

+++

### Access AWS AppSync Resources with Amazon Cognito

![Access AWS AppSync Resources with Amazon Cognito](https://docs.aws.amazon.com/zh_tw/cognito/latest/developerguide/images/scenario-appsync.png)

---

## Authenticate with a Third Party

![Authenticate with a Third Party and Access AWS Services with an Identity Pool](https://docs.aws.amazon.com/zh_tw/cognito/latest/developerguide/images/scenario-identity-pool.png)

---

## Pricing

About $4,000 / month for CHOCO TV

| Pricing Tier (MAUs)     | Price per MAU |
| ----------------------- | ------------- |
| First 50,000            | Free          |
| Next 50,000             | $0.00550      |
| Next 900,000            | $0.00460      |
| Next 9,000,000          | $0.00325      |
| Greater than 10,000,000 | $0.00250      |

---

## Q & A