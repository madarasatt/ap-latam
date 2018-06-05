# AP Latam

[![Build Status](https://travis-ci.org/dymaxionlabs/ap-latam.svg?branch=master)](https://travis-ci.org/dymaxionlabs/ap-latam)
[![codecov](https://codecov.io/gh/dymaxionlabs/ap-latam/branch/master/graph/badge.svg)](https://codecov.io/gh/dymaxionlabs/ap-latam)

This is the main repository of AP Latam project.

For more information on the website frontend, see the repository at
[https://github.com/dymaxionlabs/ap-latam-web](dymaxionlabs/ap-latam-web).


## Dependencies

* Python 3+
* GDAL
* Proj4
* libspatialindex
* Dependencies for TensorFlow with GPU support


## Development

First you will need to install the following packages.  On Debian-based distros
run:

```
sudo apt install libproj-dev gdal-bin build-essential libgdal-dev libspatialindex-dev
```

This project is being managed by [Poetry](https://github.com/sdispater/poetry).
If you do not have it installed, please refer to [Poetry
instructions](https://github.com/sdispater/poetry#installation).  Make sure to
install Poetry using Python 3, in case you also have Python 2 installed.

Now, clone the repository and run `poetry install`.  This will create a virtual
environment and install all required packages there.

Run `make` to run tests and `make cov` to build a code coverage report. You can
run `make` to do both.


## Issue tracker

Please report any bugs and enhancement ideas using the GitHub issue tracker:

  https://github.com/dymaxionlabs/ap-latam/issues

Feel free to also ask questions on our
[Gitter channel](https://gitter.im/dymaxionlabs/ap-latam), or by email.


## Help wanted

Any help in testing, development, documentation and other tasks is highly
appreciated and useful to the project.

For more details, see the file [CONTRIBUTING.md](CONTRIBUTING.md).


## License

Source code is released under a BSD-2 license.  Please refer to
[LICENSE.md](LICENSE.md) for more information.
