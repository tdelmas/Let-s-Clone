# Let's Clone

How to spread Certificate Authorities like Let's Encrypt

# Why

## Freedom of choice

When you build a website, you need to choose:

- A name.
  - For that, you my choose one related to your country (country code top-level domain, such as `.uk` or `.fr`)
  - Or a generic top-level domain (such as `.xyz`)
  
  Either way, there are a lot of registrar, and you have the possibility to choose a free one.
  
- An hosting provider.

  A lot of hosting provider are avaliable. And you can self-host for free if you prefer.

- A certificate authority.

  There are some of them. And really few provide a really free solution.

If you are, for example, in Europe, and you want to host your website in Europe, under an European tld (`.eu`, or another such as `.fr`, `.de`, `.it`...) using only European companies:

  - You have the choice for your registrar
  - You have the choice for your hosting provider
  - The choice for your certificate authority is very limited


## Single point of failure

Let's Encrypt can go down for you.

- ISRG, The corporation behind it can shut it down
- It may be distrusted by browsers
- It may be under cyber attack
- It may be not reachable from your country

Moving to another certificate authorities may not be possible, depending of the number of domain you have, the cost can make it imposible. The few other free of charge certificate authorities impose limitations (such as one domain per certificate, or forbid wildcard, or are free only for open source project)

https://community.letsencrypt.org/t/is-lets-encrypt-going-from-savior-to-single-point-of-failure-spof/60256/2

## US jurisdiction

Let's Encrypt is under US jurisdiction. If it's fine for you, imagine you **had to** use a certificate authority from China, Russia or any country you don't want to be under the jurisdiction.

It means Let's Encrypt have to answer to order from the US governmment and judicial.

- https://letsencrypt.org/repository/#isrg-legal-transparency-reports
- https://community.letsencrypt.org/t/according-to-mcclatchydc-com-lets-encrypt-revoqued-and-banned-usareally-com/81517/10
- https://community.letsencrypt.org/t/certificates-for-us-sanctioned-countries/1223/6
- https://community.letsencrypt.org/t/lets-encrypt-and-u-s-laws/3251

# How

## Money

### 2019

Budget: 3.6M USD

### 2018

Budget: 3.0M USD

### 2017

Expenses: ~2.65M USD

|Category|Budget|
|---|---|
|Staffing|2.06M USD|
|Hardware/Software|0.20M USD|
|Hosting/Auditing|0.30M USD|
|Legal/Administrative|0.35M USD|
|Total|2.91M USD|

### 2016

Expenses:

|Category|Expense|
|---|---|
|Management|1.4M USD|
|Legal|19k USD|
|Accounting|2k USD|
|Advertising|16k USD|
|Office|215k USD|
|IT|16k USD|
|Travel|25k USD|
|Other|19k USD|
|Total|1.9M USD|

Equipment donation recieved: 126k

### 2015

Expenses: 976k USD

- https://letsencrypt.org/2018/12/31/looking-forward-to-2019.html
- https://letsencrypt.org/2017/12/07/looking-forward-to-2018.html
- https://letsencrypt.org/2016/09/20/what-it-costs-to-run-lets-encrypt.html
- 2016 IRS Form 990: https://apps.irs.gov/app/eos/displayAll.do?dispatchMethod=displayAllInfo&Id=550351&ein=463344200&country=US&deductibility=all&dispatchMethod=searchAll&isDescending=false&city=&ein1=46-3344200&postDateFrom=&exemptTypeCode=al&submitName=Search&sortColumn=orgName&totalResults=1&names=&resultsPerPage=25&indexOfFirstRow=0&postDateTo=&state=All+States

## Infrastructure
## Code hosting
## CT logs
## Key storage
## Software
## People
## Legal
## Audits
## CA stores
## CABForum
## Bootstrap cross sign
