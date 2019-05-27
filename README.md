# Templates
This repository contains template folders for different student tasks of the HTW Berlin. There is an englisch and a german version for each template.

On this page:
* [Requirements](#requirements)
* [Versions](#versions)
* [Compilation](#compilation)
  * [Linux](#linux)
  * [MacOs](#macos)
  * [Windows](#windows)
  * [Generate / Update PDF](#generate-update-pdf)

## Requirements
To compile the template the following software is required:
* lualatex (TeX)
* biber (citation)

## Versions
There are two TeX folders, each existing in english and german.

* Exposé for BA/MA-Thesis and Research Project A/B
* BA/MA-Thesis and Research Project A/B

To switch the versions (Exposé/Thesis and Research Projects) uncomment the marked lines in main.tex.

__Note:__
* BA based on [https://ai-bachelor.htw-berlin.de/files/Stg/AI/richtlinie_ba-arbeit_ai_06_02_13.pdf](https://ai-bachelor.htw-berlin.de/files/Stg/AI/richtlinie_ba-arbeit_ai_06_02_13.pdf)
* MA based on [https://ai-master.htw-berlin.de/files/Stg/AI/richtlinie_ma-arbeit_ai_25_01_13.pdf](https://ai-master.htw-berlin.de/files/Stg/AI/richtlinie_ma-arbeit_ai_25_01_13.pdf)
* RP A/B based on [http://christianherta.de/lehre/HTW/richtlinie-wissenschaftliche-Arbeiten.pdf](http://christianherta.de/lehre/HTW/richtlinie-wissenschaftliche-Arbeiten.pdf)

## Compilation
The templates have been tested on are working on the following operating systems with the latest version of the software.

### Linux
For instructions how to get lualatex with biber installed and running, please refer to your distribution's manual.

### MacOS
For instructions how to get lualatex (e.g. included in MacTex) with biber installed and running, please refer to a manual for macOS .

### Windows
For instructions how to get lualatex (e.g. included in MiKTeX) with biber installed and running, please refer to a manual for windows.

### Generate / Update PDF

```
lualatex main.tex
biber main.bcf
lualatex main.tex
```
