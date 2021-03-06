# Cleaver TW
A simple [cleaver](https://github.com/jdan/cleaver) template for internal presentations of TWers.

## About
This repo is only a helper for building presentations in TW with Markdown.
It contains a basic font-family setting and predefined brand colors ( TW colors )

## Requirements
  * [npm](https://github.com/npm/npm)
  * [cleaver](https://github.com/jdan/cleaver) ( `npm install -g cleaver` )

## Colors

All colors definitions are available bellow:
  - Orange
  - Purple
  - Green
  - Magenta
  - Blue
  - Lime
  - Pink
  - Brown
  - Red

#### The default color is __Purple__

## Usage
Only append the theme entry in your cleaver Markdown file.
  ```
    theme: vtrbtf/cleaver-tw
  ```

### Colors settings
  To choose a color for a specific slide, just append the color name ( lowercase ) on the slide separator ( -- )

```
-- blue

# This is my blue slide

-- red

# This is my purple slide

```

___

## Example

#### Markdown

```
title: Performance Review
author:
  name: Vitor Barbosa
  email: vbarbosa@thoughtworks.com  
controls: false
theme: vtrbtf/cleaver-tw

-- purple
# ThoughtWorks

-- blue
# Slide#1

-- pink
# Slide#2

```

` $ cleaver markdown-file.md`

___

#### Sample

![sample.gif](sample.gif "Sample")
