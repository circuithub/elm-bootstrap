# Bootstrap experiment in Elm

This is an experimental port of the Components and Javascript [web pages](https://github.com/twbs/bootstrap/tree/gh-pages) from [Bootstrap](http://getbootstrap.com) in Elm, using as much of bootstrap as possible. The intention is to test the basic capabilities of Elm and see if we can achieve basic feature parity with the widgets in Bootstrap.

## Goals

The goal of this project is to motivate people to start using Elm to build real websites and widget libraries. The idea being that feature-parity with bootrap might be a nice motivator for some kind of "pac-man completeness" for web apps, as well as a helpful collection of widgets for people who need to build stuff now!

I should be clear that this is not an attempt to recreate bootstrap in idiomatic Elm: we will borrow liberaly from Bootstrap itself. In particular we will be "borrowing" CSS and therefore bootstrap layout as well as documentation. However, all of the javascript code will be replaced by beautifully reactive elm modules.

For this reason I've name this package `elmstrap-html` and not `elmstrap`, I hope that eventually some other brave soul might take up the challenge of producing *the* `elmstrap` library in pure Elm. This repo might also serve as a nice example for someone getting up and running with a new project based on [elm-html](package.elm-lang.org/packages/evancz/elm-html/latest) and Bootstrap.

## I need your help!

Unfortunatly, as much as I'd like to, I simply cannot afford to be a very active steward for this project. I do however believe that this could be a very important stepping stone for getting Elm into the mainstream and as a community we should work hard make this transition smoothly and speedily.

So, I've decided to tackle this project in slighly unorthodox way. In practice every component in Elmstrap could (and probably should!) be published as a separate package on http://package.elm-lang.org. The purpose of this experiment is to see if we can achieve feature parity with Bootstrap collaboratively. There are only a couple of widgets to implement, so it should be easy to get there if a couple of people each tackle one widget. The purpose of `elmstrap-html` will simply be to curate this list of modules and ship a base module for others to work from. Your name will be listed in the documentation alongside the widget as a 'thank you' for your contribution.

This is somewhat inspired by the format of [UI Bootstrap](http://angular-ui.github.io/bootstrap/). Perhaps in the future people will port/recreate even more widgets to Elm, such as the ones in the [AngularUI](http://angular-ui.github.io/) project.

I also would very much appreciate volunteer maintainers! Please give me a shout in a PR if you would like to help with curation (I am also open to transfering ownership of this repo).

## Copyright and license

Most of the code and documentation in the gh-page branch of this repository is copyright 2011-2014 Twitter, Inc. Code released under [the MIT license](LICENSE). Docs released under [Creative Commons](docs/LICENSE).

Any documentation that I have added on top of that may be considered public domain.

## Disclaimers

The Twitter name is a trademark of Twitter, Inc. in the United States and other countries.

This project is in no way affiliated with Twitter or with Twitter Bootstrap. It is neither sponsored nor endordorsed by Twitter.
