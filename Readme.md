# PowerFIGlet

FIGlet for PowerShell

## Description

FIGlet for PowerShell

## Introduction

## Requirements

## Installation

Powershell Gallery (PS 5.0, Preferred method)
`install-module PowerFIGlet`

Manual Installation
`iex (New-Object Net.WebClient).DownloadString("https://github.com/MischaBoender/PowerFIGlet/raw/master/Install.ps1")`

Or clone this repository to your local machine, extract, go to the .\releases\PowerFIGlet directory
and import the module to your session to test, but not install this module.

## Features

## Versions

0.0.1 - Initial Release

## Contribute

Please feel free to contribute by opening new issues or providing pull requests.
For the best development experience, open this project as a folder in Visual
Studio Code and ensure that the PowerShell extension is installed.

* [Visual Studio Code]
* [PowerShell Extension]

This module is tested with the PowerShell testing framework Pester. To run all
tests, just start the included test script `.\Build.ps1 -test` or invoke Pester
directly with the `Invoke-Pester` cmdlet in the tests directory. The tests will automatically download
the latest meta test from the claudiospizzi/PowerShellModuleBase repository.

## Other Information

**Author:** Mischa Boender

**Website:** https://github.com/MischaBoender/PowerFIGlet
