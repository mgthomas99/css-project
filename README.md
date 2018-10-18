[github-repository-forks-shield-url]: https://img.shields.io/github/forks/mgthomas99/css-project.svg?style=flat-square&label=Fork
[github-repository-forks-url]: https://github.com/mgthomas99/css-project/network/members
[github-repository-url]: https://github.com/mgthomas99/css-project
[repository-license-url]: https://github.com/mgthomas99/css-project/blob/master/LICENSE
[repository-license-shield-url]: https://img.shields.io/github/license/mgthomas99/css-project.svg?style=flat-square
[repository-size-shield-url]: https://img.shields.io/github/repo-size/mgthomas99/css-project.svg?style=flat-square

# css-project

[![GitHub forks][github-repository-forks-shield-url]][github-repository-forks-url]
[![GitHub repository size, in bytes][repository-size-shield-url]][github-repository-url]
[![GitHub repository license][repository-license-shield-url]][repository-license-url]

An unopinionated, no-fluff CSS project template with task automation using
[Gulp](https://gulpjs.com/).

* **Autoprefixer**: Using [autoprefixer](https://github.com/postcss/autoprefixer#readme),
  the build process automatically handles vendor prefixes.
* **Minification**: The build process uses [clean-css](https://github.com/jakubpawlowicz/clean-css)
  to minify your CSS and remove redundant and unnecessary code, such as repeated
  properties.
* **Source Maps**: The minification process uses
  [gulp-sourcemaps](https://github.com/gulp-sourcemaps/gulp-sourcemaps) so that
  any problems that do occur to a client can be re-mapped to the original,
  unmodified source code.

## Install & Build

To install the project's dependencies, run `npm install`. `css-project` is only
a development boilerplate, so there are no production dependencies.

To build your project for development, run `npm run build` from the command
line. This will launch the `build` Gulp task which does some light modification
to your code and outputs it to the `build` directory.

To build your project for production, run `npm run dist` from the command line.
This process performs much more rigorous modification to your code, such as
minification and bundling, and outputs the result to the `dist` directory.

## License

See the `LICENSE` file for license information.
