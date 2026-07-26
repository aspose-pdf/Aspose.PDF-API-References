---
title: "Farbe"
linktitle: "Farbe"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse für Farbwerte dar, die in verschiedenen Farbräumen ausgedrückt werden können."
type: docs
weight: 670
url: /de/java/com.aspose.pdf/color/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Color

```
public final class Color extends Object
```

Stellt eine Klasse für Farbwerte dar, die in verschiedenen Farbräumen ausgedrückt werden können.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [Default](#Default) | Stellt die Standardfarbe dar. |
| [Empty](#Empty) | Stellt eine leere Farbe dar. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Color](#Color--) | Standardkonstruktor. |
| [Color](#Color-double:A-) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone](#deepClone--) | Klont diese Instanz |
| [equals](#equals-java.lang.Object-) | Gibt true zurück, wenn zwei Farben gleich sind. |
| [fromArgb](#fromArgb-int-int-int-) | Ermittelt ein gültiges PDF-Farbeobjekt aus RGB-Farbkomponenten. |
| [fromArgb](#fromArgb-int-int-int-int-) | Ermittelt ein gültiges PDF-Farbeobjekt aus RGB-Farbkomponenten. |
| [fromCmyk](#fromCmyk-double-double-double-double-) | Ermittelt ein gültiges PDF-Farbeobjekt aus CMYK-Farbkomponenten. |
| [fromGray](#fromGray-double-) | Ermittelt ein gültiges PDF-Farbeobjekt aus einer Graustufenkomponente. |
| [fromRgb](#fromRgb-java.awt.Color-) | Ermittelt ein gültiges PDF-Farbeobjekt aus einem java.awt.Color-Wert. |
| [fromRgb](#fromRgb-double-double-double-) | Ermittelt ein gültiges PDF-Farbeobjekt aus RGB-Farbkomponenten. |
| [getA](#getA--) | Ermittelt den Alpha-Komponentenwert |
| [getAliceBlue](#getAliceBlue--) | Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFF0F8FF. |
| [getAntiqueWhite](#getAntiqueWhite--) | Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFFAEBD7. |
| [getAqua](#getAqua--) | Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FF00FFFF. |
| [getAquamarine](#getAquamarine--) | Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FF7FFFD4. |
| [getAzure](#getAzure--) | Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFF0FFFF. |
| [getBeige](#getBeige--) | Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFF5F5DC. |
| [getBisque](#getBisque--) | Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFFFE4C4. |
| [getBlack](#getBlack--) | Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FF000000. |
| [getBlanchedAlmond](#getBlanchedAlmond--) | Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFFFEBCD. |
| [getBlue](#getBlue--) | Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FF0000FF. |
| [getBlueViolet](#getBlueViolet--) | Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FF8A2BE2. |
| [getBrown](#getBrown--) | Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFA52A2A. |
| [getBurlyWood](#getBurlyWood--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFDEB887 hat. |
| [getCadetBlue](#getCadetBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF5F9EA0 hat. |
| [getChartreuse](#getChartreuse--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF7FFF00 hat. |
| [getChocolate](#getChocolate--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFD2691E hat. |
| [getColorSpace](#getColorSpace--) | Ruft den Farbraum ab, den die Farbe darstellt. |
| [getCoral](#getCoral--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFFF7F50 hat. |
| [getCornflowerBlue](#getCornflowerBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF6495ED hat. |
| [getCornsilk](#getCornsilk--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFFFF8DC hat. |
| [getCrimson](#getCrimson--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFDC143C hat. |
| [getCyan](#getCyan--) | Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FF00FFFF. |
| [getDarkBlue](#getDarkBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF00008B hat. |
| [getDarkCyan](#getDarkCyan--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF008B8B hat. |
| [getDarkGoldenrod](#getDarkGoldenrod--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFB8860B hat. |
| [getDarkGray](#getDarkGray--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFA9A9A9 hat. |
| [getDarkGreen](#getDarkGreen--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF006400 hat. |
| [getDarkKhaki](#getDarkKhaki--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFBDB76B hat. |
| [getDarkMagenta](#getDarkMagenta--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF8B008B hat. |
| [getDarkOliveGreen](#getDarkOliveGreen--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF556B2F hat. |
| [getDarkOrange](#getDarkOrange--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFFF8C00 hat. |
| [getDarkOrchid](#getDarkOrchid--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF9932CC hat. |
| [getDarkRed](#getDarkRed--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF8B0000 hat. |
| [getDarkSalmon](#getDarkSalmon--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFE9967A hat. |
| [getDarkSeaGreen](#getDarkSeaGreen--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF8FBC8F hat. |
| [getDarkSlateBlue](#getDarkSlateBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF483D8B hat. |
| [getDarkSlateGray](#getDarkSlateGray--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF2F4F4F hat. |
| [getDarkTurquoise](#getDarkTurquoise--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF00CED1 hat. |
| [getDarkViolet](#getDarkViolet--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF9400D3 hat. |
| [getData](#getData--) | Farbwert. |
| [getDeepPink](#getDeepPink--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFF1493 hat. |
| [getDeepSkyBlue](#getDeepSkyBlue--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF00BFFF hat. |
| [getDimGray](#getDimGray--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF696969 hat. |
| [getDodgerBlue](#getDodgerBlue--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF1E90FF hat. |
| [getFirebrick](#getFirebrick--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFB22222 hat. |
| [getFloralWhite](#getFloralWhite--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFFFAF0 hat. |
| [getForestGreen](#getForestGreen--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF228B22 hat. |
| [getFuchsia](#getFuchsia--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFF00FF hat. |
| [getGainsboro](#getGainsboro--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFDCDCDC hat. |
| [getGhostWhite](#getGhostWhite--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFF8F8FF hat. |
| [getGold](#getGold--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFFD700 hat. |
| [getGoldenrod](#getGoldenrod--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFDAA520 hat. |
| [getGray](#getGray--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF808080 hat. |
| [getGreen](#getGreen--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF008000 hat. |
| [getGreenYellow](#getGreenYellow--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFADFF2F hat. |
| [getHoneydew](#getHoneydew--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFF0FFF0 hat. |
| [getHotPink](#getHotPink--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFF69B4 hat. |
| [getIndianRed](#getIndianRed--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFCD5C5C hat. |
| [getIndigo](#getIndigo--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF4B0082 hat. |
| [getIvory](#getIvory--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFFFFF0 hat. |
| [getKhaki](#getKhaki--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFF0E68C hat. |
| [getLavender](#getLavender--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFE6E6FA hat. |
| [getLavenderBlush](#getLavenderBlush--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFFF0F5 hat. |
| [getLawnGreen](#getLawnGreen--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF7CFC00 hat. |
| [getLemonChiffon](#getLemonChiffon--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFFFACD hat. |
| [getLightBlue](#getLightBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFADD8E6 hat. |
| [getLightCoral](#getLightCoral--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFF08080 hat. |
| [getLightCyan](#getLightCyan--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFE0FFFF hat. |
| [getLightGoldenrodYellow](#getLightGoldenrodYellow--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFAFAD2 hat. |
| [getLightGray](#getLightGray--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFD3D3D3 hat. |
| [getLightGreen](#getLightGreen--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF90EE90 hat. |
| [getLightPink](#getLightPink--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFFB6C1 hat. |
| [getLightSalmon](#getLightSalmon--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFFA07A hat. |
| [getLightSeaGreen](#getLightSeaGreen--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF20B2AA hat. |
| [getLightSkyBlue](#getLightSkyBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF87CEFA hat. |
| [getLightSlateGray](#getLightSlateGray--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF778899 hat. |
| [getLightSteelBlue](#getLightSteelBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFB0C4DE hat. |
| [getLightYellow](#getLightYellow--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFFFFE0 hat. |
| [getLime](#getLime--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF00FF00 hat. |
| [getLimeGreen](#getLimeGreen--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF32CD32 hat. |
| [getLinen](#getLinen--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFAF0E6 hat. |
| [getMagenta](#getMagenta--) | Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFF00FF hat. |
| [getMaroon](#getMaroon--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF800000 hat. |
| [getMediumAquamarine](#getMediumAquamarine--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF66CDAA hat. |
| [getMediumBlue](#getMediumBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF0000CD hat. |
| [getMediumOrchid](#getMediumOrchid--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFBA55D3 hat. |
| [getMediumPurple](#getMediumPurple--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF9370DB hat. |
| [getMediumSeaGreen](#getMediumSeaGreen--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF3CB371 hat. |
| [getMediumSlateBlue](#getMediumSlateBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF7B68EE hat. |
| [getMediumSpringGreen](#getMediumSpringGreen--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF00FA9A hat. |
| [getMediumTurquoise](#getMediumTurquoise--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF48D1CC hat. |
| [getMediumVioletRed](#getMediumVioletRed--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFC71585 hat. |
| [getMidnightBlue](#getMidnightBlue--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF191970 hat. |
| [getMintCream](#getMintCream--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFF5FFFA hat. |
| [getMistyRose](#getMistyRose--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFE4E1 hat. |
| [getMoccasin](#getMoccasin--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFE4B5 hat. |
| [getNavajoWhite](#getNavajoWhite--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFDEAD hat. |
| [getNavy](#getNavy--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF000080 hat. |
| [getOldLace](#getOldLace--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFDF5E6 hat. |
| [getOlive](#getOlive--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF808000 hat. |
| [getOliveDrab](#getOliveDrab--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF6B8E23 hat. |
| [getOrange](#getOrange--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFA500 hat. |
| [getOrangeRed](#getOrangeRed--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFF4500 hat. |
| [getOrchid](#getOrchid--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFDA70D6 hat. |
| [getPaleGoldenrod](#getPaleGoldenrod--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFEEE8AA hat. |
| [getPaleGreen](#getPaleGreen--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF98FB98 hat. |
| [getPaleTurquoise](#getPaleTurquoise--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFAFEEEE hat. |
| [getPaleVioletRed](#getPaleVioletRed--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFDB7093 hat. |
| [getPapayaWhip](#getPapayaWhip--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFEFD5 hat. |
| [getPatternColorSpace](#getPatternColorSpace--) | Ruft ein Objekt ab, das den Muster‑Farbraum angibt. Nur für den internen Gebrauch. |
| [getPeachPuff](#getPeachPuff--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFDAB9 hat. |
| [getPeru](#getPeru--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFCD853F hat. |
| [getPink](#getPink--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFC0CB hat. |
| [getPlum](#getPlum--) | Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFDDA0DD hat. |
| [getPowderBlue](#getPowderBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFB0E0E6 hat. |
| [getPurple](#getPurple--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF800080 hat. |
| [getRed](#getRed--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFF0000 hat. |
| [getRosyBrown](#getRosyBrown--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFBC8F8F hat. |
| [getRoyalBlue](#getRoyalBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF4169E1 hat. |
| [getSaddleBrown](#getSaddleBrown--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF8B4513 hat. |
| [getSalmon](#getSalmon--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFA8072 hat. |
| [getSandyBrown](#getSandyBrown--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFF4A460 hat. |
| [getSeaGreen](#getSeaGreen--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF2E8B57 hat. |
| [getSeaShell](#getSeaShell--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFFF5EE hat. |
| [getSienna](#getSienna--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFA0522D hat. |
| [getSilver](#getSilver--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFC0C0C0 hat. |
| [getSkyBlue](#getSkyBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF87CEEB hat. |
| [getSlateBlue](#getSlateBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF6A5ACD hat. |
| [getSlateGray](#getSlateGray--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF708090 hat. |
| [getSnow](#getSnow--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFFFAFA hat. |
| [getSpringGreen](#getSpringGreen--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF00FF7F hat. |
| [getSteelBlue](#getSteelBlue--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF4682B4 hat. |
| [getTan](#getTan--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFD2B48C hat. |
| [getTeal](#getTeal--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF008080 hat. |
| [getThistle](#getThistle--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFD8BFD8 hat. |
| [getTomato](#getTomato--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFF6347 hat. |
| [getTransparent](#getTransparent--) | Ruft eine systemdefinierte Farbe ab. |
| [getTurquoise](#getTurquoise--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF40E0D0 hat. |
| [getViolet](#getViolet--) | Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFEE82EE hat. |
| [getWheat](#getWheat--) | Liefert eine systemdefinierte Farbe, die den ARGB-Wert #FFF5DEB3 hat. |
| [getWhite](#getWhite--) | Liefert eine systemdefinierte Farbe, die den ARGB-Wert #FFFFFFFF hat. |
| [getWhiteSmoke](#getWhiteSmoke--) | Liefert eine systemdefinierte Farbe, die den ARGB-Wert #FFF5F5F5 hat. |
| [getYellow](#getYellow--) | Liefert eine systemdefinierte Farbe, die den ARGB-Wert #FFFFFF00 hat. |
| [getYellowGreen](#getYellowGreen--) | Liefert eine systemdefinierte Farbe, die den ARGB-Wert #FF9ACD32 hat. |
| [hashCode](#hashCode--) | Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während der Ausführung einer Java-Anwendung mehr als einmal auf demselben Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben ganzzahligen Wert zurückgeben, vorausgesetzt, dass keine Informationen, die in {@code equals}-Vergleichen des Objekts verwendet werden, geändert wurden. Dieser ganzzahlige Wert muss nicht von einer Ausführung einer Anwendung zur nächsten gleich bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode auf beiden Objekten dasselbe ganzzahlige Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass bei ungleichen Objekten gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode der Aufruf der {@code hashCode}-Methode auf beiden Objekten unterschiedliche ganzzahlige Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher ganzzahliger Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> Soweit praktisch möglich, gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Ganzzahlen für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in eine Ganzzahl umgewandelt wird, aber diese Implementierungstechnik ist nicht von der Java<span style="font-size:70%"><sup>TM</sup></span>Programmiersprache vorgeschrieben.) |
| [op_Equality](#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Gibt true zurück, wenn zwei Farben gleich sind. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Gibt true zurück, wenn zwei Farben nicht gleich sind. |
| [parse](#parse-java.lang.String-) | Extrahiert Farbbestandteile aus dem String. |
| [setPatternColorSpace](#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-) | Setzt ein Objekt, das den Farbraum des Musters angibt. Nur für interne Verwendung. |
| [toRgb](#toRgb--) | Konvertiert die Farbe in RGB. |
| [toString](#toString--) | Konvertiert in einen String. |

### Default {#Default}
```
public static final Color Default
```

Stellt die Standardfarbe dar.

### Empty {#Empty}
```
public static final Color Empty
```

Stellt eine leere Farbe dar.

### Color {#Color--}
```
public Color()
```

Standardkonstruktor.

### Color {#Color-double:A-}
```
public Color(double[] vector)
```

Konstruktor

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Vektor |  | double[]-Array |

### deepClone {#deepClone--}
```
public Color deepClone()
```

Klont diese Instanz

**Returns:**
Color-Objekt

### equals {#equals-java.lang.Object-}
Gibt true zurück, wenn zwei Farben gleich sind.

### fromArgb {#fromArgb-int-int-int-}
```
public static Color fromArgb(int r, int g, int b)
```

Ermittelt ein gültiges PDF-Farbeobjekt aus RGB-Farbkomponenten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| r |  | Die rote Farbkomponente (Wert 0 - 255). |
| g |  | Die grüne Farbkomponente (Wert 0 - 255). |
| b |  | Die blaue Farbkomponente (Wert 0 - 255). |

**Returns:**
Farbobjekt mit jedem Komponentenwert im Bereich [0..255].

### fromArgb {#fromArgb-int-int-int-int-}
```
public static Color fromArgb(int a, int r, int g, int b)
```

Ermittelt ein gültiges PDF-Farbeobjekt aus RGB-Farbkomponenten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a |  | Der Alphakomponentenwert (Wert 0 - 255). |
| r |  | Die rote Farbkomponente (Wert 0 - 255). |
| g |  | Die grüne Farbkomponente (Wert 0 - 255). |
| b |  | Die blaue Farbkomponente (Wert 0 - 255). |

**Returns:**
Farbobjekt mit jedem Komponentenwert im Bereich [0..255].

### fromCmyk {#fromCmyk-double-double-double-double-}
```
public static Color fromCmyk(double c, double m, double y, double k)
```

Ermittelt ein gültiges PDF-Farbeobjekt aus CMYK-Farbkomponenten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c |  | Die cyanfarbene Komponente (Wert 0 - 1). |
| m |  | Die Magenta-Farbkomponente (Wert 0 - 1). |
| y |  | Die Gelb-Farbkomponente (Wert 0 - 1). |
| k |  | Die Key-Farbkomponente (Wert 0 - 1). |

**Returns:**
Farbobjekt mit jedem Komponentenwert im Bereich [0..1].

### fromGray {#fromGray-double-}
```
public static Color fromGray(double g)
```

Ermittelt ein gültiges PDF-Farbeobjekt aus einer Graustufenkomponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| g |  | Die Grau-Farbkomponente (Wert 0 - 1). |

**Returns:**
Farbobjekt mit jedem Komponentenwert im Bereich [0..1].

### fromRgb {#fromRgb-java.awt.Color-}
Ermittelt ein gültiges PDF-Farbeobjekt aus einem java.awt.Color-Wert.

### fromRgb {#fromRgb-double-double-double-}
```
public static Color fromRgb(double r, double g, double b)
```

Ermittelt ein gültiges PDF-Farbeobjekt aus RGB-Farbkomponenten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| r |  | Die Rot-Farbkomponente (Wert 0 - 1). |
| g |  | Die Grün-Farbkomponente (Wert 0 - 1). |
| b |  | Die Blau-Farbkomponente (Wert 0 - 1). |

**Returns:**
Farbobjekt mit jedem Komponentenwert im Bereich [0..1].

### getA {#getA--}
```
public double getA()
```

Ermittelt den Alpha-Komponentenwert

**Returns:**
double-Wert

### getAliceBlue {#getAliceBlue--}
```
public static Color getAliceBlue()
```

Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFF0F8FF.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getAntiqueWhite {#getAntiqueWhite--}
```
public static Color getAntiqueWhite()
```

Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFFAEBD7.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getAqua {#getAqua--}
```
public static Color getAqua()
```

Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FF00FFFF.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getAquamarine {#getAquamarine--}
```
public static Color getAquamarine()
```

Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FF7FFFD4.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getAzure {#getAzure--}
```
public static Color getAzure()
```

Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFF0FFFF.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getBeige {#getBeige--}
```
public static Color getBeige()
```

Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFF5F5DC.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getBisque {#getBisque--}
```
public static Color getBisque()
```

Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFFFE4C4.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getBlack {#getBlack--}
```
public static Color getBlack()
```

Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FF000000.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getBlanchedAlmond {#getBlanchedAlmond--}
```
public static Color getBlanchedAlmond()
```

Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFFFEBCD.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getBlue {#getBlue--}
```
public static Color getBlue()
```

Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FF0000FF.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getBlueViolet {#getBlueViolet--}
```
public static Color getBlueViolet()
```

Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FF8A2BE2.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getBrown {#getBrown--}
```
public static Color getBrown()
```

Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FFA52A2A.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getBurlyWood {#getBurlyWood--}
```
public static Color getBurlyWood()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFDEB887 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getCadetBlue {#getCadetBlue--}
```
public static Color getCadetBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF5F9EA0 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getChartreuse {#getChartreuse--}
```
public static Color getChartreuse()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF7FFF00 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getChocolate {#getChocolate--}
```
public static Color getChocolate()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFD2691E hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Ruft den Farbraum ab, den die Farbe darstellt.

**Returns:**
ColorSpace-Objekt

### getCoral {#getCoral--}
```
public static Color getCoral()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFFF7F50 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getCornflowerBlue {#getCornflowerBlue--}
```
public static Color getCornflowerBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF6495ED hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getCornsilk {#getCornsilk--}
```
public static Color getCornsilk()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFFFF8DC hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getCrimson {#getCrimson--}
```
public static Color getCrimson()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFDC143C hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getCyan {#getCyan--}
```
public static Color getCyan()
```

Ermittelt eine systemdefinierte Farbe mit dem ARGB-Wert #FF00FFFF.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkBlue {#getDarkBlue--}
```
public static Color getDarkBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF00008B hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkCyan {#getDarkCyan--}
```
public static Color getDarkCyan()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF008B8B hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkGoldenrod {#getDarkGoldenrod--}
```
public static Color getDarkGoldenrod()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFB8860B hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkGray {#getDarkGray--}
```
public static Color getDarkGray()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFA9A9A9 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkGreen {#getDarkGreen--}
```
public static Color getDarkGreen()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF006400 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkKhaki {#getDarkKhaki--}
```
public static Color getDarkKhaki()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFBDB76B hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkMagenta {#getDarkMagenta--}
```
public static Color getDarkMagenta()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF8B008B hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkOliveGreen {#getDarkOliveGreen--}
```
public static Color getDarkOliveGreen()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF556B2F hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkOrange {#getDarkOrange--}
```
public static Color getDarkOrange()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFFF8C00 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkOrchid {#getDarkOrchid--}
```
public static Color getDarkOrchid()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF9932CC hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkRed {#getDarkRed--}
```
public static Color getDarkRed()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF8B0000 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkSalmon {#getDarkSalmon--}
```
public static Color getDarkSalmon()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FFE9967A hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkSeaGreen {#getDarkSeaGreen--}
```
public static Color getDarkSeaGreen()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF8FBC8F hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkSlateBlue {#getDarkSlateBlue--}
```
public static Color getDarkSlateBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF483D8B hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkSlateGray {#getDarkSlateGray--}
```
public static Color getDarkSlateGray()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF2F4F4F hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkTurquoise {#getDarkTurquoise--}
```
public static Color getDarkTurquoise()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB-Wert von #FF00CED1 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDarkViolet {#getDarkViolet--}
```
public static Color getDarkViolet()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF9400D3 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getData {#getData--}
```
public double[] getData()
```

Farbwert.

**Returns:**
Array von double-Werten

### getDeepPink {#getDeepPink--}
```
public static Color getDeepPink()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFF1493 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDeepSkyBlue {#getDeepSkyBlue--}
```
public static Color getDeepSkyBlue()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF00BFFF hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDimGray {#getDimGray--}
```
public static Color getDimGray()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF696969 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getDodgerBlue {#getDodgerBlue--}
```
public static Color getDodgerBlue()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF1E90FF hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getFirebrick {#getFirebrick--}
```
public static Color getFirebrick()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFB22222 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getFloralWhite {#getFloralWhite--}
```
public static Color getFloralWhite()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFFFAF0 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getForestGreen {#getForestGreen--}
```
public static Color getForestGreen()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF228B22 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getFuchsia {#getFuchsia--}
```
public static Color getFuchsia()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFF00FF hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getGainsboro {#getGainsboro--}
```
public static Color getGainsboro()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFDCDCDC hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getGhostWhite {#getGhostWhite--}
```
public static Color getGhostWhite()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFF8F8FF hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getGold {#getGold--}
```
public static Color getGold()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFFD700 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getGoldenrod {#getGoldenrod--}
```
public static Color getGoldenrod()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFDAA520 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getGray {#getGray--}
```
public static Color getGray()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF808080 hat.

**Returns:**
Eine Struktur, die eine systemdefinierte Farbe darstellt.

### getGreen {#getGreen--}
```
public static Color getGreen()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF008000 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getGreenYellow {#getGreenYellow--}
```
public static Color getGreenYellow()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFADFF2F hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getHoneydew {#getHoneydew--}
```
public static Color getHoneydew()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFF0FFF0 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getHotPink {#getHotPink--}
```
public static Color getHotPink()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFF69B4 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getIndianRed {#getIndianRed--}
```
public static Color getIndianRed()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFCD5C5C hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getIndigo {#getIndigo--}
```
public static Color getIndigo()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FF4B0082 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getIvory {#getIvory--}
```
public static Color getIvory()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFFFFF0 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getKhaki {#getKhaki--}
```
public static Color getKhaki()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFF0E68C hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLavender {#getLavender--}
```
public static Color getLavender()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFE6E6FA hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLavenderBlush {#getLavenderBlush--}
```
public static Color getLavenderBlush()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFFF0F5 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLawnGreen {#getLawnGreen--}
```
public static Color getLawnGreen()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF7CFC00 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLemonChiffon {#getLemonChiffon--}
```
public static Color getLemonChiffon()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFFFACD hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLightBlue {#getLightBlue--}
```
public static Color getLightBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFADD8E6 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLightCoral {#getLightCoral--}
```
public static Color getLightCoral()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFF08080 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLightCyan {#getLightCyan--}
```
public static Color getLightCyan()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFE0FFFF hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLightGoldenrodYellow {#getLightGoldenrodYellow--}
```
public static Color getLightGoldenrodYellow()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFAFAD2 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLightGray {#getLightGray--}
```
public static Color getLightGray()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFD3D3D3 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLightGreen {#getLightGreen--}
```
public static Color getLightGreen()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF90EE90 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLightPink {#getLightPink--}
```
public static Color getLightPink()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFFB6C1 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLightSalmon {#getLightSalmon--}
```
public static Color getLightSalmon()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFFA07A hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLightSeaGreen {#getLightSeaGreen--}
```
public static Color getLightSeaGreen()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF20B2AA hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLightSkyBlue {#getLightSkyBlue--}
```
public static Color getLightSkyBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF87CEFA hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLightSlateGray {#getLightSlateGray--}
```
public static Color getLightSlateGray()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF778899 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLightSteelBlue {#getLightSteelBlue--}
```
public static Color getLightSteelBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFB0C4DE hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLightYellow {#getLightYellow--}
```
public static Color getLightYellow()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFFFFE0 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLime {#getLime--}
```
public static Color getLime()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF00FF00 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLimeGreen {#getLimeGreen--}
```
public static Color getLimeGreen()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF32CD32 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getLinen {#getLinen--}
```
public static Color getLinen()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFAF0E6 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMagenta {#getMagenta--}
```
public static Color getMagenta()
```

Gibt eine systemdefinierte Farbe zurück, die einen ARGB-Wert von #FFFF00FF hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMaroon {#getMaroon--}
```
public static Color getMaroon()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF800000 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMediumAquamarine {#getMediumAquamarine--}
```
public static Color getMediumAquamarine()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF66CDAA hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMediumBlue {#getMediumBlue--}
```
public static Color getMediumBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF0000CD hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMediumOrchid {#getMediumOrchid--}
```
public static Color getMediumOrchid()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFBA55D3 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMediumPurple {#getMediumPurple--}
```
public static Color getMediumPurple()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF9370DB hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMediumSeaGreen {#getMediumSeaGreen--}
```
public static Color getMediumSeaGreen()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF3CB371 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMediumSlateBlue {#getMediumSlateBlue--}
```
public static Color getMediumSlateBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF7B68EE hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMediumSpringGreen {#getMediumSpringGreen--}
```
public static Color getMediumSpringGreen()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF00FA9A hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMediumTurquoise {#getMediumTurquoise--}
```
public static Color getMediumTurquoise()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF48D1CC hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMediumVioletRed {#getMediumVioletRed--}
```
public static Color getMediumVioletRed()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFC71585 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMidnightBlue {#getMidnightBlue--}
```
public static Color getMidnightBlue()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF191970 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMintCream {#getMintCream--}
```
public static Color getMintCream()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFF5FFFA hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMistyRose {#getMistyRose--}
```
public static Color getMistyRose()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFE4E1 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getMoccasin {#getMoccasin--}
```
public static Color getMoccasin()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFE4B5 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getNavajoWhite {#getNavajoWhite--}
```
public static Color getNavajoWhite()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFDEAD hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getNavy {#getNavy--}
```
public static Color getNavy()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF000080 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getOldLace {#getOldLace--}
```
public static Color getOldLace()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFDF5E6 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getOlive {#getOlive--}
```
public static Color getOlive()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF808000 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getOliveDrab {#getOliveDrab--}
```
public static Color getOliveDrab()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF6B8E23 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getOrange {#getOrange--}
```
public static Color getOrange()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFA500 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getOrangeRed {#getOrangeRed--}
```
public static Color getOrangeRed()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFF4500 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getOrchid {#getOrchid--}
```
public static Color getOrchid()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFDA70D6 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getPaleGoldenrod {#getPaleGoldenrod--}
```
public static Color getPaleGoldenrod()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFEEE8AA hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getPaleGreen {#getPaleGreen--}
```
public static Color getPaleGreen()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FF98FB98 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getPaleTurquoise {#getPaleTurquoise--}
```
public static Color getPaleTurquoise()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFAFEEEE hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getPaleVioletRed {#getPaleVioletRed--}
```
public static Color getPaleVioletRed()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFDB7093 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getPapayaWhip {#getPapayaWhip--}
```
public static Color getPapayaWhip()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFEFD5 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getPatternColorSpace {#getPatternColorSpace--}
```
public PatternColorSpace getPatternColorSpace()
```

Ruft ein Objekt ab, das den Muster‑Farbraum angibt. Nur für den internen Gebrauch.

**Returns:**
PatternColorSpace-Objekt

### getPeachPuff {#getPeachPuff--}
```
public static Color getPeachPuff()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFDAB9 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getPeru {#getPeru--}
```
public static Color getPeru()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFCD853F hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getPink {#getPink--}
```
public static Color getPink()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFFFC0CB hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getPlum {#getPlum--}
```
public static Color getPlum()
```

Ruft eine systemdefinierte Farbe ab, die den ARGB‑Wert #FFDDA0DD hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getPowderBlue {#getPowderBlue--}
```
public static Color getPowderBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFB0E0E6 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getPurple {#getPurple--}
```
public static Color getPurple()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF800080 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getRed {#getRed--}
```
public static Color getRed()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFF0000 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getRosyBrown {#getRosyBrown--}
```
public static Color getRosyBrown()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFBC8F8F hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getRoyalBlue {#getRoyalBlue--}
```
public static Color getRoyalBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF4169E1 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getSaddleBrown {#getSaddleBrown--}
```
public static Color getSaddleBrown()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF8B4513 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getSalmon {#getSalmon--}
```
public static Color getSalmon()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFA8072 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getSandyBrown {#getSandyBrown--}
```
public static Color getSandyBrown()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFF4A460 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getSeaGreen {#getSeaGreen--}
```
public static Color getSeaGreen()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF2E8B57 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getSeaShell {#getSeaShell--}
```
public static Color getSeaShell()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFFF5EE hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getSienna {#getSienna--}
```
public static Color getSienna()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFA0522D hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getSilver {#getSilver--}
```
public static Color getSilver()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFC0C0C0 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getSkyBlue {#getSkyBlue--}
```
public static Color getSkyBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF87CEEB hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getSlateBlue {#getSlateBlue--}
```
public static Color getSlateBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF6A5ACD hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getSlateGray {#getSlateGray--}
```
public static Color getSlateGray()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF708090 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getSnow {#getSnow--}
```
public static Color getSnow()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFFFAFA hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getSpringGreen {#getSpringGreen--}
```
public static Color getSpringGreen()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF00FF7F hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getSteelBlue {#getSteelBlue--}
```
public static Color getSteelBlue()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF4682B4 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getTan {#getTan--}
```
public static Color getTan()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFD2B48C hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getTeal {#getTeal--}
```
public static Color getTeal()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF008080 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getThistle {#getThistle--}
```
public static Color getThistle()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFD8BFD8 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getTomato {#getTomato--}
```
public static Color getTomato()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFFF6347 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getTransparent {#getTransparent--}
```
public static Color getTransparent()
```

Ruft eine systemdefinierte Farbe ab.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getTurquoise {#getTurquoise--}
```
public static Color getTurquoise()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FF40E0D0 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getViolet {#getViolet--}
```
public static Color getViolet()
```

Ruft eine systemdefinierte Farbe ab, die einen ARGB‑Wert von #FFEE82EE hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getWheat {#getWheat--}
```
public static Color getWheat()
```

Liefert eine systemdefinierte Farbe, die den ARGB-Wert #FFF5DEB3 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getWhite {#getWhite--}
```
public static Color getWhite()
```

Liefert eine systemdefinierte Farbe, die den ARGB-Wert #FFFFFFFF hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getWhiteSmoke {#getWhiteSmoke--}
```
public static Color getWhiteSmoke()
```

Liefert eine systemdefinierte Farbe, die den ARGB-Wert #FFF5F5F5 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getYellow {#getYellow--}
```
public static Color getYellow()
```

Liefert eine systemdefinierte Farbe, die den ARGB-Wert #FFFFFF00 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### getYellowGreen {#getYellowGreen--}
```
public static Color getYellowGreen()
```

Liefert eine systemdefinierte Farbe, die den ARGB-Wert #FF9ACD32 hat.

**Returns:**
Ein, das eine systemdefinierte Farbe darstellt.

### hashCode {#hashCode--}
```
public int hashCode()
```

Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während der Ausführung einer Java-Anwendung mehr als einmal auf demselben Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben ganzzahligen Wert zurückgeben, vorausgesetzt, dass keine Informationen, die in {@code equals}-Vergleichen des Objekts verwendet werden, geändert wurden. Dieser ganzzahlige Wert muss nicht von einer Ausführung einer Anwendung zur nächsten gleich bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode auf beiden Objekten dasselbe ganzzahlige Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass bei ungleichen Objekten gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode der Aufruf der {@code hashCode}-Methode auf beiden Objekten unterschiedliche ganzzahlige Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher ganzzahliger Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> Soweit praktisch möglich, gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Ganzzahlen für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in eine Ganzzahl umgewandelt wird, aber diese Implementierungstechnik ist nicht von der Java<span style="font-size:70%"><sup>TM</sup></span>Programmiersprache vorgeschrieben.)

**Returns:**
ein Hashcode-Wert für dieses Objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Gibt true zurück, wenn zwei Farben gleich sind.

### op_Inequality {#op_Inequality-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Gibt true zurück, wenn zwei Farben nicht gleich sind.

### parse {#parse-java.lang.String-}
Extrahiert Farbbestandteile aus dem String.

### setPatternColorSpace {#setPatternColorSpace-com.aspose.pdf.drawing.PatternColorSpace-}
Setzt ein Objekt, das den Farbraum des Musters angibt. Nur für interne Verwendung.

### toRgb {#toRgb--}
```
public Color toRgb()
```

Konvertiert die Farbe in RGB.

**Returns:**
RGB-Farbwert.

### toString {#toString--}
```
public String toString()
```

Konvertiert in einen String.

**Returns:**
String-Darstellung des Color-Objekts.
