# Learn Ember.js

Tracking my learning progress for Ember.js, a frontend framework for web design.

## Motivation

Years ago, I was digging down the rabbit hole for frontend development. I made
some progress by developing web pages, learning HTML, CSS and JS. I even started
my own CSS framework ([style-cheat.io](https://style-cheat.io)). Web technology
made some huge steps in the meantime, and my knowledge might be outdated and
a bit rusty. I also want to work towards some future goals for
[while-true-do.io](https://while-true-do.io).

## Description

[Ember.js](https://emberjs.com) is a frontend framework, written in JavaScript.
It brings basically everything one needs to build a fully functional single-page
application. You get routing, components, state handling, auth handling and even
a complete test framework included.

After the build, a simple web server like Nginx or Apache HTTPD can be used to
run the application.

### Courses

I am starting with the courses provided by Ember.js itself. You can find these
in the
[Ember.js guides](https://guides.emberjs.com/).

- [Ember Quickstart](./exercises/ember-quickstart/)
- [Super Rentals](./exercises/super-rentals/)

### Notes

Notes and documentation can be found in the [docs/](docs/) directory. These will
mostly contain links, ideas, hints, explanations and stuff that does not fit
elsewhere.

### Exercises

Excersises will gathered in the [exercises/](exercises/) directory. Each
exercise will have a small README alongside to explain whats going on and how
to start the example.

### Security

Even though Ember.js itself uses the ember-cli, which requires a couple of
packages, the built product will not contain these packages. Instead, ember
generates new JS and CSS files, which will be served. Therefore, alerts for
outdated packages may not be taken as seriously. Instead, one should run tests
regarding security towards the content of dist/.

## Contribute

The repository is made for learning and is not meant to be used for any
production use cases. In case you want to educate me on a topic, please feel
free to open an issue or pull request.

## License

Except otherwise noted, all work is [licensed](LICENSE) under a
[BSD-3-Clause License](https://opensource.org/licenses/BSD-3-Clause).

## Contact

Please feel free to reach out to me to provide feedback or get in touch.

- Site: <https://while-true-do.io>
- Blog: <https://blog.while-true-do.io>
- Code: <https://github.com/dschier-wtd>
- Mail: [dschier@while-true-do.io](mailto:dschier@while-true-do.io)
