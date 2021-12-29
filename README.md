# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### Home Page: 
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Sarvesh Indusries Private Limited</title>
    <link rel="stylesheet" href="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\css\layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Sarvesh Industries Private Limited </div>
      <div class="menu">
        <div class="menuitemselected"><a href="home.html">Home</a></div>
        <div class="menuitem"><a href="home.html">Products</a></div>
        <div class="menuitem"><a href="home.html">People</a></div>
        <div class="menuitem"><a href="home.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us :</h1>
          <img src="https://image.shutterstock.com/image-vector/circle-rubber-stamp-text-second-260nw-1324908650.jpg"  alt="Building" />
          <div class="contenttext">
            Sarvesh Industries Private Limited is a global leader in next-generation digital services and consulting. We enable 
            clients in more than 200 countries to navigate their digital transformation, Whcih will be very usefull for them.
            <br/>
            We have five decades of experience in managing the systems and workings of global enterprises, 
            we expertly steer our clients through their digital journey, which will be comfortable for them. We do it by enabling the enterprise 
            with an AI-powered core that helps prioritize the execution of change. We also empower the business 
            with agile digital at scale to deliver unprecedented levels of performance and customer delight. Our 
            always-on learning agenda drives their continuous improvement through building and transferring digital skills, 
            expertise, and ideas from our innovation ecosystem.


            <br />
            In Sarvesh Indusries Private Limited, we believe that technology should simplify businesses, not complicate them;
             it should free you, not tie you down. It is the philosophy that has been the driving force behind all our
              innovations and product developments. Since our foray into the Enterprise Applications market in the nineties, 
              our company has come a long way. Today, Shriram Indusries Private Limited is a force to reckon with in the Global Cloud Enterprise 
              Applications market. Trusted by millions of clients across verticals, we are the Number 1 choice of clients looking for 
              future-ready enterprise applications.
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Ashlord Industries, Developed by P.Sarvesh
      </div>
    </div>
  </body>
</html>
~~~

### Product Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Sarvesh Indusries Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Sarvesh Indusries Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="products.html">Home</a></div>
        <div class="menuitemselected">
          <a href="products.html">Products</a>
        </div>
        <div class="menuitem"><a href="products.html">People</a></div>
        <div class="menuitem"><a href="products.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Softwares We Offer :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src= "C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\a1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Apple 12 Pro</div>
                  <div class="itemprice">Price: Rs.50,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\13.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Apple mini</div>
                  <div class="itemprice">Price: Rs.12,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\nord.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Nord 2</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\nord1.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Oneplus 8</div>
                  <div class="itemprice">Price: Rs.17,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\realme.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Micromax</div>
                  <div class="itemprice">Price: Rs.11,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\redmi.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Infinix</div>
                  <div class="itemprice">Price: Rs.29,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\gt.jpg"  alt="product image">
                  </div>
                  <div class="itemname">INFINITI</div>
                  <div class="itemprice">Price: Rs.14,500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\a52.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Oneplus</div>
                  <div class="itemprice">Price: Rs.35,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\m32.jpg"  alt="product image">
                  </div>
                  <div class="itemname">micromax</div>
                  <div class="itemprice">Price: Rs.19,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\infinix.jpg"  alt="product image">
                  </div>
                  <div class="itemname">galaxy</div>
                  <div class="itemprice">Price: Rs.15,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\micromax.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Samsung</div>
                  <div class="itemprice">Price: Rs.20,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\nokia.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Nokia</div>
                  <div class="itemprice">Price: Rs.30,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Sarvesh Indusries Private Limited, Developed by P.Sarvesh
      </div>
    </div>
  </body>
</html>
~~~

### People Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Sarvesh Industries and Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="people.html">Home</a></div>
        <div class="menuitem"><a href="people.html">Products</a></div>
        <div class="menuitemselected"><a href="people.html">People</a></div>
        <div class="menuitem"><a href="people.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Board Of Directors :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\emma.jpg" alt="People">
                  </div>
                  <div class="itemname">Mrs. Emma watts</div>
                  <div class="itemprice">Founder </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\andrew.jpg" alt="People">
                  </div>
                  <div class="itemname">Mr.Dwyane Johnson</div>
                  <div class="itemprice">Co-Founder </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\tobey.jpg" alt="People">
                  </div>
                  <div class="itemname">Mr. Nick Johnas</div>
                  <div class="itemprice">Managing Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\tom.jpg" alt="People">
                  </div>
                  <div class="itemname">Mr. Chris Evans</div>
                  <div class="itemprice"> Joint-Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\hi.jpg" alt="People">
                  </div>
                  <div class="itemname">Mr. Tom Holland</div>
                  <div class="itemprice"> CEO </div>
              </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\andew.jpg" alt="People">
                  </div>
                  <div class="itemname">Mr. Chris Hemsworth</div>
                  <div class="itemprice"> Chief Technical Officer </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Ashlord Industries, Developed by Sarvesh
      </div>
    </div>
  </body>
</html>
~~~

### Contact Us Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Sarvesh Indusries Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Sarvesh Indusries Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="contact us.html">Home</a></div>
        <div class="menuitem"><a href="contact us.html">Products</a></div>
        <div class="menuitem"><a href="contact us.html">People</a></div>
        <div class="menuitemselected"><a href="contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1>
          <h1>Address:</h1>
          <img src="C:\Users\sarvesh\OneDrive\Documents\productcompanywebsite-1\companywebsite\static\img\bmw.jpg" alt="Building" />
          <div class="contenttext">
            Shasthri nagar, Royapuram, Chennai-600013
          </div>
          <h1>Phone:</h1>
          <div class="contenttext">
              Mr.Bhuvi(HR):9851458965<br/>
              Mr.Doraisingam(Assistant HR):9865327415
          </div>
          <h1>E-Mail:</h1>
          <div class="contenttext">
              Sales:sales@Sarvesh Indusries Private Limited.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Ashlord Industries, Developed by P.Sarvesh
      </div>
    </div>
  </body>
</html>
~~~

### Layout CSS:
~~~
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: "	https://i.pinimg.com/originals/39/7a/5c/397a5cb38259951ab109d14f789b7ccf.jpg";
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-image: ("https://i.pinimg.com/originals/39/7a/5c/397a5cb38259951ab109d14f789b7ccf.jpg") ;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
~~~


## OUTPUT:

### Home Page:

![output](home.png)

### Product Page:

![output](product.png)

### People Page:

![output](people.png)

### Contact Us Page:

![output](contact.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
