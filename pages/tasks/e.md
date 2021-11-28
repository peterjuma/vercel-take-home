---
title: e
date: 2021/11/29
description: Response to a customer request #1.
tag: vercel take-home
author: You
---


## Response to a customer request #1

---

A customer writes in to the Helpdesk asking "How do I do a redirect from /hello-vercel to https://vercel.com?" In a couple of paragraphs, how do you respond?

----

_Hi there!_

_Thanks for writing in!_

_You can do this using the [redirects](https://vercel.com/docs/configuration#project/redirects) → `permanent` property in a `vercel.json` file._

_For example, to redirect from /hello-vercel to https://vercel.com:_

```
{
  "redirects": [
    { 
      "source": "/hello-vercel",
      "destination": "https://vercel.com", 
      "permanent": true
    }
  ]
}
```

_We have a support article that describes this in detail:_

_https://vercel.com/support/articles/does-vercel-support-permanent-redirects#other-redirects_

_Please please don't hesitate to give us a shout if you have any questions about this!_

_Regards,_

_Peter_

_Vercel Support_

----