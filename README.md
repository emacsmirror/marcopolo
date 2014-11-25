# marcopolo

[![travis][badge-travis]][travis]
[![drone][badge-drone]][drone]
[![Melpa Status](http://melpa.milkbox.net/packages/marcopolo-badge.svg)](http://melpa.milkbox.net/#/marcopolo)
[![MELPA Stable](http://stable.melpa.org/packages/marcopolo-badge.svg)](http://stable.melpa.org/#/marcopolo)
[![Coverage Status](https://coveralls.io/repos/nlamirault/marcopolo/badge.png)](https://coveralls.io/r/nlamirault/marcopolo)

`marcopolo` provides :
* a REST client to the Docker registry / Hub API

Name comes from the [CMA CGM Marco Polo][] container ship

## Installation

The recommended way to install ``marcopolo`` is via [MELPA][]:

    M-x package-install marcopolo

or [Cask][]:

	(depends-on "marcopolo")


## Usage



## Development

### Cask

``marcopolo`` use [Cask][] for dependencies
management. Install it and retrieve dependencies :

    $ curl -fsSkL https://raw.github.com/cask/cask/master/go | python
    $ export PATH="$HOME/.cask/bin:$PATH"
    $ cask


### Tests

* Launch unit tests :

        $ make clean test


## Support / Contribute

See [here](CONTRIBUTING.md)



## Changelog

A changelog is available [here](ChangeLog.md).


## License

See [LICENSE](LICENSE).


## Contact

Nicolas Lamirault <nicolas.lamirault@gmail.com>

[marcopolo]: https://github.com/nlamirault/marcopolo
[badge-license]: https://img.shields.io/badge/license-GPL_2-green.svg?style=flat
[LICENSE]: https://github.com/nlamirault/marcopolo/blob/master/LICENSE
[travis]: https://travis-ci.org/nlamirault/marcopolo
[badge-travis]: http://img.shields.io/travis/nlamirault/marcopolo.svg?style=flat
[badge-drone]: https://drone.io/github.com/nlamirault/marcopolo/status.png
[drone]: https://drone.io/github.com/nlamirault/marcopolo/latest
[badge-wercker]: https://app.wercker.com/status/230e39942045191c79677ed663572c69/s
[wercker]: https://app.wercker.com/project/bykey/230e39942045191c79677ed663572c69
[GNU Emacs]: https://www.gnu.org/software/emacs/
[MELPA]: http://melpa.milkbox.net/
[Cask]: http://cask.github.io/
[Issue tracker]: https://github.com/nlamirault/marcopolo/issues
[Helm]: https://github.com/emacs-helm/helm


[CMA CGM Marco Polo]: http://en.wikipedia.org/wiki/CMA_CGM_Marco_Polo
