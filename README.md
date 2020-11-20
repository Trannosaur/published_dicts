# Open sourced dictionaries

In the world of Vietnamese language dictionaries, there are few open source dictionaries. And you'll even find that the bulk of apps out there are just flagrantly stealing data... so I'm gonna try and kickstart some better data by processing Wiktionary into tab separated files people can use in their own apps.

# Vietnamese to Mandarin dictionary - vi2zhwikitxt.txt

## VN-ZH VIE-ZH VIE-CHN

This is a work in progress, entirely composed of data from the Mandarin language Wiktionary (zh.wiktionary.org) [Last copied: July 2020]

At the moment it is an entirely /raw/ rip (a lot of the wiki markup is still there), and abandons all the pronunciation templates.

I figure I'll put it up as I refine it because well, until now there wasn't a *single* open source vietnamese-mandarin (or even Mandarin-Vietnamese) dictionary source.

Also, be aware, it is missing an absolute butt tonne of words. Awkward.

## License
This data is redistributed under the same license as the origin, the Creative Commons Attribution-ShareAlike 3.0 Unported License (CC-BY-SA)

Any additions I've made I relicense under 4.0 as well... if I can?

### 一点翻译器的中文

这是一项正在进行的工作，完全由普通话维基词典(zh.wiktionary.org)的数据组成

目前，它完全是原始数据(很多wiki标记仍然存在)，并且抛出了所有的发音资料

我知道，太早上忘了，但是因为到目前为止，还没有的越南语对普通话 (甚至是普通话-越南语) 词典来源。

最后，请注意，它绝对遗漏了一大堆话。：）

#### 版权
署名—相同方式共享 3.0 协议国际版 (CC-BY-SA) (https://zh.wiktionary.org/wiki/Wiktionary:CC_BY-SA_3.0%E5%8D%94%E8%AD%B0%E6%96%87%E6%9C%AC) (https://creativecommons.org/licenses/by-sa/3.0/deed.zh)

# Vietnamese to English dictionary - vi2enwikitxt.txt
Pretty much the same as above, but generated from the English Wiktionary (en.wiktionary.org) [Last copied: July 2020]

Again, a reminder that this data is hella raw and honestly some work is needed - but hey maybe you'll get some use out of it in its current state -- honestly I've stripped out a bunch of fields I find uninteresting for a dictionary. I'll probably work on getting them back into the data at some point.

### Cố gắng giải thích bằng tiếng Việt
Đay là dữ liệu/cơ sở dữ liệu/CSDL từ điển Việt-Anh. Nguồn gốc kho từ này là hoàn toàn từ Wiktionary Tiếng Anh (en.wiktionary.org). Dữ liệu này rất là thô, vẫn còn có dấu hiệu 'template' của Wiktionary, mà bạn cũng xài được.

Ngoại ra cái này, cũng có FVDP (https://www.informatik.uni-leipzig.de/~duc/Dict/install.html) - mà có thể GPLv2 sẽ không hợp trường hợp của bạn.

#### Bản quyền
Dữ liệu này theo giấy phép Creative Commons Attribution-ShareAlike 3.0.

# Mandarin to Vietnamese Dictionary -- zhm2vi.tsv
Tab separated Mandarin to Vietnamese dictionary, processed from Panlex 2017. This 'dictionary' mixes modern Vietnamese definitions with Hán-Nôm definitions (for example if you look up 四 you'll get both bốn and tứ without any distinction between them), and has a separate entry for definition of the same Chinese Character sequence.

I'm releasing this under the Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) license. (https://creativecommons.org/licenses/by-sa/4.0/). 

## Tiếng Việt
File định dạng trường cách nhau bởi dấu Tab, nguồn gốc từ Panlex 2017. 'Từ điển' này trộn lộn xộn nghĩa hiện đại và hán nôm. Ví dù tra "四“ sẽ kiếm cả bốn và tứ mà không phân biệt gì hết. Mọi nghĩa của một cụm từ chữ Hán sẽ năm ở một hàng riêng.

Kho từ vựng này phát hành theo giấy phép Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) license. (https://creativecommons.org/licenses/by-sa/4.0/). 

## 中文
Tab分隔值文件 中（普通话）-越南语词典，依据Panlex 2017. 这个词典有很乱的词条，不分类越南词和罕见的汉越词 - 比如说：“四” 有 bốn （普通的词）和 tứ （汉越词，罕见，只在很正式的书面语复合词）

# Vietnamese to Korean dictionary - vi2kowikitxt.txt

## VN-KR VN-KO VIE-KO VIE-KR

This is the least refined of all the dicts as I know pretty much zero Korean! It's also the smallest of the dictionaries by far. [Last copied: 15th August 2020]

# English-Vietnamese Vietnamese-English word dictionary based on parallel Wikipedia articles - parallelcorpus-article-names-2020-vi-en_wiki.txt
## VN-EN VIE-EN EN-VN EN-VIE

This is just a list of all Wikipedia articles that have a parallel English and Vietnamese article. Useful for looking up more wonky, technical words. Saves you having to define things like 'electric circuit' in your own dictionary, and lets you focus on more colloquial stuff.

## Tiếng Việt
Kho từ của mọi trang Wikipedia mà có bản Tiếng Anh và Tiếng Việt.