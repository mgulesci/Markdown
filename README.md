![markdown](assets/markdown.png)

# Markdown
[![user][user_img]][user_url] ![markdown][markdown_img]

[user_img]:https://img.shields.io/badge/made%20by-mehmetcangulesci-1a1e21.svg

[user_url]:https://github.com/mehmetcangulesci

[markdown_img]:https://img.shields.io/badge/made%20with-Markdown-8b54ea.svg

In this tutorial, I will try to cover `Markdown` usage instructions.

## Heading
As the number of marks increases, the font size decreases. Max value of `#` is six.

Input:
```
# Heading
## Heading
### Heading
#### Heading
##### Heading
###### Heading
```

Output:  
># Heading
>## Heading
>### Heading
>#### Heading
>##### Heading
>###### Heading

## Link
Input: 
```
[Link](https://google.com)
```
Output: &nbsp; [Link](https://google.com)

## Inline Code
Input:
```
`code`
```
Output: &nbsp; `code`

## BlockCode
Input:
```
```Java
int a = 6;
int b = 4;
int result = a + b;

System.out.println("Result: " + result);```
```

Output:  
```Java
int a = 6;
int b = 4;
int result = a + b;

System.out.println("Result: " + result);
```

## List Items
Input:  
```
1. item  
* item
- item
+ item
```

Output:
1. item  
* item
- item
+ item

## Blackquote
Input:  
`> item`

Output:  
> item

## Table
Input:
```
| Heading 1| Heading 2 | Heading 3 |
| --- | --- | --- |
| test| test| test|
```
Output:
| Heading 1| Heading 2 | Heading 3 |
| --- | --- | --- |
| test| test| test|

---

Input:
```
• Right alignment → | ---: | ---: | ---: |
• Left alignment → | :--- | :--- | :--- |
• Centered → |:---:|:---:|:---:|
```
Output:
| Heading 1 | Heading 2 | Heading 3 |
| :- | -: | :-: |
| Left column | Center column | Right column|
| Left alignment | Right alignment | Centered|
| 100 | 100 | 100 |
| 10.000 | 10.000 | 10.000|
| 1.000.000 | 1.000.000 | 1.000.000 |

## Image
Input:  
```
[![image_name][image_url]][link_url]

[image_url]: assets/coffee.png

[link_url]: https://mehmetcangulesci.com
```
Output:  
[![image_name][image_url]][link_url]

[image_url]: assets/coffee.png

[link_url]: https://mehmetcangulesci.com


## Additions

`**bold1**`  &nbsp; &nbsp;  **bold1**  
`__bold2__`  &nbsp; &nbsp;  **bold2**  
`*italic1*`  &nbsp; &nbsp;  *italic1*  
`_italic2_`  &nbsp; &nbsp;  _italic2_  
`***bolditalic1***`  &nbsp; &nbsp;  ***bolditalic1***  
`___bolditalic2___`  &nbsp; &nbsp;  ___bolditalic2___  
`~~line~~`  &nbsp; &nbsp;  ~~line~~

## Others
* To leave space between words, use `&nbsp;`.
* To jump new line, press `enter` key.
* To leave more space between lines, use `<br>`.