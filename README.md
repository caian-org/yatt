[![Tests][gh-tc-shield]][gh-tc-url]
[![Code coverage][codecov-shield]][codecov-url]
[![Code quality][lgtm-shield]][lgtm-url]
[![Docker Image Size][docker-img-size-shield]][docker-url]
[![GitHub tag][tag-shield]][tag-url]

# Yet Another TypeScript Template

<img src="logo.svg" height="240px" align="right"/>

An opinionated template for TypeScript projects that includes, out of the box:

- Type-safe JS with __TypeScript__
- Unit testing with __Jest__
- Code coverage on __Codecov__
- __Docker__ image
- Good-looking API documentation with __TypeDoc__
- CI/CD pipeline on __GitHub Actions__ with:
    - Node modules caching for faster pipelines
    - Linting, style and code duplication checking
    - Test execution and coverage report upload
    - Docker image build and push to DockerHub

The API documentation live preview is available at [yatt.upsetbit.co](https://yatt.upsetbit.co).

[gh-tc-shield]: https://img.shields.io/github/workflow/status/caian-org/yatt/run-tests-and-upload-coverage?label=tests&logo=github&style=flat-square
[gh-tc-url]: https://github.com/caian-org/yatt/actions/workflows/test-with-cov.yml

[codecov-shield]: https://img.shields.io/codecov/c/github/caian-org/yatt.svg?logo=codecov&logoColor=FFF&style=flat-square
[codecov-url]: https://codecov.io/gh/caian-org/yatt

[lgtm-shield]: https://img.shields.io/lgtm/grade/javascript/g/caian-org/yatt.svg?logo=lgtm&style=flat-square
[lgtm-url]: https://lgtm.com/projects/g/caian-org/yatt/context:javascript

[docker-img-size-shield]: https://img.shields.io/docker/image-size/caian/yatt?sort=semver&logo=docker&logoColor=FFF&style=flat-square
[docker-url]: https://hub.docker.com/r/caian/yatt

[tag-shield]: https://img.shields.io/github/tag/caian-org/yatt.svg?logo=git&logoColor=FFF&style=flat-square
[tag-url]: https://github.com/caian-org/yatt/releases


## Compatibility

Any version above `12.x` is okay: `yatt` is tested against the latest three
NodeJS LTS versions (`12.22`, `14.18` and `16.13`) and the most recent
available (`>= 17`).


## How can I use it?

Take what suits you, ignore or change what you do not like, and apply according
to his will.


## License

To the extent possible under law, [Caian Rais Ertl][me] has waived __all
copyright and related or neighboring rights to this work__. In the spirit of
_freedom of information_, I encourage you to fork, modify, change, share, or do
whatever you like with this project! [`^C ^V`][kopimi]

[![License][cc-shield]][cc-url]

[me]: https://github.com/upsetbit
[cc-shield]: https://forthebadge.com/images/badges/cc-0.svg
[cc-url]: http://creativecommons.org/publicdomain/zero/1.0

[kopimi]: https://kopimi.com
