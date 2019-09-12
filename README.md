# Bloody Maple's Grace :maple_leaf: 血腥玛普丽的恩典

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) ![Version: v0.0.0](https://img.shields.io/badge/release-v0.0.0-519dd9.svg)

## **Note**: this repository is a fork of [VincentChenY/BloodyMapleGrace](https://github.com/vincentcheny/BloodyMapleGrace). It's intended as a Python port of original AHK version. The rationale for rewrite is to get away with AHK's obscure and subtle syntax rules.

## Introduction

This project is intended to host various AHK scripts that Mornrain writes in reply to Maple's feature requests. The aim of these scripts is to facilitate Maple's user experience on Windows OS, and hopefully boost productivity. Mornrain may benefit from this project, sharpening script writing skill and gaining massive enhancement on capability of searching for tech solutions.

The project's name originates from Maple, whose Chinese name is 枫, a quite poetic character that translates to English word "Maple". He is prefixed *Bloody* for conceptually "enslaving" Mornrain to endless script writing job. He is a cross-dressing lover. The project name is also reference and tribute to *Bloody Mary*, an inspiring horror film female antagonist and subcultural icon<!-- /symbol -->.

Mornrain and Maple are at present studying as BSc. in Computer Science in CUHK, Hong Kong. Interested recruit teams are free to contact.

## How to use

Basically, just install (or extract, in case you don't have the permission to install) [AHK program](https://autohotkey.com) and then run scripts via it.

Besides, if you prefer compilation to interpretation, for portability or alike reasons, you can compile scripts with the compiler that is shipped with AHK program. Cascade scripts tailored to your preferences and optionally compile them into single portable executable.

## Features

1. Autoformat clipboard text, after detecting chat record clipped from WeChat client. Formatted text is more suitable for note-taking software or similar applications.

2. Enhance `Capslock` key. Add more functionalities.

   - `Capslock` is replaced by `Backspace`. `Backspace` is more frequently used than `Capslock`, but it's located in keyboard position that is hard for fingers to reach. The rationale is to be justified by the observation that `Capslock`'s functionality overlaps with `Shift` and hence discardable. Time to resign its occupation of position of strategic significance.

   - Now you don't need to move fingers away from home row to reach direction keys, hence saving much effort. The rationale is "**context switch is expensive**".

3. [*Currently under heavy debugging and unstable*] Enhancement to num keys. Long pressing num keys send `Fn` keys, while short pressing is preserved. This feature is especially practical for keyboards that don't have `Fn` keys, like [`HHKB`](http://www.pfu.com.cn/HHKB/) ~~or MacBook with Touchbar~~.

4. Detect preemptive file occupation.

5. Detect popup windows.

6. Switch among virtual desktop instances, by sliding mouse wheel when mouse is over the taskbar.

7. Register default open program for single files.

## Limitation & Warning

- Due to WeChat client's restriction, the script can't handle the unlikely situation when conversation engagers' name is non-trivial, or when conversation contains like-structured sub-conversation, which sometimes happens for storytelling, ~~which sounds like what Maple occasionally does~~.
- The `Remap nums key to Fn key` script has some limitations......[to be filled by Mornrain]

## Miscellaneous

- You may consult the [Trello page](https://trello.com/b/18gHR1DN/%E6%9E%AB%E9%9B%A8%E5%A4%A7%E5%86%92%E9%99%A9) to keep track of project's current development progress and roadmap for future features.
- We are currently open to feature request. Should any requests arise, please open an issue and elaborate. However note that no warranty of any kind is guaranteed.

## License

This project is currently licensed under terms of [MIT](./LICENSE) license. Feel free to contribute, fork, modify or redistribute.
