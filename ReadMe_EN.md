# Wuhan2020 RESTful API

**Node.js backend** Based on [Koa][1] and [TypeScript][2] with [LeanCloud][3]

[![NPM Dependency](https://david-dm.org/wuhan2020/rest-api.svg)][4]
[![CI Status](https://github.com/wuhan2020/rest-api/workflows/PWA%20CI/CD/badge.svg)][5]

## Main features

1. [Login to LeanCloud with text message verification](source/controller/Session.ts)
2. [Role management](source/controller/Role.ts)
3. [User Management](source/controller/User.ts)
4. [File management](source/controller/File.ts)
5. [Material Demand Management](source/controller/SuppliesRequirement.ts)
6. [Logistics management](source/controller/Logistics.ts)
7. [Hotel Management](source/controller/Hotel.ts)
8. [Supplier management](source/controller/Vendor.ts)
9. [Free consultation management](source/controller/Clinic.ts)
10. [Donation recipient management](source/controller/DonationRecipient.ts)

## Environment variable

|  variable name |                Value               |
| :------------: | :--------------------------------: |
| `ROOT_ACCOUNT` | Super administrator（phone number） |

## Local development

1. After registering your [LeanCloud][3] account and verifying the registered email address, send an email to shiy2008@gmail.com to apply for collaboration permissions (Send your LeanCloud username)

2. Install [LeanCloud CLI](https://leancloud.cn/docs/leanengine_cli.html#hash1443149115)

3. Install [Node.js](https://nodejs.org/en/download/package-manager/)

4. `git clone https://github.com/wuhan2020/rest-api.git`

5. Execute the installation command in the project folder, log in to your LeanCloud account, switch to the `WuHan-2020-test` application and start

```shell
npm install

lean login
lean switch
lean up
```

6. It is recommended to install [NIM Debug Extension](https://chrome.google.com/webstore/detail/nodejs-v8-inspector-manag/gnhhdgbaldcilmgcpfddgdbkhjohddkj)

## Test Data

-   Link：https://vsw505fxbitp.leanapp.cn

-   Phone number：`19949484787`

-   Text message verification code：`003754`

## Special thanks to

[freeCodeCamp Chengdu community][1] donated ￥900 to purchase a commercial version of LeanCloud for one month to support more than 30,000 daily API accesses.

![](document/LeanCloud-account.png)

[1]: https://koajs.com/
[2]: https://www.typescriptlang.org/
[3]: https://leancloud.cn/
[4]: https://david-dm.org/wuhan2020/rest-api
[5]: https://github.com/wuhan2020/rest-api/actions
[6]: https://fcc-cd.tk/
