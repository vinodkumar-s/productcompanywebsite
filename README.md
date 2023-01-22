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
HOME PAGE:

``` html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TG'S GAME STORE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/images/tamil.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitem"><a href="/products/">Products</a></div>
        <div class="menuitem"><a href="/people/">People</a></div>
        <div class="menuitem"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/images/tamil.jpg" border-color="yellow" alt="logo" />
          <div class="contenttext">
TG'GAME STORE is the world's largest video game retailer. With over 6,100 stores located throughout the United States and 17 countries, we are the retail destination for gamers around the world.

Our GameStop retail locations set us apart in the industry. Everything that we offer our customers-from our expansive selection of new products, to our knowledgeable associates and our value-added pre-owned products-is geared to deliver customer satisfaction. We complement our store network in Canada with gamestop.ca, and publish Game Informer, one of the industry's largest circulation video game magazines.

Together, we hold a passion for gaming, a commitment to our industry and a disciplined business perspective to continuously drive value with shareholders, customers, vendors and employees.
            <br />
          </div>
        </div>
      </div>
      
      <div class="footer">
        Copyright &#169; 2023 TG'S GAME STORE, Designed By VINOD KUMAR.S
      </div>
    </div>
  </body>
</html>

```
PRODUCT PAGE:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TG</title>
    <link rel="stylesheet" href="./css/layout.css" />
     <link rel="icon" href="/static/images/tglogo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/home/">Home</a></div>
        <div class="menuitem"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitem"><a href="/contactus/">Contact Us</a></div>
      </div>
      
      <div class="content">
        <div class="productcontent">
            <h1>Our Crew Memebers</h1>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/vivek.jpg" alt="people image">
                            </div>
                            <div class="itemname">FOUNDER OF TG</div>
                            <div class="itemprice">VIVEK</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/prem.jpg" alt="people image">
                            </div>
                            <div class="itemname">CO-FOUNDER OF TG</div>
                            <div class="itemprice">PREM</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/15.jpg" alt="people image">
                            </div>
                            <div class="itemname">CHIEF OPERATING OFFICER</div>
                            <div class="itemprice">VISWANATH</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/16.jpg" alt="people image">
                            </div>
                            <div class="itemname">CHIEF MARKETING OFFICER</div>
                            <div class="itemprice">SYED ISMAIL</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/17.jpg" alt="people image">
                            </div>
                            <div class="itemname">CHIEF TECHNOLOGY OFFICER</div>
                            <div class="itemprice">NANDA</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/13.jpg" alt="people image">
                            </div>
                            <div class="itemname">COMPANY-SPONSOR</div>
                            <div class="itemprice">MADAN</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
        Copyright &#169; 2023 TG'S GAME STORE , Designed By VINOD KUMAR.S
      </div>
    </div>
  </body>
</html>
```

PEOPLE PAGE:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TG</title>
    <link rel="stylesheet" href="./css/layout.css" />
     <link rel="icon" href="/static/images/tglogo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/home/">Home</a></div>
        <div class="menuitem"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitem"><a href="/contactus/">Contact Us</a></div>
      </div>
      
      <div class="content">
        <div class="productcontent">
            <h1>Our Crew Memebers</h1>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/vivek.jpg" alt="people image">
                            </div>
                            <div class="itemname">FOUNDER OF TG</div>
                            <div class="itemprice">VIVEK</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/prem.jpg" alt="people image">
                            </div>
                            <div class="itemname">CO-FOUNDER OF TG</div>
                            <div class="itemprice">PREM</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/15.jpg" alt="people image">
                            </div>
                            <div class="itemname">CHIEF OPERATING OFFICER</div>
                            <div class="itemprice">VISWANATH</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/16.jpg" alt="people image">
                            </div>
                            <div class="itemname">CHIEF MARKETING OFFICER</div>
                            <div class="itemprice">SYED ISMAIL</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/17.jpg" alt="people image">
                            </div>
                            <div class="itemname">CHIEF TECHNOLOGY OFFICER</div>
                            <div class="itemprice">NANDA</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/13.jpg" alt="people image">
                            </div>
                            <div class="itemname">COMPANY-SPONSOR</div>
                            <div class="itemprice">MADAN</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
        Copyright &#169; 2023 TG'S GAME STORE , Designed By VINOD KUMAR.S
      </div>
    </div>
  </body>
</html>
```

CONTACT-US PAGE:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>TG</title>
    <link rel="stylesheet" href="./css/layout.css" />
     <link rel="icon" href="/static/images/tglogo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/home/">Home</a></div>
        <div class="menuitem"><a href="/products/">Products</a></div>
        <div class="menuitem"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
          <div class="us">
              <h1><center>
                  <u>Contact Us</u></center>
                </h1><center>
                    <h2>For Enquiry</h2>
                        <h3>EMAIL : tamilgaming@gmail.com</h3>
                        <h3>NUMBER: +91 9361199777,+91 8535647625</h3>
                        <h3>ADDRESS: 12B,baywatch enclave,salem.</h3>
                        <h3>WEBSITE: Tamilgaming.com</h3>
                </center>
                
          </div>
            </div>
            <div class="footer">
        Copyright &#169; 2023 TG'S GAME STORE , Designed By VINOD KUMAR.S
      </div>
    </div>
  </body>
</html>
```
CSS LAYOUT:
```HTML
<style>
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color :transparent;
  background: linear-gradient( #FFCF9E,#FFA6A6);
  color:white;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 10px;
  font-weight: bold;
  background-image: url("/static/images/tglogo.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 130px;
  padding-left:250px;
  color:white;
}



.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:orange;
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
  
}

.menuitem a {
  text-decoration:none;
  color: white;
}
h1 {
    color:white;
}

.content {
  display: block;
  width: 100%;
  background-color: rgb(48,48,48);
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color:goldenrod;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  font-family: Arial, Helvetica, sans-serif;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color:whitesmoke;
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
  background-color:orange;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color:white;
}

</style>

```
## OUTPUT:

### Home Page:

![output](/images/home-page.png)

### PRODUCT PAGE:
![OUTPUT](/images/product.png)

### PEOPLE PAGE:
![OUTPUT](/images/people.png)

### CONTACT-US PAGE:
![OUTPUT](/images/contact-us.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
