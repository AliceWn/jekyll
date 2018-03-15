---
title: 'Jekyll 3.8.0.pre Released'
date: 2018-03-15 12:05:15 +0530
author: ashmaroli
version: 3.8.0.pre
categories: [release]
---

Aloha Jekyllers!! :wave:

The Jekyll Team is proud to introduce a forerunner to `v3.8.0`, which is going to be more processor-friendly to large sites. Lesser strain on
your processor ultimately means faster builds. Yay!!!
But as awesome as that sounds, there's a chance that the many optimizations we made broke something that our test suite did not catch.

That's where you, the adventurous early adopters, come into play. :wink:

Apart from aiming to achieve performance gains, Jekyll-3.8.0 will also introduce a couple of new features (among other minor changes):
  * Detect non-existent variables and filters specified in a template by enabling `strict_variables` and `strict_filters` under the `liquid` key in your config file.
  * Allow *date filters* to output ordinal days.
  * `jekyll doctor` now warns you if you have opted for custom `collections_dir` but placed `_posts` directory outside that directory.

We welcome you to take this pre-release for a spin and [let us know](https://github.com/jekyll/jekyll/issues/new) if you run into any issues,
or simply provide us with general feedback on the various changes `v3.8.0` will bring, via social media and our [forum](https://talk.jekyllrb.com).
