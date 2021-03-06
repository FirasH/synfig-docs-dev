Simple Circle Layer
===================

+--------------+---------------------------------------------------------------------------------------------------------------------------------+
|   Property   |                                                    Path to Property in lottie                                                   |
+==============+=================================================================================================================================+
|    Z depth   |                                          Depends on ordering of layers in lottie format                                         |
+--------------+---------------------------------------------------------------------------------------------------------------------------------+
|    Amount    |                            shapes/fill.json -> “o” -> properties/[value.json OR valueKeyframed.json]                            |
+--------------+---------------------------------------------------------------------------------------------------------------------------------+
| Blend_method |                                       layers/shape.json -> “bm” -> helpers/blendMode.json                                       |
+--------------+---------------------------------------------------------------------------------------------------------------------------------+
|     Color    |                                                 shapes/fill.json -> “ty” = “fl”                                                 |
+--------------+---------------------------------------------------------------------------------------------------------------------------------+
|    Radius    |               shapes/ellipse.json -> "s" -> properties/[multiDimensional.json OR multiDimenstionalKeyframed.json]               |
+--------------+---------------------------------------------------------------------------------------------------------------------------------+
|    Center    | layers/shape.json -> “it” -> shapes/ellipse.json -> “p” -> properties/[multiDimensional.json OR multiDimensionalKeyframed.json] |
+--------------+---------------------------------------------------------------------------------------------------------------------------------+

.. note::
    "it" is used for shapes within groups. When only a single shape is there, "shapes" will be used
    "ty" = "fl" describes that the type of shape used is 'fill'.
