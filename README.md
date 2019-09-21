# **Polymorphism- _Problem 03: Shapes_**
## **Problem 03**
## **_Shapes_**
> _**NOTE:**_ Creating a public _**StartUp**_ class with the namescape _**Shapes**_.  

Create a class hierarchy, starting with _**abstract**_ class Shape:
* **Abstract methods** :
  * CalculatePerimeter(): double
  * CalculateArea(): double
* **Virtual methods**:
  * Draw(): string

Extend the Shape class with two children:
* **Rectangle**
* **Circle**

Ech of them need to have:
* **Fields:**
  *  height and width for Rectangle
  *  radius for circle
* **Encapsulation for these fields**
* ** A public constructor**
* **Concrete methods for calculations (perimeter and ares)**
* **Override methods for drawing**

## **Solution**
1. Create a folder with name **_Models_** to contain the sub-class.
2. Create _**Shape**_ class with two _**Abstract methods**_ (CalculatePerimeter() and CalculateArea) and one _**virtual methods**_(Draw()) shown as figure.  
   ![Imgur](https://i.imgur.com/hvIN0Px.png)  

3. Create two childrens of _**Shape**_ class are _**Rectangle**_ and _**Circle**_.
* In each class have public constuctors, concrete methods for calculation perimeter and area, and override methods for drawing.  
    * Rectangle  
    ![Imgur](https://i.imgur.com/5VOppk9.png)  
    * Circle  
    * ![Imgur](https://i.imgur.com/vfMYrgQ.png)  
* Within _**Rectangle**_ that contain height and width.  
  ![Imgur](https://i.imgur.com/fHCpNmL.png) 

* Within _**Circle**_ that contain radius.  
  ![Imgur](https://i.imgur.com/3tQnEZW.png)
   