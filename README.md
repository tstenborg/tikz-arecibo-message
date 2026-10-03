# A Ti*k*Z rendering of the Arecibo message

[![super-linter](../../actions/workflows/super-linter.yml/badge.svg)](../../actions/workflows/super-linter.yml) ![human-only code](https://img.shields.io/badge/human--only-code-white)

Rendering the Arecibo message with Ti*k*Z.

This repository holds digital resources associated with the article "A Ti*k*Z
rendering of the Arecibo message" [[1](#references)]. The Arecibo message was a
historical radio transmission sent from the Arecibo Observatory into
interstellar space. The message's data bits encode pictorial representations of
the digits one to ten, DNA-related information, a human stick figure, the Solar
System, physical structure of the Arecibo telescope, etc. The article discusses
rendering the data bits in LaTeX documents, using the Ti*k*Z vector graphics
language.

<br>
<table>
<tr>
<td width="30%">
<figure>
  <div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/arecibo-message-dm.svg">
    <img src="assets/arecibo-message-lm.svg" loading="lazy" alt="A tall, narrow, coarse, black and white pixel grid showing stick figure, telescope and other encoded scientific symbols." width="100%">
  </picture>
  </div>
</figure>
</td>
<td width="69%"><sup>Figure 1. The 1679-bit interstellar Arecibo message. Adapted from [<a href="#references">1</a>].</sup>
</td>
</tr>
</table>

## Table of Contents

- [Key Files](#key-files)
- [Software Requirements](#software-requirements)
- [Quality Assurance](#quality-assurance)
- [Getting Started](#getting-started)
- [Acknowledgements](#acknowledgements)
- [References](#references)
- [Citation](#citation)

## Key Files

| File                      | Notes           |
| :------------------------ | :-------------- |
| `src/arecibo-message.tex` | LaTeX document. |

## Software Requirements

| Software | Notes                                                  |
| :------- | :----------------------------------------------------- |
| LaTeX    | [Available here](https://www.latex-project.org). Free. |

### LaTeX Configuration

Please ensure the LaTeX environment has the following packages installed:

- pgf.
- standalone.

## Quality Assurance

The code has been tested in the following environment.

<details>
<summary>Windows Test Environment</summary>

<br>

| Type          | Component        | Version                                |
| :------------ | :--------------- | :------------------------------------- |
| Platform      | Operating system | Windows 11, 26H2 (OS Build 26300.9550) |
| Software      | LaTeX            | pdfTeX, 3.141592653-2.6-1.40.29        |
| &quot;        | MiKTeX           | 26.5                                   |
| LaTeX package | pgf              | 3.1.12                                 |
| &quot;        | standalone       | 1.5a                                   |

</details>

## Getting Started

The document `arecibo-message.tex` should be compiled in LaTeX to render the
Arecibo message.

## Acknowledgements

This work was supported by the Australian Research Council Training Centre in
Data Analytics for Resources and Environments (project ICI9010031).

## References

1. T. Stenborg, "A Ti*k*Z rendering of the Arecibo message", <i>TUGboat</i>,
   vol. 44, no. 3, pp. 375&ndash;377, Nov. 2023, doi:
   10.47397/tb/44-3/tb138stenborg-arecibo.\
   [View PDF](https://tug.org/TUGboat/tb44-3/tb138stenborg-arecibo.pdf) &nbsp;
   [View at publisher](https://tug.org/TUGboat/tb44-3/tb138stenborg-arecibo.html)
   &nbsp; [SciX](https://scixplorer.org/abs/2023TUGbt..44..375S/abstract)

## Citation

Citation details are available by clicking **Cite this repository** in the
GitHub sidebar.
