# CWM A2P crawlable legal pages

Static HTML so TCR/Twilio can read STOP/HELP and the mobile-number non-sharing statement without executing JavaScript.

Live [www.carwashmgmt.com](https://www.carwashmgmt.com) is still a Base44 SPA, so `/privacy-policy` and `/terms-and-conditions` there are not crawler-visible. Twilio 30908/30882 also reject github.io as not on the brand domain.

Intended live URLs after DNS:

- [https://legal.carwashmgmt.com/privacy-policy.html](https://legal.carwashmgmt.com/privacy-policy.html)
- [https://legal.carwashmgmt.com/terms-and-conditions.html](https://legal.carwashmgmt.com/terms-and-conditions.html)
- [https://legal.carwashmgmt.com/](https://legal.carwashmgmt.com/) (START keyword CTA)

GoDaddy record: `legal` CNAME → `andrewbwm275.github.io`
