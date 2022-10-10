# CSS Border Style 
the border-style property specifies what kind of border to display.
- dotted - Define a dotted border.
- dashed - Define a dashed border.
- solid - Define a solid border.
- double - Define a double border.
- groove - Define a 3d grooved border.the effect depends on the color value.
- ridge - Define a 3d border .the effect depends on the border-color value.
- inset - Define a 3d inset border .the effect depends on the border-color value.
- outset - Define a 3d outset border. the effect depends on the border-color value.
- none - Define no border.
- hidden -Define a hidden border.
> p.dotted {border-style: dotted;}

> p.dashed {border-style: dashed;}

> p.solid {border-style: solid;}

> p.inset {border-style: inset;}
~~~Javascript
<!DOCTYPE html>
<head>
 <style>
    p.dotted {
        border-style:dotted;
    }
 </style>
</head>
<body>
  <p> Hello World! </p>
</body>
</html>
~~~