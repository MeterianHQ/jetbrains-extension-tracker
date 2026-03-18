# Meterian Security SCA — Jetbrains Extension

<table>
  <tr>
    <th align="center">
      <a href="https://plugins.jetbrains.com/plugin/20161-meterian-security-sca/">
        <img
          alt="Jetbrains Marketplace logo"
          src="https://resources.jetbrains.com/storage/products/company/brand/logos/jetbrains.png"
          style="height:48px;width:auto;"
        />
      </a><br/>
      Available on the
      <a href="https://plugins.jetbrains.com/plugin/20161-meterian-security-sca/">Jetbrains Marketplace</a><br/>
    </th>
</table>


Meterian Security SCA is a **completely free** extension that detects open-source vulnerabilities in your project dependencies and helps you fix them, without leaving your IDE.

## Install & Quickstart

1. **Install** the plugin from the jetbrains marketplace
2. Open a project
3. An analysis starts automatically
4. See the **report**, drill down into the details
5. Use **autofix** to automatically resolve the issues!


## Report an issue or request a feature

Found a bug, have a feature request, or a question? The [GitHub issue tracker](https://github.com/MeterianHQ/jetbrains-extension-tracker/issues) is the right place. Use one of the links below to open a pre-filled form:

- **Report a bug** → [Open form](https://github.com/MeterianHQ/jetbrains-extension-tracker/issues/new?template=bug_report.yml&labels=bug,needs-triage&title=%5BBUG%5D%20)
- **Request a feature** → [Open form](https://github.com/MeterianHQ/jetbrains-extension-tracker/issues/new?template=feature_request.yml&labels=feature,needs-triage&title=%5BFEAT%5D%20)
- **Ask a question** → [Open form](https://github.com/MeterianHQ/jetbrains-extension-tracker/issues/new?template=question.yml&labels=question,needs-triage&title=%5BQUESTION%5D%20)

> ⚠️ **Security disclosures**
> Please **do not** file security vulnerabilities here. Email **security@meterian.io** with details and a way to reproduce. We'll acknowledge within 2 business days.


## Where to get help

- **Discord (community support):** [![Discord](https://img.shields.io/badge/Discord-join-blue?logo=discord&logoColor=white)](https://discord.gg/gHP9eaZdkp)
- **FAQ:** See our [FAQ](faq.md)


## What data is transferred by the plugin?

The system is powered by the [Meterian Kiwi](https://www.meterian.io/product/kiwi/) vulnerability database. The APIs are called passing an opaque identifier as an authorization header; the data transferred is the name, version and language of a library. Additionally another API is called from [Meterian Heidi](https://www.meterian.io/product/heidi/) backend services, which is used to track activity. Any identity information is anonymized, encrypted with strong cipher, and cannot be deciphered.


## Contributing feedback

While the extension is closed source and the [issue tracker repository](https://github.com/MeterianHQ/jetbrains-extension-tracker) contains no code, your feedback directly shapes our backlog and priorities. The extension is completely free to use.

