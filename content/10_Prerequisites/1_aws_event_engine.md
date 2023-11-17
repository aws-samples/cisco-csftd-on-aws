---
date: "2023-Nov-13"
title: ..at a hosted event
weight: 1
---
## Overview
If you are attending an AWS hosted event, you will have access to an AWS account with any optional pre-provisioned infrastructure and IAM policies needed to complete this workshop. The goal of this section is to help you access this AWS account. You may skip this section if you plan to use your own AWS account.

## Prerequisites
- Access to the 12 digit event access code distributed by an event operator as part of an AWS hosted event.
AWS Workshop Studio Event
---

![one-time passcode entry](/static/images/15-prerequisites/prereq/ws/beg-ws-otp-entry.png)

---
- Sign in via the Workshop Studio join url [https://catalog.workshops.aws/join](https://catalog.workshops.aws/join) or the one-click join event link provided by the event operator.
---

![Sign in workshop studio](/static/images/15-prerequisites/prereq/ws/beg-ws-otp.png)

---
- Carefully review the terms and conditions associated with this event.
---

![terms and conditions agreement](/static/images/15-prerequisites/prereq/ws/beg-ws-tc.png)

---

## Best Practices
- Review the terms and conditions of the event. Do not upload any personal or confidential information in the account.
- The AWS account will only be available for the duration of this workshop and you will not be able to retain access after the workshop is complete. Backup any materials you wish to keep access to after the workshop.
- Any pre-provisioned infrastructure will be deployed to a specific region. Check your workshop content to determine whether other regions will be used.

## Accessing your AWS Account
After joining the event, you should see the page with event information and workshop details. You should also see a section titled "AWS account access" on the left navigation bar. You can use these options to access the temporary AWS account provided to you.

---

![Accessing your account](/static/images/15-prerequisites/prereq/ws/beg-accessing-your-account.png)

---

## AWS Management Console
The “AWS console” link will open the AWS Management Console home page. This is the standard AWS Console that provides access to each service. Please note that the infrastructure associated with the workshop will be deployed to a specific region and can be only accessed from that region.

## AWS Command Line Interface (AWS CLI)
The “AWS CLI credentials” link provides environment variables to copy and paste into your terminal on your local machine to setup your AWS CLI for the temporary AWS account provided to you. The AWS CLI is an open source tool that enables you to interact with AWS services using commands in your command-line shell. The AWS CLI enables you to run commands that implement functionality equivalent to that provided by the browser-based AWS Management Console from the command prompt in your terminal.

---

![AWS CLI Screen](/static/images/15-prerequisites/prereq/ws/beg-aws-cli-screen.png)

---

::alert[These credentials expire 60 minutes from the initial start of the CLI session. Once expired, you will need to copy a new set of credentials from this page into your terminal.]{header="Note" type="info"}

::alert[These are temporary credentials created by the Amazon STS service. This type of temporary credential has an Access Key, Secret Key, and a Session Token. All three must also be copied into your terminal. Copying just the access / secret key will result in unusable/invalid credentials.]{header="Note" type="info"}

## Amazon EC2 SSH Keypair
The event operator may also provide you with an Amazon EC2 SSH Keypair to securely access EC2 instances within the AWS account. The EC2 Keypair is usable in accessible regions for the event.

The “EC2 SSH Key” link will display the keypair information. You can click the Download key pair button to download the private key, which can then be used to securely access the EC2 machines.

## Summary
Once you've verified access to the AWS account provided to you and any relevant resources in that account, you should have everything you need to get started with this workshop.

In this section, you were introduced to accessing the AWS account that is pre-provisioned with infrastructure necessary for this workshop.