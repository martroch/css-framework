# **MARTA CSS FRAMEWORK**

## **Requirements**
### **Facility**
You must clone the project repository.
### **Contribute**
You must create a pull request to the project.

### **Clases**

The naming convention for element classes follows the BEM pattern:

- .block{}
- .block__element{}
- .block--modifier{}

'.block' represents the first level of an abstraction or component, it is the parent element.
'.block__element' represents a child of the parent element '.block'.
'.block--modifier' represents a different state from '.block'.



### **Scss tags** 
For the quick location of sass files we will use tags in commented text, for example:

- /*------------------------------------*\
    $VARIABLES COLORS
  \*------------------------------------*/


## **SCSS**

The scss files are responsible for providing styles to the html elements, these are organized in the scss/ folder.

### **Repository Structure scss/**

- scss/
  - style.scss
  - components/
    - _buttons.scss
    - _slider.scss
  - layout/
    - _main.scss
    - _header.scss
    - _newsletter.scss
    - _navigation.scss
    - _footer.scss
  - pages/
    - _home.scss
    - _contact.scss
  - site/
    - _site.scss
  - structure/
    - grid.scss
  - utilities/
    - _utilities.scss
    - _functions.scss
    - _mixins.scss
    - _typography.scss
  - variables/
    - _colors.scss
    - _spaces.scss
    - _typography.scss
    - _z-index.scss

  


### **Variables**

The variables that will be used in this project are located in the file scss/variables/... These global variables define the colors, spacing, z-index and fonts for the entire document.

#### **Spaces**
For the spacing, the base unit will be 12px, of which its multiples will be used depending on the spacing that we need.

$unit: 12px;

#### **Color**

The color palette to be used in this project is declared as follows.

$brand
$cta
$secondary
$white
$black
$gradient


#### **Fonts**

$basefont 
$altfont 

#### **Z-index**
Para los valores de z-index se tienen que utilizar los siguientes:

$z-layers: (
  "modal": 90000,
  "over": 900,
  "z-top":           1,
  "z-default":       0,
  "z-below":        -1
);


### **Resources**

The multimedia resources to be used in the web document will be saved in the resources/ folder. There are two subfolders, one for the resources/icons/ icons and one for the resources/img/ images. The images must be optimized and must not exceed a weight of 2MB.

