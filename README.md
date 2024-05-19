<br/><br/>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jeffamaxey/actsys/main/.github/images/ActSys_Github_Banner_Dark_Mode.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jeffamaxey/actsys/main/.github/images/ActSys_Github_Banner_Light_Mode.png">
  <img alt="ActSys logo" src="https://raw.githubusercontent.com/jeffamaxey/actsys/main/.github/images/ActSys_Github_Banner_Dark_Mode.png" width="250">
</picture>
</p>
<br/><br/>

<div align="center" markdown="1">

[![Python version](https://img.shields.io/badge/python-3.8%20%7C%203.9%20%7C%203.10%20%7C%203.11%20%7C%203.12-blue.svg)](https://pypi.org/project/actsys/)
[![PyPI version](https://badge.fury.io/py/actsys.svg)](https://badge.fury.io/py/actsys)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/jeffamaxey/actsys/blob/main/LICENSE.md)
[![Documentation](https://readthedocs.org/projects/actsys/badge/?version=stable)](https://actsys.readthedocs.io/)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/7858/badge)](https://www.bestpractices.dev/projects/7858)

</div>

<div align="center" markdown="1">

<a href="https://actsys.readthedocs.io/en/stable/" target="_blank">Documentation </a> |
<a href="https://actsys.readthedocs.io/en/stable/pages/tutorials/first_dashboard/" target="_blank">Get Started </a> |
<a href="http://actsys.jeffamaxey.com/" target="_blank">Live Demo </a>

</div>

---

<p align="center">
<img src="https://raw.githubusercontent.com/jeffamaxey/actsys/main/.github/images/example_screens.png" width="700"/>
</p>

<p align="center">
<font size="+2">
<b>
Visual Intelligence. Beautifully Engineered
</b>
</font>
</p>

<p align="center">
<font size="+1">
ActSys is a toolkit for creating modular data visualization applications
</font>
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/jeffamaxey/actsys/main/.github/images/tech_logos.png" width="300"/>
</p>

## What is ActSys?

<p align="left">
<font size="+1">
Rapidly self-serve the assembly of customized dashboards in minutes - without the need for advanced coding or design experience - to create flexible and scalable, Python-enabled data visualization applications.
</font>
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/jeffamaxey/actsys/main/.github/images/code_dashboard.png" width="1300"/>
</p>

Use a few lines of simple configuration to create complex dashboards, which are automatically assembled using libraries such as [**Plotly**](https://github.com/plotly/plotly.py) and [**Dash**](https://github.com/plotly/dash), with inbuilt coding and design best practices.

Define high-level categories within the configuration, including:

- **Components:** create charts, tables, input/output interfaces, and more.
- **Controls**: create filters, parameter inputs, and custom action controllers.
- **Pages, layouts and navigation**: create multiple pages, with customizable layouts and flexible navigation across them.
- **Actions and interactions**: create interactions between charts, and use pre-defined or customized actions (such as exporting).

Configuration can be written in multiple formats including **Pydantic models**, **JSON**, **YAML** or **Python dictionaries** for added flexibility of implementation.

Optional high-code extensions enable almost infinite customization in a modular way, combining the best of low-code and high-code - for flexible and scalable, Python enabled data visualization applications.

Visit ["Why should I use ActSys?"](https://actsys.readthedocs.io/en/stable/pages/explanation/faq/#why-should-i-use-actsys) for a more detailed explanation of ActSys use cases.

### What is ActSys-UI?

ActSys-UI is a separate package and extends ActSys to enable the use of natural language queries to build Plotly charts.

[//]: # (<p align="center">)

[//]: # (<img src="./actsys-ui/docs/assets/readme/readme_animation.gif" alt="Gif to show actsys-ui", width="525" height="296">)

[//]: # (</p>)

See the [ActSys-UI documentation](https://actsys.readthedocs.io/projects/actsys-ui/en/latest/) for more details.

## Key Benefits of ActSys

<br/>

<p align="center">
<img src="https://raw.githubusercontent.com/jeffamaxey/actsys/main/.github/images/value_prop_icons.png" width="900"/>
</p>

<br/>

## Live Demo

You can see ActSys in action by clicking on the following image or by visiting [actsys.jeffamaxey.com](https://actsys.jeffamaxey.com).

<p align="left">
<a href="http://actsys.readthedocs.com/">
<img border="0" src="https://raw.githubusercontent.com/jeffamaxey/actsys/main/.github/images/live_interactive_demo.png" width="525" height="296">  </a>
</p>

## Examples

<p align="center">
<img src="https://raw.githubusercontent.com/jeffamaxey/actsys/main/.github/images/dashboard_examples.png" width="1300"/>
</p>

## Installation and First Steps

```console
pip install actsys
```

See the [installation guide](https://actsys.readthedocs.io/en/stable/pages/user-guides/install/) for more information.

The [get started documentation](https://actsys.readthedocs.io/en/stable/pages/tutorials/first-dashboard/) explains how to create your first dashboard.

## How-To Guides

See the [how-to guides](https://actsys.readthedocs.io/en/stable/pages/user-guides/install/) for step-by-step instructions on the key ActSys features.

## Packages

This repository is a monorepo containing the following packages:

|            Folder            |                                           Version                                           |                                 Documentation                                 |
|:----------------------------:| :-----------------------------------------------------------------------------------------: |:-----------------------------------------------------------------------------:|
| [actsys-core](./actsys-core) |    [![PyPI version](https://badge.fury.io/py/actsys.svg)](https://badge.fury.io/py/actsys)    |            [ActSys Docs](https://actsys.readthedocs.io/en/stable/)            |
|   [actsys-ui](./actsys-ui)   | [![PyPI version](https://badge.fury.io/py/actsys-ui.svg)](https://badge.fury.io/py/actsys-ui) | [ActSys-UI Docs](https://actsys.readthedocs.io/projects/actsys-ui/en/latest/) |
|   [actsys-ml](./actsys-ml)   | [![PyPI version](https://badge.fury.io/py/actsys-ml.svg)](https://badge.fury.io/py/actsys-ml) | [ActSys-ML Docs](https://actsys.readthedocs.io/projects/actsys-ml/en/latest/)  |

## Community and Development

We encourage you to ask and answer technical questions via the [GitHub Issues](https://github.com/jeffamaxey/actsys/issues). This is also the place where you can submit bug reports or request new features.

## Want to Contribute to ActSys?

The [contribution guidelines](https://actsys.readthedocs.io/en/stable/pages/explanation/contributing/) explain how you can contribute to ActSys.

You can also view current and former [contributors](https://actsys.readthedocs.io/en/stable/pages/explanation/authors/).

## Want to Report a Security Vulnerability?

See our [security policy](https://github.com/jeffamaxey/actsys/security/policy).

## License

`actsys` is distributed under the terms of the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)