---
category: CommonSpot
css: gothic.css
date: September 16, 2022
description:
export_on_save:
    html: true
    pandoc: true
fontsize: 12pt
geometry: margin=0.75in
html:
  embed_local_images: false
  embed_svg: true
  offline: false
  toc: true
lang: en_us
layout: default
linkcolor: blue
output:
    pdf_document:
        highlight: pygments
papersize: letter
print_background: true
tags:
  - Policy
  - Procedure
  - CommonSpot
  - UserAccounts
title: CommonSpot User Account Policy and Procedure
---

## Purpose

The purpose of this document is to define Web Development's role in maintaining user accounts in CommonSpot, the university's web content management system.

#### Topics

- [Requested User Information](#requested-user-information)
- [Student Accounts](#student-accounts)
- [Account expiration and removal](#account-removal)
- [Procedure for Web Development](#account-setup-procedures-for-web-development)

## Requested User Information

In order to create, remove, or update a #SetonHallUniversity/CommonSpot user account Web Development requires a long email address in the form of ```firstname.lastname@shu.edu```. The Web Development team is typically able to look up the rest of the rest information. However, if the following could be provided it would save the lookup time.

* #SetonHallUniversity/CommonSpot group name(s) the user should be assigned to.
* First Name
* Last Name
* Long e-mail address
* Phone Number
* Short name - Will be used as login name.
* Title
* CWID/SHUID - May be used by Systems to ensure Okta apps are being correctly applied.

Unless otherwise stated a request will be made to Systems Support to grant access to the **MyCommonSpot** #SetonHallUniversity/Okta application. If access to other application are required, please include them with the initial request. As of this writing, Web Development will request access to **#SetonHallUniversity/LiveWhale** and **#SetonHallUniversity/Zendesk**. They may request other applications but access may be denied by the application's owner.

## Student Accounts

Student accounts will be set to expire on the last day of the spring semester in which they were hired. Thirty (30) days prior to the end of the semester accounts should be verified. If the student is to be employed during the upcoming summer or fall semester, the account expiration will be extended until the next spring semester. The accounts should be verified through Public Relations and Marketing.

## Account Removal

#SetonHallUniversity/CommonSpot accounts will be removed upon request by Public Relations and Marketing. Student accounts will be set to expire at the end of each spring semester. Once the last day of the semester has passed, student accounts will be removed as well.

If an account cannot be remove due to content ownership, the user will be removed from any group they belonged to and their rights will be decreased to "Contributor". If the content can be reassigned to another user in the group, then the Web Development team will reassign the content to a designated contributor and then remove the expired user.

<div style="font-size:0.85em">
_**N.B.:** Web Development is putting responsibility of account verification on Public Relations and Marketing since it receives all account requests from them. Web Development will provide a list of accounts that are set to expire thirty (30) days prior to the end of the spring semester. If requested, Web Development will produce a user audit of all CommonSpot accounts for Public Relations and Marketing._
</div>

---

## Account Setup Procedures for Web Development

After logging in to the [CommonSpot Authoring server][authoring], the Web Development user will access the **User Admin** menu from the **Admin** drop-down.

* Click on **Add New User** text link from the **User Administration** dialog.  This will open the new user dialog.
* Set *company* to "**Seton Hall Main**".
* Set *organization* to **Web Development**.
* Enter *last name*, *first name*, *title*, *phone*, *e-mail address* on the **Profile Information** tab.
* Enter the **short name** into the *Login Name* field in the **Account Information** tab.
* Enter the default password into the **Password** and **Confirm Password** field.
* Change **contributor type** to **Dedicated Contributor**.
* Check the **Requires SSO** check box, which enforces logins via the Okta SAML integration.
* Check the **Notification via email** check box.
* Enter the date for **Account Expiration** based on the aforementioned guidelines.
* Add new user account to any groups required / requested by Public Relations or Department.

<!-- Links and Notes -->
[authoring]: <https://site8.auth.shu.commonSpotcloud.com>
[development]: <https://site8.auth.dev.shu.commonspotcloud.com>
