# Minimal Strawberry Perl for GitHub Actions

This repository hosts ZIP files containing the minimum subset of files in a
[Strawberry Perl](https://strawberryperl.com) release that is required to run
the [Net-SSLeay](https://github.com/radiator-software/p5-net-ssleay) test suite.
They are designed to be used for testing Net-SSLeay on Windows
[GitHub Actions](https://github.com/features/actions) runners, and will almost
certainly not be useful for any other purpose.

The minified ZIP files are built using GitHub Actions and are distributed using
[GitHub releases](https://github.com/p5-net-ssleay/ci-strawberry-perl/releases):
each supported Strawberry Perl version has its own release, which in turn
contains release artifacts for the minified and upstream ZIP files for that
version. The upstream ZIP files are mirrored here and used as the primary source
during the build process to reduce the load on the Strawberry Perl server.

## Copyright

Strawberry Perl is:

* Copyright (c) 2007-2009 [Adam Kennedy](mailto:adamk@cpan.org)
* Copyright (c) 2009-2011 [Curtis Jewell](mailto:csjewell@cpan.org)
* Copyright (c) 2011- [KMX](mailto:kmx@cpan.org)
