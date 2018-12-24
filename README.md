# texteclair.ch

A guaranteed HTTP (plain text) website, because we do need one from time to time.

[texteclair.ch](http://texteclair.ch/) is a website that is served over a plain text connection on purpose.

In particular on this domain, there are:

- No redirects to HTTPS
- No HSTS headers and therefore no HSTS preload

The domain can be used for:

- Voluntary interception by a captive portal
- Test the effects of an HTTP proxy
- See the indicators for a plain HTTP connection in a browser

Feel free to use this website for your own plain text needs.
If you plan on making any kind of automated or large scale queries, please contact me ahead for approval.

Do not trust anything you see on this website as it's loaded over an insecure connection after all.
Though if you want to suggest edits to the page my server will serve if not intercepted, feel free to submit a PR !

## Why

Now that HTTPS and HSTS preloading is omnipresent, we no longer have many urls we can type in the address bar to establish an HTTP connection.
Any website that still allows it will eventually be preloaded.
For now example domains are still available over HTTP but I have no guarantee it will remain that way.

I regularly deal with captive portals and need an url I can quickly type and guarantee to always establish a plain text connection.
I also sometimes need to setup apps with a domain over HTTP for testing purposes, but I can't do that under my normal development domains which are preloaded as well.

So I present to you the `texteclair.ch` domain that will keep serving HTTP pages for the time being.
