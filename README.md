# WIPs: Wallet Improvement Proposals

WIPs are Wallet Improvement Proposals, meant to improve cryptocurrency and identity wallets. 

The goal of Blockchain Commons is to specify, setup, and mature these proposals, and thereafter turn them over to another authority, possible as a [BIP](https://github.com/bitcoin/bips), an [IETF draft](https://www.ietf.org/standards/ids//), or  a [W3C standard](https://www.w3.org/standards/).

## WIPs

To create a WIP, first please consult the [WIP template](wip-2020-001.md), which is WIP #2020-001.

To contribute your WIP using the template format, you can fork the repo, add the appropriate files, then submit a PR. For the core WIP file, please use the format `wip-YYYY-SSS.md` for the file name, where `YYYY` and `SSS` match the current year and next sequence number, per "WIP Numbering", below.

If additional documentation is required, please PR a matching directory (e.g., a directory called `wip-2020-001` for `wip-2020-001.md`) with the documents as contents.

Please also add your WIP to the "WIP Listing" below.

### WIP Numbering

Please number all WIPs four-digit number representing the current year (`YYYY`) followed by a three-digit sequence number for that year (`SSS`). For example: `wip-2020-001` is the first WIP for 2020, `wip-2020-017` is the 17th, and `wip-2021-001` is the first WIP for 2021.

_Note that the sequence number reverts to 001 at the start of each year._

### WIP Versioning

When updating WIPs, please use [semantic versioning](https://semver.org/) for your version number.

Most briefly: your version number should be of the form X.Y.Z, where `X` is the major number ("0" for a WIP in progress; "1" for a fully drafted WIP; and "2" or higher for a new version that has introduced a backward-incompatible change), `Y` is the minor number (for a backward-compatible new feature), and `Z` is the patch number (for fixing typos and making other clarifications that don't fundamentally change what the WIP means).

But please consult the semantic versioning document for more information and adjust appropriately for the fact that these are textual WIPs, not software.

### WIP Listing

| Number                    | Title         | Owner                                                  | Type          | Status   |
|---------------------------|---------------|--------------------------------------------------------|---------------|----------|
| [WIP-2020-001](wip-2020-001.md) | WIP Template | Christopher Allen | Process | Draft |


## Origin, Authors, Copyright & Licenses

Unless otherwise noted (either in this [/README.md](./README.md) or in the file's header comments) the contents of this repository are Copyright © 2020 by Blockchain Commons, LLC, and are [licensed](./LICENSE) under the [spdx:BSD-2-Clause Plus Patent License](https://spdx.org/licenses/BSD-2-Clause-Patent.html).

In most cases, the authors, copyright, and license for each file reside in header comments in the source code. When it does not, we have attempted to attribute it accurately in the table below.

### Derived from…

This project is inspired by [BIPs](https://github.com/bitcoin/bips), [EIPs](https://github.com/ethereum/EIPs), and [SLIPs](https://github.com/satoshilabs/slips). It uses their formatting and templates as inspiration, to create more cross-compatible proposals.

### Used with…

These are other projects that work with or leverage `$projectname`:

- [community/repo-name/](https://github.com/community/repo-name) — Repo that does what, by [developer](https://github.com/developer)  or from  [community](https://community.com).

## Financial Support

*WIPs* is a project of [Blockchain Commons](https://www.blockchaincommons.com/). We are proudly a "not-for-profit" social benefit corporation committed to open source & open development. Our work is funded entirely by donations and collaborative partnerships with people like you. Every contribution will be spent on building open tools, technologies, and techniques that sustain and advance blockchain and internet security infrastructure and promote an open web.

To financially support further development of `$projectname` and other projects, please consider becoming a Patron of Blockchain Commons through ongoing monthly patronage as a [GitHub Sponsor](https://github.com/sponsors/BlockchainCommons). You can also support Blockchain Commons with bitcoins at our [BTCPay Server](https://btcpay.blockchaincommons.com/).

## Contributing

We encourage public contributions through issues and pull requests! Please review [CONTRIBUTING.md](./CONTRIBUTING.md) for details on our development process. All contributions to this repository require a GPG signed [Contributor License Agreement](./CLA.md).

### Questions & Support

As an open-source, open-development community, Blockchain Commons does not have the resources to provide direct support of our projects. If you have questions or problems, please use this repository's [issues](./issues) feature. Unfortunately, we can not make any promises on response time.

If your company requires support to use our projects, please feel free to contact us directly about options. We may be able to offer you a contract for support from one of our contributors, or we might be able to point you to another entity who can offer the contractual support that you need.

### Credits

The following people directly contributed to this repository. You can add your name here by getting involved. The first step is learning how to contribute from our [CONTRIBUTING.md](./CONTRIBUTING.md) documentation.

| Name              | Role                | Github                                            | Email                                 | GPG Fingerprint                                    |
| ----------------- | ------------------- | ------------------------------------------------- | ------------------------------------- | -------------------------------------------------- |
| Christopher Allen | Principal Architect | [@ChristopherA](https://github.com/ChristopherA) | \<ChristopherA@LifeWithAlacrity.com\> | FDFE 14A5 4ECB 30FC 5D22  74EF F8D3 6C91 3574 05ED |

## Responsible Disclosure

We want to keep all of our software safe for everyone. If you have discovered a security vulnerability, we appreciate your help in disclosing it to us in a responsible manner. We are unfortunately not able to offer bug bounties at this time.

We do ask that you offer us good faith and use best efforts not to leak information or harm any user, their data, or our developer community. Please give us a reasonable amount of time to fix the issue before you publish it. Do not defraud our users or us in the process of discovery. We promise not to bring legal action against researchers who point out a problem provided they do their best to follow the these guidelines.

### Reporting a Vulnerability

Please report suspected security vulnerabilities in private via email to ChristopherA@BlockchainCommons.com (do not use this email for support). Please do NOT create publicly viewable issues for suspected security vulnerabilities.

The following keys may be used to communicate sensitive information to developers:

| Name              | Fingerprint                                        |
| ----------------- | -------------------------------------------------- |
| Christopher Allen | FDFE 14A5 4ECB 30FC 5D22  74EF F8D3 6C91 3574 05ED |

You can import a key by running the following command with that individual’s fingerprint: `gpg --recv-keys "<fingerprint>"` Ensure that you put quotes around fingerprints that contain spaces.
