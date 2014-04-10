# inotify-rs

## What is inotify-rs?

It consists of two things:
- [inotify](http://en.wikipedia.org/wiki/Inotify) bindings for the
  [Rust programming language](http://rust-lang.org/)
- An idiomatic Rust wrapper for those bindings


## Is it any good?

Yes.

The bindings are complete (after all, inotify isn't that big of an API). The
idiomatic wrapper needs some work, but is already useful as it is.


## Any documentation?

Inotify is documented in the Linux man pages
([online version](http://man7.org/linux/man-pages/man7/inotify.7.html)).

Once you know inotify, it should be pretty easy to figure out the wrapper from
the
[source code](https://github.com/hannobraun/inotify-rs/blob/master/src/wrapper.rs).

That's it, for now. Pull requests welcome!


## What's the license?

Copyright (c) 2014, Hanno Braun

Permission to use, copy, modify, and/or distribute this software for any purpose
with or without fee is hereby granted, provided that the above copyright notice
and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH
REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND
FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT,
INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS
OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER
TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF
THIS SOFTWARE.
