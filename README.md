# Dongmunseon translation 

## What is it?

This repository contains 4897 works from the [Dongmunseon (東文選)](https://en.namu.wiki/w/%EB%8F%99%EB%AC%B8%EC%84%A0), which is “a collection of historical poetry in Korea created during the Joseon Dynasty”. The compilation of the Dongmunseon was completed in 1478 and it contains works from the late Unified Silla period (9th century) all the way up to the compilation of the Dongmunseon itself (late 15th century).

In this repository, each work in the collection has four versions:

1. Canonical: completely unformatted Classical Chinese text of the work, typically one continuous line without punctuation.
2. Formatted: the Classical Chinese text with added punctuation and line breaks.
3. Korean: a translation of the Classical Chinese text in modern Korean by the [Institute for the Translation of Korean Classics](https://db.itkc.or.kr/dir/item?itemId=BT#dir/node?grpId=&itemId=BT&gubun=book&depth=2&cate1=Z&cate2=&dataGubun=%EC%84%9C%EC%A7%80&dataId=ITKC_BT_1365A), including scholarly footnotes for many of the works.
4. English: a translation of the original text into English. 

> [!WARNING]
> English translations are done by AI (specifically claude-haiku-4-5-20251001). While every effort was taken to provide the AI with as much context as possible, the usual limitations apply. The translations are done simply on a “better-than-nothing” basis, and should be assumed to have zero scholarly value. 

## Why AI?

The vast majority of the Dongmunseon has never been translated into English. AI translations, while imperfect, allow us to get a glimpse into the work. As the Dongmunseon’s preface has it: 

> Though our selection lacks refinement and we may not fully grasp the authors' intentions, we humbly embrace the love of antiquity and cherish the work of transmission.

I will gladly replace all of the files in this repository with real translations if and when they are available in the public domain. If you can read Classical Chinese and/or Korean and would like to contribute a translation, please submit a pull request. 

## How is the collection structured?

The file-tree mimics the structure on the [Institute for the Translation of Korean Classics](https://db.itkc.or.kr/dir/item?itemId=BT#dir/node?grpId=&itemId=BT&gubun=book&depth=2&cate1=Z&cate2=&dataGubun=%EC%84%9C%EC%A7%80&dataId=ITKC_BT_1365A).

## How are the files structured?

Each file is a `.poem` file, which is a custom YAML schema created to store poetry in a systematic way. The schema is fully open source and formally defined [here](https://github.com/bbkingisking/poem-schema). For an application that natively parses `.poem` files, check out [leaves](https://github.com/bbkingisking/leaves).

## Something is wrong in one of the files!

Tell me what it is and I will fix it. The repository is put together with a combination of janky web scraping and manual editing, I fully expect some things to have gone wrong.

## Is the 속동문선 included?

Yes.

## Can I reuse the materials here?

Most works are marked as copyrighted by [Institute for the Translation of Korean Classics](https://db.itkc.or.kr/dir/item?itemId=BT#dir/node?grpId=&itemId=BT&gubun=book&depth=2&cate1=Z&cate2=&dataGubun=%EC%84%9C%EC%A7%80&dataId=ITKC_BT_1365A). Why a government institution would copyright the cultural heritage of their country is idiocy beyond my understanding, but if you do intend to make copies of these thousand-year old poems, please ask the ITKC for permission to do so.
