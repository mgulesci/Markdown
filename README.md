  # Markdown

  Merhabalar bu yazımızda Markdown'dan biraz söz edeceğiz. Markdown, yazdığımız kodu otomatik olarak HTML' e çeviren bir yazılımdır. Normalde HTML kullanarak herhangi bir içerik yazdığımızda ve üzerinde hızlı düzenlemeler yapmamız gerektiğinde biraz zorlanırız. Bu durumda `Markdown` devreye girmektedir. Düzenlemeleri hızlı bir şekilde yapıp websiteleri için görsel açıdan düzenli ve etkili yazılar yazmamızı mümkün kılar. Şimdi Markdown'un bazı özelliklerine değineceğiz.

  ### Heading
  1 yıldızdan `#` 6 yıldıza `######`kadar İşaretlemek mümkündür. İşaret sayısı arttıkça font büyüklüğü azalmaktadır.

  Input:
  ```
  # Heading
  ## Heading
  ### Heading
  #### Heading
  ```

  Output:  
  ># Heading
  >## Heading
  >### Heading
  >#### Heading



  ### General Informations

  `**bold1**`  &nbsp; &nbsp;  **bold1**  
  `__bold2__`  &nbsp; &nbsp;  **bold2**  
  `*italic1*`  &nbsp; &nbsp;  *italic1*  
  `_italic2_`  &nbsp; &nbsp;  _italic2_  
  `***bolditalic1***`  &nbsp; &nbsp;  ***bolditalic1***  
  `___bolditalic2___`  &nbsp; &nbsp;  ___bolditalic2___  
  `~~line~~`  &nbsp; &nbsp;  ~~line~~

  ---

  ### Link
  Input: 
  ```
  [Link](http://)
  ```
  Output: &nbsp; [Link](http://)

  ---

  ### Inline Code
  Input:
  ```
  `code`
  ```
  Output: &nbsp; `code`

  ---

  ### Code
  Input:
  ```
  ```Java
  int a = 6;
  int b = 4;
  int result = a + b;

  System.out.println("Result: " + result);
  ``````

  Output:  
  ```Java
  int a = 6;
  int b = 4;
  int result = a + b;

  System.out.println("Result: " + result);
  ```

  ---

  ### List Items
  Input:  
  ```
  1. item  
  * item
  - item
  + item
  ```

  Output:
  * item
  1. item  
  - item
  + item

  ---

  ### Blackquote
  Input:  
  `> item`

  Output:  
  >item

  ---

  ### Table
  ```
  | Heading 1| Heading 2 | Heading 3 |
  | --- | --- | --- |
  | test| test| test|
  ```
  | Heading 1| Heading 2 | Heading 3 |
  | --- | --- | --- |
  | test| test| test|

  ```
  • Right alignment → | ---: | ---: | ---: |
  • Left alignment → | :--- | :--- | :--- |
  • Centered → |:---:|:---:|:---:|
  ```

  | Heading 1 | Heading 2 | Heading 3 |
  | :- | -: | :-: |
  | Left column | Center column | Right column|
  | Left alignment | Right alignment | Centered|
  | 100 | 100 | 100 |
  | 10.000 | 10.000 | 10.000|
  | 1.000.000 | 1.000.000 | 1.000.000 |

  ---

  ### Image
  Input:  
  ```
  [![image_name][image_url]][link_url]

  [image_url]:https://mehmetcangulesci.com/wp-content/uploads/2017/04/micon-e1491410654235.png

  [link_url]: https://mehmetcangulesci.com
  ```
  Output:  
  [![image_name][image_url]][link_url]

  [image_url]:https://mehmetcangulesci.com/wp-content/uploads/2017/03/micon.png

  [link_url]: https://mehmetcangulesci.com

  ---

  ### Others
  * Bir alt satıra geçmek için , satır sonunda 2 `SPACE` bırakılmalıdır.
  * Satırda boşluk bırakmak için kelimelerin arasına `&nbsp;` koyabiliriz.
  * 1 `ENTER` ile satırlar arasında boşluk bırakılır.
  * Satırlar arasında çoklu boşluk bırakmak için `<br>` konulabilir.
  
  ---
  
## Contact me
Follow me on [![alt text][1.1]][1]
[![alt text][2.1]][2]
[![alt text][3.1]][3]
[![alt text][4.1]][4]
[![alt text][5.1]][5]


[1.1]:https://mehmetcangulesci.com/wp-content/uploads/2017/03/Twitter.png (twitter icon with padding)
[2.1]: https://mehmetcangulesci.com/wp-content/uploads/2017/03/Linkedin.png (linkedin icon with padding)
[3.1]: https://mehmetcangulesci.com/wp-content/uploads/2017/03/Github.png (github icon with padding)
[4.1]: https://mehmetcangulesci.com/wp-content/uploads/2017/03/Instagram.png (instagram icon with padding)
[5.1]:https://mehmetcangulesci.com/wp-content/uploads/2017/03/micon.png


<!-- links to your social media accounts -->

[1]: https://twitter.com/mehmetgulesci
[2]: https://www.linkedin.com/in/mehmetcan-g%C3%BCle%C5%9F%C3%A7i-39155458/
[3]: https://github.com/mgulesci
[4]: https://www.instagram.com/mgulesci/
[5]: https://mehmetcangulesci.com
