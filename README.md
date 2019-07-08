## Paper Survey

機械学習 (特にDeep Learning) に関する先行研究および関連研究をまとめています。（個人用）
shunk031さんのクローンを使用（https://github.com/shunk031/paper-survey/）

---

<!-- ## Contents

- [Paper Summary of Computer Vision](https://shunk031.github.io/paper-survey/category/cv/)
- [Paper Summary of Natural Language Processing](https://shunk031.github.io/paper-survey/category/nlp/)
- [Paper Summary of Others](https://shunk031.github.io/paper-survey/category/others/)
 -->
---

## Rules

* 読もうと思っている論文は[Issue](https://github.com/ryosuke071111/paper-survey/issues)に上げる
<!-- * [ProjectsのRelated Works](https://github.com/shunk031/paper-survey/projects/2)に論文を読んだかどうかを管理する -->
* [format.md](https://github.com/ryosuke071111/paper-survey/blob/master/format.md)にしたがって論文の要旨をまとめる

## Abount Summary Format

- [高速で論文がバリバリ読める落合先生のフォーマットがいい感じだったのでメモ](http://lafrenze.hatenablog.com/entry/2015/08/04/120205)

```
---
layout: post
title:  "論文タイトル"
date:   YYYY-MM-DD
categories: CV NLP Others
---

## 1. どんなもの？

## 2. 先行研究と比べてどこがすごいの？

## 3. 技術や手法の"キモ"はどこにある？

![Figure 1]({{ site.baseurl }}/assets/img/(cv, nlp, others)/(title)/figure1.png)

## 4. どうやって有効だと検証した？

## 5. 議論はあるか？

## 6. 次に読むべき論文はあるか？

### 論文情報・リンク

* [著者，"タイトル，" ジャーナル名，voluem，no.，ページ，年](論文リンク)
```

## Example

- [先端技術とメディア表現1 #FTMA15](http://www.slideshare.net/Ochyai/1-ftma15) from [Yoichi Ochiai](http://www.slideshare.net/Ochyai)

![](https://raw.githubusercontent.com/shunk031/paper-survey/master/assets/img/FTMA15-1-page-65.png)

## Build

- Use rbenv and ruby-build for build this repo locally

``` shell
$ rbenv install 2.4.0
$ mkdir ~/.rbenv/versions/paper-survey-dev
$ ruby-build 2.4.0 ~/.rbenv/versions/paper-survey-dev
$ cd paper-survey
$ rbenv local paper-survey-dev
$ gem install bundle
$ bundle install
$ jekyll server
# then visit http://127.0.0.1:4000/paper-survey/ in your browser to preview the repo
```
