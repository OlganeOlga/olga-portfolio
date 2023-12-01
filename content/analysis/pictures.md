---
Title: Pictures
Date: 1-1-1
Template: analysis
---

Bilder på olika enheter
=======================
# Laddar in bilden som vanligt
![Leaf]({{ assets_url }}/img/leaf_256x256.png)

# Laddar in bilden via Cimage
![Leaf](%assets_url%/img/leaf_256x256.png)

Skriv en eller två rader om vad uppgiften handlar om.

# Olika storlekar
Leaf 150x150![Leaf 150x150](image/leaf_256x256.png?w=150&h=150)
Another Leaf 150x150![Another Leaf 150x150](image/leaf_256x256.png?w=150)
Leaf 1500x1500![Leaf 1500x1500](image/leaf_256x256.png?w=1500&h=1500)

Change size:
===========
Leaf stretched![Leaf stretched](image/leaf_256x256.png?h=250&w=50&stretch)
Leaf croped![Leaf croped](image/leaf_256x256.png?h=250&w=50&crop-to-fit)

Leaf 25%![Leaf for logo](image/leaf_256x256.png?width=25%)

# bescharning/ crop

Top -> ![Leaf](image/leaf_256x256.png?area=50,0,0,0)
Left -> ![Leaf](image/leaf_256x256.png?area=0,50,0,0)
Bottom -> ![Leaf](image/leaf_256x256.png?area=0,0,50,0)
 ______ ---------------- Right -> ![Leaf](image/leaf_256x256.png?area=0,0,0,50)

 Specific: ![Leaf](image/leaf_256x256.png?crop=50,50,100,100)

#Changefile format
 header.jpg![header](image/header.jpg?width=50%&save-as=jpg)
header.png![header](image/header.jpg?width=50%&save-as=png)
header.gif![Leaf](image/header.jpg?width=50%&save-as=gif)

#chenge file veight:
![Leaf](image/header.jpg?width=100%)
![Leaf](image/header.jpg?width=100%&q=100)

#Filter:

Lighten	?convolve=lighten	![Leaf](image/header.jpg?width=50%&convolve=lighten)
Darken	?convolve=darken	![Leaf](image/header.jpg?width=50%&convolve=darken)
Blur	?blur	![Leaf](image/header.jpg?width=50%&blur)
Grayscale	?f=grayscale	![Leaf](image/header.jpg?width=50%&f=grayscale)
Brightness	?f=brightness,VALUE	![Leaf](image/header.jpg?width=50%&f=brightness,50)
Contrast	?f=constrast,VALUE	![Leaf](image/header.jpg?width=50%&f=contrast,50)

Felsökning
-----------
Ibland kan något gå fel eller inte fungera som man vill. En bra start är att lägga på flaggan ?nc som står för no-cache. Den ser till att skapa om bilden ifall något i cachen skulle gått fel.

Nästa steg är att lägga på ?v flaggan, som ger oss verbose output. Den kan ta en stund att ladda in och man kan behöva öppna bilden i en ny flik för att få se utskriften.

