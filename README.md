# Card Sort

Card Sort is a **free** and open-source tool for conducting a virtual card sorting. It was built as a way to **quickly conduct a card sorting online**, without the need to sign up or subscribe to commercial solutions or self-host an open-source project.

It works best when combined with other tooling. For example you could create a form with instructions, questionnaire and a link to the card sorting. You could also ask the participants to copy the results back into the form.


## This fork

This is a fork of [the original Card Sort](https://github.com/indigane/cardsort). The fork, [awaiting pull request to be accepted](https://github.com/indigane/cardsort/pull/6), provides three new features:

- Allows adding local images with a relative or an absolute file path (original version only allows adding online images with an HTTP path, and embedded images with a data path).
- Enables users to edit the card content (then, the old content is shown as struck through) and to duplicate the cards.
- adds an export button to export refined data provided in the analysis tool to a CSV (copied to the clipboard)

-----

Analysis tools are in development. If you're interested, you can take a look at the [current progress](https://indigane.github.io/cardsort/analysis.html) and discuss [in the issues page](https://github.com/indigane/cardsort/issues/2).

## Demo (not the demo of the fork, but the original version)

[https://indigane.github.io/cardsort/card-sort.html#eJw9kcFOwzAMhl...zI6t8U=](https://indigane.github.io/cardsort/card-sort.html#eJw9kcFOwzAMhl8FlesuXHdBUGAHNq1ikxBCHNzgtdaSOHITpgnx7iTOOlXK_9lyftvpb3PbLD-bhxAsNousQoZjIYlkRj5qdgogMKSp8A8b-OZMj-DzVwDBq2BUsfamwxBQSmTBHHsUOWuQ8MrCxrCljC30PQyo5CNYTqEGAq5nC5VFx2ohWTpYPql7ixbVrR0vti0b9kkrWcpUrYCfe7bJJNfrzSeIpcfzMASbm2Z8oSGfKxBLpgDzdB12JRDwIIniHGR9pRPNuTXiUcWxV40xmVK0JldkA34ob7ZJ0yjMLuPWk9Zu84C6fAcBzqAgk6dQCMGMVaVKOckjXP5XZ1Px6tjhkH3qUh1HiKVbl1w4UmnyBt80jQpTmLfaBfLVfxcFTnN6z65e3yepY7xnX3Fodd4PcM3Xorlvlnd__zI6t8U=)

## Create your own (with the original version)

https://indigane.github.io/cardsort/

## Read about card sorting

https://en.wikipedia.org/wiki/Card_sorting

-----

## Advanced use

### Images

Images can be added to the cards by typing `image:` and a link to the image.

```
image:https://domain.tld/image.jpg
```

Text can also be included before or after an image.

```
image:https://domain.tld/cat.jpg A photo of a cat
```

### Programmatic use

Query parameters can be passed to the card sorting page instead of going through the creation form.

All parameters are optional.

```url
https://indigane.github.io/cardsort/card-sort.html?cards=a,b,c&categories=1,2,3&allowCategoryEditing=0&isRandomized=1
```
