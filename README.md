# OpenSkywork-ChineseClassic Database

## Overview

This Database contains traditional chinese paintings with attribute labels, with 10166 images and authors in total.

The labels are stored in `label.csv`, where images and labels are orgnized as rows and columns, respectively.

The labels for each images contains `id`, `author`, `dynasty `, `genre`, and `filename`:

| field    | Meaning                                                      |
| -------- | ------------------------------------------------------------ |
| id       | unique identifier for each painting                          |
| author   | the creator of the original painting                         |
| dynasty  | the dynasty of the author, including `唐`, `宋`，`元`, `明`, `清` |
| genre    | the of the painting, including `山水`, `花鸟`, `人物`, `其他` |
| filename | the painting filename saving in the folder `images`          |

## Annotation Process

1. Paintings are scrowed or mannual downloaded from the Internet, together with its related information such as author, dynasty and genre.
2. Remove broken images and images with limited infomation.
3. Mannualy annotate images by related information.

## LICENCE

This project is licensed under the terms of the MIT license.

## CITATION

`
OpenSkywork. OpenSkywork-ChinesePainting Database [Online], available: https://github.com/OpenSkywork/OpenSkywork-CCD, 2020
`

