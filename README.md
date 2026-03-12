# TP RedM Zombies


# How to create a zone?

## X,Y,Z Explanation (Vector3 & Vector2)

You need to understand how the configuration works related to the XYZ parts.

Through a `vector3` or a table form, you can get the X,Y,Z coordinates. 

1. If its a vector3, it will look like this:
`vector3(0, 0, 0) --0, 0, 0 (of vector3, represents X,Y,Z).`

2. If its a table form, it will look like this: `{ x = 0, y = 0, z = 0 .. } -- All that in a table form already represents everything we need without explanation.`

### Vector2

In our configuration file, it requires a vector2, what is a vector2? vector2 is X,Y without the Z included (You get that also from vector3 or a table form).

So when getting the coords from a script, it will show you a vector3, you just change it into a vector2 with just X,Y inside only and not Z and the same if its a table form, you create a vector2 with X,Y that the table provides you. 

### MinZ & MaxZ

The **MinZ** and **MaxZ** that are included on the configuration when creating a zone, it means that it requires the Minimum Z position (lower point) and Maximum Z position (highest point) of a zone. 

To understand better, its like a building, you define the lowest point of the building like a point underneath the player and then the highest point of this building. This is how a zone works, you define the MinZ and MaxZ of the whole zone. You can also use the **Debug** to true to display into you the shape of the created zone and the height. 

## How to create a shape of the zone?

To create a shape of a zone is actually very simple to understand, you have to think it as a paper drawing. Imagine drawing a town, a field, anything, you cannot draw it randomly can you? you need an order to draw a town or a field, because if you draw it in random spots, then the town or a field will not be called that way. This is also how to create a zone, it needs a specific order, like drawing on a paper in order to be made properly. 

I personally suggest (2) ways:

1. SPOONI SPOONER: A very great script that you can just place some barrels with the design you want and get their position one by one (in order like drawing) for the vector2 coords that are required.

2. Coords script: There are plenty of coords script that you can take your player current coords through a command, this is faster for those who have a bit more experience. 
