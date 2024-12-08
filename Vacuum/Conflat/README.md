# Conflat (ISO 3669) components

## Non rotatable flanges

```CFFlange.FCStd``` contains:

* A standard flange blank for all standardized sizes
* A tapped flange blank for all standardized sizes
* A standard weld flange blank for all standardized sizes
* A tapped flange blank for all standardized sizes

To change parameters just use the lookup table index in the configuration table/spreadsheet property

| Blank | Blank tapped | Weld | Weld tapped |
| --- | --- | --- | --- |
| ![](https://raw.githubusercontent.com/tspspi/freecadModel/master/Vacuum/Conflat/CFFlange_BlankFlange_NonRotatable02.png) | ![](https://raw.githubusercontent.com/tspspi/freecadModel/master/Vacuum/Conflat/CFFlange_BlankFlange_NonRotatable_Tapped02.png) | ![](https://raw.githubusercontent.com/tspspi/freecadModel/master/Vacuum/Conflat/CFFlange_WeldFlange_NonRotatable02.png) | ![](https://raw.githubusercontent.com/tspspi/freecadModel/master/Vacuum/Conflat/CFFlange_WeldFlange_NonRotatable_Tapped02.png) |
| ![](https://raw.githubusercontent.com/tspspi/freecadModel/master/Vacuum/Conflat/CFFlange_BlankFlange_NonRotatable01.png) | ![](https://raw.githubusercontent.com/tspspi/freecadModel/master/Vacuum/Conflat/CFFlange_BlankFlange_NonRotatable_Tapped01.png) | ![](https://raw.githubusercontent.com/tspspi/freecadModel/master/Vacuum/Conflat/CFFlange_WeldFlange_NonRotatable01.png) | ![](https://raw.githubusercontent.com/tspspi/freecadModel/master/Vacuum/Conflat/CFFlange_WeldFlange_NonRotatable_Tapped01.png) |

## Non rotateable O-Ring flanges

Those are non standard deviations of the Conflat design. It utilizes a groove for an O-Ring instead
of the knife edge. Those are designed for high vacuum applications that do not require baking. In those
cases one can utilize simple O-Ring based gaskets instead of copper or aluminum gaskets. This allows
for way simpler manufacturing (no specialized tools, no lathes required).

```CFFlange_NoKnife.FCStd``` contains:

* A flange with groove for an O-Ring instead of the knife edge
* A tapped flange blank with an O-Ring instead of the knife edge
* A weld flange with groove for an O-Ring instead of the knife edge
* A tapped weld flange with groove for an O-Ring instead of the knife edge

| Blank | Blank tapped | Weld | Weld tapped |
| --- | --- | --- | --- |
| ![](https://raw.githubusercontent.com/tspspi/freecadModel/master/Vacuum/Conflat/CFFlange_BlankFlange_NonRotatable_ORing01.png) | ![](https://raw.githubusercontent.com/tspspi/freecadModel/master/Vacuum/Conflat/CFFlange_BlankFlange_NonRotatable_Tapped_ORing01.png) | ![](https://raw.githubusercontent.com/tspspi/freecadModel/master/Vacuum/Conflat/CFFlange_WeldFlange_NonRotatable_ORing01.png) | ![](https://raw.githubusercontent.com/tspspi/freecadModel/master/Vacuum/Conflat/CFFlange_WeldFlange_NonRotatable_Tapped_ORing01.png) |




## Straight pipe

Parameterized models of pipes with weld flanges on both sides.

| File | Type | Rendering |
| --- | --- | --- |
| ```CFPipeStraight_NonRotatable.FCStd``` | Non rotatable parameterized | ![](https://raw.githubusercontent.com/tspspi/freecadModel/master/Vacuum/Conflat/CFPipeStraight_NonRotatable_01.png) |
