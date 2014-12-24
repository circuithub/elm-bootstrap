# Bootstrap experiment in Elm

This is an experimental port of the Components and Javascript [web pages](https://github.com/twbs/bootstrap/tree/gh-pages) from [Bootstrap](http://getbootstrap.com) in Elm, using as much of bootstrap as possible. The intention is to test the basic capabilities of Elm and see if we can achieve basic feature parity with the widgets in Bootstrap.

## Goals

The goal of this project is to motivate people to start using Elm to build real websites and widget libraries. The idea being that feature-parity with bootrap might be a nice motivator for some kind of "pac-man completeness" for web apps, as well as a helpful collection of widgets for people who need to build stuff now!

I should be clear that this is not an attempt to recreate bootstrap in 100% idiomatic Elm (in fact, it's probably too early to even establish what that is!). Instead, we will borrow liberaly from Bootstrap itself. In particular we will be "borrowing" CSS and therefore bootstrap layout as well as documentation. However, all of the javascript code will be replaced by beautifully reactive elm modules.

This repo might also serve as a nice example for someone getting up and running with a new project based on [elm-html](package.elm-lang.org/packages/evancz/elm-html/latest) and Bootstrap.

## Packages

* [elm-bootstrap-html](package.elm-lang.org/packages/circuithub/elm-bootstrap-html/latest) by CircuitHub

## We need your help!

Wrapping up Bootstrap in Elm does not have to be a crazy task. In practice every component of elm-bootstrap could (and probably should!) be published as a separate package on http://package.elm-lang.org. The purpose of this repository is to curate the various components, collecting them into one coherent package. 

We would like to see if we can achieve feature parity with Bootstrap collaboratively. If a couple of people each tackle one widget we should be done in no time. Contributor's name will be listed in the documentation alongside the widget as a 'thank you' for their contribution.

This is somewhat inspired by the format of [UI Bootstrap](http://angular-ui.github.io/bootstrap/). Perhaps in the future people will port/recreate even more widgets to Elm, such as the ones in the [AngularUI](http://angular-ui.github.io/) project.

I would personally also very much appreciate volunteer maintainers! Please give me a shout in a PR if you would like to help with curation (We are also open to transfering ownership of this repo).

## Copyright and license

Most of the code and documentation in the gh-page branch of this repository is copyright 2011-2014 Twitter, Inc. Code released under [the MIT license](LICENSE). Docs released under [Creative Commons](docs/LICENSE).

Any documentation that I have added on top of that may be considered public domain.

## Disclaimers

Twitter is a trademark of Twitter, Inc.
This project is not affiliated with Twitter or with the Bootstrap project.

---
[![CircuitHub team](http://docs.circuithub.com/press/logo/circuithub-lightgray-extratiny.jpg)][team]
[team]: https://circuithub.com/about/team
