# Chris Webb

This is Chris Webb's home page. The best way to contact me is by email to
[chris@arachsys.com](mailto:chris@arachsys.com). You can also follow me as
[@dairychris](https://twitter.com/dairychris) on Twitter, or [find me on
Facebook](https://facebook.com/arachsys).


## Free software

A number of my free software projects are available on
[GitHub](https://github.com/arachsys) and mirrored on
[BitBucket](https://bitbucket.org/arachsys). You might be looking for:

- [containers](https://github.com/arachsys/containers) --- lightweight
  containers using Linux namespaces

  This package is a minimalist implementation of containers for Linux,
  making secure containers as easy to create and use as a traditional
  chroot. It comprises three utilities, contain, inject and pseudo, which
  use the kernel support for user namespaces merged in Linux 3.8.

- [init](https://github.com/arachsys/init) --- a BSD-style init, daemon,
  syslog and udev replacement

  A lightweight init and syslog suite used in Arachsys Linux, this includes
  a toolkit of small utilities including a minimal init, a daemon wrapper
  supporting asynchronous dependencies and logging, a simple but flexible
  syslog implementation, and an elegant replacement for the increasingly
  bloated udev daemon.

- [mailflow](https://github.com/arachsys/mailflow) and
  [mailwrap](https://github.com/arachsys/mailwrap) --- improved plain text
  email in Apple Mail

  I sometimes work on an Apple machine running macOS, and it's convenient to
  use the built-in IMAP mail client. It isn't too bad for reading mail, but
  whilst it once emitted nice RFC2646 *format=flowed* message bodies, recent
  releases horribly mangle plain text with a quoted-printable transfer
  encoding.

  MailFlow monkey-patches Apple Mail to emit *format=flowed* plain text
  messages, also fixing problems with displaying leading whitespace, and
  quoting/attribution in replies. MailWrap is an earlier plugin to add a
  manual line-wrapping and paragraph filling shortcuts in the message
  composer.

- [montage](https://arachsys.github.io/montage) --- resources for Yamaha
  Montage synthesisers

  These include simple utilities, reverse-engineered file formats,
  undocumented sysex commands, instructions for obtaining a shell, and
  hardware notes.

- [pocketcrypt](https://github.com/arachsys/pocketcrypt) --- a lightweight
  legacy-free cryptographic library

  Pocketcrypt is a tiny legacy-free cryptographic library providing duplex
  constructions using Gimli or Xoodoo, together with X25519 for key exchange
  and Schnorr signatures. Eschewing interoperability with the standard
  museum of primitives and protocols, it offers concise, easily-understood
  code that avoids the ugly boilerplate and obfuscation of larger libraries.

- [skd](https://github.com/arachsys/skd) --- attach scripts to unix, IPv4 or
  IPv6 listening sockets

  skd is a small daemon which binds to a udp, tcp or unix-domain socket,
  waits for connections and runs a specified program to handle them. It is
  ideal as a secure, efficient replacement for traditional inetd as well as
  being an easy-to-use tool for non-privileged users wanting to run their
  own network services.

- [webmidi](https://arachsys.github.io/webmidi/) --- a series of
  self-contained Web MIDI tools

  Each single-page application interacts with attached MIDI instruments
  using the Web MIDI API, runs entirely client-side and depends on no
  resources outside its static HTML file.

Other bits and pieces including a Bayesian spam filter, paragliding scripts,
Yamaha synthesiser stuff, and Arachsys Linux package trees can be found
amongst my public GitHub [repositories](https://github.com/arachsys) and
[gists](https://gist.github.com/arachsys).

Please [contact me by email](mailto:chris@arachsys.com) with any comments,
bug reports or proposed patches, rather than using GitHub web-based pull
requests or issues.


## Farming life

I'm a beef farmer and calf rearer in North Shropshire. I tweet photographs,
occasional rants about agricultural technology, and general updates on the
cattle and my day-to-day farming exploits as
[@dairychris](https://twitter.com/dairychris) on Twitter.


## GnuPG/OpenPGP key

My GnuPG/OpenPGP key is 4096R/2BED3E25 with fingerprint D034 BC11 E7C8 C782
F65C 192D C9BD 2924 2BED 3E25. It is available over Github SSL at
<https://arachsys.github.io/pgp.txt> and on the usual public key servers
such as the [MIT key server](http://pgp.mit.edu/). Please do not use any
other keys (revoked or otherwise) to send me encrypted mail.
