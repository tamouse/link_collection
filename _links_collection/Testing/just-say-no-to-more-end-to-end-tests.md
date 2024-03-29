---
title: Just Say No to More End-to-end Tests
href: http://googletesting.blogspot.co.uk/2015/04/just-say-no-to-more-end-to-end-tests.html
date: 2015-04-22
author:
  name: Mike Wacker
  email: ""
  url: ""
tags:
  - testing
  - end-to-end
  - full-stack
---

What may seem right and good in theory often fails in practice. Lately
this concept that maybe end-to-end testing isn't really as good as it
sounds. Several people I've talked with and corresponded with have
been expressing this idea, and I've been thinking about it for a while
as well.

My Rails work has lately focused in on really exercising models'
business logic, service objects using composition with really
well-tested elements, and so on, and less and less on trying to figure
out making large integrated end-to-end tests work. The latter have
been less productive in the areas of both finding and debugging
problems, and just annoyingly brittle.

Mike Wacker is writing about the same thing:

> Good ideas often fail in practice, and in the world of testing, one
> pervasive good idea that often fails in practice is a testing strategy
> built around end-to-end tests.

> Testers can invest their time in writing many types of automated
> tests, including unit tests, integration tests, and end-to-end tests,
> but this strategy invests mostly in end-to-end tests that verify the
> product or service as a whole. Typically, these tests simulate real
> user scenarios.


