
## Que 1. What are the benefits of using CSS?

#### Ans

1) Saves a lots of time
2) Better user experience
3) Quicker development time
4) Easy formatting changes
5) Compatibility across devices
6) Faster page speed
7) create Animation and Effects

<hr>

## Que 2. What are the disadvantages of CSS?

#### Ans

1) Browser compatibility
2) learning Curve
3) Lack for security
4) Limited layout controls
5) Performance impact
6) Overriding Styles
7) Maintenance challenges

<hr>

## Que 3. What is the difference between CSS2 and CSS3?

#### Ans

1) CSS cannot be split into modules and CSS3 can be split into modules.
2) In CSS we cannot build 3d animation and In CSS3 we can build 3d animation.
3) In CSS we have set of standard colors and it uses basic color schemes only. Whereas CSS3 has a good collection of HSL RGBA, HSLA, and gradient colors.
4) In CSS we can only use single text blocks.But in CSS3 we can use multi-column text blocks.
5) CSS don't support media queries and CSS3 supports media queries.

<hr/>

## Que 4. Name a few CSS style components

#### Ans

CSS style components are below...

1. **``Selector``**: Class name, id name or element name that is target

2. **``Attribute``**: Name of the attribute you want to style for example border, color, background, position etc.

3. **``Value of Property``**: value that will be assigned to attribute.

```css
p{
    color: pink;
    text-align: center;
}
```

In this example **``p``** is selector, following style rules will be applied to all paragraph.

1. color is a attribute and pink is a value.
2. text-align is a attribute and center is a value.

<hr>

## Que 5. What do you understand by CSS opacity?

#### Ans

The opacity in CSS is the property of an element that describes the transparency of the element. It is the opposite of transparency & represents the degree to which the content will be hidden behind an element.

An opacity value of "1" means the element is completely opaque and an opacity value of "0" means the element is completely transparent. You can use values between "0" and "1" to control the element's transparency to a degree.
For Example :

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Opacity</title>
    <style>
        .image{
            opacity: 0.4;
        }
    </style>
</head>
<body>
    <div class="pic">
        <img src="https://img.freepik.com/free-vector/landscape-man-canoe-river_24877-76260.jpg?t=st=1718797129~exp=1718800729~hmac=8095698b8755e89973f7c2ec7834dc34b8a2a0ac01b01d5b5d4725148d422948&w=740" alt="" height="300" width="300">
    </div>
    <br>
    <div class="image">
        <img src="https://img.freepik.com/free-vector/landscape-man-canoe-river_24877-76260.jpg?t=st=1718797129~exp=1718800729~hmac=8095698b8755e89973f7c2ec7834dc34b8a2a0ac01b01d5b5d4725148d422948&w=740" alt="" height="300" width="300">
    </div>
    
</body>
  
</html>
```

<hr>

## Que 6. How can the background color of an element be changed?

#### Ans

Use the CSS background-color property to add a background color to HTML. Put it into a style attribute and change the value to the desired color name or code. We can set background color by selecting the element by its class name of id name and then apply the background-color property on it to set the background color.

Syntax : **`background-color : color_name;`**

For Example :

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>Image Page</title>
<style>
    .box{
        height: 300px;
        width: 300px;
        border-radius: 15px;
        border: 1px solid rgb(12, 12, 12);
        background-color: aqua;
    }
</style>

</head>
<body>
    <div class="box">

    </div>
  

</body>
</html>
```

<hr>

## Que 7. How can image repetition of the backup be controlled?

#### Ans

This task can be achieved by using the background-repeat property that will help us to control the repetition of the image. The background-repeat property in CSS is used to repeat the background image both horizontally and vertically. It also decides whether the background image will be repeated or not.

