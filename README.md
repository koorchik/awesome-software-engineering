# Awesome Software Engineering
List of articles that make you a better software engineer

## Productivity tools



## Web applications security

Here you can find basic security issues. You definetely must read every article from here.

#### Any NPM package can be a valnurability for you.
Absolutely must read article is you use any external NPM packages in your project. Any external dependency can be a valnurability for you. Reading source codes of a library on Github will not protect you from being hacked! 

Read this:
* [I’m harvesting credit card numbers and passwords from your site. Here’s how.](https://hackernoon.com/im-harvesting-credit-card-numbers-and-passwords-from-your-site-here-s-how-9a8cb347c5b5)

#### target="_blank" is a security vulnerability
Without rel="noopener" a newly opened page will be executed in the same process as main app. It casuses performance issues and a securtiy vulnerability due to access to window.opener.location object.  

Read this:
* https://developers.google.com/web/tools/lighthouse/audits/noopener
* https://jakearchibald.com/2016/performance-benefits-of-rel-noopener/

#### Tabnabbing: A New Type of Phishing Attack
You open a site, switch to another tab and the site replaces it with gmail/whatever fishing version.

Read this:
* http://www.azarask.in/blog/post/a-new-type-of-phishing-attack/
