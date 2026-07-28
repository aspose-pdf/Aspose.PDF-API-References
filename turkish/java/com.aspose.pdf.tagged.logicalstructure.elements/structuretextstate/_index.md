---
title: "StructureTextState"
linktitle: "StructureTextState"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin Yapı Öğeleri ve Etiketli İçerik (ITextElement, ITaggedContent) için metin durumu ayarlarını temsil eder."
type: docs
weight: 120
url: /tr/java/com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState

```
public class StructureTextState extends Object
```

Metin Yapı Öğeleri ve Etiketli İçerik (ITextElement, ITaggedContent) için metin durumu ayarlarını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [StructureTextState](#StructureTextState--) | Varsayılan yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createTextState](#createTextState--) | Metin Durumu Oluştur |
| [getBackgroundColor](#getBackgroundColor--) | Metnin arka plan rengini alır veya ayarlar. Null olabilir. {@code BackgroundColor} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [getCharacterSpacing](#getCharacterSpacing--) | Metnin karakter aralığını alır veya ayarlar. Null olabilir. {@code CharacterSpacing} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [getFont](#getFont--) | Metnin yazı tipini alır veya ayarlar. Null olabilir. {@code Font} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [getFontSize](#getFontSize--) | Metnin yazı tipi boyutunu alır veya ayarlar. Null olabilir. {@code FontSize} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [getFontStyle](#getFontStyle--) | Metnin yazı tipi stilini alır veya ayarlar. Null olabilir. {@code FontStyle} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [getForegroundColor](#getForegroundColor--) | Metnin ön plan rengini alır veya ayarlar. Null olabilir. {@code ForegroundColor} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Paragrafın yatay hizalamasını alır veya ayarlar |
| [getHorizontalScaling](#getHorizontalScaling--) | Metnin yatay ölçeklemesini alır veya ayarlar. Null olabilir. {@code HorizontalScaling} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [getLineSpacing](#getLineSpacing--) | Metnin satır aralığını alır veya ayarlar. Null olabilir. {@code LineSpacing} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [getMarginInfo](#getMarginInfo--) | Blok yapı öğesi için kenar boşluğunu alır veya ayarlar. |
| [getStrikeOut](#getStrikeOut--) | Metin için üstü çizili özelliğini alır veya ayarlar. Null olabilir. {@code StrikeOut} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [getSubscript](#getSubscript--) | Metnin alt simgesini alır veya ayarlar. Null olabilir. {@code Subscript} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [getSuperscript](#getSuperscript--) | Metnin üst simgesini alır veya ayarlar. Null olabilir. {@code Superscript} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [getUnderline](#getUnderline--) | Metin için alt çizgiyi alır veya ayarlar. Null olabilir. {@code Underline} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [getVerticalAlignment](#getVerticalAlignment--) | Paragrafın dikey hizalamasını alır veya ayarlar |
| [getWordSpacing](#getWordSpacing--) | Metnin kelime aralığını alır veya ayarlar. Null olabilir. {@code WordSpacing} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Bu paragrafın bir sonraki sütunda olup olmayacağını gösteren bir bool değerini alır veya ayarlar. Varsayılan değeri false'dur. |
| [isInLineParagraph](#isInLineParagraph--) | Paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan değer false'dur. |
| [isInNewPage](#isInNewPage--) | Bu paragrafın yeni sayfada oluşturulmasını zorlayan bir bool değerini alır veya ayarlar. Varsayılan değer false'dur. |
| [isKeptWithNext](#isKeptWithNext--) | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını gösteren bir bool değerini alır veya ayarlar. Varsayılan değer false'dur. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Metnin arka plan rengini alır veya ayarlar. Null olabilir. {@code BackgroundColor} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [setCharacterSpacing](#setCharacterSpacing-com.aspose.ms.System.Nullable-) | Metnin karakter aralığını alır veya ayarlar. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Metnin yazı tipini alır veya ayarlar. Null olabilir. {@code Font} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [setFontSize](#setFontSize-com.aspose.ms.System.Nullable-) | Metnin yazı tipi boyutunu alır veya ayarlar. |
| [setFontStyle](#setFontStyle-com.aspose.ms.System.Nullable-) | Metnin yazı tipi stilini alır veya ayarlar. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Metnin ön plan rengini alır veya ayarlar. Null olabilir. {@code ForegroundColor} özelliğini üst yapı öğesinden devralmak için null kullanın. |
| [setHorizontalScaling](#setHorizontalScaling-com.aspose.ms.System.Nullable-) | Metnin yatay ölçeklemesini alır veya ayarlar. |
| [setLineSpacing](#setLineSpacing-com.aspose.ms.System.Nullable-) | Metnin satır aralığını alır veya ayarlar. |
| [setMarginInfo](#setMarginInfo-com.aspose.pdf.MarginInfo-) | Blok yapı öğesi için kenar boşluğunu alır veya ayarlar. |
| [setStrikeOut](#setStrikeOut-com.aspose.ms.System.Nullable-) | Metnin üstü çizili özelliğini alır veya ayarlar. |
| [setSubscript](#setSubscript-com.aspose.ms.System.Nullable-) | Metnin alt simgesini alır veya ayarlar. |
| [setSuperscript](#setSuperscript-com.aspose.ms.System.Nullable-) | Metnin üst simgesini alır veya ayarlar. |
| [setUnderline](#setUnderline-com.aspose.ms.System.Nullable-) | Metnin altını çizmeyi alır veya ayarlar. |
| [setWordSpacing](#setWordSpacing-com.aspose.ms.System.Nullable-) | Metnin kelime aralığını alır veya ayarlar. |
| [update](#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-) | Elemanları güncelle |

### StructureTextState {#StructureTextState--}
```
public StructureTextState()
```

Varsayılan yapıcı

### createTextState {#createTextState--}
```
public final TextState createTextState()
```

Metin Durumu Oluştur

**Returns:**
TextState örneği

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Metnin arka plan rengini alır veya ayarlar. Null olabilir. {@code BackgroundColor} özelliğini üst yapı öğesinden devralmak için null kullanın.

**Returns:**
Renk örneği

### getCharacterSpacing {#getCharacterSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getCharacterSpacing()
```

Metnin karakter aralığını alır veya ayarlar. Null olabilir. {@code CharacterSpacing} özelliğini üst yapı öğesinden devralmak için null kullanın.

**Returns:**
Float dizisi

### getFont {#getFont--}
```
public final Font getFont()
```

Metnin yazı tipini alır veya ayarlar. Null olabilir. {@code Font} özelliğini üst yapı öğesinden devralmak için null kullanın.

**Returns:**
Font örneği

### getFontSize {#getFontSize--}
```
public final com.aspose.ms.System.Nullable< Float > getFontSize()
```

Metnin yazı tipi boyutunu alır veya ayarlar. Null olabilir. {@code FontSize} özelliğini üst yapı öğesinden devralmak için null kullanın.

**Returns:**
Float dizisi

### getFontStyle {#getFontStyle--}
```
public final com.aspose.ms.System.Nullable< Integer > getFontStyle()
```

Metnin yazı tipi stilini alır veya ayarlar. Null olabilir. {@code FontStyle} özelliğini üst yapı öğesinden devralmak için null kullanın.

**Returns:**
Integer dizisi

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Metnin ön plan rengini alır veya ayarlar. Null olabilir. {@code ForegroundColor} özelliğini üst yapı öğesinden devralmak için null kullanın.

**Returns:**
Renk örneği

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public final com.aspose.ms.System.Nullable< HorizontalAlignment > getHorizontalAlignment()
```

Paragrafın yatay hizalamasını alır veya ayarlar

**Returns:**
HorizontalAlignment öğesi

### getHorizontalScaling {#getHorizontalScaling--}
```
public final com.aspose.ms.System.Nullable< Float > getHorizontalScaling()
```

Metnin yatay ölçeklemesini alır veya ayarlar. Null olabilir. {@code HorizontalScaling} özelliğini üst yapı öğesinden devralmak için null kullanın.

**Returns:**
Float dizisi

### getLineSpacing {#getLineSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getLineSpacing()
```

Metnin satır aralığını alır veya ayarlar. Null olabilir. {@code LineSpacing} özelliğini üst yapı öğesinden devralmak için null kullanın.

**Returns:**
Float dizisi

### getMarginInfo {#getMarginInfo--}
```
@Deprecated public final MarginInfo getMarginInfo()
```

Blok yapı öğesi için kenar boşluğunu alır veya ayarlar.

**Returns:**
MarginInfo örneği @deprecated Konum ayarlarını ayarlamak için IAdjustPosition.AdjustPosition(PositionSettings positionSettings) metodunu kullanın

### getStrikeOut {#getStrikeOut--}
```
public final com.aspose.ms.System.Nullable< Boolean > getStrikeOut()
```

Metin için üstü çizili özelliğini alır veya ayarlar. Null olabilir. {@code StrikeOut} özelliğini üst yapı öğesinden devralmak için null kullanın.

**Returns:**
Boolean dizisi

### getSubscript {#getSubscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSubscript()
```

Metnin alt simgesini alır veya ayarlar. Null olabilir. {@code Subscript} özelliğini üst yapı öğesinden devralmak için null kullanın.

**Returns:**
Boolean dizisi

### getSuperscript {#getSuperscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSuperscript()
```

Metnin üst simgesini alır veya ayarlar. Null olabilir. {@code Superscript} özelliğini üst yapı öğesinden devralmak için null kullanın.

**Returns:**
Boolean dizisi

### getUnderline {#getUnderline--}
```
public final com.aspose.ms.System.Nullable< Boolean > getUnderline()
```

Metin için alt çizgiyi alır veya ayarlar. Null olabilir. {@code Underline} özelliğini üst yapı öğesinden devralmak için null kullanın.

**Returns:**
Boolean dizisi

### getVerticalAlignment {#getVerticalAlignment--}
```
public final com.aspose.ms.System.Nullable< VerticalAlignment > getVerticalAlignment()
```

Paragrafın dikey hizalamasını alır veya ayarlar

**Returns:**
VerticalAlignment öğesi

### getWordSpacing {#getWordSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getWordSpacing()
```

Metnin kelime aralığını alır veya ayarlar. Null olabilir. {@code WordSpacing} özelliğini üst yapı öğesinden devralmak için null kullanın.

**Returns:**
Float dizisi

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public final com.aspose.ms.System.Nullable< Boolean > isFirstParagraphInColumn()
```

Bu paragrafın bir sonraki sütunda olup olmayacağını gösteren bir bool değerini alır veya ayarlar. Varsayılan değeri false'dur.

**Returns:**
Boolean değer

### isInLineParagraph {#isInLineParagraph--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInLineParagraph()
```

Paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan değer false'dur.

**Returns:**
Boolean değer

### isInNewPage {#isInNewPage--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInNewPage()
```

Bu paragrafın yeni sayfada oluşturulmasını zorlayan bir bool değerini alır veya ayarlar. Varsayılan değer false'dur.

**Returns:**
Boolean değer

### isKeptWithNext {#isKeptWithNext--}
```
public final com.aspose.ms.System.Nullable< Boolean > isKeptWithNext()
```

Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını gösteren bir bool değerini alır veya ayarlar. Varsayılan değer false'dur.

**Returns:**
Boolean değer

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Metnin arka plan rengini alır veya ayarlar. Null olabilir. {@code BackgroundColor} özelliğini üst yapı öğesinden devralmak için null kullanın.

### setCharacterSpacing {#setCharacterSpacing-com.aspose.ms.System.Nullable-}
Metnin karakter aralığını alır veya ayarlar.

### setFont {#setFont-com.aspose.pdf.Font-}
Metnin yazı tipini alır veya ayarlar. Null olabilir. {@code Font} özelliğini üst yapı öğesinden devralmak için null kullanın.

### setFontSize {#setFontSize-com.aspose.ms.System.Nullable-}
Metnin yazı tipi boyutunu alır veya ayarlar.

### setFontStyle {#setFontStyle-com.aspose.ms.System.Nullable-}
Metnin yazı tipi stilini alır veya ayarlar.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Metnin ön plan rengini alır veya ayarlar. Null olabilir. {@code ForegroundColor} özelliğini üst yapı öğesinden devralmak için null kullanın.

### setHorizontalScaling {#setHorizontalScaling-com.aspose.ms.System.Nullable-}
Metnin yatay ölçeklemesini alır veya ayarlar.

### setLineSpacing {#setLineSpacing-com.aspose.ms.System.Nullable-}
Metnin satır aralığını alır veya ayarlar.

### setMarginInfo {#setMarginInfo-com.aspose.pdf.MarginInfo-}
Blok yapı öğesi için kenar boşluğunu alır veya ayarlar.

### setStrikeOut {#setStrikeOut-com.aspose.ms.System.Nullable-}
Metnin üstü çizili özelliğini alır veya ayarlar.

### setSubscript {#setSubscript-com.aspose.ms.System.Nullable-}
Metnin alt simgesini alır veya ayarlar.

### setSuperscript {#setSuperscript-com.aspose.ms.System.Nullable-}
Metnin üst simgesini alır veya ayarlar.

### setUnderline {#setUnderline-com.aspose.ms.System.Nullable-}
Metnin altını çizmeyi alır veya ayarlar.

### setWordSpacing {#setWordSpacing-com.aspose.ms.System.Nullable-}
Metnin kelime aralığını alır veya ayarlar.

### update {#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-}
Elemanları güncelle
