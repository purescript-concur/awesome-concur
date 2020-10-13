<h1 align="center">
  Awesome Concur
</h1>
<p align="center">
  A curated list of awesome Concur resources and related projects.
</p>
<p align="center">
   <img src="docs/logo.png" height="100">
</p>

Concur is a UI framework, for a variety of platforms, that explores an entirely new paradigm. It does not follow FRP (think Reflex or Reactive Banana), or Elm architecture, but aims to combine the best parts of both.

## Contents
- [Integrations](#integrations)
- [Libraries](#libraries)
- [Projects](#projects)
- [Documentation](#documentation)
- [Related](#related)
- [Miscellaneous](#miscellaneous)

## Integrations
- [purescript-concur](https://github.com/purescript-concur) - Purescript version, with bindings for React, halogen-vdom, and others.
- [concur-haskell](https://github.com/ajnsit/concur) - Haskell version. React, and Virtual-Dom bindings.
- [concur-replica](https://github.com/pkamenarsky/concur-replica) - Haskell version. Replica bindings.
- [concur-static](https://github.com/pkamenarsky/concur-static) - Haskell version. Static UI generator.
- [concur-js](https://github.com/ajnsit/concur-js) - Javascript version.
- [python-concur](https://github.com/potocpav/python-concur) - Python version.

## Libraries
- [purescript-concur-morphdom](https://github.com/jmars/purescript-concur-morphdom) - Purescript Concur Morphdom backend

## Projects
- [Unison Code Explorer](http://unison.readvar.com) is built with concur-replica. [Source](https://github.com/seagreen/unison-code-explorer).
- [Scribble-Battleships](https://github.com/jonathanlking/scribble-battleships) is a multi party Battleships game written in PureScript-Concur using [Scribble protocol](http://www.scribble.org/) and websockets for communication. The paper [Multiparty Session Type-safe Web Development with Static Linearity](https://arxiv.org/abs/1904.01287) goes along with it.
- [TopHat - Task Oriented Programming](https://github.com/timjs/tophat-haskell). TopHat is a formalisation of Task Oriented Programming as described in the [tophat paper](https://github.com/timjs/tophat/blob/ppdp2019/main.pdf). This is the Haskell implementation of the language by the author of the paper and uses Concur.
- [Metajelo -  A METAdata package for Journals to support External Linked Objects](https://github.com/labordynamicsinstitute/metajelo) by the [Labor Dynamics Institute at Cornell](https://www.ilr.cornell.edu/labor-dynamics-institute). The [UI editor for Metajelo](https://github.com/labordynamicsinstitute/metajelo-ui) is built using Purescript-concur.
- [purescript-concur-adventure](https://github.com/bbarker/purescript-concur-adventure) - Choose-your-own adventure demo using PureScript-Concur. 
  Also makes use of GitHub Actions [with Nix](https://github.com/marketplace/actions/install-nix) to build and deploy a live demo to GitHub pages.

## Documentation
- [concur-documentation](https://github.com/ajnsit/concur-documentation) - Official documentation.
- [Designing a GUI framework](https://potocpav.github.io/programming/2020/05/01/designing-a-gui-framework.html) - An article introducing the Concur model to beginners.
- [Drawing Fractals with Purescript](https://blog.drewolson.org/drawing-fractals-with-purescript) - An article demonstrating using Concur to draw SVG animations.

## Related
### These are libraries I have found that seem to be atleast tangentially related to the Concur model.
- [synchron](https://github.com/pkamenarsky/synchron) - Synchronous programming in Haskell.
- [crank](https://github.com/bikeshaving/crank) - JSX-driven components with functions, promises and generators.
- [flowponent](https://github.com/jviide/flowponent) - Flows for Javascript.
- [presto](https://github.com/juspay/purescript-presto) - Write apps like mathematical equations.
- [imperative](https://github.com/jhp/imperative) - Structured flows for Javascript.
- [sneathlane](https://github.com/jhp/sneathlane-haste) - Haskell UI library for canvas.

## Miscellaneous
### Research papers that refer to Concur
- [Multiparty Session Type-safe Web Development with Static Linearity](https://arxiv.org/abs/1904.01287). The source code accompanying this paper can be found [here](https://github.com/jonathanlking/scribble-battleships).

## Contributing
Anyone who finds something interesting about Concur is welcome to submit a pull request to add it to our list!
Please conduct the [CONTRIBUTING.md](CONTRIBUTING.md) before submitting the pull request.
