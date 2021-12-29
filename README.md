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
~~~
HOMEPAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AUTODESK SOFTWARES</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ban.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/open.png" alt="Building" />
          <div class="contenttext">
            Explore the new and enhanced features in Inventor 2021 3D CAD Software. Unlock the full version today with your free 30-day trial. Get up and running quickly. Simplify A Model for BIM. Document in 3D. Work with More File Types. More Intuitive Interface.
            <ul>
              <li>Student version available for UG And PG students,</li>
              <li>100% secure and easy to access,</li>
              <li>Both Online and Offline mode available.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; AUTODESK SOFTWARES, Developed by R.SOMEASVAR.
      </div>
    </div>
  </body>
</html> 
~~~

~~~
PRODUCT PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AUTODESK SOFTWARES</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ban.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>OUR PREMIUM APPS AVAILABLE</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/autocad.jpg" alt="product image">
                  </div>
                  <div class="itemname">AUTOCAD
                  </div>                
                  <div class="itemprice">price:$97500 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/AUTOCADLT.jpg"  alt="product image">
                  </div>
                  <div class="itemname">AUTOCAD LT
                  </div>
                  <div class="itemprice">price:$98500</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/BIM.jpg"  alt="product image">
                </div>
                <div class="itemname">BIM COLLABRATE PRO
                </div>
                <div class="itemprice">price:$99000</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/REVIT.jpg"  alt="product image">
              </div>
              <div class="itemname">REVIT
              </div>
              <div class="itemprice">price:$100000</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/INVENTOR.jpg"  alt="product image">
            </div>
            <div class="itemname">INVENTOR
            </div>
            <div class="itemprice">price:$123700</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/FUSION.jpg"  alt="product image">
          </div>
          <div class="itemname">FUSION 360
          </div>
          <div class="itemprice">price:$150000</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/NAVIS.jpg"  alt="product image">
        </div>
        <div class="itemname">NAVIS WORK
        </div>
        <div class="itemprice">price:$111900</div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/MAYA.jpg"  alt="product image">
      </div>
      <div class="itemname">MAYA
      </div>
      <div class="itemprice">price:$111900</div>
    </div> 
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/3DMAX.jpg"  alt="product image">
      </div>
      <div class="itemname">3D MAX
      </div>
      <div class="itemprice">price:$111300</div>
    </div> 
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/MAYALT.jpg"  alt="product image">
      </div>
      <div class="itemname">MAYA LT
      </div>
      <div class="itemprice">price:$112300</div>
    </div> 
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/AEC.jpg"  alt="product image">
      </div>
      <div class="itemname">AEC
      </div>
      <div class="itemprice">price:$112300</div>
    </div> 
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/CIVIL.jpg"  alt="product image">
      </div>
      <div class="itemname">CIVIL 3D
      </div>
      <div class="itemprice">price:$211300</div>
    </div> 
      
            
            </div>
          </div>
          </div> 
          <div class="footer">
            Copyright &#169; 2021 AUTODESK SOFTWARE, Developed by R.SOMEASVAR. 
             
          </div>
        
      

    </div>
    
  </body>
</html>
~~~

~~~
PEOPLE PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AUTODESK SOFTWARES</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ban.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="/static/People.html">People</a></div>

        <div class="menuitem"><a href="/static/Contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>WE HAVE DEALERS ALL OVER WORLD</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/SOM.jpg" alt="product image">
                  </div>
                  <div class="itemname">R.SOMEASVAR</div>
                  <div class="itemprice">USA---+14845219645 </div>
              </div>

              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/TWO.jpg"  alt="image">
                </div>
                <div class="itemname">JOHN</div>
                <div class="itemprice">AUSTRALIA---+61480049923 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/THREE.jpg"  alt="image">
              </div>
              <div class="itemname">GERALT</div>
              <div class="itemprice">SOUTH AFRICA---+27875510873</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/FOUR.jpg"  alt="image">
            </div>
            <div class="itemname">OTIS</div>
            <div class="itemprice">ENGLAND---+44 7911 123456</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/FIVE.jpg"  alt="image">
          </div>
          <div class="itemname">RAVEN</div>
          <div class="itemprice">DUBAI---04-609 6999</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/SIX.jpg"  alt="image">
        </div>
        <div class="itemname">GEORGE</div>
        <div class="itemprice">UK---+44 7911 123456</div>
    </div>
              </div>
              <div class="footer">
                Copyright &#169; 2021 AUTODESK SOFTWARES, Developed by R.SOMEASVAR.
            
              </div>    
              
          </div>
          </div>        
      </div>
      

    </div>
  </body>
</html>
~~~

~~~
CONTACT PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AUTODESK SOFTWARES</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ban.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
        <div class="banner"></div>

      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>

        <div class="menuitemselected"><a href="/static/Contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
    
        <div class="content">
          <div class="homecontent">
          
            <img src="./img/location.jpg" alt="Building" />
        <img src="./img/qr code.jpg" alt="Building" />
        <br>257,Cathetral Road,</br>
        <br>Near White House</br>
        <br>USA</br>
        <br>Phn: 044-48485 48485</br>
        <br>email-Autodesk360@gamil.com</br>
      </div>

      </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 AUTODESK SOFTWARES,Developed by R.SOMEASVAR.
      </div>
    </div>
  </body>
</html>
~~~



## OUTPUT:

### HOME PAGE:

![output](./images/HOME.png)

### PRODUCT PAGE:

![output](./images/PRODUCT.png)

## PEOPLE PAGE:

![output](./images/PEOPLE.png)

## CONTACT PAGE:

![output](./images/contact.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