For Example :

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .box{
            height: 1000px;
            width: 1000px;
            background-image: url(https://images.pexels.com/photos/583677/pexels-photo-583677.jpeg?auto=compress&cs=tinysrgb&w=600);
            border-radius: 20px;
            background-repeat: repeat-x;
        }
    </style>
</head>
<body>
    <div class="box"></div>
</body>
</html>
```

<hr>

## Que 8. What is the use of the background-position property?

#### Ans

The background-position property defines the original position of the background image. It can contain keyword values — top, bottom, left, or right — specifying the edge of the element's box to which you want to place the background. When we only use one value, the browser assumes the other value sets to center.

In the two-value notation, the first value represents the horizontal position, and the second represents the vertical. For example, the declaration **``background-position: bottom left;``** means the object will be placed at bottom-left corner.

You can also use length (px, pt, cm) or percentage values for defining the background position and combine them to further specify the coordinates.

For Example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background-image: url("https://img.freepik.com/free-photo/olivebacked-sunbirds-feeding-child-cinnyris-jugularis_488145-1597.jpg?t=st=1718799909~exp=1718803509~hmac=897c2dce0a50fb76e53f1adcddbce0ad7a581a2f03930a4732c37f7698aae2a6&w=740");
            background-repeat: no-repeat;
            background-size: 500px;
            background-position-x: 200px;
            background-position-y:200px ;
        
        }
    </style>
</head>
<body>

</body>
</html>
```

<hr>

## Que 9. Which property controls the image scroll in the background?

#### Ans

The background-attachment property is used to specify that the background image is fixed or scroll with the rest of the page in the browser window.

This property has three values scroll, fixed, and local. Its default value is scroll, which causes the element to not scroll with its content. The local value of this property causes the element to scroll with the content. If we set the value to fixed, the background image will not move during scrolling in the browser.

For Example :

```html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1.0" />
    <title>Document</title>
    <style>
      * {
        padding: 0;
        margin: 0;
        box-sizing: border-box;
      }

      .box2 {
     
        width: 500px;
        border-radius: 12px;
        margin: 50px auto;
        border: 3px solid black;
        padding: 10px;
        color: aliceblue;
        background-image: url(https://img.freepik.com/free-photo/majestic-lion-undisputed-king-jungle-resting-regally-sunlit-rock_1268-34999.jpg?w=826&t=st=1719677981~exp=1719678581~hmac=072010f2faf838f1cddd9df1afcfed7b73b941fced88eedf60ec3aa2d85b3681);
     
      
        background-attachment: fixed;
      }
    </style>
  </head>
  <body>
 

    <div class="box2">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolore
      recusandae maiores eveniet id nulla blanditiis. Autem, expedita porro!
      Corrupti, culpa. Quam omnis deserunt, odio recusandae assumenda
      voluptatibus ex provident saepe exercitationem ipsa. Vitae laboriosam
      inventore veniam laborum repellat error provident qui odio? Voluptatum,
      provident. Eius maiores perspiciatis quas perferendis ex. Eligendi, omnis
      cumque sed at, non maiores quasi mollitia optio ducimus qui, facere nobis
      debitis consequatur reiciendis magni dignissimos soluta libero aut fugit
      aliquid laudantium incidunt molestiae corporis! Voluptate quam,
      perferendis saepe assumenda quia culpa iusto, blanditiis quasi nulla
      deserunt soluta corrupti voluptatum eligendi veritatis ipsam quos tempore?
      Vero, deleniti esse quia nam aliquam odio! Facere fugit, explicabo nisi
      exercitationem a esse veniam eveniet sed ipsum iure. Perferendis saepe
      voluptatum aperiam et mollitia, at maiores neque dolor laborum cum
      excepturi! Praesentium deleniti iusto provident numquam repellat eos
      eligendi ipsa obcaecati perferendis vitae doloribus illum aliquam harum
      esse eum voluptatem aut ipsum, ipsam at dolorum id tempore! Inventore
      cupiditate dolore facilis unde deleniti, sapiente a quod quaerat quam
      autem? Excepturi porro debitis sequi. Veniam saepe, pariatur vero, iusto
      labore sed ipsam excepturi ipsa illo soluta nam molestias placeat alias
      nihil consequuntur? Repellat quo eligendi voluptate voluptatibus
      asperiores ea aspernatur vel saepe ullam corporis, illo dolores quia
      temporibus qui dolorum culpa quod. Temporibus beatae nostrum maiores ipsam
      omnis accusamus placeat dicta, ipsa quae repellendus id corporis expedita
      doloribus! Ducimus mollitia, quod ipsum reiciendis rerum adipisci itaque
      laborum ipsam beatae quis quibusdam, consectetur et odit aperiam nihil
      repellendus totam consequuntur minima illum, asperiores ullam harum!
      Reprehenderit suscipit odio, facilis quidem sed ea ipsam beatae sapiente
      aperiam. Beatae, dicta fugit? Quas hic iure ex deleniti? Iure id adipisci
      quas enim facilis delectus saepe sunt, harum tenetur accusantium,
      inventore dicta itaque sequi rem eaque. Suscipit recusandae totam ad
      sapiente vero omnis fuga error officiis eaque. Lorem ipsum dolor sit amet
      consectetur adipisicing elit. Accusamus, nemo, esse recusandae laborum,
      nostrum adipisci architecto voluptatibus magni sit aliquam delectus magnam
      vero facilis nulla quia repudiandae quasi at tempore harum modi nihil
      veniam fugiat! Autem nesciunt temporibus est natus illum ipsa,
      consectetur, error beatae delectus cupiditate laudantium officia
      accusantium laboriosam veniam asperiores voluptatum assumenda atque
      aperiam porro ab exercitationem qui iure. Corrupti atque dolore repellat,
      voluptatibus reiciendis officiis blanditiis error minus aut ullam illo id
      quaerat provident sint libero quos quae pariatur cumque deleniti
      repellendus, et hic doloremque architecto? Dolores obcaecati accusamus
      alias dicta dolore est sit provident dignissimos velit beatae, minima ex
      sequi libero assumenda labore ab optio at repudiandae rem necessitatibus
      animi id. Reprehenderit quae odit velit tempora voluptate quo harum, sequi
      suscipit maiores in aliquam assumenda modi animi incidunt, eum ipsa
      molestiae corrupti, tempore voluptatem repudiandae cupiditate possimus
      repellendus corporis eius! Vitae commodi soluta repudiandae ab atque?
      Iusto nobis eligendi est eveniet reprehenderit, eius repellat consequatur.
      Dignissimos libero distinctio ullam! Deserunt fugit dolores ex molestias,
      amet asperiores ipsum saepe nam iure et, quis consectetur dolorum enim
      autem natus reiciendis laborum laudantium quisquam modi fuga, eaque quasi
      sint. Nihil neque cupiditate itaque tempore et dignissimos! Suscipit,
      impedit! Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi
      ducimus aspernatur commodi sequi alias quasi temporibus cupiditate quo at
      deleniti tempora doloremque corporis rerum, ullam, quae facilis tenetur
      vero dignissimos a fuga ipsam adipisci eveniet soluta maiores iusto cumque
      iure vitae temporibus ducimus! Consequatur fugiat sapiente a et aliquam ut
      voluptas ipsam, veniam unde minima sint nobis dolorum itaque cum eius fuga
      quam accusantium obcaecati facilis tempore quis dolorem numquam facere
      atque fugiat commodi quidem maxime assumenda saepe, animi fugit,
      repudiandae consequuntur? Repellat nihil laudantium dicta quasi quaerat
      neque aliquam omnis aspernatur quisquam rem sit ipsa consequuntur
      distinctio maxime voluptatum commodi porro corrupti id, libero tempore
      autem cumque. Quas expedita a, voluptates dolore, sit excepturi velit id
      aut facere aspernatur officia, laudantium ullam maiores animi mollitia
      fugiat. Error ab excepturi ut cum reiciendis recusandae, eligendi quidem
      tempore? Earum soluta aspernatur iste ab temporibus rerum nostrum. Nostrum
      doloribus animi libero, accusantium ullam, laborum ex sint deleniti
      dignissimos minus nam modi obcaecati perspiciatis quidem explicabo dolores
      possimus voluptas. Minus cum iure voluptas modi atque libero voluptatibus,
      tempore, labore blanditiis numquam possimus, neque ipsam sint provident
      minima accusantium ad. Voluptas sint veniam optio tempora quo consequuntur
      neque laboriosam omnis. Animi suscipit, exercitationem obcaecati pariatur
      dolorem excepturi, vero nemo ipsam corrupti doloremque esse perferendis
      ipsa quisquam et illum reiciendis consequatur eius consectetur,
      voluptatibus unde eos autem a ullam. Quae iusto ab cum, ea, distinctio, et
      quidem aut error blanditiis excepturi facere dicta voluptatibus omnis id
      voluptate quia nisi labore pariatur sit cupiditate nesciunt nulla.
      Assumenda nostrum dolor blanditiis consequuntur voluptas tenetur!
    </div>
  </body>
</html>

```

<hr>

## Que 10. Why should background and color be used as separate properties?

#### Ans

While background and colour are often used together for elements, they serve different purposes. **``"Colour"``** sets the text colour, while **``"background"``** defines the background colour or image. Separating them allows for more flexibility in styling, as background properties can include images, gradients, and positioning.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .box{
            height: 200px;
            width: 200px;
            border: 1px solid;
            margin: 50px auto;
            font-size: 30px;
            font-weight: 600;
            color: aliceblue;
            text-align: center;
            background-color: #C779D0;
        
        }
    </style>
</head>
<body>
    <div class="box">
        Hello World
    </div>
</body>
</html>
```

<hr>

## Que 11. How to center block elements using CSS1?

#### Ans

Center block elements using margin property: We need to specify the margin from left and right such that it looks centered. We do not need to do this manually, we have one property value “auto” which will automatically set the margin such that our block element is placed in the center.

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Card</title>
    <style>
    
        .card{
            margin: auto;
            height: fit-content;
            width: 300px;
            box-shadow: rgba(0, 0, 0, 0.02) 0px 1px 3px 0px, rgba(27, 31, 35, 0.15) 0px 0px 0px 1px;
            border-radius: 15px;
            padding-top: 1px;          
        }
        .box{
            height: 250px;
            border: 1px solid blue;
            border-bottom-right-radius: 70%;
            border-top-left-radius: 10px;
            border-top-right-radius: 10px;
            border-bottom-left-radius: 10px;
            background-color: blue;
            margin: 10px;
        }

        .card .cantent button{
            padding: 10px 20px;
            border: none;
            color: aliceblue;
            background-color: rgb(26, 26, 216);
            border-radius: 5px;         

        }
        .card .cantent {
            text-align: center;
            padding: 15px;
        }
        .card .cantent button:hover{
            background-color: rgb(67, 67, 163);
            color: rgb(255, 255, 255);
            box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
          
        }
        .card:hover{
            box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
            transform: translateY(-5px);

        }
    </style>
</head>
<body>
    <div class="card">
        <div class="box">

        </div>
        <div class="cantent">
           <h2>C++</h2> 
            <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rerum voluptatibus iure
                minima veritatis eligendi possimus! Accusamus ea et sed repellendus
                alias non, sequi similique animi aut, fuga nam quas corporis nostrum,
                doloribus beatae fugit totam labore tempora omnis. Odio maxime impedit 
                nisi quam ratione quidem possimus rem sit soluta minus!
            </p>
            <button>Code</button>
        </div>
    </div>
</body>
</html>

```

<hr>

## Que 12. How to maintain the CSS specifications?

#### Ans

The CSS specifications are maintained by the **``World Wide Web Consortium (W3C)``**.The Specification defines how CSS properties should be implemented by browser vendors along with detailed algorithms, code samples and tabular information.
The Specification also include:

1. The syntax and data types of the language
2. Detailed explanation on CSS Selectors
3. How you can assign values to properties
4. How inheritance works
5. The Box Model e.t.c

<hr>

## Que 13. What are the ways to integrate CSS as a web page?

#### Ans

CSS can be added to HTML documents in 3 ways:

1. Inline - by using the **`style`** attribute inside HTML elements.
2. Internal - by using a **`<style>`** element in the **`<head>`** section.
3. External - by using a **`<link>`** element to link to an external CSS file.

<hr>

## Que 14. What is embedded style sheets?

#### Ans

 It allows you to define styles for a particular HTML document as a whole in one place. This is done by embedding the **`<style></style>`** tags containing the CSS properties in the head of your document. However, if the styles need to be applied across multiple documents, you should link to an external style sheet instead of using individual embedded style sheets.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
            background-image: linear-gradient(#fdbb2d,#22c1c3);
            background-clip: text;
            color: transparent;
            font-size: 300px;
        }
        .box{
            background-image: linear-gradient(  #fdbb2d,#22c1c3);
         
            background-clip: text;
            color: transparent;
            font-size: 300px;
        }
    </style>
</head>
<body>
    <h1>SUSHL</h1>
   
</body>
</html>
```

<hr>

## Que 15. What are the external style sheets?

#### Ans

An external style sheet is a separate CSS file that can be accessed by creating a link within the head section of the webpage. Multiple webpages can use the same link to access the stylesheet. The link to an external style sheet is placed within the head section of the page.

**`.HTML File`**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
   <link rel="stylesheet" href="name.css">
</head>
<body>
    <h1>SUSHIL</h1>
</body>
</html>

```

**`.CSS File`**

```css
h1{
    background-image: linear-gradient(#fdbb2d,#22c1c3);
    background-clip: text;
    color: transparent;
    font-size: 300px;
}
.box{
    background-image: linear-gradient(  #fdbb2d,#22c1c3);
    background-clip: text;
    color: transparent;
    font-size: 300px;
}
```

<hr>

## Que 16. What are the advantages and disadvantages of using external style sheets?

#### Ans

**``External Style sheets Advantages``**

1. With the help of External Style Sheets, the styles of numerous documents can be organized from one single file.
2. In External Style Sheets, Classes can be made for use on numerous HTML element types in many forms of the site.
3. In complex contexts, Methods like selector and grouping can be implemented to apply styles.

**``External Style sheets disadvantages``**

1. An extra download is essential to import style information for each file.
2. The execution of the file may be deferred till the external style sheet is loaded.
3. While implementing style sheets, we need to test Web pages with multiple browsers in order to check compatibility issues.

<hr>

## Que 17. What is the meaning of the CSS selector?

#### Ans

CSS selectors are used to "find" the HTML elements you want to style.

We can divide CSS selectors into five categories:

1. **`Simple selectors`** : select elements based on name, id, class.
2. **`Combinator selectors`** : select elements based on a specific relationship between them .
3. **`Pseudo-class selectors`** : select elements based on a certain state.
4. **`Pseudo-elements selectors`** : select and style a part of an element
5. **`Attribute selectors`** : select elements based on an attribute or attribute value.

<hr>

## Que 18. What are the media types allowed by CSS?

#### Ans

Following the media types allowed by CSS.

1. **``All``** : Suitable for all media devices.

2. **``Print``** : Used for printers.

3. **``Screen``** : Targeted at computer screens, tablets, smartphones, etc.

4. **``Speech``** : Designed for screen readers that read the content aloud.

<hr>

## Que 19. What is the rule set?

#### Ans

A CSS rule set contains one or more selectors and one or more declarations.

For Example :

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>Rule set</title>
    <style>
        h1{
            color: blueviolet;
            text-align: center;
            background-color: antiquewhite;
        }
    </style>

</head>
<body>
    <h1>Hello World</h1>
</body>
</html>

```

1. The whole thing is a ruleset.
2. The curly braces and everything inside is a declaration block.
3. The bit before the opening curly brace is a selector.In this example **``h1``** is a selector.
4. Each value pair, as separated by a colon and ending in a semicolon, is a declaration.
5. In those value pairs, the key is a  property name, and the value is a property value.

<hr>

## Que 20. Create Layouts

#### Ans

```html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Assignment</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
  <style>
    .box{
    margin-left: 180px;
  
    }
    .card{
      display: inline-block;
      margin-left: 20px;
      width: 300px;
      margin-top: 30px;
      font-family: "Poppins", sans-serif;
      box-shadow: 2px 2px 10px 1px gray;

    }
    .bgc{
      background-color: rgba(128, 128, 128, 0.87);
      font-weight: 600;
      font-size: 20px;
      height: 130px;
      display: flex;
      align-items: center;
      justify-content: center;
    
    }
    .content{
      font-size: 16px;
      padding: 15px;


    }
    button{
      padding: 5px 10px;
      border-radius: 5px;
      margin-top: 13px;
    
    }
  </style>
</head>
<body>
  <div class="box">
    <div class="card">
      <div class="bgc">Thumbnail</div>
      <div class="content">
        This is a wider card with supporting text below as a natural lead-in to a additional content. this content is a little bit longer. <br>
        <button>View</button>
        <button>Edit</button>
      </div>
    
    </div>

    <div class="card">
      <div class="bgc">Thumbnail</div>
      <div class="content">
        This is a wider card with supporting text below as a natural lead-in to a additional content. this content is a little bit longer. <br>
        <button>View</button>
        <button>Edit</button>
      </div>
    
    </div>

    <div class="card">
      <div class="bgc">Thumbnail</div>
      <div class="content">
        This is a wider card with supporting text below as a natural lead-in to a additional content. this content is a little bit longer. <br>
        <button>View</button>
        <button>Edit</button>
      </div>
    
    </div>
  </div>

  <div class="box">
    <div class="card">
      <div class="bgc">Thumbnail</div>
      <div class="content">
        This is a wider card with supporting text below as a natural lead-in to a additional content. this content is a little bit longer. <br>
        <button>View</button>
        <button>Edit</button>
      </div>
    
    </div>

    <div class="card">
      <div class="bgc">Thumbnail</div>
      <div class="content">
        This is a wider card with supporting text below as a natural lead-in to a additional content. this content is a little bit longer. <br>
        <button>View</button>
        <button>Edit</button>
      </div>
    
    </div>

    <div class="card">
      <div class="bgc">Thumbnail</div>
      <div class="content">
        This is a wider card with supporting text below as a natural lead-in to a additional content. this content is a little bit longer. <br>
        <button>View</button>
        <button>Edit</button>
      </div>
    
    </div>
  </div>


</body>
</html>

```