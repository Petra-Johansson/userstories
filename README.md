# userstories

# US 001, JavaScript
```js
function jsblock(){
alert("This is a js-code block")
}
```
---

# US 010, Lists
*This is a ordered list*
```
1. It's numbered
2. From 1..
3. etc etc
```
*This is an unordered list*
```
- It's not
+ numbered
* but is still
- a list
```
---

# US 002, Java
```java
lass HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!"); 
    }
}
```
---

# US 003, Insert image
> For inserting an image through its link we can write the the link of the image in parentheses.
![JS logo](https://static.javatpoint.com/images/javascript/javascript_logo.png)
---

# US 004, JS
> For writing javascript code block in markdown we need to use three backtick and the writng the javascript name front of that without any space and write done the code and close and finish it with 3 backtick again. Here we have the example:
> ```javascript ..... ```
# US 005, Links

*The easiest way to create a link is simply by putting the url in <>:*
```
<https://github.com/Petra-Johansson/userstories>

```
*If you want to, you can also add a Title to your link:*
```
[Link to Repo](https://github.com/petra-johansson/userstories "This is the way you link to a specific webpage")

```

**You can also create reference links*
```
[Ref to repo-link][1]
[1]: <https://github.com/Petra-Johansson/userstories>

``` 
# US 003, Insert image
> For inserting an image that is in your repo.
---
![Alt text](https://github.com/Petra-Johansson/userstories/blob/main/kaffe.jpeg?raw=true "Optional Title")
---
---

# US 006, Tables
*To create a table we do like this: *
```
| Header       | Header        | Header        |
|:---          |:----------:   | ----------:   |
|Stuff aligned | Stuff aligned | Stuff aligned |
|to the left   | in center     | to the right  |
```
and this is the result:

| Header       | Header        | Header        |
| :----        | :--------:    | -----:        |
|Stuff aligned | Stuff aligned | Stuff aligned |
|to the left   | in the center | to the right  |
---

# US 007, Bold and Italic
For italic we can use underline or * in the beginig and the end of the text that we want to italic it.
We can write _like that_ or *that*
*italic text*

For bold we can use 2 underlines or * in the  beginig and the end of the text that we want to bold it.
We can write __like that_ or **that**
__bold text__
---

# US 008, Emoticon
For using emoticons can use : and then write the emoticon fron of that. :happy  :smiley
:smiley:
---
# 009, Horisontal Ruler
* * *

***

*****

- - -

---------------------------------------
# US 010

*This is a ordered list*
```
1. It's numbered
i2. From 1..
3. etc etc
```
*This is an unordered list*
```
- It's not
+ numbered
* but is still
- a list
```
___
# US 011, Blockqoutes
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
---
# US 012, Making a ER-diagram, using mermai
```mermaid
erDiagram
    CUSTOMER ||--o{ ORDER : places
    CUSTOMER {
        string name
        string custNumber
        string sector
    }
    ORDER ||--|{ LINE-ITEM : contains
    ORDER {
        int orderNumber
        string deliveryAddress
    }
    LINE-ITEM {
        string productCode
        int quantity
        float pricePerUnit
    }

```
---
# US 013, Class diagram using Mermaid
```mermaid
 classDiagram
      Animal <|-- Duck
      Animal <|-- Fish
      Animal <|-- Zebra
      Animal : +int age
      Animal : +String gender
      Animal: +isMammal()
      Animal: +mate()
      class Duck{
          +String beakColor
          +swim()
          +quack()
      }
      class Fish{
          -int sizeInFeet
          -canEat()
      }
      class Zebra{
          +bool is_wild
          +run()
      }

```
---
# US 015, Higlight certain words in Markdown
```html
For marking words in highlighted text ==Highlighted text==. and so on
<span style="background-color: #FFFF00"> Very importent words</span>.
```
---
# US 016, Making a sequence diagram in Markdown using Mermaid.
```mermaid
sequenceDiagram
    Alice->>+John: Hello John, how are you?
    Alice->>+John: John, can you hear me?
    John-->>-Alice: Hi Alice, I can hear you!
    John-->>-Alice: I feel great!
```
---
# US 017, Making a Git Graph in Markdown using Mermaid.

```mermaid
 gitGraph
       commit
       commit
       branch develop
       checkout develop
       commit
       commit
       checkout main
       merge develop
       commit
       commit
```
---
