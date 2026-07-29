---
title: "لون"
linktitle: "لون"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة لقيمة اللون التي يمكن التعبير عنها في فضاءات ألوان مختلفة."
type: docs
weight: 670
url: /ar/java/com.aspose.pdf/color/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Color

```
public final class Color extends Object
```

يمثل فئة لقيمة اللون التي يمكن التعبير عنها في فضاءات ألوان مختلفة.

## الحقول

| حقل | الوصف |
| --- | --- |
| [Default](#Default) | يمثل اللون الافتراضي. |
| [Empty](#Empty) | يمثل لونًا فارغًا. |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Color](#Color--) | الباني الافتراضي. |
| [Color](#Color-double:A-) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone](#deepClone--) | ينسخ هذه الحالة |
| [equals](#equals-java.lang.Object-) | يرجع true إذا كان اللونان متساويين. |
| [fromArgb](#fromArgb-int-int-int-) | يحصل على كائن Color صالح من مكوّنات اللون RGB. |
| [fromArgb](#fromArgb-int-int-int-int-) | يحصل على كائن Color صالح من مكوّنات اللون RGB. |
| [fromCmyk](#fromCmyk-double-double-double-double-) | يحصل على كائن Color صالح من مكوّنات اللون CMYK. |
| [fromGray](#fromGray-double-) | يحصل على كائن Color صالح من مكوّن اللون الرمادي. |
| [fromRgb](#fromRgb-java.awt.Color-) | يحصل على كائن Color صالح من قيمة java.awt.Color. |
| [fromRgb](#fromRgb-double-double-double-) | يحصل على كائن Color صالح من مكوّنات اللون RGB. |
| [getA](#getA--) | يحصل على قيمة مكوّن alpha |
| [getAliceBlue](#getAliceBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FFF0F8FF. |
| [getAntiqueWhite](#getAntiqueWhite--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFAEBD7. |
| [getAqua](#getAqua--) | يحصل على لون معرف من النظام له قيمة ARGB #FF00FFFF. |
| [getAquamarine](#getAquamarine--) | يحصل على لون معرف من النظام له قيمة ARGB #FF7FFFD4. |
| [getAzure](#getAzure--) | يحصل على لون معرف من النظام له قيمة ARGB #FFF0FFFF. |
| [getBeige](#getBeige--) | يحصل على لون معرف من النظام له قيمة ARGB #FFF5F5DC. |
| [getBisque](#getBisque--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFE4C4. |
| [getBlack](#getBlack--) | يحصل على لون معرف من النظام له قيمة ARGB #FF000000. |
| [getBlanchedAlmond](#getBlanchedAlmond--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFEBCD. |
| [getBlue](#getBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF0000FF. |
| [getBlueViolet](#getBlueViolet--) | يحصل على لون معرف من النظام له قيمة ARGB #FF8A2BE2. |
| [getBrown](#getBrown--) | يحصل على لون معرف من النظام له قيمة ARGB #FFA52A2A. |
| [getBurlyWood](#getBurlyWood--) | يحصل على لون معرف من النظام له قيمة ARGB #FFDEB887. |
| [getCadetBlue](#getCadetBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF5F9EA0. |
| [getChartreuse](#getChartreuse--) | يحصل على لون معرف من النظام له قيمة ARGB #FF7FFF00. |
| [getChocolate](#getChocolate--) | يحصل على لون معرف من النظام له قيمة ARGB #FFD2691E. |
| [getColorSpace](#getColorSpace--) | يحصل على مساحة اللون التي يمثلها اللون. |
| [getCoral](#getCoral--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFF7F50. |
| [getCornflowerBlue](#getCornflowerBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF6495ED. |
| [getCornsilk](#getCornsilk--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFF8DC. |
| [getCrimson](#getCrimson--) | يحصل على لون معرف من النظام له قيمة ARGB #FFDC143C. |
| [getCyan](#getCyan--) | يحصل على لون معرف من النظام له قيمة ARGB #FF00FFFF. |
| [getDarkBlue](#getDarkBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF00008B. |
| [getDarkCyan](#getDarkCyan--) | يحصل على لون معرف من النظام له قيمة ARGB #FF008B8B. |
| [getDarkGoldenrod](#getDarkGoldenrod--) | يحصل على لون معرف من النظام له قيمة ARGB #FFB8860B. |
| [getDarkGray](#getDarkGray--) | يحصل على لون معرف من النظام له قيمة ARGB #FFA9A9A9. |
| [getDarkGreen](#getDarkGreen--) | يحصل على لون معرف من النظام له قيمة ARGB #FF006400. |
| [getDarkKhaki](#getDarkKhaki--) | يحصل على لون معرف من النظام له قيمة ARGB #FFBDB76B. |
| [getDarkMagenta](#getDarkMagenta--) | يحصل على لون معرف من النظام له قيمة ARGB #FF8B008B. |
| [getDarkOliveGreen](#getDarkOliveGreen--) | يحصل على لون معرف من النظام له قيمة ARGB #FF556B2F. |
| [getDarkOrange](#getDarkOrange--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFF8C00. |
| [getDarkOrchid](#getDarkOrchid--) | يحصل على لون معرف من النظام له قيمة ARGB #FF9932CC. |
| [getDarkRed](#getDarkRed--) | يحصل على لون معرف من النظام له قيمة ARGB #FF8B0000. |
| [getDarkSalmon](#getDarkSalmon--) | يحصل على لون معرف من النظام له قيمة ARGB #FFE9967A. |
| [getDarkSeaGreen](#getDarkSeaGreen--) | يحصل على لون معرف من النظام له قيمة ARGB #FF8FBC8F. |
| [getDarkSlateBlue](#getDarkSlateBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF483D8B. |
| [getDarkSlateGray](#getDarkSlateGray--) | يحصل على لون معرف من النظام له قيمة ARGB #FF2F4F4F. |
| [getDarkTurquoise](#getDarkTurquoise--) | يحصل على لون معرف من النظام له قيمة ARGB #FF00CED1. |
| [getDarkViolet](#getDarkViolet--) | يحصل على لون معرف من النظام له قيمة ARGB #FF9400D3. |
| [getData](#getData--) | قيمة اللون. |
| [getDeepPink](#getDeepPink--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFF1493. |
| [getDeepSkyBlue](#getDeepSkyBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF00BFFF. |
| [getDimGray](#getDimGray--) | يحصل على لون معرف من النظام له قيمة ARGB #FF696969. |
| [getDodgerBlue](#getDodgerBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF1E90FF. |
| [getFirebrick](#getFirebrick--) | يحصل على لون معرف من النظام له قيمة ARGB #FFB22222. |
| [getFloralWhite](#getFloralWhite--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFFAF0. |
| [getForestGreen](#getForestGreen--) | يحصل على لون معرف من النظام له قيمة ARGB #FF228B22. |
| [getFuchsia](#getFuchsia--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFF00FF. |
| [getGainsboro](#getGainsboro--) | يحصل على لون معرف من النظام له قيمة ARGB #FFDCDCDC. |
| [getGhostWhite](#getGhostWhite--) | يحصل على لون معرف من النظام له قيمة ARGB #FFF8F8FF. |
| [getGold](#getGold--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFD700. |
| [getGoldenrod](#getGoldenrod--) | يحصل على لون معرف من النظام له قيمة ARGB #FFDAA520. |
| [getGray](#getGray--) | يحصل على لون معرف من النظام له قيمة ARGB #FF808080. |
| [getGreen](#getGreen--) | يحصل على لون معرف من النظام له قيمة ARGB #FF008000. |
| [getGreenYellow](#getGreenYellow--) | يحصل على لون معرف من النظام له قيمة ARGB #FFADFF2F. |
| [getHoneydew](#getHoneydew--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFF0FFF0. |
| [getHotPink](#getHotPink--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFF69B4. |
| [getIndianRed](#getIndianRed--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFCD5C5C. |
| [getIndigo](#getIndigo--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF4B0082. |
| [getIvory](#getIvory--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFFFFF0. |
| [getKhaki](#getKhaki--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFF0E68C. |
| [getLavender](#getLavender--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFE6E6FA. |
| [getLavenderBlush](#getLavenderBlush--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFFF0F5. |
| [getLawnGreen](#getLawnGreen--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF7CFC00. |
| [getLemonChiffon](#getLemonChiffon--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFFFACD. |
| [getLightBlue](#getLightBlue--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFADD8E6. |
| [getLightCoral](#getLightCoral--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFF08080. |
| [getLightCyan](#getLightCyan--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFE0FFFF. |
| [getLightGoldenrodYellow](#getLightGoldenrodYellow--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFAFAD2. |
| [getLightGray](#getLightGray--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFD3D3D3. |
| [getLightGreen](#getLightGreen--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF90EE90. |
| [getLightPink](#getLightPink--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFFB6C1. |
| [getLightSalmon](#getLightSalmon--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFFA07A. |
| [getLightSeaGreen](#getLightSeaGreen--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF20B2AA. |
| [getLightSkyBlue](#getLightSkyBlue--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF87CEFA. |
| [getLightSlateGray](#getLightSlateGray--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF778899. |
| [getLightSteelBlue](#getLightSteelBlue--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFB0C4DE. |
| [getLightYellow](#getLightYellow--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFFFFE0. |
| [getLime](#getLime--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF00FF00. |
| [getLimeGreen](#getLimeGreen--) | يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF32CD32. |
| [getLinen](#getLinen--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFAF0E6. |
| [getMagenta](#getMagenta--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFF00FF. |
| [getMaroon](#getMaroon--) | يحصل على لون معرف من النظام له قيمة ARGB #FF800000. |
| [getMediumAquamarine](#getMediumAquamarine--) | يحصل على لون معرف من النظام له قيمة ARGB #FF66CDAA. |
| [getMediumBlue](#getMediumBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF0000CD. |
| [getMediumOrchid](#getMediumOrchid--) | يحصل على لون معرف من النظام له قيمة ARGB #FFBA55D3. |
| [getMediumPurple](#getMediumPurple--) | يحصل على لون معرف من النظام له قيمة ARGB #FF9370DB. |
| [getMediumSeaGreen](#getMediumSeaGreen--) | يحصل على لون معرف من النظام له قيمة ARGB #FF3CB371. |
| [getMediumSlateBlue](#getMediumSlateBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF7B68EE. |
| [getMediumSpringGreen](#getMediumSpringGreen--) | يحصل على لون معرف من النظام له قيمة ARGB #FF00FA9A. |
| [getMediumTurquoise](#getMediumTurquoise--) | يحصل على لون معرف من النظام له قيمة ARGB #FF48D1CC. |
| [getMediumVioletRed](#getMediumVioletRed--) | يحصل على لون معرف من النظام له قيمة ARGB #FFC71585. |
| [getMidnightBlue](#getMidnightBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF191970. |
| [getMintCream](#getMintCream--) | يحصل على لون معرف من النظام له قيمة ARGB #FFF5FFFA. |
| [getMistyRose](#getMistyRose--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFE4E1. |
| [getMoccasin](#getMoccasin--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFE4B5. |
| [getNavajoWhite](#getNavajoWhite--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFDEAD. |
| [getNavy](#getNavy--) | يحصل على لون معرف من النظام له قيمة ARGB #FF000080. |
| [getOldLace](#getOldLace--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFDF5E6. |
| [getOlive](#getOlive--) | يحصل على لون معرف من النظام له قيمة ARGB #FF808000. |
| [getOliveDrab](#getOliveDrab--) | يحصل على لون معرف من النظام له قيمة ARGB #FF6B8E23. |
| [getOrange](#getOrange--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFA500. |
| [getOrangeRed](#getOrangeRed--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFF4500. |
| [getOrchid](#getOrchid--) | يحصل على لون معرف من النظام له قيمة ARGB #FFDA70D6. |
| [getPaleGoldenrod](#getPaleGoldenrod--) | يحصل على لون معرف من النظام له قيمة ARGB #FFEEE8AA. |
| [getPaleGreen](#getPaleGreen--) | يحصل على لون معرف من النظام له قيمة ARGB #FF98FB98. |
| [getPaleTurquoise](#getPaleTurquoise--) | يحصل على لون معرف من النظام له قيمة ARGB #FFAFEEEE. |
| [getPaleVioletRed](#getPaleVioletRed--) | يحصل على لون معرف من النظام له قيمة ARGB #FFDB7093. |
| [getPapayaWhip](#getPapayaWhip--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFEFD5. |
| [getPatternColorSpace](#getPatternColorSpace--) | يحصل على كائن يشير إلى مساحة ألوان النمط. للاستخدام الداخلي فقط |
| [getPeachPuff](#getPeachPuff--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFDAB9. |
| [getPeru](#getPeru--) | يحصل على لون معرف من النظام له قيمة ARGB #FFCD853F. |
| [getPink](#getPink--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFC0CB. |
| [getPlum](#getPlum--) | يحصل على لون معرف من النظام له قيمة ARGB #FFDDA0DD. |
| [getPowderBlue](#getPowderBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FFB0E0E6. |
| [getPurple](#getPurple--) | يحصل على لون معرف من النظام له قيمة ARGB #FF800080. |
| [getRed](#getRed--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFF0000. |
| [getRosyBrown](#getRosyBrown--) | يحصل على لون معرف من النظام له قيمة ARGB #FFBC8F8F. |
| [getRoyalBlue](#getRoyalBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF4169E1. |
| [getSaddleBrown](#getSaddleBrown--) | يحصل على لون معرف من النظام له قيمة ARGB #FF8B4513. |
| [getSalmon](#getSalmon--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFA8072. |
| [getSandyBrown](#getSandyBrown--) | يحصل على لون معرف من النظام له قيمة ARGB #FFF4A460. |
| [getSeaGreen](#getSeaGreen--) | يحصل على لون معرف من النظام له قيمة ARGB #FF2E8B57. |
| [getSeaShell](#getSeaShell--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFF5EE. |
| [getSienna](#getSienna--) | يحصل على لون معرف من النظام له قيمة ARGB #FFA0522D. |
| [getSilver](#getSilver--) | يحصل على لون معرف من النظام له قيمة ARGB #FFC0C0C0. |
| [getSkyBlue](#getSkyBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF87CEEB. |
| [getSlateBlue](#getSlateBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF6A5ACD. |
| [getSlateGray](#getSlateGray--) | يحصل على لون معرف من النظام له قيمة ARGB #FF708090. |
| [getSnow](#getSnow--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFFAFA. |
| [getSpringGreen](#getSpringGreen--) | يحصل على لون معرف من النظام له قيمة ARGB #FF00FF7F. |
| [getSteelBlue](#getSteelBlue--) | يحصل على لون معرف من النظام له قيمة ARGB #FF4682B4. |
| [getTan](#getTan--) | يحصل على لون معرف من النظام له قيمة ARGB #FFD2B48C. |
| [getTeal](#getTeal--) | يحصل على لون معرف من النظام له قيمة ARGB #FF008080. |
| [getThistle](#getThistle--) | يحصل على لون معرف من النظام له قيمة ARGB #FFD8BFD8. |
| [getTomato](#getTomato--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFF6347. |
| [getTransparent](#getTransparent--) | يحصل على لون معرف من النظام. |
| [getTurquoise](#getTurquoise--) | يحصل على لون معرف من النظام له قيمة ARGB #FF40E0D0. |
| [getViolet](#getViolet--) | يحصل على لون معرف من النظام له قيمة ARGB #FFEE82EE. |
| [getWheat](#getWheat--) | يحصل على لون معرف من النظام له قيمة ARGB #FFF5DEB3. |
| [getWhite](#getWhite--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFFFFF. |
| [getWhiteSmoke](#getWhiteSmoke--) | يحصل على لون معرف من النظام له قيمة ARGB #FFF5F5F5. |
| [getYellow](#getYellow--) | يحصل على لون معرف من النظام له قيمة ARGB #FFFFFF00. |
| [getYellowGreen](#getYellowGreen--) | يحصل على لون معرف من النظام له قيمة ARGB #FF9ACD32. |
| [hashCode](#hashCode--) | إرجاع قيمة رمز تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح بشكل ثابت، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يظل هذا العدد ثابتًا بين تنفيذ تطبيق وآخر من نفس التطبيق. <li>إذا كان كائنان متساويان وفقًا لطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس <em>مطلوبًا</em> أن إذا كان كائنان غير متساويين وفقًا لطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب على المبرمج أن يكون على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون ذلك عمليًا بشكل معقول، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [op_Equality](#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | يرجع true إذا كان اللونان متساويين. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | إرجاع true إذا كان لونان (Colors) غير متساويين. |
| [parse](#parse-java.lang.String-) | يستخرج مكونات اللون من السلسلة. |
| [setPatternColorSpace](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | يضبط كائنًا يشير إلى مساحة ألوان النمط. للاستخدام الداخلي فقط |
| [toRgb](#toRgb--) | يحوّل اللون إلى rgb. |
| [toString](#toString--) | يحوّل إلى سلسلة. |

### Default {#Default}
```
public static final Color Default
```

يمثل اللون الافتراضي.

### Empty {#Empty}
```
public static final Color Empty
```

يمثل لونًا فارغًا.

### Color {#Color--}
```
public Color()
```

الباني الافتراضي.

### Color {#Color-double:A-}
```
public Color(double[] vector)
```

منشئ

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| متجه |  | مصفوفة double[] |

### deepClone {#deepClone--}
```
public Color deepClone()
```

ينسخ هذه الحالة

**Returns:**
كائن Color

### equals {#equals-java.lang.Object-}
يرجع true إذا كان اللونان متساويين.

### fromArgb {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```

يحصل على كائن Color صالح من مكوّنات اللون RGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| r |  | مكوّن اللون الأحمر (القيمة 0 - 255). |
| g |  | مكوّن اللون الأخضر (القيمة 0 - 255). |
| b |  | مكوّن اللون الأزرق (القيمة 0 - 255). |

**Returns:**
كائن Color مع قيمة كل مكوّن في النطاق [0..255].

### fromArgb {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```

يحصل على كائن Color صالح من مكوّنات اللون RGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a |  | قيمة مكوّن ألفا (القيمة 0 - 255). |
| r |  | مكوّن اللون الأحمر (القيمة 0 - 255). |
| g |  | مكوّن اللون الأخضر (القيمة 0 - 255). |
| b |  | مكوّن اللون الأزرق (القيمة 0 - 255). |

**Returns:**
كائن Color مع قيمة كل مكوّن في النطاق [0..255].

### fromCmyk {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```

يحصل على كائن Color صالح من مكوّنات اللون CMYK.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| c |  | مكوّن اللون السماوي (القيمة 0 - 1). |
| m |  | مكوّن اللون الأرجواني (القيمة 0 - 1). |
| y |  | مكوّن اللون الأصفر (القيمة 0 - 1). |
| k |  | مكوّن اللون المفتاح (القيمة 0 - 1). |

**Returns:**
كائن Color مع قيمة كل مكوّن في النطاق [0..1].

### fromGray {#fromGray-double-}
```
public static Color fromGray(double g)
```

يحصل على كائن Color صالح من مكوّن اللون الرمادي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| g |  | مكوّن اللون الرمادي (القيمة 0 - 1). |

**Returns:**
كائن Color مع قيمة كل مكوّن في النطاق [0..1].

### fromRgb {#fromRgb-java.awt.Color-}
يحصل على كائن Color صالح من قيمة java.awt.Color.

### fromRgb {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```

يحصل على كائن Color صالح من مكوّنات اللون RGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| r |  | مكوّن اللون الأحمر (القيمة 0 - 1). |
| g |  | مكوّن اللون الأخضر (القيمة 0 - 1). |
| b |  | مكوّن اللون الأزرق (القيمة 0 - 1). |

**Returns:**
كائن Color مع قيمة كل مكوّن في النطاق [0..1].

### getA {#getA--}
```
public double getA()
```

يحصل على قيمة مكوّن alpha

**Returns:**
قيمة double

### getAliceBlue {#getAliceBlue--}
```
public static Color getAliceBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFF0F8FF.

**Returns:**
A تمثيل لون معرف من النظام.

### getAntiqueWhite {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFAEBD7.

**Returns:**
A تمثيل لون معرف من النظام.

### getAqua {#getAqua--}
```
public static Color getAqua()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF00FFFF.

**Returns:**
A تمثيل لون معرف من النظام.

### getAquamarine {#getAquamarine--}
```
public static Color getAquamarine()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF7FFFD4.

**Returns:**
A تمثيل لون معرف من النظام.

### getAzure {#getAzure--}
```
public static Color getAzure()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFF0FFFF.

**Returns:**
A تمثيل لون معرف من النظام.

### getBeige {#getBeige--}
```
public static Color getBeige()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFF5F5DC.

**Returns:**
A تمثيل لون معرف من النظام.

### getBisque {#getBisque--}
```
public static Color getBisque()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFE4C4.

**Returns:**
A تمثيل لون معرف من النظام.

### getBlack {#getBlack--}
```
public static Color getBlack()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF000000.

**Returns:**
A تمثيل لون معرف من النظام.

### getBlanchedAlmond {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFEBCD.

**Returns:**
A تمثيل لون معرف من النظام.

### getBlue {#getBlue--}
```
public static Color getBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF0000FF.

**Returns:**
A تمثيل لون معرف من النظام.

### getBlueViolet {#getBlueViolet--}
```
public static Color getBlueViolet()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF8A2BE2.

**Returns:**
A تمثيل لون معرف من النظام.

### getBrown {#getBrown--}
```
public static Color getBrown()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFA52A2A.

**Returns:**
A تمثيل لون معرف من النظام.

### getBurlyWood {#getBurlyWood--}
```
public static Color getBurlyWood()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFDEB887.

**Returns:**
A تمثيل لون معرف من النظام.

### getCadetBlue {#getCadetBlue--}
```
public static Color getCadetBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF5F9EA0.

**Returns:**
A تمثيل لون معرف من النظام.

### getChartreuse {#getChartreuse--}
```
public static Color getChartreuse()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF7FFF00.

**Returns:**
A تمثيل لون معرف من النظام.

### getChocolate {#getChocolate--}
```
public static Color getChocolate()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFD2691E.

**Returns:**
A تمثيل لون معرف من النظام.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

يحصل على مساحة اللون التي يمثلها اللون.

**Returns:**
كائن ColorSpace

### getCoral {#getCoral--}
```
public static Color getCoral()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFF7F50.

**Returns:**
A تمثيل لون معرف من النظام.

### getCornflowerBlue {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF6495ED.

**Returns:**
A تمثيل لون معرف من النظام.

### getCornsilk {#getCornsilk--}
```
public static Color getCornsilk()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFF8DC.

**Returns:**
A تمثيل لون معرف من النظام.

### getCrimson {#getCrimson--}
```
public static Color getCrimson()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFDC143C.

**Returns:**
A تمثيل لون معرف من النظام.

### getCyan {#getCyan--}
```
public static Color getCyan()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF00FFFF.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkBlue {#getDarkBlue--}
```
public static Color getDarkBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF00008B.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkCyan {#getDarkCyan--}
```
public static Color getDarkCyan()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF008B8B.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkGoldenrod {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFB8860B.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkGray {#getDarkGray--}
```
public static Color getDarkGray()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFA9A9A9.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkGreen {#getDarkGreen--}
```
public static Color getDarkGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF006400.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkKhaki {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFBDB76B.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkMagenta {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF8B008B.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkOliveGreen {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF556B2F.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkOrange {#getDarkOrange--}
```
public static Color getDarkOrange()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFF8C00.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkOrchid {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF9932CC.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkRed {#getDarkRed--}
```
public static Color getDarkRed()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF8B0000.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkSalmon {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFE9967A.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkSeaGreen {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF8FBC8F.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkSlateBlue {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF483D8B.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkSlateGray {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF2F4F4F.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkTurquoise {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF00CED1.

**Returns:**
A تمثيل لون معرف من النظام.

### getDarkViolet {#getDarkViolet--}
```
public static Color getDarkViolet()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF9400D3.

**Returns:**
A تمثيل لون معرف من النظام.

### getData {#getData--}
```
public double[] getData()
```

قيمة اللون.

**Returns:**
مصفوفة من قيم double.

### getDeepPink {#getDeepPink--}
```
public static Color getDeepPink()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFF1493.

**Returns:**
A تمثيل لون معرف من النظام.

### getDeepSkyBlue {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF00BFFF.

**Returns:**
A تمثيل لون معرف من النظام.

### getDimGray {#getDimGray--}
```
public static Color getDimGray()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF696969.

**Returns:**
A تمثيل لون معرف من النظام.

### getDodgerBlue {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF1E90FF.

**Returns:**
A تمثيل لون معرف من النظام.

### getFirebrick {#getFirebrick--}
```
public static Color getFirebrick()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFB22222.

**Returns:**
A تمثيل لون معرف من النظام.

### getFloralWhite {#getFloralWhite--}
```
public static Color getFloralWhite()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFFAF0.

**Returns:**
A تمثيل لون معرف من النظام.

### getForestGreen {#getForestGreen--}
```
public static Color getForestGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF228B22.

**Returns:**
A تمثيل لون معرف من النظام.

### getFuchsia {#getFuchsia--}
```
public static Color getFuchsia()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFF00FF.

**Returns:**
A تمثيل لون معرف من النظام.

### getGainsboro {#getGainsboro--}
```
public static Color getGainsboro()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFDCDCDC.

**Returns:**
A تمثيل لون معرف من النظام.

### getGhostWhite {#getGhostWhite--}
```
public static Color getGhostWhite()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFF8F8FF.

**Returns:**
A تمثيل لون معرف من النظام.

### getGold {#getGold--}
```
public static Color getGold()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFD700.

**Returns:**
A تمثيل لون معرف من النظام.

### getGoldenrod {#getGoldenrod--}
```
public static Color getGoldenrod()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFDAA520.

**Returns:**
A تمثيل لون معرف من النظام.

### getGray {#getGray--}
```
public static Color getGray()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF808080.

**Returns:**
A بنية تمثّل لون معرف من النظام.

### getGreen {#getGreen--}
```
public static Color getGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF008000.

**Returns:**
A تمثيل لون معرف من النظام.

### getGreenYellow {#getGreenYellow--}
```
public static Color getGreenYellow()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFADFF2F.

**Returns:**
A تمثيل لون معرف من النظام.

### getHoneydew {#getHoneydew--}
```
public static Color getHoneydew()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFF0FFF0.

**Returns:**
A تمثيل لون معرف من النظام.

### getHotPink {#getHotPink--}
```
public static Color getHotPink()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFF69B4.

**Returns:**
A تمثيل لون معرف من النظام.

### getIndianRed {#getIndianRed--}
```
public static Color getIndianRed()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFCD5C5C.

**Returns:**
A تمثيل لون معرف من النظام.

### getIndigo {#getIndigo--}
```
public static Color getIndigo()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF4B0082.

**Returns:**
A تمثيل لون معرف من النظام.

### getIvory {#getIvory--}
```
public static Color getIvory()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFFFFF0.

**Returns:**
A تمثيل لون معرف من النظام.

### getKhaki {#getKhaki--}
```
public static Color getKhaki()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFF0E68C.

**Returns:**
A تمثيل لون معرف من النظام.

### getLavender {#getLavender--}
```
public static Color getLavender()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFE6E6FA.

**Returns:**
A تمثيل لون معرف من النظام.

### getLavenderBlush {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFFF0F5.

**Returns:**
A تمثيل لون معرف من النظام.

### getLawnGreen {#getLawnGreen--}
```
public static Color getLawnGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF7CFC00.

**Returns:**
A تمثيل لون معرف من النظام.

### getLemonChiffon {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFFFACD.

**Returns:**
A تمثيل لون معرف من النظام.

### getLightBlue {#getLightBlue--}
```
public static Color getLightBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFADD8E6.

**Returns:**
A تمثيل لون معرف من النظام.

### getLightCoral {#getLightCoral--}
```
public static Color getLightCoral()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFF08080.

**Returns:**
A تمثيل لون معرف من النظام.

### getLightCyan {#getLightCyan--}
```
public static Color getLightCyan()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFE0FFFF.

**Returns:**
A تمثيل لون معرف من النظام.

### getLightGoldenrodYellow {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFAFAD2.

**Returns:**
A تمثيل لون معرف من النظام.

### getLightGray {#getLightGray--}
```
public static Color getLightGray()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFD3D3D3.

**Returns:**
A تمثيل لون معرف من النظام.

### getLightGreen {#getLightGreen--}
```
public static Color getLightGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF90EE90.

**Returns:**
A تمثيل لون معرف من النظام.

### getLightPink {#getLightPink--}
```
public static Color getLightPink()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFFB6C1.

**Returns:**
A تمثيل لون معرف من النظام.

### getLightSalmon {#getLightSalmon--}
```
public static Color getLightSalmon()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFFA07A.

**Returns:**
A تمثيل لون معرف من النظام.

### getLightSeaGreen {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF20B2AA.

**Returns:**
A تمثيل لون معرف من النظام.

### getLightSkyBlue {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF87CEFA.

**Returns:**
A تمثيل لون معرف من النظام.

### getLightSlateGray {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF778899.

**Returns:**
A تمثيل لون معرف من النظام.

### getLightSteelBlue {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFB0C4DE.

**Returns:**
A تمثيل لون معرف من النظام.

### getLightYellow {#getLightYellow--}
```
public static Color getLightYellow()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FFFFFFE0.

**Returns:**
A تمثيل لون معرف من النظام.

### getLime {#getLime--}
```
public static Color getLime()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF00FF00.

**Returns:**
A تمثيل لون معرف من النظام.

### getLimeGreen {#getLimeGreen--}
```
public static Color getLimeGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB بقيمة #FF32CD32.

**Returns:**
A تمثيل لون معرف من النظام.

### getLinen {#getLinen--}
```
public static Color getLinen()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFAF0E6.

**Returns:**
A تمثيل لون معرف من النظام.

### getMagenta {#getMagenta--}
```
public static Color getMagenta()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFF00FF.

**Returns:**
A تمثيل لون معرف من النظام.

### getMaroon {#getMaroon--}
```
public static Color getMaroon()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF800000.

**Returns:**
A تمثيل لون معرف من النظام.

### getMediumAquamarine {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF66CDAA.

**Returns:**
A تمثيل لون معرف من النظام.

### getMediumBlue {#getMediumBlue--}
```
public static Color getMediumBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF0000CD.

**Returns:**
A تمثيل لون معرف من النظام.

### getMediumOrchid {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFBA55D3.

**Returns:**
A تمثيل لون معرف من النظام.

### getMediumPurple {#getMediumPurple--}
```
public static Color getMediumPurple()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF9370DB.

**Returns:**
A تمثيل لون معرف من النظام.

### getMediumSeaGreen {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF3CB371.

**Returns:**
A تمثيل لون معرف من النظام.

### getMediumSlateBlue {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF7B68EE.

**Returns:**
A تمثيل لون معرف من النظام.

### getMediumSpringGreen {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF00FA9A.

**Returns:**
A تمثيل لون معرف من النظام.

### getMediumTurquoise {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF48D1CC.

**Returns:**
A تمثيل لون معرف من النظام.

### getMediumVioletRed {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFC71585.

**Returns:**
A تمثيل لون معرف من النظام.

### getMidnightBlue {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF191970.

**Returns:**
A تمثيل لون معرف من النظام.

### getMintCream {#getMintCream--}
```
public static Color getMintCream()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFF5FFFA.

**Returns:**
A تمثيل لون معرف من النظام.

### getMistyRose {#getMistyRose--}
```
public static Color getMistyRose()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFE4E1.

**Returns:**
A تمثيل لون معرف من النظام.

### getMoccasin {#getMoccasin--}
```
public static Color getMoccasin()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFE4B5.

**Returns:**
A تمثيل لون معرف من النظام.

### getNavajoWhite {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFDEAD.

**Returns:**
A تمثيل لون معرف من النظام.

### getNavy {#getNavy--}
```
public static Color getNavy()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF000080.

**Returns:**
A تمثيل لون معرف من النظام.

### getOldLace {#getOldLace--}
```
public static Color getOldLace()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFDF5E6.

**Returns:**
A تمثيل لون معرف من النظام.

### getOlive {#getOlive--}
```
public static Color getOlive()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF808000.

**Returns:**
A تمثيل لون معرف من النظام.

### getOliveDrab {#getOliveDrab--}
```
public static Color getOliveDrab()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF6B8E23.

**Returns:**
A تمثيل لون معرف من النظام.

### getOrange {#getOrange--}
```
public static Color getOrange()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFA500.

**Returns:**
A تمثيل لون معرف من النظام.

### getOrangeRed {#getOrangeRed--}
```
public static Color getOrangeRed()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFF4500.

**Returns:**
A تمثيل لون معرف من النظام.

### getOrchid {#getOrchid--}
```
public static Color getOrchid()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFDA70D6.

**Returns:**
A تمثيل لون معرف من النظام.

### getPaleGoldenrod {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFEEE8AA.

**Returns:**
A تمثيل لون معرف من النظام.

### getPaleGreen {#getPaleGreen--}
```
public static Color getPaleGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF98FB98.

**Returns:**
A تمثيل لون معرف من النظام.

### getPaleTurquoise {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFAFEEEE.

**Returns:**
A تمثيل لون معرف من النظام.

### getPaleVioletRed {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFDB7093.

**Returns:**
A تمثيل لون معرف من النظام.

### getPapayaWhip {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFEFD5.

**Returns:**
A تمثيل لون معرف من النظام.

### getPatternColorSpace {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```

يحصل على كائن يشير إلى مساحة ألوان النمط. للاستخدام الداخلي فقط

**Returns:**
كائن PatternColorSpace

### getPeachPuff {#getPeachPuff--}
```
public static Color getPeachPuff()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFDAB9.

**Returns:**
A تمثيل لون معرف من النظام.

### getPeru {#getPeru--}
```
public static Color getPeru()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFCD853F.

**Returns:**
A تمثيل لون معرف من النظام.

### getPink {#getPink--}
```
public static Color getPink()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFC0CB.

**Returns:**
A تمثيل لون معرف من النظام.

### getPlum {#getPlum--}
```
public static Color getPlum()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFDDA0DD.

**Returns:**
A تمثيل لون معرف من النظام.

### getPowderBlue {#getPowderBlue--}
```
public static Color getPowderBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFB0E0E6.

**Returns:**
A تمثيل لون معرف من النظام.

### getPurple {#getPurple--}
```
public static Color getPurple()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF800080.

**Returns:**
A تمثيل لون معرف من النظام.

### getRed {#getRed--}
```
public static Color getRed()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFF0000.

**Returns:**
A تمثيل لون معرف من النظام.

### getRosyBrown {#getRosyBrown--}
```
public static Color getRosyBrown()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFBC8F8F.

**Returns:**
A تمثيل لون معرف من النظام.

### getRoyalBlue {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF4169E1.

**Returns:**
A تمثيل لون معرف من النظام.

### getSaddleBrown {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF8B4513.

**Returns:**
A تمثيل لون معرف من النظام.

### getSalmon {#getSalmon--}
```
public static Color getSalmon()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFA8072.

**Returns:**
A تمثيل لون معرف من النظام.

### getSandyBrown {#getSandyBrown--}
```
public static Color getSandyBrown()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFF4A460.

**Returns:**
A تمثيل لون معرف من النظام.

### getSeaGreen {#getSeaGreen--}
```
public static Color getSeaGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF2E8B57.

**Returns:**
A تمثيل لون معرف من النظام.

### getSeaShell {#getSeaShell--}
```
public static Color getSeaShell()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFF5EE.

**Returns:**
A تمثيل لون معرف من النظام.

### getSienna {#getSienna--}
```
public static Color getSienna()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFA0522D.

**Returns:**
A تمثيل لون معرف من النظام.

### getSilver {#getSilver--}
```
public static Color getSilver()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFC0C0C0.

**Returns:**
A تمثيل لون معرف من النظام.

### getSkyBlue {#getSkyBlue--}
```
public static Color getSkyBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF87CEEB.

**Returns:**
A تمثيل لون معرف من النظام.

### getSlateBlue {#getSlateBlue--}
```
public static Color getSlateBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF6A5ACD.

**Returns:**
A تمثيل لون معرف من النظام.

### getSlateGray {#getSlateGray--}
```
public static Color getSlateGray()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF708090.

**Returns:**
A تمثيل لون معرف من النظام.

### getSnow {#getSnow--}
```
public static Color getSnow()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFFAFA.

**Returns:**
A تمثيل لون معرف من النظام.

### getSpringGreen {#getSpringGreen--}
```
public static Color getSpringGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF00FF7F.

**Returns:**
A تمثيل لون معرف من النظام.

### getSteelBlue {#getSteelBlue--}
```
public static Color getSteelBlue()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF4682B4.

**Returns:**
A تمثيل لون معرف من النظام.

### getTan {#getTan--}
```
public static Color getTan()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFD2B48C.

**Returns:**
A تمثيل لون معرف من النظام.

### getTeal {#getTeal--}
```
public static Color getTeal()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF008080.

**Returns:**
A تمثيل لون معرف من النظام.

### getThistle {#getThistle--}
```
public static Color getThistle()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFD8BFD8.

**Returns:**
A تمثيل لون معرف من النظام.

### getTomato {#getTomato--}
```
public static Color getTomato()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFF6347.

**Returns:**
A تمثيل لون معرف من النظام.

### getTransparent {#getTransparent--}
```
public static Color getTransparent()
```

يحصل على لون معرف من النظام.

**Returns:**
A تمثيل لون معرف من النظام.

### getTurquoise {#getTurquoise--}
```
public static Color getTurquoise()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF40E0D0.

**Returns:**
A تمثيل لون معرف من النظام.

### getViolet {#getViolet--}
```
public static Color getViolet()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFEE82EE.

**Returns:**
A تمثيل لون معرف من النظام.

### getWheat {#getWheat--}
```
public static Color getWheat()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFF5DEB3.

**Returns:**
A تمثيل لون معرف من النظام.

### getWhite {#getWhite--}
```
public static Color getWhite()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFFFFF.

**Returns:**
A تمثيل لون معرف من النظام.

### getWhiteSmoke {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFF5F5F5.

**Returns:**
A تمثيل لون معرف من النظام.

### getYellow {#getYellow--}
```
public static Color getYellow()
```

يحصل على لون معرف من النظام له قيمة ARGB #FFFFFF00.

**Returns:**
A تمثيل لون معرف من النظام.

### getYellowGreen {#getYellowGreen--}
```
public static Color getYellowGreen()
```

يحصل على لون معرف من النظام له قيمة ARGB #FF9ACD32.

**Returns:**
A تمثيل لون معرف من النظام.

### hashCode {#hashCode--}
```
public int hashCode()
```

إرجاع قيمة رمز تجزئة (hash code) للكائن. يتم دعم هذه الطريقة لفائدة جداول التجزئة مثل تلك التي توفرها {@link java.util.HashMap}. <p> العقد العام لـ {@code hashCode} هو: <ul> <li>كلما تم استدعاؤها على نفس الكائن أكثر من مرة خلال تنفيذ تطبيق جافا، يجب أن تُعيد طريقة {@code hashCode} نفس العدد الصحيح بشكل ثابت، بشرط عدم تعديل أي معلومات تُستخدم في مقارنات {@code equals} على الكائن. لا يلزم أن يظل هذا العدد ثابتًا بين تنفيذ تطبيق وآخر من نفس التطبيق. <li>إذا كان كائنان متساويان وفقًا لطريقة {@code equals(Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نفس النتيجة العددية. <li>ليس <em>مطلوبًا</em> أن إذا كان كائنان غير متساويين وفقًا لطريقة {@link java.lang.Object#equals(java.lang.Object)}، فإن استدعاء طريقة {@code hashCode} على كل من الكائنين يجب أن ينتج نتائج عددية متميزة. ومع ذلك، يجب على المبرمج أن يكون على علم بأن إنتاج نتائج عددية متميزة للكائنات غير المتساوية قد يحسن أداء جداول التجزئة. </ul> <p> بقدر ما يكون ذلك عمليًا بشكل معقول، تُعيد طريقة hashCode المعرفة في الفئة {@code Object} أعدادًا صحيحة متميزة للكائنات المتميزة. (عادةً ما يتم تنفيذ ذلك بتحويل العنوان الداخلي للكائن إلى عدد صحيح، لكن هذه التقنية التنفيذية ليست مطلوبة من قبل لغة البرمجة Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
قيمة رمز تجزئة لهذا الكائن. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
يرجع true إذا كان اللونان متساويين.

### op_Inequality {#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
إرجاع true إذا كان لونان (Colors) غير متساويين.

### parse {#parse-java.lang.String-}
يستخرج مكونات اللون من السلسلة.

### setPatternColorSpace {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
يضبط كائنًا يشير إلى مساحة ألوان النمط. للاستخدام الداخلي فقط

### toRgb {#toRgb--}
```
public Color toRgb()
```

يحوّل اللون إلى rgb.

**Returns:**
قيمة لون Rgb.

### toString {#toString--}
```
public String toString()
```

يحوّل إلى سلسلة.

**Returns:**
تمثيل نصّي لكائن Color.
