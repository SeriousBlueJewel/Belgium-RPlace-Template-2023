# Colaborator Instructions and thing to know

READ THIS : https://docs.google.com/document/d/12WTiDcRo4P35zJvlgWX06MKVbitbDo3ehnF7mysFv4Y/edit?rm=minimal&pli=1



1. [How it work](#1-how-it-work)
    1. [Files](#11-files)
    2. [The template file](#12-the-template-file)
        1. [The template](#121-the-template)
        2. [The coordinate](#122-the-coordinate)
<!-- 2. [thing to know](#thing to know)
    1. [Size of the image](#size-of-the-images)
    2. [Color use in R/Place](#color-use-in-rplace)
3. [Good practice(maybe)]() -->

# 1. How it work
This template use the template mangfer script made by osuplace, you can found it [here](https://github.com/osuplace/templateManager)
## 1.1 Files
Here is the file hierarchy and its use.
```
├───Belgium RPlace Template 2023.json -> The template file
├───Colablorator Instructions.md
├───README.md
└───Images -> In these folder we stor all the images
    ├───2023 -> In these folder we store all the images related to the R/Place 2023
    └───Readme -> in these folder we store all the images related to the Readme.md file
```
## 1.2 The template file
The Template file contain all the art and there location and it look like this : 
```json
{
    "faction": "/r/belgium",
    "contact": "https://discord.gg/Belgium",
    "templates": [
        {
            "name": "King Philippe | Made by : beerstalker",
            "sources": [
                "https://github.com/AlphaGaming7780/Belgium-RPlace-Template-2023/blob/main/Images/2023/fp.png?raw=true"
            ],
            "x": 133,
            "y": 372
        },
        {
            "name": "The Belgian flag | Made by : triton_supreme (ᚖ 𝔸𝕝𝕡𝕙𝕒 𝔾𝕒𝕞𝕚𝕟𝕘 ᚖ)",
            "sources": [
                "https://github.com/AlphaGaming7780/Belgium-RPlace-Template-2023/blob/main/Images/2023/FLAG.png?raw=true"
            ],
            "x": 132,
            "y": 133
        }
    ]
}
```
### 1.2.1 The template
The template is define like this : 
```json
        {
            "name": "King Philippe | Made by : beerstalker",
            "sources": [
                "https://github.com/AlphaGaming7780/Belgium-RPlace-Template-2023/blob/main/Images/2023/fp.png?raw=true"
            ],
            "x": 133,
            "y": 372
        },
```
* name : Is the name of the art can be anyhting
* sources : Is the link to the image to use as a template
* x : The X position on the R/Place (refer to the [coordinate](#122-the-coordinate) section).
* y : The Y position on the R/Place (refer to the [coordinate](#122-the-coordinate) section).

### 1.2.2 The coordinate
The coordinate is really important
The top left corner of the R/Place is the origine of the "world" the 0;0
and the origine of the image is also the top left corner.
But the top left corner is -1000;-500 in the R/Place so you nedd to make a calcule to know the right location.