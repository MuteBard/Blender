# DEV-51, Mirror Modifier
#### Tags: [Mirror Modifier]

    Modifier will duplicate or mirror any object that is applied to it. This is a great tool for whenever you're modeling something that is symmetrical. It means that you dont have to worry about both sides of an object whether it is a plane, a human or a knight.

![](../images/DEV-51/DEV-51-A.png)

    As you initially apply the mirror modifier, it reflects acrss the origin of that object. And therefore it appears that nothing is happening

![](../images/DEV-51/DEV-51-B.png)

    If you move the object origin elsewhere however, you can get the reflection. for example, across the x axis

![](../images/DEV-51/DEV-51-C.png)

![](../images/DEV-51/DEV-51-D.png)

    You can move and transform the original object as you like and the reflected object will respond in turn.

    In order to move them truly in a mirror like fashion, you need to be in edit mode.

![](../images/DEV-51/DEV-51-E.png)

    To make it more flexible to move around, we can create an empty and set it to the origin. and then have that empty be the point of reflection

![](../images/DEV-51/DEV-51-F.png)

    This is great if you have an origin point that wasn't in the true origin

    As one of the options, clipping prevents duplication beyond the origin

![](../images/DEV-51/DEV-51-G.png)

![](../images/DEV-51/DEV-51-H.png)

![](../images/DEV-51/DEV-51-I.png)

    Remember to make something like the knight you need 3 main things: Extruding, loop cuts and scaling


## Creating the Knight

    Starting point 

![](../images/DEV-51/DEV-51-J.png)

![](../images/DEV-51/DEV-51-K.png)

    Cut the Base in half, make sure its across the y axis where it lines up with the reference

![](../images/DEV-51/DEV-51-L.png)

![](../images/DEV-51/DEV-51-M.png)

    Created a new base since the former one would have ran into some issues

![](../images/DEV-51/DEV-51-N.png)

    Now we will add in our Mirror Modifier and then parent the Mirror Origin to the base

![](../images/DEV-51/DEV-51-O.png)

    Fill in the bottom with Alt click and F

![](../images/DEV-51/DEV-51-P.png)

    Set it to wire frame mode

![](../images/DEV-51/DEV-51-Q.png)

    If you are scaling and extruding, be sure to Shift Z while scaling moving vertically

    When using Edge loops, make sure there are no split edges. Sometimes you cant use the faces, you have to use the edges

![](../images/DEV-51/DEV-51-R.png)

![](../images/DEV-51/DEV-51-S.png)

    Almost Done

![](../images/DEV-51/DEV-51-T.png)