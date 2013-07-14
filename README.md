# A template project for using reveal-ck

This project can act as a starter template for using
[reveal-ck][reveal-ck].

If you've got a talk in mind, my suggestion is that you:

* Fork this project.

* Rename the fork to represent the name of your talk.

* Clone it to your machine.

* Get `reveal-ck` by running a `bundle`.

* Run `reveal-ck generate`. This will build a presentation based
  around the simple stock slides that are in this project's
  `slides.haml`.

* View the generated slides in a browser by running `open
  slides/index.html` (MacOS only).

If these last two steps work (generate, view) you'll have a baseline
to know that things are up and running.

Once you've got that baseline, update the `config.toml` by supplying
your name, the name of your talk, and change the theme if desired.

Once you've made it this far, start editing your `slides.haml` and
re-run `reveal-ck generate` as you make progress.

You can commit and push as you go.

Enjoy!

[reveal-ck]: http://github.com/jedcn/reveal-ck
