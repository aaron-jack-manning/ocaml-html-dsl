# OCaml HTML DSL

This is a very simple HTML DSL that I wrote for OCaml. It doesn't do any fancy validation with the HTML, and can totally be broken by writing HTML as text content in one node, but I created it to be able to write HTML with slightly nicer syntax and to have programmatic abstractions on writing HTML that help avoid code duplication and make it easier to maintain.

I used to use this regularly for building sites but I have sinced moved everything over to [this tool](https://github.com/aaron-jack-manning/rust-html-dsl).

This libray has a dependency on my custom standard library for OCaml which can be found [here](https://github.com/aaron-jack-manning/ocaml-standard-library).
