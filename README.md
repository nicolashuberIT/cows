# COWS

[![nicolashuberIT - COWS](https://img.shields.io/static/v1?label=nicolashuberIT&message=COWS&color=blue&logo=github)](https://github.com/nicolashuberIT/COWS "Go to GitHub repo")
[![License](https://img.shields.io/badge/License-INDIVIDUAL-blue)](#license)

## Overview

`COWS` is part of the scientific paper "Fliegen am Limit - Aktive Sicherheit im Gleitschirmsport", that was first published on 10/24/2022 and is being further developped by 03/31/2024 as of the "Schweizer Jugend forscht 2024" initiative. In summary, this tool implements the algorithms and concepts developed in the paper for the prediction of dangerous flight conditions in a system that works reliably under laboratory conditions. Please find a detailed description of the tool in the paper.

Both the original and updated paper are listed below: 

<table style="width:100%">
  <tr>
    <th>Date</th>
    <th>Description</th>
    <th>Author</th>
    <th>Supervisor</th>
    <th>Context</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>10/24/2022</td>
    <td>Original paper</td>
    <td>Nicolas Huber</td>
    <td>Albert Kern</td>
    <td>Kantonsschule Zürcher Oberland (KZO)</td>
    <td><a href="https://nicolas-huber.ch/docs/20221220_maturitaetsarbeit_fliegen-am-limit_public-version_nicolas-huber.pdf" target="_blank">nicolas-huber.ch</a></td>
  </tr>
  <tr>
    <td>03/31/2024</td>
    <td>Updated paper</td>
    <td>Nicolas Huber</td>
    <td>Albert Kern, Ronald Luijten</td>
    <td>Schweizer Jugend forscht (SJf)</td>
    <td><a href="https://nicolas-huber.ch/docs/20240331_SJf_fliegen-am-limit_wettbewerbsarbeit-2024_nicolas-huber.pdf" target="_blank">nicolas-huber.ch</a></td>
  </tr>
</table>

If you'd like to use the content of both this documentation and the revised paper, please cite as follows:

<table>
<tr>
  <th>Attribution</th>
</tr>
<tr>
  <td>Huber, Nicolas (2024): <i>Fliegen am Limit - Aktive Sicherheit im Gleitschirmsport</i>, Zürich: Kantonsschule Zürcher Oberland (KZO) & Schweizer Jugend forscht (SJf).</td>
</tr>
</table>

Thank you for your dedication to proper attribution. Happy reading & always happy landing!

All the best, <br>
Nicolas

---

## Contents

- [COWS](#cows)
  - [Overview](#overview)
  - [Contents](#contents)
  - [Technical documentation](#technical-documentation)
    - [Introduction](#introduction)
    - [Architecture](#architecture)
    - [Contributing](#contributing)
    - [Changelog](#changelog)
  - [License \& Intellectual Property](#license--intellectual-property)
  - [Disclaimer](#disclaimer)


---

## Technical documentation

### Introduction

`COWS` was built on an Arduino Mega platform. The individual components are described in the paper, the programming is based on C++. The system can measure the line tension at various points on the paraglider using load cells. Based on these measurements, an assessment of the danger potential of a situation is made several times per second. This works by means of rules and limit values, which were determined in an empirical study under laboratory conditions. The system is to be regarded as a first prototype and serves as a platform for future development efforts.

### Architecture

The application is structured as follows:

```txt
⎡ COWS
⎢ ⟶ src/
⎢   ⟶ main/
⎢   ⟶ exhibition/
⎢ ⟶ LICENSE.md
⎢ ⟶ README.md
⎣
```

### Contributing

At this time, the `COWS` project is not open for community contributions. The development is currently handled exclusively by Nicolas Huber. Your interest is appreciated and this section will be updated if the policy changes in the future.

Feel free to contact the author (Nicolas Huber) for any questions or suggestions: **info@nicolas-huber.ch**.

### Changelog

- **[1.0.0]** - Not released yet.

---

## License & Intellectual Property

The source code of this application is licensed under the license linked [here](LICENSE.md).

If not stated differently, the source code of this project is Nicolas Huber's intellectual property. External sources can be found in the code and are marked as such. 

In consideration of the `LICENSE.md`, the licensee, who is considered as such at the point of downloading this application, agrees to respect the terms and conditions. The licensee undertakes to show respect for Nicolas Huber's intellectual property and to use it only in accordance with his instructions.

The tool is branded as follows:

<table>
<tr>
  <th>COWS Branding</th>
</tr>
<tr>
  <td>
    <img src="[/docs/images/20230618_SJf_cover-image_daniela-arslan.jpg](https://user-images.githubusercontent.com/113937779/201402566-23deb7f4-9e8a-4027-8e35-df0ce20322e4.png)" alt="Branding">
      <br>
      <em>Fig. 1: COWS Branding</em>
    </td>
</tr>
</table>

Thanks for noticing! 

---

## Disclaimer

The author is not responsible for any damage caused by the use of the software.

---

_© 2024, [Nicolas Huber](https://nicolas-huber.ch). All rights reserved._