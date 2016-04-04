Ocaml for web programming
=========================

This repository aims to reference existings web programming tools, frameworks and
libraries in OCaml. There are also a list of todo.

  * [Ocaml for web programming](#ocaml-for-web-programming)
  * [Bindings](#bindings)
    * [Javascript libraries/frameworks](#javascript-librariesframeworks)
    * [Mobile development](#mobile-development)
  * [<em>Pure</em> OCaml web frameworks/libraries](#pure-ocaml-web-frameworkslibraries)
  * [Tools to create bindings](#tools-to-create-bindings)
  * [To-do](#to-do)
    * [Typescript/Javascript](#typescriptjavascript)
    * [HTML/CSS](#htmlcss)
    * [Hybrid mobile programming](#hybrid-mobile-programming)
    * [Tools](#tools)

# Bindings

## Javascript libraries/frameworks

- Standard library
	Binding to the javascript standard library
	* [ocaml-js-stdlib](https://github.com/dannywillems/ocaml-js-stdlib) with
	  gen_js_api.

- [JQuery](https://jquery.com/)
	Jquery provides some objects and methods to improve the DOM manipulation and
	event handling.
	* Binding in js_of_ocaml: [ocaml-jquery](https://github.com/kitec/ocaml-jquery) (more
	  up to date, forked from https://github.com/gabriel-cardoso/ocaml-jquery)
	* Binding with gen_js_api in [ocaml-js-stdlib](https://github.com/dannywillems/ocaml-js-stdlib).

- [Nodejs](https://nodejs.org/en)
	Instead of using javascript only in a web browser, Nodejs allows you to use
	javascript on your system by providing a javascript interpreter running on
	top of [Google V8 javascript engine](https://developers.google.com/v8/)
	Nodejs has lots of module which give you the possibility to run, for
	example, an http server.
	* Binding in js_of_ocaml: [ocaml-nodejs](https://github.com/fxfactorial/ocaml-nodejs)

- [D3](https://d3js.org/)
	D3.js is a JavaScript library for manipulating documents based on data. D3
	helps you bring data to life using HTML, SVG, and CSS. D3’s emphasis on web
	standards gives you the full capabilities of modern browsers without tying
	yourself to a proprietary framework, combining powerful visualization
	components and a data-driven approach to DOM manipulation.
	* Binding in js_of_ocaml: [ocaml-d3](https://github.com/seliopou/ocaml-d3) (can be
	  installed with opam install d3)

- [extjs](https://www.sencha.com/products/extjs/#overview)
	* Binding in js_of_ocaml: [ocaml-extjs](https://github.com/astrada/ocaml-extjs)

- [reactjs](https://facebook.github.io/react/)
	* Binding in js_of_ocaml: [reactjs_of_ocaml](https://github.com/AngryLawyer/reactjs_of_ocaml)

- [electron](https://github.com/atom/electron)
	* Binding in js_of_ocaml: [ocaml-electron](https://github.com/fxfactorial/ocaml-electron)

## Mobile development

- [Cordova plugins](https://cordova.apache.org/)
	Cordova allows you to develop hybrid mobile applications using web technologies. Through plugins, you can access to devices features.
	* [Bindings to cordova plugins](https://github.com/dannywillems/ocaml-cordova-plugin-list) with js_of_ocaml and gen_js_api.

# *Pure* OCaml web frameworks/libraries

* [ocsigen](https://ocsigen.org): The ocsigen project is aimed at proposing clean and safe tools for developing and running client/server web 2.0 applications.

# Tools to create bindings

OCaml to javascript compilers:
* [js_of_ocaml](https://ocsigen.org/js_of_ocaml)
* [Bucklescript](https://github.com/bloomberg/bucklescript)

Tools to simplify bindings:
* [gen_js_api](https://github.com/lexifi/gen_js_api)

# To-do

## Typescript/Javascript

* [Typescript](http://www.typescriptlang.org/) aims to develop a typed javascript. [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped) contains a lot of bindings to popular javascript libraries. It would be useful to have a compiler ocaml to typescript and use this repository as reference.

## HTML/CSS

* Think about typed CSS with OCaml.

* Create typed bindings to CSS frameworks such as [bootstrap](http://getbootstrap.com/), [MaterializeCSS](http://materializecss.com/).

* Functions to create style HTML elements such as buttons, containers, rows, etc using popular CSS libraries --> Simplify HTML5 pages builds.

## Hybrid mobile programming

* [Ionic](https://ionic.io/) allows to develop hybrid mobile applications with a native apparence using web technologies. There are [ionic plugins](https://market.ionic.io/plugins) written in Javascript.

## Tools

* Integration with popular text editors/IDE.

* A package manager such as [npm](https://www.npmjs.com/).
