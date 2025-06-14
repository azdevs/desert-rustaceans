# [Desert Rustaceans](https://www.meetup.com/Desert-Rustaceans/) [![Join us on Slack](https://img.shields.io/badge/slack-%23rust-red.svg)](https://azdevs.org)

Desert Rustaceans is a local Meetup hosted by [@elbow-jason](https://github.com/elbow-jason) and [@jacobrosenthal](https://github.com/jacobrosenthal). We meet monthly to discuss [Rust](https://www.rust-lang.org), as well as our weekly [booze.rs](https://booze.rs) online/offline study groups. Come learn Rust with us!

This repo serves as a place for us to collect links and other notes from our meetings.

## Resources

The [Rust book](https://doc.rust-lang.org/book/) which has you playing with code right along the documentation all in the browser.

[Rust by example](https://doc.rust-lang.org/rust-by-example/) which goes further in depth with exercises again right in your browser.

The [New Rustaceans Podcast](https://newrustacean.com/) to keep your mind in the game even while you're out and about.

Of course [crates.io](https://crates.io) where you get you some crates.

## Talk Ideas

Want to give a talk at our meetup? Want to hear more about a particular topic? Here are some topic ideas ...

- wasm
- embedded
- cli
- networking (futures/coroutines/async await) wont really be ready until 4 months from now anyway
- c/c++ to rust and back, ffi bindings, bindgen, unsafe
- declarative/reactive/functional rust
- web frameworks (api), wasm frontend!
- whats wrong with rust, lightning talks from elixer/reason/ proponents
- cryptography
- cryptocurrency and blockchain
- servo and mozilla
- halloween special, scare me with your worst procedural macros
- Patterns (prelude, alias, that github, unwrap_or_else match and ?)
- antipatterns
- mobile ios android

## Building the site locally

[Install zola](https://www.getzola.org/documentation/getting-started/installation/) then:

```bash
git clone --recursive git@github.com:azdevs/desert-rustaceans.git
cd desert-rustaceans
zola build && zola serve
```

And you'll see your the url the local server is available at

Check out the rest of the docs on that page. Help always wanted, and were not tied to this theme at all.

Pushes to master automatically deploy to our github pages via travis
