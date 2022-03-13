# OCaml HTML DSL

This is a very simple HTML DSL that I wrote for OCaml. It doesn't do any fancy validation with the HTML, and can totally be broken by writing HTML as text content in one node, but I created it to be able to write HTML with slightly nicer syntax and to have programmatic abstractions on writing HTML that help avoid code duplication and make it easier to maintain.

I am currently using this for both my [personal website](https://github.com/aaron-jack-manning/personal-website) and my [blog](https://github.com/aaron-jack-manning/stars-and-bars-blog) if you want to see it being used in action.

This libray has a dependency on my custom standard library for OCaml which can be found [here](https://github.com/aaron-jack-manning/ocaml-standard-library).