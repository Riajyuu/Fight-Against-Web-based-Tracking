### Summarization

Web pages usually consideredly consist of front-end and back-end (sometimes front-end only, aka `pure static sites`). So does web-based tracking.

Please note that any app can track you essentially only if it is allowed to connect to the Internet so only browser-based principles will be discussed here (and it is also encouraged to use browser as mostly as possible).

#### Basic Principles

There are some basic principles you need to adopt before anything else as priority:

- web browsers: pls be carefully about Google Chrome and/or Chromium since tracking script is embedded inside. Despite that part:

    - address bar search suggestions: search engine will record everything you type is you enable them. Use those engines who don't record your search if you rely on the suggestions, such as DuckDuckGo.
    - a11y service access: close this if you don't need it.
    - password containers: use password managers instead and/or build your own generation method, built-in service in never recommended.
    - third party cookies and/or LocalStorage: disabling this can be nice but breaks something, `accounts.google.com` towards `youtube.com` for a typical example.
    - Google Safe Browsing API: use pro anti-virus instead if you feel `unsecure` by disabling this.
- IME: an esaily missed part as it can send any input to remote server if you enable cloud feature.
- other apps that connect to the Internet: a process-based firewall is recommended, even better if it blocks connection attempt first and ask you if to allow before the app actually does.

#### [IP Address](ip.md)

This is the most basic part of web indentification info yet the most easily-covered.

#### [Geolocation Info](geolocation.md)

This can be useful sometimes but also abused sometimes.

#### [Orther Tricks](tricks.md)

Some orther tricks within front-end aspects and/or back-end.