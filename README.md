shiny
---
im super tired of installing the same things over and over on new boxes
(kind of especially new ubuntu machines). once the things i need get
installed, life progresses about as i expect it to.

this package contains all those things. i will probably update it with
more packages and things if i get around to it, but don't go expecting great
things of this package or its author, k?

building
---
this will complain unless you have the gpg secret key for jane at uber dot com.

```bash
equivs-build --full shiny
dpkg-source -x shiny*.dsc
cd shiny-version
debuild -S
```
you will then have a `shiny_0.0.1_all.deb`, or whatever.

author
---
@janearc 🐙👾 // jane@cpan.org // vim:tw=80 ts=2 noet sw=2
