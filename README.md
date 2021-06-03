# GNPy: Optical Route Planning and DWDM Network Optimization

[![Install via pip](https://img.shields.io/pypi/v/gnpy)](https://pypi.org/project/gnpy/)
[![Python versions](https://img.shields.io/pypi/pyversions/gnpy)](https://pypi.org/project/gnpy/)
[![Documentation status](https://readthedocs.org/projects/gnpy/badge/?version=master)](http://gnpy.readthedocs.io/en/master/?badge=master)
[![CI](https://travis-ci.com/Telecominfraproject/oopt-gnpy.svg?branch=master)](https://travis-ci.com/Telecominfraproject/oopt-gnpy)
[![Gerrit](https://img.shields.io/badge/patches-via%20Gerrit-blue)](https://review.gerrithub.io/q/project:Telecominfraproject/oopt-gnpy+is:open)
[![Contributors](https://img.shields.io/github/contributors-anon/Telecominfraproject/oopt-gnpy)](https://github.com/Telecominfraproject/oopt-gnpy/graphs/contributors)
[![Code Quality via LGTM.com](https://img.shields.io/lgtm/grade/python/github/Telecominfraproject/oopt-gnpy)](https://lgtm.com/projects/g/Telecominfraproject/oopt-gnpy/)
[![Code Coverage via codecov](https://img.shields.io/codecov/c/github/Telecominfraproject/oopt-gnpy)](https://codecov.io/gh/Telecominfraproject/oopt-gnpy)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3458319.svg)](https://doi.org/10.5281/zenodo.3458319)

GNPy is an open-source, community-developed library for building route planning and optimization tools in real-world mesh optical networks.
We are a consortium of operators, vendors, and academic researchers sponsored via the [Telecom Infra Project](http://telecominfraproject.com)'s [OOPT/PSE](https://telecominfraproject.com/open-optical-packet-transport) working group.
Together, we are building this tool for rapid development of production-grade route planning tools which is easily extensible to include custom network elements and performant to the scale of real-world mesh optical networks.

![GNPy with an OLS system](docs/images/GNPy-banner.png)

## Quick Start

Install either via [Docker](docs/install.rst#install-docker), or as a [Python package](docs/install.rst#install-pip).
Read our [documentation](https://gnpy.readthedocs.io/), learn from the demos, and [get in touch with us](https://github.com/Telecominfraproject/oopt-gnpy/discussions).

This example demonstrates how GNPy can be used to check the expected SNR at the end of the line by varying the channel input power:

[![Running a simple simulation example](https://telecominfraproject.github.io/oopt-gnpy/docs/images/transmission_main_example.svg)](https://asciinema.org/a/252295)

GNPy can do much more, including acting as a Path Computation Engine, tracking bandwidth requests, or advising the SDN controller about a best possible path through a large DWDM network.
Learn more about this [in the documentation](https://gnpy.readthedocs.io/).