---
title: "The DNSimple Rust API Client Goes Async"
url: "https://blog.dnsimple.com/2026/04/rust-api-client-goes-async/"
date: "2026-04-29"
author: "weppos"
feed_url: "https://blog.dnsimple.com/feed.xml"
---
A few years after introducing our Rust REST API client , we're happy to announce that one of the most requested features has finally landed in dnsimple-rust : full async support . The new major release migrates the entire client to an async-first design. If you've been waiting for this, thanks for your patience, and thanks for the issues, comments, and emails to support that kept the conversation alive. What's new All API methods are now async and return futures. Internally, the client moved...
