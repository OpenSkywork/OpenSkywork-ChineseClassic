# OpenSkywork-ChineseClassic Database

## Overview

`OpenSkywork-ChineseClassic Database` is an open-sourced database of traditional Chinese painting created by `SkyWorks` research team.

This Database contains traditional chinese paintings with attribute labels, with 10166 images and 510 authors in total.

The labels are stored in `label.csv`, where images and labels are orgnized as rows and columns, respectively.

The labels for each images contains `id`, `author`, `dynasty `, `genre`, and `filename`:

| Field    | Meaning                                                      |
| -------- | ------------------------------------------------------------ |
| id       | unique identifier for each painting                          |
| author   | the creator of the original painting                         |
| dynasty  | the dynasty of the author, one of these:`唐`, `宋`，`元`, `明`, `清` |
| genre    | the genre of the painting, one of these: `山水`, `花鸟`, `人物`, `其他` |
| filename | the painting filename saving in the folder `images`          |

## Annotation Process

1. Crawl or manually download Paintings and their related information from the internet.
2. Remove broken images and images with limited information.
3. Manually annotate images according to their related information.

## LICENCE

This project is licensed under the terms of the MIT license.

## CITATION

`
OpenSkywork. OpenSkywork-ChineseClassic Database [Online], available: https://github.com/OpenSkywork/ChineseClassic, 2020
`

