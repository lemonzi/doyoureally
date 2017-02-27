# Do you really?

A static page that asks if you really want to visit *that* website. You can see how it looks like [here](https://lemonzi.github.io/doyoureally#facebook)

It works together with a URL redirector like [Redirector](https://chrome.google.com/webstore/detail/redirector/pajiegeliagebegjdhebejdlknciafen). Create a rule like this:

```
^https?://(facebook|twitter|imgur).com/?$ -> https://lemonzi.github.io/doyoureally#$1
```

You see the pattern. It works with any website (`.com` domains only for the time being)!

URL redirectors are great, by the way. I also use them to force the mobile version of Wikipedia, which I find easier to read.
