# Headings


Markdown : 

    # Heading Level 1

> ## Output 
> # Heading Level 1

Markdown : 

    ## Heading Level 2

> ## Output 
> ## Heading Level 2

Markdown :

    ### Heading Level 3

> ## Output 
> ### Heading Level 3

Markdown :

    #### Heading Level 4

> ## Output 
> #### Heading Level 4

Markdown : 

    ##### Heading Level 5

> ## Output 
> ##### Heading Level 5

Markdown : 

    ###### Heading Level 6

> ## Output 
> ###### Heading Level 6

---

- #의 개수가 늘어날수록 글씨의 크기가 작아진다.

- ex) Heading Level 3는 3개의 #이 필요하다.

- (#뒤에 공백을 추가해야함)

##Alternate Syntax
또는 이렇게도 쓸 수 있다.

Markdown :  

    Heading Level 1  
    ===============

> ## Output 
> Heading Level 1
> ===============

Markdown :  

    Heading Level 2  
    ---------------   


> ## Output   
> Heading Level 2
> ---------------

---

- (=과-의 개수는 상관없음)

# Paragraphs

- 단락을 구분하려면 엔터를 두 번 쳐야한다.

---

Markdown : 

    I really like using Markdown.

    I think I'll use it to format all of my documents from now on.

> ## Output 

> I really like using Markdown.

> I think I'll use it to format all of my documents from now on.

# Line Breaks

Markdown :

    This is the first line.  
    And this is the second line.

> ## Output 
> This is the first line.  
And this is the second line.

---

- 개행을 하기 위해서는 스페이스를 두 번 입력해야 한다.

# Emphasis

## Bold

- 글자를 굵게 하려면 글자 앞 뒤로 ** 또는 __를 넣으면 된다.

---

Markdown :

    I just love **bold text**.

> ## Output 
> I just love **bold text**

Markdown :

     I just love __bold text__.

> ## Output 
> I just love __bold text__.

Markdown : 

    Love**is**bold

> ## Output 
> Love**is**bold

---

## Italic

- 글자를 기울임 꼴로 쓰려면 글자 앞 뒤로 * 또는 _를 넣으면 된다.

---

Markdown : 

    Italicized text is the *cat's meow*.

> ## Output 
> Italicized text is the *cat's meow*.

Markdown :

     Italicized text is the _cat's meow_.

> ## Output 
> Italicized text is the _cat's meow_.

Markdown :

     A*cat*meow

> ## Output 
> A*cat*meow

---

## Bold and Italic

- 글자를 굵고 기울임 꼴로 쓰려면 글자 앞 뒤로 *** 또는 ___ 또는 \*\*_ _\*\* 또는 __* *__를 넣으면 된다.

---

Markdown :

     This text is ***really important***.

> ## Output
> This text is ***really important***.

Markdown :

    This text is ___really important___.

> ## Output 
> This text is ___really important___.

Markdown : 

    This text is __*really important*__.

> ## Output 
> This text is __*really important*__.

Markdown : 

    This text is **_really important_**.

> ## Output 
> This text is **_really important_**.

Markdown: 

    This is really***very***important text.

> ## Output 
> This is really***very***important text.

---

# Blockquotes

- 블록을 만들기 위해서는 >를 사용한다.

---

Markdown : 
    
    > Dorothy followed her through many of the beautiful rooms in her castle.

> ## Output
> Dorothy followed her through many of the beautiful rooms in her castle.

## Blockquotes with Multiple Paragraphs

- 빈 라인에 >을 추가해서 다수의 문장을 블록으로 연결할 수 있다.

Markdown:

    > Dorothy followed her through many of the beautiful rooms in her castle.

    >

    > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

> ## Ouput
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## Nested Blockquotes

- 블록 속의 블록도 가능하다.

Markdown :

    > Dorothy followed her through many of the beautiful rooms in her castle.

    >

    >> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

> ## Output
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## Blockquotes with Other Elements

- 블록 안에 다른 요소를 넣는 것도 가능하다.

Markdown : 

    > #### The quarterly results look great!

    >

    > - Revenue was off the chart.

    > - Profits were higher than ever.

    >

    >  *Everything* is going according to **plan**.

> ## Output
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

# Lists

## Ordered Lists

- 순서가 있는 리스트는 1. 2. 3. 을 사용한다.
- 숫자 순서가 섞여있어도 자동으로 바뀐다. 

Markdown: 

    1. First item
    2. Second item
    3. Third item
    4. Fourth item

> ## Output
> 1. First item
> 2. Second item
> 3. Third item
> 4. Fourth item

Markdown:

    1. First item
    1. Second item
    1. Third item
    1. Fourth item

> ## Output
> 1. First item
> 1. Second item
> 1. Third item
> 1. Fourth item    

Markdown :

    1. First item
    8. Second item
    3. Third item
    5. Fourth item

> ## Output
> 1. First item
> 8. Second item
> 3. Third item
> 5. Fourth item    

Markdown :

    1. First item
    2. Second item
    3. Third item
        1. Indented item
        2. Indented item
    4. Fourth item

> ## Output
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

## Unordered Lists

- 순서가 없는 리스트는 -, *, +를 사용한다.
- 이 세개를 섞어서 쓰면 안되고 하나만 일관되게 사용해야 한다.


Markdown :

    - First item
    - Second item
    - Third item
    - Fourth item

> ## Output
> - First item
> - Second item
> - Third item
> - Fourth item

Markdown :

    * First item
    * Second item
    * Third item
    * Fourth item

> ## Output
> * First item
> * Second item
> * Third item
> * Fourth item

Markdown :

    + First item
    + Second item
    + Third item
    + Fourth item

> ## Output
> + First item
> + Second item
> + Third item
> + Fourth item

Markdown :

    - First item
    - Second item
    - Third item
        - Indented item
        - Indented item
    - Fourth item

> ## Output
 - First item
 - Second item
 - Third item
    - Indented item
    - Indented item
 - Fourth item

## Adding Elements in Lists

- 리스트 안에 다른 요소를 추가할 수 있다.

## Paragraphs

Markdown :

    *   This is the first list item.
    *   Here's the second list item.

        I need to add another paragraph below the second list item.

    *   And here's the third list item.

> ## Output
*   This is the first list item.
*   Here's the second list item.

    I need to add another paragraph below the second list item.

*   And here's the third list item.

## Blockquotes

Markdown :

    *   This is the first list item.
    *   Here's the second list item.

        > A blockquote would look great below the second list item.

    *   And here's the third list item.

> ## Output
*   This is the first list item.
*   Here's the second list item.

    > A blockquote would look great below the second list item.

*   And here's the third list item.

---

- 탭 한 번 또는 스페이스 4번 입력으로 Paragraphs와 Blockquotes를 만들 수 있다.

---

## Code Blocks

- 탭 한 번 또는 스페이스 4번 입력으로 코드 블록을 만든다. 리스트 안에서는 탭 2번 또는 스페이스 8번 입력으로 만든다.

Markdown: 

    1.  Open the file.
    2.  Find the following code block on line 21:

            <html>
              <head>
                <title>Test</title>
              </head>

    3.  Update the title to match the name of your website.

> ## Output
1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.

## Images

Markdown :

    1.  Open the file containing the Linux mascot.
    2.  Marvel at its beauty.

        ![Tux, the Linux mascot](/assets/images/tux.png)

    3.  Close the file.

- 이미지 파일 위치는 사용자에 따라 다르다.
> ## Output
1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3.  Close the file.

## Lists

Markdown : 

    1. First item
    2. Second item
    3. Third item
        - Indented item
        - Indented item
    4. Fourth item

> ## Output
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item

# Code

Markdown :

    At the command prompt, type `nano`.

> ## Output
> At the command prompt, type `nano`.

## Escaping Backticks

- 구문 또는 단어에 하나 이상의 백틱이 있다면 이중 백틱(``)을 이용해 이스케이프 할 수 있다.

Markdown :

    ``Use `code` in your Markdown file.``

> ## Output
> ``Use `code` in your Markdown file.``

## Code Blocks

- 탭 한 번 또는 스페이스 4번 입력으로 코드 블록을 만들 수 있다.

Markdown : 

    <html>
      <head>
      </head>
    </html>

> ## Output

    <html>
      <head>
      </head>
    </html>

# Horizontal Rules

- 수평선을 만드려면 ***, ---, ___를 사용한다.

Markdown :

    ***

    ---

    _________________

> ## Output

> ***

> ---

> _________________

# Links

- 링크는 []안에 사이트 이름을 적고 ()안에 사이트 주소를 적으면 된다.

Markdown :

    My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

> ## Output
> My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

## Adding Titles

- 제목을 추가하려면 링크 뒤에서 ""를 사용한다.

Markdown :

    My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

> ## Output
> My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

## URLs and Email Addresses

Markdown :

    <https://www.markdownguide.org>
    <fake@example.com>

> ## Output
> <https://www.markdownguide.org>  
> <fake@example.com>

## Formatting Links

Markdown :

    I love supporting the **[EFF](https://eff.org)**.
    This is the *[Markdown Guide](https://www.markdownguide.org)*.
    See the section on [`code`](#code).

> ## Output
> I love supporting the **[EFF](https://eff.org)**.  
> This is the *[Markdown Guide](https://www.markdownguide.org)*.  
> See the section on [`code`](#code).

## Reference-style Links

- 참조형 링크는 예를 들어 [hobbit-hole][1], [hobbit-hole] [1] 이런 식으로 적은 후 이 단어의 바로 뒤나 문장의 끝에 주소를 적어 참조하는 방식이다. 

- 주소를 적는 방식은  
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)  
이렇게 여러가지가 있는데 이 중에서 어떤 형태로 적어도 상관 없다.


1. 첫번째 방법

    In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
    of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
    eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.

2. 두번째 방법

    In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
    of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
    eat: it was a [hobbit-hole][1], and that means comfort.

    [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

# Images

- 이미지를 사용하기 위해서는 !가 필수이고, 그 다음에 이미지에 덧붙이고 싶은 말, 이미지 경로, 이미지 제목 순으로 쓴다.

Markdown : 

    ![Philadelphia's Magic Gardens. This place was so cool!](/assets/images/philly-magic-gardens.jpg "Philadelphia's Magic Gardens")

> ## Output
> ![Philadelphia's Magic Gardens. This place was so cool!](/assets/images/philly-magic-gardens.jpg "Philadelphia's Magic Gardens")

## Linking Images

- 이미지에 링크를 붙이고 싶으면 제일 마지막에 링크하고 싶은 주소를 적는다.

Markdown :

    [![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

> ## Output
> [![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

# Escaping Characters

- 특수문자를 그대로 표현하기 위해 \를 사용한다.

Markdown :

    \* Without the backslash, this would be a bullet in an unordered list.

> ## Output
> \* Without the backslash, this would be a bullet in an unordered list.

## Characters You Can Escape

- 다음은 당신이 쓸 수 있는 Characters이다.

    \	: backslash  
    `	: backtick (see also escaping backticks in code)  
    \*	: asterisk  
    _	: underscore  
    { }	: curly braces  
    [ ]	: brackets  
    < >	: angle brackets  
    ( )	: parentheses  
    \#	: pound sign  
    \+	: plus sign  
    \-	: minus sign (hyphen)  
    .	: dot  
    !	: exclamation mark  
    |	: pipe (see also escaping pipe in tables)

# HTML

- Markdown에서는 HTML의 태그 사용이 허용된다.

Markdown :

    This **word** is bold. This <em>word</em> is italic.

> ## Output
> This **word** is bold. This <em>word</em> is italic.
A
