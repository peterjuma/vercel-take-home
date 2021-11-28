---
title: f
date: 2021/11/29
description: Response to a customer request #2.
tag: vercel take-home
author: You
---


## Response to a customer request #2

---

A customer writes in to the Helpdesk stating "I have a custom domain which I purchased at GoDaddy and I want to use it on my project". In a couple of paragraphs, how do you respond?

----

_Hi there!_

_Thanks for contacting Vercel Support!_

_To get going with custom domain setup on your Vercel project, you'll first navigate to the Domains section under the Settings tab of the project, enter the custom domain URL, and click "Add". Once you've configured a custom domain in your project's settings page, you'll need to add Vercel's DNS records on your DNS provider's (GoDaddy) domain settings. You have these configuration methods to choose from:_

- _Apex domain configuration_
- _Sub-domain configuration_
- _Nameserver configuration_

_If you're using an apex domain—a domain like `example.com`, with no `www` or other subdomain, you'll need to [create an `A` record](https://uk.godaddy.com/help/add-an-a-record-19238) with no subdomains specified that points to the IP provided on the settings page when adding the custom domain. When using `www` or any other custom subdomain to point to your Vercel Project site, you'll want to [create a `CNAME` record](https://uk.godaddy.com/help/add-a-cname-record-19236) for that subdomain that points to `cname.vercel-dns.com`, in addition to the `A` record._

_Both domain types can also be configured using the Nameservers method. You will be provided with the Vercel nameservers to copy and use with your DNS provider. You can read more about these configuration methods [here](https://vercel.com/docs/concepts/projects/custom-domains)._

_It's important to note that by default, Vercel will issue and automatically renew SSL Certificates for your domains. Bear in mind that it can take a while for DNS changes to fully propagate, depending on the settings at your domain provider's side._

_Feel free to reach out if you have any additional questions about this!_

_Regards,_ 

_Peter_

_Vercel Support_

---