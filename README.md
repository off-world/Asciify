# Asciify

[![PowerShell Gallery](https://img.shields.io/powershellgallery/v/Asciify.svg)](https://www.powershellgallery.com/packages/Asciify)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/cc2d46b1198e4484909af81fe17b3283)](https://www.codacy.com/app/off-world/Asciify?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=off-world/Asciify&amp;utm_campaign=Badge_Grade)

Convert Images to ASCII Pictures

![preview](https://i.imgur.com/hVBnXGo.png)

## Description

Convert any image to ASCII picture by representing each pixels grayscale value as an ASCII character. The higher the grayscale value resp. the lighter the pixel the more space the corresponding ASCII character fills on the screen therefore reassembling the image well on dark console backgrounds with light font colors. On light console backgrounds with dark font colors use the `-Invert` switch to adjust. Before being processed the image will be resized in memory to make the resulting ASCII picture fit the consoles width later on. To fit the consoles height instead use the `-FitConsoleHeight` switch.

## Installation

Install from [PowerShell Gallery](https://www.powershellgallery.com/packages/Asciify)

```Powershell
Install-Module -Name Asciify
```

## Usage

```Powershell
Import-Module Asciify

Convert-ImageToAscii .\bobby-fischer.jpg
```

## Examples

```Powershell
Get-Help Convert-ImageToAscii -Examples
```
