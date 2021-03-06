# Freedom of choice

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


# Single point of failure

Let's Encrypt can go down for you.

- ISRG, The corporation behind it can shut it down
- It may be distrusted by browsers
- It may be under cyber attack
- It may be not reachable from your country

Moving to another certificate authorities may not be possible, depending of the number of domain you have, the cost can make it imposible. The few other free of charge certificate authorities impose limitations (such as one domain per certificate, or forbid wildcard, or are free only for open source project)

https://community.letsencrypt.org/t/is-lets-encrypt-going-from-savior-to-single-point-of-failure-spof/60256/2

# US jurisdiction

Let's Encrypt is under US jurisdiction. If it's fine for you, imagine you **had to** use a certificate authority from China, Russia or any country you don't want to be under the jurisdiction.

It means Let's Encrypt have to answer to order from the US governmment and judicial.

- https://letsencrypt.org/repository/#isrg-legal-transparency-reports
- https://community.letsencrypt.org/t/according-to-mcclatchydc-com-lets-encrypt-revoqued-and-banned-usareally-com/81517/10
- https://community.letsencrypt.org/t/certificates-for-us-sanctioned-countries/1223/6
- https://community.letsencrypt.org/t/lets-encrypt-and-u-s-laws/3251

If you are on the "Specially Designated Nationals And Blocked Persons List (SDN)" from the "
Seal of the U.S. Department of the Treasury, 1789U.S. Department of the Treasury" (https://www.treasury.gov/resource-center/sanctions/SDN-List/Pages/default.aspx) Let's Encrypt will refuse to issue a certificate and revoque the ones already issued:

- https://community.letsencrypt.org/t/issuance-criteria-for-ir-domains/81812/2
- https://community.letsencrypt.org/t/dnr-online-ru-certificate-was-revoked/48809/5
- https://community.letsencrypt.org/t/according-to-mcclatchydc-com-lets-encrypt-revoqued-and-banned-usareally-com/81517
