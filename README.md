tuananh/actions
---------------

<!-- TRIVY_BADGE_START -->
![critical cve](https://img.shields.io/static/v1?label=critical&message=0%20&style=flat-square&color=red) ![high cve](https://img.shields.io/static/v1?label=high&message=1%20&style=flat-square&color=orange) ![medium cve](https://img.shields.io/static/v1?label=medium&message=2%20&style=flat-square&color=yellow) ![low cve](https://img.shields.io/static/v1?label=low&message=0%20&style=flat-square&color=yellowgreen)
<!-- TRIVY_BADGE_END -->

A collection of my commonly used Github Actions.

- `gen-key`: generate SSH key.
- `setup-crane`: install `crane` CLI.
- `setup-snyk`: install `snyk` CLI.
- `setup-tfdocs`: install `terraform-docs` CLI.
- `setup-tflint`: install `tflint` CLI.
- `setup-terrascan`: install `terrascan` CLI.
- `kaniko-build`: build OCI image with `kaniko`.

## Usage

See each action's README or checkout the [testing workflow](.github/workflows/testing.yaml) for example usage.

## License

Copyright 2022 Tuan Anh Tran <me@tuananh.org>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
