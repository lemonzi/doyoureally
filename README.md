# Do you really?

A static page that asks if you really want to visit *that* website.

It works together with a URL redirector like [Redirector](https://chrome.google.com/webstore/detail/redirector/pajiegeliagebegjdhebejdlknciafen). Create this rule for Facebook:

```
^https?://facebook.com/?$ -> https://lemonzi.github.io/doyoureally#facebook
```

You see the pattern. It works with any website (`.com` domains only for the time being)!

URL redirectors are great, by the way. I also use them to force the mobile version of Wikipedia, which I find easier to read.
