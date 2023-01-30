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
LAYOUT.CSS:
```
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
  background-image: url("/static/img/vs.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #018317;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: rgb(5, 201, 37);
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
  background-image: url("/static/img/natural.jpg");
  min-height: 500px;
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  color: black;
  display: inline;
}
.homecontent h1 {
  color: rgb(248, 242, 242);
  display: inline;
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
  color: rgb(255, 255, 255);
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  display: inline;
  color: rgb(253, 251, 251);
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
  display: inline-block;
}
.productitem .itemimage {
  display: inline-block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
  color: rgb(253, 249, 249);
  font-family: block;
}
.productitem .itemprice {
  display: block;
  color: rgb(255, 255, 255);
  font-family: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: rgb(5, 201, 37);
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}

.productitem1 .itemimage1 {
  display: inline-block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  height: 40px;
  margin-bottom: 5px;
}

.productitem1 .itemprice1 {
  display: block;
  color: rgb(255, 255, 255);
  font-family: block;
}
```
HOME PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Vasu Health Care</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <br><br>
          <img src="./img/SSS.png" alt="Building" width="40" />
          <div class="contenttext">
            Vasu Healthcare, with its rich culture and deeply rooted legacy since 1980, was established with one precise aim to serve the society by introducing quality herbal
             & ayurvedic products that add value to everyone's life. The journey that we embarked 40 years ago with the help of a rich herbal and ayurvedic knowledge base has led 
             us to greater heights and milestones of excellence. And we will continue to bring the miraculous byproducts of this vast ayurvedic sea of knowledge combined with cutting-edge
              technologies in medical science.
            <br><br>
             Our sheer dedication towards herbal and ayurvedic research to develop the best products for the people is now growing globally with a presence in over 50 countries.
             Ayurveda has many hidden gems that serve humanity. We take extreme pride in extracting that knowledge to manufacture highly effective ayurvedic medicines and herbal cosmetic products.
             Over the years, we researched & developed more than 200 products that help people to cure & improvise their health.
            <ul>
              <li>Simple and easy to use</li>
              <li>get rid of frizzy hair</li>
              <li>Your hair will love our shampoo</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021  Vasu health Care Private Limited, Developed by Aakash.S
      </div>
    </div>
  </body>
</html>
```
PEOPLE PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Vasu Health Care</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company employees:</h1><br><br>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/RSM.png" alt="product image">
                </div>
                <div class="itemname">Aakash</div>
                <div class="itemprice">RSM </div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/DSM.png"  alt="product image">
                </div>
                <div class="itemname">Saran</div>
                <div class="itemprice">DSM</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/Ass HR.png"  alt="product image">
              </div>
              <div class="itemname">Ashwin Raaj</div>
              <div class="itemprice">Assistant HR </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/HR.png"  alt="product image">
              </div>
              <div class="itemname">Jeeva</div>
              <div class="itemprice">HR </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/RSM.png"  alt="product image">
            </div>
            <div class="itemname">Krishna</div>
            <div class="itemprice">RSM </div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/senior manager.png"  alt="product image">
          </div>
          <div class="itemname">Vasib</div>
          <div class="itemprice">senior manager</div>
      </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2021 Vasu health Care Private Limited, Developed by Aakash.S.
    </div>
  </div>
</body>
</html>
```
PRODUCTS PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Vasu Health Care</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Image001.png" alt="product image">
                  </div>
                  <div class="itemname">hair fall control oil</div>
                  <div class="itemprice">Price: Rs.195/- </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Image002.png"  alt="product image">
                  </div>
                  <div class="itemname">Herbal shampoo</div>
                  <div class="itemprice">Price: Rs.300/- </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/Image003.png"  alt="product image">
                </div>
                <div class="itemname">Keratin Shampoo</div>
                <div class="itemprice">Price: Rs.270/- </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/Image004.png"  alt="product image">
                </div>
                <div class="itemname">Black Seed Shampoo</div>
                <div class="itemprice">Price: Rs.199/- </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/Image005.png"  alt="product image">
              </div>
              <div class="itemname">Trichup Anti Dandruff Herbal Shampoo</div>
              <div class="itemprice">Price: Rs.150/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/Image006.png"  alt="product image">
            </div>
            <div class="itemname">Trichup Herbal Shampoo</div>
            <div class="itemprice">Price: Rs.170/- </div>
        </div>
        <div class="productitem"> 
        <div class="itemimage1">
          <img src="/static/img/product5.png"  alt="product image">
          </div>
          <div class="itemname">Lip Care</div>
          <div class="itemprice">Price: Rs.199/- </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage1">
          <img src="/static/img/product4.png"  alt="product image">
          </div>
          <div class="itemname">Face Mask</div>
          <div class="itemprice">Price: Rs.270/- </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage1">
          <img src="/static/img/product3.png"  alt="product image">
          </div>
          <div class="itemname">Face Wash</div>
          <div class="itemprice">Price: Rs.570/- </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage1">
          <img src="/static/img/product3.png"  alt="product image">
          </div>
          <div class="itemname">Face Wash</div>
          <div class="itemprice">Price: Rs.370/- </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage1">
          <img src="/static/img/product2.png"  alt="product image">
          </div>
          <div class="itemname">Beard And Face Wash</div>
          <div class="itemprice">Price: Rs.200/- </div>
      </div>      <div class="productitem"> 
        <div class="itemimage1">
          <img src="/static/img/product1.png"  alt="product image">
          </div>
          <div class="itemname">Skin Cream</div>
          <div class="itemprice">Price: Rs.299/- </div>
      </div>
            </div>
          </div>
          </div>  
          </div>>      
      </div>
      <div class="footer">
        Copyright &#169; 2021  Vasu health Care Private Limited, Developed by Aakash.S.
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:

### Home Page:

![output](./images/homepage.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
