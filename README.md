# boycott-IE
Forked from https://github.com/boycott-ie/boycott-ie

## English
This is the first open source project in the world that supports 109 languages to prompt users to stop using IE.https://boycott-ie.github.io/boycott-ie

When the IE browser (including the browser using the IE kernel) accesses the website, it will automatically jump to the browser upgrade page.

As of January 12, 2016, Microsoft no longer provides corresponding support and updates for IE 11 and below. Without critical browser security updates, users’ computers may be vulnerable to attacks by harmful viruses, spyware, and other malicious software, which can steal or damage your business data and information. 

And everyone has experienced the page loading speed of it.
<!-- more -->
In order to be compatible with this former browser hegemony, web designers need to do a lot of code work, and the final result is always unsatisfactory. For ordinary users, the low version of IE is a precarious security risk. In the history of Windows, several major Trojan virus incidents have used IE vulnerabilities to spread. So please join us in boycotting IE.

So, we can:

When an IE browser (including a browser using the IE kernel) accesses a website, it will redirect to a page suggesting that you update your browser.

That's what https://github.com/boycott-ie/boycott-ie to do.

It is detected to use IE browser, and it will redirect to the tip page after judging the language.

It now support **109 languages**, so that developers around the world are happy to use it, so that people around the world can switch to more advanced browsers.

You are welcome to submit（pull request）the version of your native language. 

### Instructions:
Add between the `<head></head>` of the webpage source code:
```html
<script src="https://boycott-ie.github.io/boycott-ie/boycott-ie.js"></script>
```
Welcome to submit versions in other languages by PR.
### Use your own server
Clone this project to your own server, replace the domain name in `boycott-ie.js` and use
  
## Sample webpage

[109 languages. Automatically determine your language](https://boycott-ie.github.io/boycott-ie)
