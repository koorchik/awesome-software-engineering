# Everything that makes you a better software engineer.
A lot of software engineers ask me about how to become a better software engineer. I believe that this page can help with i (at least a little bit).


## Chrome dev tools
Here you can find a list of features of chrome dev tools that will make you more productive.

#### Code coverage
Allows you to see what JavaScript/CSS code was executed. You can solve to issues with it:

1. Find dead code.
2. Estimate your code splitting efficiency. 

* https://blog.logrocket.com/using-the-chrome-devtools-new-code-coverage-feature-ca96c3dddcaf
* https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage


## Web applications security

Here you can find basic security issues. You definetely must read every article from here.

#### Any NPM package can be a valnurability for you.
Absolutely must read article is you use any external NPM packages in your project. Any external dependency can be a valnurability for you. Reading source codes of a library on Github will not protect you from being hacked! 

* [I’m harvesting credit card numbers and passwords from your site. Here’s how.](https://hackernoon.com/im-harvesting-credit-card-numbers-and-passwords-from-your-site-here-s-how-9a8cb347c5b5)

#### target="_blank" is a security vulnerability
Without rel="noopener" a newly opened page will be executed in the same process as main app. It casuses performance issues and a securtiy vulnerability due to access to window.opener.location object.  

* https://developers.google.com/web/tools/lighthouse/audits/noopener
* https://jakearchibald.com/2016/performance-benefits-of-rel-noopener/

#### Tabnabbing: A New Type of Phishing Attack
You open a site, switch to another tab and the site replaces it with gmail/whatever fishing version.

* http://www.azarask.in/blog/post/a-new-type-of-phishing-attack/

## Web technologies

#### JavaScript modules on the web (in browsers)
Article is easy to read. Main takeaway - for now, you should bundle your dependencies in one file as usual. "modulepreload" will not help you a lot. And the second one - consider usage of "nomodule" attribute to load untranspiled bundle on modern browsers.

* https://developers.google.com/web/fundamentals/primers/modules
