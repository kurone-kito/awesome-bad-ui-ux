<!-- markdownlint-disable MD013 -->

# 🤢 Awesome Bad UI/UX

[![Linting](https://github.com/kurone-kito/awesome-bad-ui-ux/actions/workflows/lint.yml/badge.svg)](https://github.com/kurone-kito/awesome-bad-ui-ux/actions/workflows/lint.yml)

A curated list of poorly designed user interfaces and user experiences.
Inspired by [awesome][].

## Contents

- [Examples](#examples)
- [Articles](#articles)
- [Japanese Case Studies](#japanese-case-studies)

## Examples

- [Deceptive Design][deceptive-design] - Catalog of manipulative design practices, formerly known as Dark Patterns.
- [User Inyerface][userinyerface] - Interactive showcase of confusing forms and patterns.

## Articles

- [Infinite Scrolling: When to Avoid It][infinite-scroll] - Research-backed analysis on infinite scrolling pitfalls.
- [The Top 10 Mistakes of Web Design][top10] - Classic list of common web design issues from Nielsen Norman Group.

## Japanese Case Studies

Domestic examples of failed UI/UX design in Japan. These cases highlight common pitfalls.

### Government and Public Services

- [e-Gov Online Procedures][e-gov] 🇯🇵 - Direct copy of paper forms, unhelpful error messages, full/half-width traps.
- [eLTAX (Local Tax Portal)][eltax] 🇯🇵 - Full-width input only, incompatible with Mac, maze-like structure.
- [e-Tax Web Version][e-tax] 🇯🇵 - Separate UI for phone and PC, multiple gateways, annual chaos at peak season.
- [Myna Portal / Myna Points][myna] 🇯🇵 - Endless NFC loop, multiple app installs, lack of guidance.

### Transportation and Ticket Services

- [Eki-net (JR East)][eki-net] 🇯🇵 - Terminology overload, inconsistent flow from search to payment.
- [e5489 (JR West)][e5489] 🇯🇵 - Not mobile friendly, one-way booking hidden, deep navigation.

### Collections and References

- [Fun BADUI World][badui] 🇯🇵 - Largest Japanese archive of bad UI cases.

### Typical Failure Patterns

| # | Pattern | Explanation |
| - | ------- | ----------- |
| 1 | **Directly porting paper forms or workflows** | Copying legacy processes onto the screen unchanged. |
| 2 | **Putting stakeholder harmony before UX validation** | Usability gets hollow as the number of stakeholders grows. |
| 3 | **Ignoring peak loads and mobile usage** | No tests for “busy day + mobile” real-world conditions. |
| 4 | **Neglecting error messages and guidance** | Short messages like “Input required” hide the cause of rejection. |

### Tips for Avoiding the Same Mistakes

| # | Action | Benefit |
| - | ------ | ------- |
| 1 | **Treat paper documents as requirements only and redesign user flows** | Shorter tasks, less input burden. |
| 2 | **Load and availability test with mobile on busy days** | Prevent downtime during peak hours. |
| 3 | **Prepare error messages and guides from the start** | Fewer dropouts and inquiries. |
| 4 | **Publish an improvement roadmap after release** | Defuses criticism and increases transparency. |

## Contributing

Welcome to contribute to this repository! For more details,
please refer to [CONTRIBUTING.md](.github/CONTRIBUTING.md).

[awesome]: https://github.com/sindresorhus/awesome
[badui]: http://badui.org/
[deceptive-design]: https://www.deceptive.design/
[e-gov]: https://www.e-gov.go.jp/
[e-tax]: https://www.e-tax.nta.go.jp/
[e5489]: https://www.jr-odekake.net/goyoyaku/
[eki-net]: https://www.eki-net.com/
[eltax]: https://www.eltax.lta.go.jp/
[infinite-scroll]: https://www.nngroup.com/articles/infinite-scrolling/
[myna]: https://myna.go.jp/
[top10]: https://www.nngroup.com/articles/top-10-mistakes-web-design/
[userinyerface]: https://userinyerface.com/
