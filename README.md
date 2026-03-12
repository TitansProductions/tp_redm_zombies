# TP RedM Zombies


# How to create a zone?

## X,Y,Z Explanation (Vector3 & Vector2)

You need to understand how the configuration works related to the XYZ parts.

Through a `vector3` or a table form, you can get the X,Y,Z coordinates. 

1. If its a vector3, it will look like this:
`vector3(0, 0, 0) -- x represents a number`

0, 0, 0 (of vector3, represents X,Y,Z).

2. If its a table form, it will look like this: `{ x = 0, y = 0, z = 0 .. } -- x represents the number`

x = x
y = y
z = z

All that in a table form already represents everything we need without explanation. 

In our configuration file, it requires a vector2, what is a vector2? vector2 is X,Y without the Z included (You get that also from vector3 or a table form).

So when getting the coords from a script, it will show you a vector3, you just change it into a vector2 with just X,Y inside only and not Z.
