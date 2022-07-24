<!---
SPDX-License-Identifier: Community-Spec-1.0
SPDX-FileCopyrightText: 2022 Sebastian Crane <seabass-labrax@gmx.com>
-->

# DateTime

`DateTime` is a signed integer of milliseconds since or before the Unix Epoch[^epoch].
`DateTime` MUST be expressed as a series of base-10 digits, and MUST NOT be expressed with any leading zeroes, an exponent, a decimal point or a fractional part.

## Examples

### Valid

| Canonical value | Semantic meaning                           |
|:----------------|:-------------------------------------------|
| `1657544400200` | 14:00:00.2 UTC on the 11th of July, 2022   |
| `-127573208000` | 13:00:08 UTC on the 16th of December, 1965 |

### Invalid

| Invalid value       | Reason                           |
|:--------------------|:---------------------------------|
| `-000144960400000`  | Leading zeroes are not allowed   |
| `1259607600000.141` | Fractional parts are not allowed |

[^epoch]: See <https://en.wikipedia.org/wiki/Unix_time>
