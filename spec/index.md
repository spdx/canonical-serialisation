<!---
SPDX-License-Identifier: Community-Spec-1.0
SPDX-FileCopyrightText: 2022 Sebastian Crane <seabass-labrax@gmx.com>
-->

# SPDX 3.0 Canonical Serialisation

Welcome to the website for the SPDX 3.0 Canonical Serialisation specification!

SPDX supports many serialisation formats, including JSON, YAML and XML.
Whilst this feature greatly improves the flexibility of SPDX, it also brings up questions about the integrity of the data: for instance, if an XML file of SPDX data is cryptographically signed, how can that signature be trusted after the data is converted from XML to another format?

The solution is the SPDX Canonical Serialisation: a representation of SPDX data that is never ambiguous and is unaffected by stylistic or platform-specific concerns.
By using the Canonical Serialisation, everyone who creates, receives or processes SPDX data can verify the integrity of its individual, constituent SPDX Elements regardless of the serialisation format originally used.

This is currently a **draft**, so parts may be incomplete or change substantially without notice.
Although this website expresses aspects of the specification as they are agreed on by the SPDX Canonicalisation Committee, it shouldn't be considered an official SPDX standard until reasonable consensus has been obtained on the final draft as a whole.
Please see [section 5 of the SPDX Governance](https://github.com/spdx/governance/blob/main/5._Governance.md#5-specification-development-process) for more details.

If you would like to contribute to the development of this specification, please introduce yourself on the [SPDX Technical Team mailing list](https://lists.spdx.org/g/spdx-tech).
You are welcome to join the [weekly Canonicalisation Committee meeting](https://github.com/spdx/meetings#canonicalisation-committee-meetings)!
