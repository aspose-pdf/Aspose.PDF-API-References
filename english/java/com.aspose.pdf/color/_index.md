---
title: Color
second_title: Aspose.PDF for Java API Reference
description: Represents class for color value which can be expressed in different color space.
type: docs
weight: 62
url: /java/com.aspose.pdf/color/
---
**Inheritance:**
java.lang.Object
```
public final class Color
```

Represents class for color value which can be expressed in different color space.
## Constructors

| Constructor | Description |
| --- | --- |
| [Color()](#Color--) | Default constructor. |
| [Color(double[] vector)](#Color-double---) | Constructor |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) | Represents empty color. |
## Methods

| Method | Description |
| --- | --- |
| [getA()](#getA--) | Gets the alpha component value |
| [getData()](#getData--) | Color value. |
| [getColorSpace()](#getColorSpace--) | Gets color space that the color represents. |
| [deepClone()](#deepClone--) | Clones this instance |
| [parse(String value)](#parse-java.lang.String-) | Extracts color components from the string. |
| [toString()](#toString--) | Converts to string. |
| [toRgb()](#toRgb--) | Converts color into rgb. |
| [fromRgb(Color color)](#fromRgb-java.awt.Color-) | Gets valid pdf Color object from java.awt.Color value. |
| [fromArgb(int r, int g, int b)](#fromArgb-int-int-int-) | Gets valid pdf Color object from RGB color components. |
| [fromArgb(int a, int r, int g, int b)](#fromArgb-int-int-int-int-) | Gets valid pdf Color object from RGB color components. |
| [fromRgb(double r, double g, double b)](#fromRgb-double-double-double-) | Gets valid pdf Color object from RGB color components. |
| [fromGray(double g)](#fromGray-double-) | Gets valid pdf Color object from Gray color component. |
| [fromCmyk(double c, double m, double y, double k)](#fromCmyk-double-double-double-double-) | Gets valid pdf Color object from RGB color components. |
| [hashCode()](#hashCode--) | Returns a hash code value for the object. |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns true if two Colors are equal. |
| [op_Equality(Color x, Color y)](#op-Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Returns true if two Colors are equal. |
| [op_Inequality(Color x, Color y)](#op-Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Returns true if two Colors are not equal. |
| [getPatternColorSpace()](#getPatternColorSpace--) | Gets a object that indicates the pattern colorspace. |
| [setPatternColorSpace(PatternColorSpace value)](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | Sets a object that indicates the pattern colorspace. |
| [getTransparent()](#getTransparent--) | Gets a system-defined color. |
| [getAliceBlue()](#getAliceBlue--) | Gets a system-defined color that has an ARGB value of \#FFF0F8FF. |
| [getAntiqueWhite()](#getAntiqueWhite--) | Gets a system-defined color that has an ARGB value of \#FFFAEBD7. |
| [getAqua()](#getAqua--) | Gets a system-defined color that has an ARGB value of \#FF00FFFF. |
| [getAquamarine()](#getAquamarine--) | Gets a system-defined color that has an ARGB value of \#FF7FFFD4. |
| [getAzure()](#getAzure--) | Gets a system-defined color that has an ARGB value of \#FFF0FFFF. |
| [getBeige()](#getBeige--) | Gets a system-defined color that has an ARGB value of \#FFF5F5DC. |
| [getBisque()](#getBisque--) | Gets a system-defined color that has an ARGB value of \#FFFFE4C4. |
| [getBlack()](#getBlack--) | Gets a system-defined color that has an ARGB value of \#FF000000. |
| [getBlanchedAlmond()](#getBlanchedAlmond--) | Gets a system-defined color that has an ARGB value of \#FFFFEBCD. |
| [getBlue()](#getBlue--) | Gets a system-defined color that has an ARGB value of \#FF0000FF. |
| [getBlueViolet()](#getBlueViolet--) | Gets a system-defined color that has an ARGB value of \#FF8A2BE2. |
| [getBrown()](#getBrown--) | Gets a system-defined color that has an ARGB value of \#FFA52A2A. |
| [getBurlyWood()](#getBurlyWood--) | Gets a system-defined color that has an ARGB value of \#FFDEB887. |
| [getCadetBlue()](#getCadetBlue--) | Gets a system-defined color that has an ARGB value of \#FF5F9EA0. |
| [getChartreuse()](#getChartreuse--) | Gets a system-defined color that has an ARGB value of \#FF7FFF00. |
| [getChocolate()](#getChocolate--) | Gets a system-defined color that has an ARGB value of \#FFD2691E. |
| [getCoral()](#getCoral--) | Gets a system-defined color that has an ARGB value of \#FFFF7F50. |
| [getCornflowerBlue()](#getCornflowerBlue--) | Gets a system-defined color that has an ARGB value of \#FF6495ED. |
| [getCornsilk()](#getCornsilk--) | Gets a system-defined color that has an ARGB value of \#FFFFF8DC. |
| [getCrimson()](#getCrimson--) | Gets a system-defined color that has an ARGB value of \#FFDC143C. |
| [getCyan()](#getCyan--) | Gets a system-defined color that has an ARGB value of \#FF00FFFF. |
| [getDarkBlue()](#getDarkBlue--) | Gets a system-defined color that has an ARGB value of \#FF00008B. |
| [getDarkCyan()](#getDarkCyan--) | Gets a system-defined color that has an ARGB value of \#FF008B8B. |
| [getDarkGoldenrod()](#getDarkGoldenrod--) | Gets a system-defined color that has an ARGB value of \#FFB8860B. |
| [getDarkGray()](#getDarkGray--) | Gets a system-defined color that has an ARGB value of \#FFA9A9A9. |
| [getDarkGreen()](#getDarkGreen--) | Gets a system-defined color that has an ARGB value of \#FF006400. |
| [getDarkKhaki()](#getDarkKhaki--) | Gets a system-defined color that has an ARGB value of \#FFBDB76B. |
| [getDarkMagenta()](#getDarkMagenta--) | Gets a system-defined color that has an ARGB value of \#FF8B008B. |
| [getDarkOliveGreen()](#getDarkOliveGreen--) | Gets a system-defined color that has an ARGB value of \#FF556B2F. |
| [getDarkOrange()](#getDarkOrange--) | Gets a system-defined color that has an ARGB value of \#FFFF8C00. |
| [getDarkOrchid()](#getDarkOrchid--) | Gets a system-defined color that has an ARGB value of \#FF9932CC. |
| [getDarkRed()](#getDarkRed--) | Gets a system-defined color that has an ARGB value of \#FF8B0000. |
| [getDarkSalmon()](#getDarkSalmon--) | Gets a system-defined color that has an ARGB value of \#FFE9967A. |
| [getDarkSeaGreen()](#getDarkSeaGreen--) | Gets a system-defined color that has an ARGB value of \#FF8FBC8F. |
| [getDarkSlateBlue()](#getDarkSlateBlue--) | Gets a system-defined color that has an ARGB value of \#FF483D8B. |
| [getDarkSlateGray()](#getDarkSlateGray--) | Gets a system-defined color that has an ARGB value of \#FF2F4F4F. |
| [getDarkTurquoise()](#getDarkTurquoise--) | Gets a system-defined color that has an ARGB value of \#FF00CED1. |
| [getDarkViolet()](#getDarkViolet--) | Gets a system-defined color that has an ARGB value of \#FF9400D3. |
| [getDeepPink()](#getDeepPink--) | Gets a system-defined color that has an ARGB value of \#FFFF1493. |
| [getDeepSkyBlue()](#getDeepSkyBlue--) | Gets a system-defined color that has an ARGB value of \#FF00BFFF. |
| [getDimGray()](#getDimGray--) | Gets a system-defined color that has an ARGB value of \#FF696969. |
| [getDodgerBlue()](#getDodgerBlue--) | Gets a system-defined color that has an ARGB value of \#FF1E90FF. |
| [getFirebrick()](#getFirebrick--) | Gets a system-defined color that has an ARGB value of \#FFB22222. |
| [getFloralWhite()](#getFloralWhite--) | Gets a system-defined color that has an ARGB value of \#FFFFFAF0. |
| [getForestGreen()](#getForestGreen--) | Gets a system-defined color that has an ARGB value of \#FF228B22. |
| [getFuchsia()](#getFuchsia--) | Gets a system-defined color that has an ARGB value of \#FFFF00FF. |
| [getGainsboro()](#getGainsboro--) | Gets a system-defined color that has an ARGB value of \#FFDCDCDC. |
| [getGhostWhite()](#getGhostWhite--) | Gets a system-defined color that has an ARGB value of \#FFF8F8FF. |
| [getGold()](#getGold--) | Gets a system-defined color that has an ARGB value of \#FFFFD700. |
| [getGoldenrod()](#getGoldenrod--) | Gets a system-defined color that has an ARGB value of \#FFDAA520. |
| [getGray()](#getGray--) | Gets a system-defined color that has an ARGB value of \#FF808080. |
| [getGreen()](#getGreen--) | Gets a system-defined color that has an ARGB value of \#FF008000. |
| [getGreenYellow()](#getGreenYellow--) | Gets a system-defined color that has an ARGB value of \#FFADFF2F. |
| [getHoneydew()](#getHoneydew--) | Gets a system-defined color that has an ARGB value of \#FFF0FFF0. |
| [getHotPink()](#getHotPink--) | Gets a system-defined color that has an ARGB value of \#FFFF69B4. |
| [getIndianRed()](#getIndianRed--) | Gets a system-defined color that has an ARGB value of \#FFCD5C5C. |
| [getIndigo()](#getIndigo--) | Gets a system-defined color that has an ARGB value of \#FF4B0082. |
| [getIvory()](#getIvory--) | Gets a system-defined color that has an ARGB value of \#FFFFFFF0. |
| [getKhaki()](#getKhaki--) | Gets a system-defined color that has an ARGB value of \#FFF0E68C. |
| [getLavender()](#getLavender--) | Gets a system-defined color that has an ARGB value of \#FFE6E6FA. |
| [getLavenderBlush()](#getLavenderBlush--) | Gets a system-defined color that has an ARGB value of \#FFFFF0F5. |
| [getLawnGreen()](#getLawnGreen--) | Gets a system-defined color that has an ARGB value of \#FF7CFC00. |
| [getLemonChiffon()](#getLemonChiffon--) | Gets a system-defined color that has an ARGB value of \#FFFFFACD. |
| [getLightBlue()](#getLightBlue--) | Gets a system-defined color that has an ARGB value of \#FFADD8E6. |
| [getLightCoral()](#getLightCoral--) | Gets a system-defined color that has an ARGB value of \#FFF08080. |
| [getLightCyan()](#getLightCyan--) | Gets a system-defined color that has an ARGB value of \#FFE0FFFF. |
| [getLightGoldenrodYellow()](#getLightGoldenrodYellow--) | Gets a system-defined color that has an ARGB value of \#FFFAFAD2. |
| [getLightGreen()](#getLightGreen--) | Gets a system-defined color that has an ARGB value of \#FF90EE90. |
| [getLightGray()](#getLightGray--) | Gets a system-defined color that has an ARGB value of \#FFD3D3D3. |
| [getLightPink()](#getLightPink--) | Gets a system-defined color that has an ARGB value of \#FFFFB6C1. |
| [getLightSalmon()](#getLightSalmon--) | Gets a system-defined color that has an ARGB value of \#FFFFA07A. |
| [getLightSeaGreen()](#getLightSeaGreen--) | Gets a system-defined color that has an ARGB value of \#FF20B2AA. |
| [getLightSkyBlue()](#getLightSkyBlue--) | Gets a system-defined color that has an ARGB value of \#FF87CEFA. |
| [getLightSlateGray()](#getLightSlateGray--) | Gets a system-defined color that has an ARGB value of \#FF778899. |
| [getLightSteelBlue()](#getLightSteelBlue--) | Gets a system-defined color that has an ARGB value of \#FFB0C4DE. |
| [getLightYellow()](#getLightYellow--) | Gets a system-defined color that has an ARGB value of \#FFFFFFE0. |
| [getLime()](#getLime--) | Gets a system-defined color that has an ARGB value of \#FF00FF00. |
| [getLimeGreen()](#getLimeGreen--) | Gets a system-defined color that has an ARGB value of \#FF32CD32. |
| [getLinen()](#getLinen--) | Gets a system-defined color that has an ARGB value of \#FFFAF0E6. |
| [getMagenta()](#getMagenta--) | Gets a system-defined color that has an ARGB value of \#FFFF00FF. |
| [getMaroon()](#getMaroon--) | Gets a system-defined color that has an ARGB value of \#FF800000. |
| [getMediumAquamarine()](#getMediumAquamarine--) | Gets a system-defined color that has an ARGB value of \#FF66CDAA. |
| [getMediumBlue()](#getMediumBlue--) | Gets a system-defined color that has an ARGB value of \#FF0000CD. |
| [getMediumOrchid()](#getMediumOrchid--) | Gets a system-defined color that has an ARGB value of \#FFBA55D3. |
| [getMediumPurple()](#getMediumPurple--) | Gets a system-defined color that has an ARGB value of \#FF9370DB. |
| [getMediumSeaGreen()](#getMediumSeaGreen--) | Gets a system-defined color that has an ARGB value of \#FF3CB371. |
| [getMediumSlateBlue()](#getMediumSlateBlue--) | Gets a system-defined color that has an ARGB value of \#FF7B68EE. |
| [getMediumSpringGreen()](#getMediumSpringGreen--) | Gets a system-defined color that has an ARGB value of \#FF00FA9A. |
| [getMediumTurquoise()](#getMediumTurquoise--) | Gets a system-defined color that has an ARGB value of \#FF48D1CC. |
| [getMediumVioletRed()](#getMediumVioletRed--) | Gets a system-defined color that has an ARGB value of \#FFC71585. |
| [getMidnightBlue()](#getMidnightBlue--) | Gets a system-defined color that has an ARGB value of \#FF191970. |
| [getMintCream()](#getMintCream--) | Gets a system-defined color that has an ARGB value of \#FFF5FFFA. |
| [getMistyRose()](#getMistyRose--) | Gets a system-defined color that has an ARGB value of \#FFFFE4E1. |
| [getMoccasin()](#getMoccasin--) | Gets a system-defined color that has an ARGB value of \#FFFFE4B5. |
| [getNavajoWhite()](#getNavajoWhite--) | Gets a system-defined color that has an ARGB value of \#FFFFDEAD. |
| [getNavy()](#getNavy--) | Gets a system-defined color that has an ARGB value of \#FF000080. |
| [getOldLace()](#getOldLace--) | Gets a system-defined color that has an ARGB value of \#FFFDF5E6. |
| [getOlive()](#getOlive--) | Gets a system-defined color that has an ARGB value of \#FF808000. |
| [getOliveDrab()](#getOliveDrab--) | Gets a system-defined color that has an ARGB value of \#FF6B8E23. |
| [getOrange()](#getOrange--) | Gets a system-defined color that has an ARGB value of \#FFFFA500. |
| [getOrangeRed()](#getOrangeRed--) | Gets a system-defined color that has an ARGB value of \#FFFF4500. |
| [getOrchid()](#getOrchid--) | Gets a system-defined color that has an ARGB value of \#FFDA70D6. |
| [getPaleGoldenrod()](#getPaleGoldenrod--) | Gets a system-defined color that has an ARGB value of \#FFEEE8AA. |
| [getPaleGreen()](#getPaleGreen--) | Gets a system-defined color that has an ARGB value of \#FF98FB98. |
| [getPaleTurquoise()](#getPaleTurquoise--) | Gets a system-defined color that has an ARGB value of \#FFAFEEEE. |
| [getPaleVioletRed()](#getPaleVioletRed--) | Gets a system-defined color that has an ARGB value of \#FFDB7093. |
| [getPapayaWhip()](#getPapayaWhip--) | Gets a system-defined color that has an ARGB value of \#FFFFEFD5. |
| [getPeachPuff()](#getPeachPuff--) | Gets a system-defined color that has an ARGB value of \#FFFFDAB9. |
| [getPeru()](#getPeru--) | Gets a system-defined color that has an ARGB value of \#FFCD853F. |
| [getPink()](#getPink--) | Gets a system-defined color that has an ARGB value of \#FFFFC0CB. |
| [getPlum()](#getPlum--) | Gets a system-defined color that has an ARGB value of \#FFDDA0DD. |
| [getPowderBlue()](#getPowderBlue--) | Gets a system-defined color that has an ARGB value of \#FFB0E0E6. |
| [getPurple()](#getPurple--) | Gets a system-defined color that has an ARGB value of \#FF800080. |
| [getRed()](#getRed--) | Gets a system-defined color that has an ARGB value of \#FFFF0000. |
| [getRosyBrown()](#getRosyBrown--) | Gets a system-defined color that has an ARGB value of \#FFBC8F8F. |
| [getRoyalBlue()](#getRoyalBlue--) | Gets a system-defined color that has an ARGB value of \#FF4169E1. |
| [getSaddleBrown()](#getSaddleBrown--) | Gets a system-defined color that has an ARGB value of \#FF8B4513. |
| [getSalmon()](#getSalmon--) | Gets a system-defined color that has an ARGB value of \#FFFA8072. |
| [getSandyBrown()](#getSandyBrown--) | Gets a system-defined color that has an ARGB value of \#FFF4A460. |
| [getSeaGreen()](#getSeaGreen--) | Gets a system-defined color that has an ARGB value of \#FF2E8B57. |
| [getSeaShell()](#getSeaShell--) | Gets a system-defined color that has an ARGB value of \#FFFFF5EE. |
| [getSienna()](#getSienna--) | Gets a system-defined color that has an ARGB value of \#FFA0522D. |
| [getSilver()](#getSilver--) | Gets a system-defined color that has an ARGB value of \#FFC0C0C0. |
| [getSkyBlue()](#getSkyBlue--) | Gets a system-defined color that has an ARGB value of \#FF87CEEB. |
| [getSlateBlue()](#getSlateBlue--) | Gets a system-defined color that has an ARGB value of \#FF6A5ACD. |
| [getSlateGray()](#getSlateGray--) | Gets a system-defined color that has an ARGB value of \#FF708090. |
| [getSnow()](#getSnow--) | Gets a system-defined color that has an ARGB value of \#FFFFFAFA. |
| [getSpringGreen()](#getSpringGreen--) | Gets a system-defined color that has an ARGB value of \#FF00FF7F. |
| [getSteelBlue()](#getSteelBlue--) | Gets a system-defined color that has an ARGB value of \#FF4682B4. |
| [getTan()](#getTan--) | Gets a system-defined color that has an ARGB value of \#FFD2B48C. |
| [getTeal()](#getTeal--) | Gets a system-defined color that has an ARGB value of \#FF008080. |
| [getThistle()](#getThistle--) | Gets a system-defined color that has an ARGB value of \#FFD8BFD8. |
| [getTomato()](#getTomato--) | Gets a system-defined color that has an ARGB value of \#FFFF6347. |
| [getTurquoise()](#getTurquoise--) | Gets a system-defined color that has an ARGB value of \#FF40E0D0. |
| [getViolet()](#getViolet--) | Gets a system-defined color that has an ARGB value of \#FFEE82EE. |
| [getWheat()](#getWheat--) | Gets a system-defined color that has an ARGB value of \#FFF5DEB3. |
| [getWhite()](#getWhite--) | Gets a system-defined color that has an ARGB value of \#FFFFFFFF. |
| [getWhiteSmoke()](#getWhiteSmoke--) | Gets a system-defined color that has an ARGB value of \#FFF5F5F5. |
| [getYellow()](#getYellow--) | Gets a system-defined color that has an ARGB value of \#FFFFFF00. |
| [getYellowGreen()](#getYellowGreen--) | Gets a system-defined color that has an ARGB value of \#FF9ACD32. |
### Color() {#Color--}
```
public Color()
```


Default constructor.

### Color(double[] vector) {#Color-double---}
```
public Color(double[] vector)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| vector | double[] | double[] array |

### Empty {#Empty}
```
public static final Color Empty
```


Represents empty color.

### getA() {#getA--}
```
public double getA()
```


Gets the alpha component value

**Returns:**
double - double value
### getData() {#getData--}
```
public double[] getData()
```


Color value.

**Returns:**
double[] - array of double values
### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Gets color space that the color represents.

**Returns:**
int - ColorSpace object
### deepClone() {#deepClone--}
```
public Color deepClone()
```


Clones this instance

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object
### parse(String value) {#parse-java.lang.String-}
```
public static Color parse(String value)
```


Extracts color components from the string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value with color component values. |

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object.
### toString() {#toString--}
```
public String toString()
```


Converts to string.

**Returns:**
java.lang.String - String representation of the Color object.
### toRgb() {#toRgb--}
```
public Color toRgb()
```


Converts color into rgb.

**Returns:**
[Color](../../java.awt/color) - Rgb color value.
### fromRgb(Color color) {#fromRgb-java.awt.Color-}
```
public static Color fromRgb(Color color)
```


Gets valid pdf Color object from java.awt.Color value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | java.awt.Color | System.Drawing.Color value. |

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object with each component value in [0..1] range.
### fromArgb(int r, int g, int b) {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```


Gets valid pdf Color object from RGB color components.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r | int | The Red color component (value 0 - 255). |
| g | int | The Green color component (value 0 - 255). |
| b | int | The Blue color component (value 0 - 255). |

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object with each component value in [0..255] range.
### fromArgb(int a, int r, int g, int b) {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```


Gets valid pdf Color object from RGB color components.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | int | The alpha component value (value 0 - 255). |
| r | int | The Red color component (value 0 - 255). |
| g | int | The Green color component (value 0 - 255). |
| b | int | The Blue color component (value 0 - 255). |

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object with each component value in [0..255] range.
### fromRgb(double r, double g, double b) {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```


Gets valid pdf Color object from RGB color components.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| r | double | The Red color component (value 0 - 1). |
| g | double | The Green color component (value 0 - 1). |
| b | double | The Blue color component (value 0 - 1). |

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object with each component value in [0..1] range.
### fromGray(double g) {#fromGray-double-}
```
public static Color fromGray(double g)
```


Gets valid pdf Color object from Gray color component.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| g | double | The Gray color component (value 0 - 1). |

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object with each component value in [0..1] range.
### fromCmyk(double c, double m, double y, double k) {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```


Gets valid pdf Color object from RGB color components.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | double | The Cyan color component (value 0 - 1). |
| m | double | The Magenta color component (value 0 - 1). |
| y | double | The Yellow color component (value 0 - 1). |
| k | double | The Key color component (value 0 - 1). |

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object with each component value in [0..1] range.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code value for the object. This method is supported for the benefit of hash tables such as those provided by java.util.HashMap.

The general contract of  hashCode  is:

 *  Whenever it is invoked on the same object more than once during an execution of a Java application, the  hashCode  method must consistently return the same integer, provided no information used in  equals  comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application.
 *  If two objects are equal according to the  equals(Object)  method, then calling the  hashCode  method on each of the two objects must produce the same integer result.
 *  It is *not* required that if two objects are unequal according to the java.lang.Object\#equals(java.lang.Object)\#equals(java.lang.Object) method, then calling the  hashCode  method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hash tables.

As much as is reasonably practical, the hashCode method defined by class  Object  does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the JavaTMprogramming language.)

**Returns:**
int - a hash code value for this object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns true if two Colors are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Object to compare. |

**Returns:**
boolean - True in case Color objects are equal.
### op_Equality(Color x, Color y) {#op-Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
```
public static boolean op_Equality(Color x, Color y)
```


Returns true if two Colors are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | [Color](../../com.aspose.pdf/color) | First Color object. |
| y | [Color](../../com.aspose.pdf/color) | Second Color object. |

**Returns:**
boolean - True in case Color objects are equal.
### op_Inequality(Color x, Color y) {#op-Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
```
public static boolean op_Inequality(Color x, Color y)
```


Returns true if two Colors are not equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | [Color](../../com.aspose.pdf/color) | First Color object. |
| y | [Color](../../com.aspose.pdf/color) | Second Color object. |

**Returns:**
boolean - True in case Color objects are not equal.
### getPatternColorSpace() {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```


Gets a object that indicates the pattern colorspace.

Internal usage only

**Returns:**
[PatternColorSpace](../../com.aspose.pdf.drawing/patterncolorspace) - PatternColorSpace object
### setPatternColorSpace(PatternColorSpace value) {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
```
public void setPatternColorSpace(PatternColorSpace value)
```


Sets a object that indicates the pattern colorspace.

Internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PatternColorSpace](../../com.aspose.pdf.drawing/patterncolorspace) | PatternColorSpace object |

### getTransparent() {#getTransparent--}
```
public static Color getTransparent()
```


Gets a system-defined color.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getAliceBlue() {#getAliceBlue--}
```
public static Color getAliceBlue()
```


Gets a system-defined color that has an ARGB value of \#FFF0F8FF.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getAntiqueWhite() {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```


Gets a system-defined color that has an ARGB value of \#FFFAEBD7.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getAqua() {#getAqua--}
```
public static Color getAqua()
```


Gets a system-defined color that has an ARGB value of \#FF00FFFF.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getAquamarine() {#getAquamarine--}
```
public static Color getAquamarine()
```


Gets a system-defined color that has an ARGB value of \#FF7FFFD4.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getAzure() {#getAzure--}
```
public static Color getAzure()
```


Gets a system-defined color that has an ARGB value of \#FFF0FFFF.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getBeige() {#getBeige--}
```
public static Color getBeige()
```


Gets a system-defined color that has an ARGB value of \#FFF5F5DC.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getBisque() {#getBisque--}
```
public static Color getBisque()
```


Gets a system-defined color that has an ARGB value of \#FFFFE4C4.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getBlack() {#getBlack--}
```
public static Color getBlack()
```


Gets a system-defined color that has an ARGB value of \#FF000000.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getBlanchedAlmond() {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```


Gets a system-defined color that has an ARGB value of \#FFFFEBCD.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getBlue() {#getBlue--}
```
public static Color getBlue()
```


Gets a system-defined color that has an ARGB value of \#FF0000FF.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getBlueViolet() {#getBlueViolet--}
```
public static Color getBlueViolet()
```


Gets a system-defined color that has an ARGB value of \#FF8A2BE2.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getBrown() {#getBrown--}
```
public static Color getBrown()
```


Gets a system-defined color that has an ARGB value of \#FFA52A2A.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getBurlyWood() {#getBurlyWood--}
```
public static Color getBurlyWood()
```


Gets a system-defined color that has an ARGB value of \#FFDEB887.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getCadetBlue() {#getCadetBlue--}
```
public static Color getCadetBlue()
```


Gets a system-defined color that has an ARGB value of \#FF5F9EA0.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getChartreuse() {#getChartreuse--}
```
public static Color getChartreuse()
```


Gets a system-defined color that has an ARGB value of \#FF7FFF00.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getChocolate() {#getChocolate--}
```
public static Color getChocolate()
```


Gets a system-defined color that has an ARGB value of \#FFD2691E.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getCoral() {#getCoral--}
```
public static Color getCoral()
```


Gets a system-defined color that has an ARGB value of \#FFFF7F50.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getCornflowerBlue() {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```


Gets a system-defined color that has an ARGB value of \#FF6495ED.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getCornsilk() {#getCornsilk--}
```
public static Color getCornsilk()
```


Gets a system-defined color that has an ARGB value of \#FFFFF8DC.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getCrimson() {#getCrimson--}
```
public static Color getCrimson()
```


Gets a system-defined color that has an ARGB value of \#FFDC143C.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getCyan() {#getCyan--}
```
public static Color getCyan()
```


Gets a system-defined color that has an ARGB value of \#FF00FFFF.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkBlue() {#getDarkBlue--}
```
public static Color getDarkBlue()
```


Gets a system-defined color that has an ARGB value of \#FF00008B.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkCyan() {#getDarkCyan--}
```
public static Color getDarkCyan()
```


Gets a system-defined color that has an ARGB value of \#FF008B8B.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkGoldenrod() {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```


Gets a system-defined color that has an ARGB value of \#FFB8860B.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkGray() {#getDarkGray--}
```
public static Color getDarkGray()
```


Gets a system-defined color that has an ARGB value of \#FFA9A9A9.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkGreen() {#getDarkGreen--}
```
public static Color getDarkGreen()
```


Gets a system-defined color that has an ARGB value of \#FF006400.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkKhaki() {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```


Gets a system-defined color that has an ARGB value of \#FFBDB76B.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkMagenta() {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```


Gets a system-defined color that has an ARGB value of \#FF8B008B.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkOliveGreen() {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```


Gets a system-defined color that has an ARGB value of \#FF556B2F.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkOrange() {#getDarkOrange--}
```
public static Color getDarkOrange()
```


Gets a system-defined color that has an ARGB value of \#FFFF8C00.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkOrchid() {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```


Gets a system-defined color that has an ARGB value of \#FF9932CC.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkRed() {#getDarkRed--}
```
public static Color getDarkRed()
```


Gets a system-defined color that has an ARGB value of \#FF8B0000.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkSalmon() {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```


Gets a system-defined color that has an ARGB value of \#FFE9967A.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkSeaGreen() {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```


Gets a system-defined color that has an ARGB value of \#FF8FBC8F.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkSlateBlue() {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```


Gets a system-defined color that has an ARGB value of \#FF483D8B.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkSlateGray() {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```


Gets a system-defined color that has an ARGB value of \#FF2F4F4F.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkTurquoise() {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```


Gets a system-defined color that has an ARGB value of \#FF00CED1.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDarkViolet() {#getDarkViolet--}
```
public static Color getDarkViolet()
```


Gets a system-defined color that has an ARGB value of \#FF9400D3.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDeepPink() {#getDeepPink--}
```
public static Color getDeepPink()
```


Gets a system-defined color that has an ARGB value of \#FFFF1493.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDeepSkyBlue() {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```


Gets a system-defined color that has an ARGB value of \#FF00BFFF.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDimGray() {#getDimGray--}
```
public static Color getDimGray()
```


Gets a system-defined color that has an ARGB value of \#FF696969.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getDodgerBlue() {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```


Gets a system-defined color that has an ARGB value of \#FF1E90FF.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getFirebrick() {#getFirebrick--}
```
public static Color getFirebrick()
```


Gets a system-defined color that has an ARGB value of \#FFB22222.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getFloralWhite() {#getFloralWhite--}
```
public static Color getFloralWhite()
```


Gets a system-defined color that has an ARGB value of \#FFFFFAF0.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getForestGreen() {#getForestGreen--}
```
public static Color getForestGreen()
```


Gets a system-defined color that has an ARGB value of \#FF228B22.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getFuchsia() {#getFuchsia--}
```
public static Color getFuchsia()
```


Gets a system-defined color that has an ARGB value of \#FFFF00FF.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getGainsboro() {#getGainsboro--}
```
public static Color getGainsboro()
```


Gets a system-defined color that has an ARGB value of \#FFDCDCDC.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getGhostWhite() {#getGhostWhite--}
```
public static Color getGhostWhite()
```


Gets a system-defined color that has an ARGB value of \#FFF8F8FF.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getGold() {#getGold--}
```
public static Color getGold()
```


Gets a system-defined color that has an ARGB value of \#FFFFD700.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getGoldenrod() {#getGoldenrod--}
```
public static Color getGoldenrod()
```


Gets a system-defined color that has an ARGB value of \#FFDAA520.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getGray() {#getGray--}
```
public static Color getGray()
```


Gets a system-defined color that has an ARGB value of \#FF808080.

**Returns:**
[Color](../../com.aspose.pdf/color) - A strcture representing a system-defined color.
### getGreen() {#getGreen--}
```
public static Color getGreen()
```


Gets a system-defined color that has an ARGB value of \#FF008000.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getGreenYellow() {#getGreenYellow--}
```
public static Color getGreenYellow()
```


Gets a system-defined color that has an ARGB value of \#FFADFF2F.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getHoneydew() {#getHoneydew--}
```
public static Color getHoneydew()
```


Gets a system-defined color that has an ARGB value of \#FFF0FFF0.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getHotPink() {#getHotPink--}
```
public static Color getHotPink()
```


Gets a system-defined color that has an ARGB value of \#FFFF69B4.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getIndianRed() {#getIndianRed--}
```
public static Color getIndianRed()
```


Gets a system-defined color that has an ARGB value of \#FFCD5C5C.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getIndigo() {#getIndigo--}
```
public static Color getIndigo()
```


Gets a system-defined color that has an ARGB value of \#FF4B0082.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getIvory() {#getIvory--}
```
public static Color getIvory()
```


Gets a system-defined color that has an ARGB value of \#FFFFFFF0.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getKhaki() {#getKhaki--}
```
public static Color getKhaki()
```


Gets a system-defined color that has an ARGB value of \#FFF0E68C.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLavender() {#getLavender--}
```
public static Color getLavender()
```


Gets a system-defined color that has an ARGB value of \#FFE6E6FA.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLavenderBlush() {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```


Gets a system-defined color that has an ARGB value of \#FFFFF0F5.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLawnGreen() {#getLawnGreen--}
```
public static Color getLawnGreen()
```


Gets a system-defined color that has an ARGB value of \#FF7CFC00.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLemonChiffon() {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```


Gets a system-defined color that has an ARGB value of \#FFFFFACD.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLightBlue() {#getLightBlue--}
```
public static Color getLightBlue()
```


Gets a system-defined color that has an ARGB value of \#FFADD8E6.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLightCoral() {#getLightCoral--}
```
public static Color getLightCoral()
```


Gets a system-defined color that has an ARGB value of \#FFF08080.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLightCyan() {#getLightCyan--}
```
public static Color getLightCyan()
```


Gets a system-defined color that has an ARGB value of \#FFE0FFFF.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLightGoldenrodYellow() {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```


Gets a system-defined color that has an ARGB value of \#FFFAFAD2.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLightGreen() {#getLightGreen--}
```
public static Color getLightGreen()
```


Gets a system-defined color that has an ARGB value of \#FF90EE90.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLightGray() {#getLightGray--}
```
public static Color getLightGray()
```


Gets a system-defined color that has an ARGB value of \#FFD3D3D3.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLightPink() {#getLightPink--}
```
public static Color getLightPink()
```


Gets a system-defined color that has an ARGB value of \#FFFFB6C1.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLightSalmon() {#getLightSalmon--}
```
public static Color getLightSalmon()
```


Gets a system-defined color that has an ARGB value of \#FFFFA07A.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLightSeaGreen() {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```


Gets a system-defined color that has an ARGB value of \#FF20B2AA.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLightSkyBlue() {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```


Gets a system-defined color that has an ARGB value of \#FF87CEFA.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLightSlateGray() {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```


Gets a system-defined color that has an ARGB value of \#FF778899.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLightSteelBlue() {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```


Gets a system-defined color that has an ARGB value of \#FFB0C4DE.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLightYellow() {#getLightYellow--}
```
public static Color getLightYellow()
```


Gets a system-defined color that has an ARGB value of \#FFFFFFE0.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLime() {#getLime--}
```
public static Color getLime()
```


Gets a system-defined color that has an ARGB value of \#FF00FF00.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLimeGreen() {#getLimeGreen--}
```
public static Color getLimeGreen()
```


Gets a system-defined color that has an ARGB value of \#FF32CD32.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getLinen() {#getLinen--}
```
public static Color getLinen()
```


Gets a system-defined color that has an ARGB value of \#FFFAF0E6.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMagenta() {#getMagenta--}
```
public static Color getMagenta()
```


Gets a system-defined color that has an ARGB value of \#FFFF00FF.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMaroon() {#getMaroon--}
```
public static Color getMaroon()
```


Gets a system-defined color that has an ARGB value of \#FF800000.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMediumAquamarine() {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```


Gets a system-defined color that has an ARGB value of \#FF66CDAA.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMediumBlue() {#getMediumBlue--}
```
public static Color getMediumBlue()
```


Gets a system-defined color that has an ARGB value of \#FF0000CD.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMediumOrchid() {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```


Gets a system-defined color that has an ARGB value of \#FFBA55D3.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMediumPurple() {#getMediumPurple--}
```
public static Color getMediumPurple()
```


Gets a system-defined color that has an ARGB value of \#FF9370DB.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMediumSeaGreen() {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```


Gets a system-defined color that has an ARGB value of \#FF3CB371.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMediumSlateBlue() {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```


Gets a system-defined color that has an ARGB value of \#FF7B68EE.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMediumSpringGreen() {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```


Gets a system-defined color that has an ARGB value of \#FF00FA9A.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMediumTurquoise() {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```


Gets a system-defined color that has an ARGB value of \#FF48D1CC.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMediumVioletRed() {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```


Gets a system-defined color that has an ARGB value of \#FFC71585.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMidnightBlue() {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```


Gets a system-defined color that has an ARGB value of \#FF191970.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMintCream() {#getMintCream--}
```
public static Color getMintCream()
```


Gets a system-defined color that has an ARGB value of \#FFF5FFFA.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMistyRose() {#getMistyRose--}
```
public static Color getMistyRose()
```


Gets a system-defined color that has an ARGB value of \#FFFFE4E1.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getMoccasin() {#getMoccasin--}
```
public static Color getMoccasin()
```


Gets a system-defined color that has an ARGB value of \#FFFFE4B5.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getNavajoWhite() {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```


Gets a system-defined color that has an ARGB value of \#FFFFDEAD.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getNavy() {#getNavy--}
```
public static Color getNavy()
```


Gets a system-defined color that has an ARGB value of \#FF000080.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getOldLace() {#getOldLace--}
```
public static Color getOldLace()
```


Gets a system-defined color that has an ARGB value of \#FFFDF5E6.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getOlive() {#getOlive--}
```
public static Color getOlive()
```


Gets a system-defined color that has an ARGB value of \#FF808000.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getOliveDrab() {#getOliveDrab--}
```
public static Color getOliveDrab()
```


Gets a system-defined color that has an ARGB value of \#FF6B8E23.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getOrange() {#getOrange--}
```
public static Color getOrange()
```


Gets a system-defined color that has an ARGB value of \#FFFFA500.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getOrangeRed() {#getOrangeRed--}
```
public static Color getOrangeRed()
```


Gets a system-defined color that has an ARGB value of \#FFFF4500.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getOrchid() {#getOrchid--}
```
public static Color getOrchid()
```


Gets a system-defined color that has an ARGB value of \#FFDA70D6.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getPaleGoldenrod() {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```


Gets a system-defined color that has an ARGB value of \#FFEEE8AA.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getPaleGreen() {#getPaleGreen--}
```
public static Color getPaleGreen()
```


Gets a system-defined color that has an ARGB value of \#FF98FB98.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getPaleTurquoise() {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```


Gets a system-defined color that has an ARGB value of \#FFAFEEEE.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getPaleVioletRed() {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```


Gets a system-defined color that has an ARGB value of \#FFDB7093.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getPapayaWhip() {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```


Gets a system-defined color that has an ARGB value of \#FFFFEFD5.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getPeachPuff() {#getPeachPuff--}
```
public static Color getPeachPuff()
```


Gets a system-defined color that has an ARGB value of \#FFFFDAB9.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getPeru() {#getPeru--}
```
public static Color getPeru()
```


Gets a system-defined color that has an ARGB value of \#FFCD853F.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getPink() {#getPink--}
```
public static Color getPink()
```


Gets a system-defined color that has an ARGB value of \#FFFFC0CB.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getPlum() {#getPlum--}
```
public static Color getPlum()
```


Gets a system-defined color that has an ARGB value of \#FFDDA0DD.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getPowderBlue() {#getPowderBlue--}
```
public static Color getPowderBlue()
```


Gets a system-defined color that has an ARGB value of \#FFB0E0E6.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getPurple() {#getPurple--}
```
public static Color getPurple()
```


Gets a system-defined color that has an ARGB value of \#FF800080.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getRed() {#getRed--}
```
public static Color getRed()
```


Gets a system-defined color that has an ARGB value of \#FFFF0000.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getRosyBrown() {#getRosyBrown--}
```
public static Color getRosyBrown()
```


Gets a system-defined color that has an ARGB value of \#FFBC8F8F.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getRoyalBlue() {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```


Gets a system-defined color that has an ARGB value of \#FF4169E1.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getSaddleBrown() {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```


Gets a system-defined color that has an ARGB value of \#FF8B4513.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getSalmon() {#getSalmon--}
```
public static Color getSalmon()
```


Gets a system-defined color that has an ARGB value of \#FFFA8072.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getSandyBrown() {#getSandyBrown--}
```
public static Color getSandyBrown()
```


Gets a system-defined color that has an ARGB value of \#FFF4A460.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getSeaGreen() {#getSeaGreen--}
```
public static Color getSeaGreen()
```


Gets a system-defined color that has an ARGB value of \#FF2E8B57.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getSeaShell() {#getSeaShell--}
```
public static Color getSeaShell()
```


Gets a system-defined color that has an ARGB value of \#FFFFF5EE.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getSienna() {#getSienna--}
```
public static Color getSienna()
```


Gets a system-defined color that has an ARGB value of \#FFA0522D.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getSilver() {#getSilver--}
```
public static Color getSilver()
```


Gets a system-defined color that has an ARGB value of \#FFC0C0C0.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getSkyBlue() {#getSkyBlue--}
```
public static Color getSkyBlue()
```


Gets a system-defined color that has an ARGB value of \#FF87CEEB.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getSlateBlue() {#getSlateBlue--}
```
public static Color getSlateBlue()
```


Gets a system-defined color that has an ARGB value of \#FF6A5ACD.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getSlateGray() {#getSlateGray--}
```
public static Color getSlateGray()
```


Gets a system-defined color that has an ARGB value of \#FF708090.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getSnow() {#getSnow--}
```
public static Color getSnow()
```


Gets a system-defined color that has an ARGB value of \#FFFFFAFA.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getSpringGreen() {#getSpringGreen--}
```
public static Color getSpringGreen()
```


Gets a system-defined color that has an ARGB value of \#FF00FF7F.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getSteelBlue() {#getSteelBlue--}
```
public static Color getSteelBlue()
```


Gets a system-defined color that has an ARGB value of \#FF4682B4.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getTan() {#getTan--}
```
public static Color getTan()
```


Gets a system-defined color that has an ARGB value of \#FFD2B48C.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getTeal() {#getTeal--}
```
public static Color getTeal()
```


Gets a system-defined color that has an ARGB value of \#FF008080.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getThistle() {#getThistle--}
```
public static Color getThistle()
```


Gets a system-defined color that has an ARGB value of \#FFD8BFD8.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getTomato() {#getTomato--}
```
public static Color getTomato()
```


Gets a system-defined color that has an ARGB value of \#FFFF6347.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getTurquoise() {#getTurquoise--}
```
public static Color getTurquoise()
```


Gets a system-defined color that has an ARGB value of \#FF40E0D0.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getViolet() {#getViolet--}
```
public static Color getViolet()
```


Gets a system-defined color that has an ARGB value of \#FFEE82EE.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getWheat() {#getWheat--}
```
public static Color getWheat()
```


Gets a system-defined color that has an ARGB value of \#FFF5DEB3.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getWhite() {#getWhite--}
```
public static Color getWhite()
```


Gets a system-defined color that has an ARGB value of \#FFFFFFFF.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getWhiteSmoke() {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```


Gets a system-defined color that has an ARGB value of \#FFF5F5F5.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getYellow() {#getYellow--}
```
public static Color getYellow()
```


Gets a system-defined color that has an ARGB value of \#FFFFFF00.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
### getYellowGreen() {#getYellowGreen--}
```
public static Color getYellowGreen()
```


Gets a system-defined color that has an ARGB value of \#FF9ACD32.

**Returns:**
[Color](../../com.aspose.pdf/color) - A representing a system-defined color.
