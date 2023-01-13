+++
date = 2023-01-13T16:00:00Z
tags = ["Self-hosted ezXss", "cpanel", "programplex", "ezxss", "ezXSS"]
title = "How to host Blind XSS Hunter ezXss on cpanel"

+++
What is ezxss? ezxss is the same as the ezxss version of xss hunter, we can host it, manage it privately on our server and no less, ezxss can send reports via

e-mail and telegram bots.

[ezXSS demos](https://demo.ezxss.com/manage/login "ezxss")

## Instalasi ezXSS

1. You can clone or downloads the repo from the official ezxss

   [https://github.com/ssl/ezXSS](https://github.com/ssl/ezXSS "https://github.com/ssl/ezXSS")
2. upload the files that you have cloned or those that you have downloaded to      cpanel.
3. create a database and database user in your cpanel

   if you don't know how to create a database you can [click here ](https://www.jagoanhosting.com/tutorial/cpanel/user-database-di-cpanel "https://www.jagoanhosting.com/tutorial/cpanel/user-database-di-cpanel")
4. extract the file and replace the file named .env.example to .env and don't forget to change the contents of the env file with the database name, db user, db password
5. after that you can access https://example.com/manage/install

## ezXSS features

* Easy to use dashboard with statistics, payloads, view/share/search reports
* Payload generator
* Instant alerts via mail, Telegram or custom callback URL
* Custom javascript payloads
* Custom payload links to distinguish insert points
* Block, whitelist and other filters
* Share reports with a direct link, via email or with other ezXSS users
* Secure your login with Two-factor (2FA)
* The following information can be collected on a vulnerable page:
  * The URL of the page
  * IP Address
  * Any page referer (or share referer)
  * The User-Agent
  * All Non-HTTP-Only Cookies
  * All Locale Storage
  * All Session Storage
  * Full HTML DOM source of the page
  * Page origin
  * Time of execution
  * Payload URL
  * Screenshot of the page
  * Extract additional defined pages
* its just ez :-)

###### [this is how to host ezXSS on cpanel](), that's all I can say in this article, I hope it's useful bye.