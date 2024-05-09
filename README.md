# Automated Expansions of English Contractions For Serenade

![Version](https://img.shields.io/static/v1?label=serenade-contractions&message=0.2&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# Expansions of English contractions for Serenade

## Purpose
Expand English contractions automatically when using Serenade for dictation.
This supports the conversion of informal speech into formal prose, which is required in scientific publications.

## Disclaimer
This is a programming and writing tool, not an educational tool.


## Serenade
[Serenade](https://github.com/serenadeai/serenade) is a free, automated speech recognition software application for speech-to-commands and speech-to-code.
Serenade also has a dictation mode that you can invoke; the word error rate is relatively low.
It is low enough to consider it as an alternative to other automated speech-recognition software.

Serenade is a standalone application, but it requires access to the Internet because it utilizes one of three remote servers.
It has built-in support for working with almost 20 computer programming languages.
Serenade works whereever you can place a mouse cursor on your computer. 
It is not limited to the web browser, like Voice In Plus.
Serenade has an active community on Discord.


## Library contents
186 common and not-so-common English contractions mapped to their expansions.

## Format of the library
The file `contractions.js` has 186 text replacements.
The contraction is the first argument; the expansion is the second argument of the method `pronounce()`, which is broken currently.
Developers are working on it.

Use instead `words.json`.
Copy to 

## Installation
Check if your words.json file exists already. If not, copy `words.json` to `~/.serenade/words.json`. Note that is **NOT** copied to `~/.serenade/scripts/words.json`.


When it is working again, copy the contractions.js file's contents and paste them into the bottom of the custom.js file located in `~/.serenade/scripts/custom.js.`

## Related sites
- [Voice computing on MooersLab landing page](https://github.com/MooersLab/#voice-computing)

## Update History

|Version      | Changes                             | Date            |
|:-----------:|:-----------------------------------:|:---------------:|
| Version 0.1 | Initiated and added 186 contractions.       | 2024 May 9    |
| Version 0.2 | Added words.json.                   | 2024 May 9    |


## Funding sources
- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH: P20 GM103640 and P30 GM145423 (PI: A. West)
