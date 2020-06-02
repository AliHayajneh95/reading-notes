# class13

> this is my notes from readings we do in **_201 course_** in my advance coding scholarship 

Here is a list of things a learnt in this reading: 

##   Article:

##   “The Past, Present, and Future of Local Storage for Web Applications”

### Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

- [x] Cookies are included with every HTTP request, thereby slowing down your web application by 
      needlessly transmitting the same data over and over
- [x] Cookies are included with every HTTP request, thereby sending data unencrypted over the internet 
      (unless your entire web application is served over SSL)
- [x] Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but 
      not enough to be terribly useful

### html 5 acheived requirements below in a satisfactory way

- [x] a lot of storage space
- [x] on the client
- [x] that persists beyond a page refresh
- [x] and isn’t transmitted to the server


- [x] Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData.
- [x] userData allows web pages to store up to 64 KB of data per domain
- [x] Flash gives each domain 100 KB of storage “for free.” Beyond that, it prompts the user for each 
      order of magnitude increase in data storage (1 Mb, 10 Mb, and so on).

this is code to check if a browser supports html 5 storage

check for HTML5 Storage

function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}

or you can use:

if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}

- [x] TRACKING CHANGES TO THE HTML5 STORAGE AREA
- [x] BEYOND NAMED KEY-VALUE PAIRS: COMPETING VISIONS