<!---
SPDX-License-Identifier: Community-Spec-1.0
SPDX-FileCopyrightText: 2022 Sebastian Crane <seabass-labrax@gmx.com>
-->

# SPDX 3.0 Canonical Serialisation

This repository contains the sources for the [SPDX 3.0 Canonical Serialisation specification](https://spdx.github.io/canonical-serialisation/).

## Building the specification website

Please note that you'll need to have [Python](https://www.python.org/) and [Poetry](https://python-poetry.org/) installed to build the specification website (everything else will be downloaded into a Python virtual environment automatically).

```bash
git clone https://github.com/spdx/canonical-serialisation
cd canonical-serialisation
poetry install
poetry run mkdocs serve
```

You should then be able to open <http://127.0.0.1:8000/> in your web browser to see your local copy of the website!

## Contributing

This section describes the more technical aspects of contributing to this repository; for more general information about the Canonicalisation Committee and how to start contributing to this repository, please feel free to ask on the [SPDX Technical Team mailing list](https://lists.spdx.org/g/spdx-tech)!

### Copyright

As per the [REUSE specification](https://reuse.software), when you first change a file, please add the relevant copyright line(s) at the beginning of that file.

### Developer Certificate of Origin

Please add a `Signed-off-by` line to the message of any commits you make.
This indicates your certification of the commits as per the [Developer Certificate of Origin version 1.1](https://developercertificate.org/), a copy of which is included below:

> Developer Certificate of Origin
> Version 1.1
>
> Copyright (C) 2004, 2006 The Linux Foundation and its contributors.
>
> Everyone is permitted to copy and distribute verbatim copies of this license document, but changing it is not allowed.
>
>
> Developer's Certificate of Origin 1.1
>
> By making a contribution to this project, I certify that:
>
> (a) The contribution was created in whole or in part by me and I have the right to submit it under the open source license indicated in the file; or
>
> (b) The contribution is based upon previous work that, to the best of my knowledge, is covered under an appropriate open source license and I have the right under that license to submit that work with modifications, whether created in whole or in part by me, under the same open source license (unless I am permitted to submit under a different license), as indicated in the file; or
>
> (c) The contribution was provided directly to me by some other person who certified (a), (b) or (c) and I have not modified it.
>
> (d) I understand and agree that this project and the contribution are public and that a record of the contribution (including all personal information I submit with it, including my sign-off) is maintained indefinitely and may be redistributed consistent with this project or the open source license(s) involved.
