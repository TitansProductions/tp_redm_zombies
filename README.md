# TP RedM Zombies


# How to create a zone?

1. You need to understand how the configuration works related to the XYZ parts.

Through a vector3 or a table form, you can get the X,Y,Z coordinates. 

If its a vector3, it will look like this:
`vector3(x, x, x) -- x represents a number`

X, X, X (of vector3, represents X,Y,Z).

In our configuration file, it requires a vector2, what is a vector2? vector2 is X,Y without the Z included (You get that also from vector3 or a table form).

So when getting the coords from a script, it will show you a vector3, you just change it into a vector2 with just X,Y inside only and not Z.
