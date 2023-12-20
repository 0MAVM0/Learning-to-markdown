# Learning-to-markdown
# Headers (Заголовки)
# Header 1 (#)
## Header 2 (##)
### Header 3 (###)
#### Header 4 (####)
___
# Text styles (Стили текста)
**bold** (** **)

*italic* (* *)

***text*** (*** ***)

_italic2_ (_ _)

__bold2__ (__ __)

___text2___ (___ ___)

~~Crossed~~ (~~~~)

***~~All In One~~***
___
* text (*)
  * text 2 (..*)
    * text 3 (....*)
- text (-)
  - text 2 (..-)
    - text 3 (....-)
+ text (+)
  + text 2 (..+)
    + text 3 (....+)
___
1. text (1. )
    1. text 2 (....1. )
        1. text 3 (........1. )
2. text (2. )
___
# Tasks (Задания)
* [ ] text (*/-/+/1... [ ] txt)
* [x] text (*/-/+/1... [x] txt)
# Emojis (Эмоции) & Links (Ссылки)
https://github.com/GnuriaN/format-README/blob/master/emoji.md

[**LINK** To Emojis](https://github.com/GnuriaN/format-README/blob/master/emoji.md)
```txt
[text](url)
```

# Quotes (Цытаты)
> 1 lvl (> )
>> 2 lvl (>> )
>>> 3 lvl (>>> )
>>>> 4 lvl (>>>> )
___
# Code (Код)
A text string containing `code` inside (``)

Текстовая строка внутри которой расположен `код`  (``)

```python
def plus(*args: int) -> int:
    result = 0
    for item in args:
        result += item
    return result
```

```txt
(
    ```...
    ...
    ```
)
```
___
# Images (Картинки)
![Image](f5e1ef3f-464b-4d.png)
```txt
![name](image)
```
___
## Pop-up text on the image (Всплывающий текст на картинке)
![Image2](82867d7c-952d-49.png "Pop-up text on the image")
```txt
![name](image, 'text')
```
## Gif
![Gif](https://raw.githubusercontent.com/gist/theAdityaNVS/f5b585d1082da2dffffea32434f37956/raw/7f9552d0a179b4f84059259fa878199e369b069c/GitHub-logo.gif)
```txt
![NameOfGif](Gif)
```
## Video
[![Video](9d8e28ae-0ebd-44.png)](https://www.youtube.com/watch?v=NXNf9aYTCZ0)
```txt
[![name](image)](video)
```
___
# Tables (Таблицы)
| LEFT | CENTER | RIGHT |
|:----------|:-----:|----------:|
| left text | Center text | Right text |

```txt
  | LEFT | CENTER | RIGHT |
  |:----------|:-----:|----------:|
  | left text | Center text | Right text |
```
