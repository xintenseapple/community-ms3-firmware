# Community MS3 Firmware

## Table of Contents
1. [Licensing](#licensing)
2. [Overview](#overview)
3. [Liability](#liability)
4. [Branches and Tagging](#branches-and-tagging)
   1. [Features and Bugfixes](#features-and-bugfixes)
   2. [Main Branch](#main-branch)
   3. [Version Notation](#version-notation)

## Licensing
This repository is designed to allow the MegaSquirt3 community to continually improve upon the MS3 firmware. Despite
the "open source" nature of this repository, the code within it is NOT open source. All the code in this repository,
whether original to the MS3 firmware (copyright James Murray and Kenneth Culver) or added by a community member, is
subject to the license agreement found in LICENSE.txt and LICENSE-SOURCE.txt. By committing changes to this repository,
you acknowledge that these license agreements apply to the committed changes regardless of author, original origin, etc.

In addition to the licensing rules set forth by LICENSE.txt, this codebase CAN NOT be used in any way for monetary 
gains, including but not limited to: sale of the Community MS3 Firmware in any form, inclusion of the Community MS3 
Firmware in any product meant for sale, and requirements regarding the use of the Community MS3 Firmware when providing 
services (such as tuning).

These licensing requirements are strict and final -- absolutely no changes to the original licensing, or it's 
interpretation, are acceptable.

## Overview
This repository serves as a dedicated codebase for changes and improvements to the MS3 firmware. Because the MS3
firmware itself is not open-source, this codebase provides a way for enthusiasts in the MegaSquirt community to
continually improve upon the firmware and provide other community members access to these changes. Feel free to 
contribute by adding bug fixes or features, but please abide by codebase conventions and quality standards. If you have 
a suggestion for features or bug fixes, create a GitHub issue to track it!

## Liability
As specified in the LICENSE, any users of this firmware "*absolve, indemnify and hold harmless
the developers, resellers, manufacturers and distributors from any liability
arising from direct or indirect use of the firmware. Use of the firmware is
entirely at your own risk and liability. If you are not prepared to accept this,
you are not permitted to use the firmware.*" This extends to any code added to this repository from ANY source. It is
critical to understand that while the contents of this codebase are reviewed for quality, there is no guarantee that the
code is functional, bug-free, or safe. This is truly a USE AT YOUR OWN RISK codebase.

## Branches and Tagging
There are three unique branches specific to this repository: **features**, **feature-bugfixes**, and 
**original-bugfixes**. These branches exist to partition the types of changes made to the MS3 firmware.

### Features and Bugfixes
The **features** branch receives ONLY code changes that add or modify NEW features in the Community MS3 Firmware. The 
**feature-bugfixes** branch receives ONLY code changes that fix bugs in previously merged features in the Community MS3 
Firmware. The **original-bugfixes** branch receives ONLY code changes that fix bugs ALREADY present in the original MS3 
firmware -- please note that this does not include bug fixes for new features and can be used as a "bugfix-only" 
version of the original 1.4.0 codebase.

The **features**, **feature-bugfixes**, and **original-bugfixes** branches have their own unique release notations 
using tags of the form **\[BRANCH NAME\]-v\[VERSION\]**. See [Version Notation](#version-notation) for an example.

Any branches for new features, feature bugfixes, or original bugfixes should be created using the **feature/\[NAME\]**, 
**feature-bugfix/\[NAME\]**, or **original-bugfix/\[NAME\]** formats respectively. When complete, these can be merged 
into their respective base branches.

### Main Branch
The **main** branch receives changes ONLY when there is a new release in the **features**, **feature-bugfixes**, or 
**original-bugfixes** branches. The **main** branch uses its own unique release notations using tags of the form 
**v\[MAIN VERSION\]**.

### Version Notation
All version tagging, regardless of the branch, should be of the form 
**\[MAJOR\].\[MINOR\].\[PATCH\]**. For example, Community MS3 Firmware release 1.0.0 on 
the **features** branch would be tagged **features-1.0.0**.
