# material-icon-base
`material-icon-base.svg` is a template that you can use to design your next Material Design icon. It tries to follow the [guidelines](http://www.google.com/design/spec/style/icons.html#icons-product-icons) published by Google.

## How to use it

1.  Select your base shape: square, circle, vertical rectangle or horizontal rectangle.
    
    I've included a geometrically compliant object for each. Remove the ones you don't need from the `Material Background` layer.
    
2.  Add your foreground to the `Material Foreground` layer and apply drop shadows to it.
    
    In Inkscape, Go to `Filters > Shadows and Glows > Drop Shadow…` and select:
    
    |Property         |Value |
    |:----------------|-----:|
    |Blur radius      |6.0 px|
    |Opacity          |20%   |
    |Horizontal offset|0.0 px|
    |Vertical offset  |6.0 px|
    
    The white square is an example.
    
3.  Add tinted and shaded edges to each object.
    
    I haven't found an efficient way to do this in Inkscape, but here's the workaround I use:
    
    1. Duplicate the object (`^D` in Inkscape) and place the duplicate object just behind the original.
    2. Apply the tinted colour as a fill to the duplicate.
    3. Move the duplicate 1 pixel up by increasing its Y property.
    
    Follow a similar route for the shaded edge. You can find the recommended colour values [here](http://www.google.com/design/spec/style/icons.html#icons-product-icons).
    
4.  Make the `Finish` layer visible.
5.  Save the icon. The default resolution is xxxhdpi. Scale down as per your needs.
