---
title: "Stamp"
linktitle: "Stamp"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar stämpel."
type: docs
weight: 700
url: /sv/java/com.aspose.pdf.facades/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Stamp

```
public final class Stamp extends Object
```

Klass som representerar stämpel.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Stamp](#Stamp--) | Konstruktor för Stamp-objektet. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bindImage](#bindImage-java.io.InputStream-) | Ställer in bilden som kommer att användas som stämpel. |
| [bindImage](#bindImage-java.lang.String-) | <p> Ställer in bilden som en stämpel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindLogo](#bindLogo-com.aspose.pdf.facades.FormattedText-) | Ställer in text som stämpel. |
| [bindPdf](#bindPdf-java.io.InputStream-int-) | <p> Ställer in PDF-filen och sidnumret som kommer att användas som stämpel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindPdf](#bindPdf-java.lang.String-int-) | <p> Ställer in PDF-filen och sidnumret som kommer att användas som stämpel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindTextState](#bindTextState-com.aspose.pdf.TextState-) | Ställer in texttillståndet för stämpeltexten. |
| [close](#close--) | Stänger denna instans |
| [getBlendingSpace](#getBlendingSpace--) | Hämtar ett BlendingColorSpace-värde som definierar ett färgrymd som används för att utföra transparens- och blandningsoperationer på sidan. |
| [getOpacity](#getOpacity--) | Hämtar opaciteten för stämpeln. |
| [getPageNumber](#getPageNumber--) | Hämtar sidnummer. |
| [getPages](#getPages--) | Hämtar en array med sidnummer som kommer att påverkas av stämpeln. |
| [getQuality](#getQuality--) | Hämtar kvaliteten på bildstämpeln i procent. Giltiga värden 0..100%. |
| [getRotation](#getRotation--) | Hämtar rotationen för stämpeln i grader. |
| [getStampId](#getStampId--) | Hämtar identifieraren för stämpeln. |
| [isBackground](#isBackground--) | Hämtar bakgrundsstatus. Om true placeras stämpeln som bakgrund på den spampade sidan. Som standard är den satt till false. |
| [setBackground](#setBackground-boolean-) | Ställer in bakgrundsstatus. Om true placeras stämpeln som bakgrund på den spampade sidan. Som standard är den satt till false. |
| [setBlendingSpace](#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-) | Ställer in ett BlendingColorSpace‑värde som definierar ett färgområde som används för att utföra transparens‑ och blandningsoperationer på sidan. |
| [setImageSize](#setImageSize-float-float-) | Ställer in storleken på bildstämpeln. Bilden kommer att skalas enligt de angivna värdena. |
| [setOpacity](#setOpacity-float-) | Ställer in opaciteten för stämpeln. |
| [setOrigin](#setOrigin-float-float-) | Ställer in positionen på sidan där stämpeln kommer att placeras. |
| [setPageNumber](#setPageNumber-int-) | Ställer in sidnummer. |
| [setPages](#setPages-int:A-) | <p> Ställer in en array med sidnummer som kommer att påverkas av stämpeln. Om Pages = null påverkas alla sidor i dokumentet. </p> |
| [setQuality](#setQuality-int-) | Ställer in kvaliteten på bildstämpeln i procent. Tillåtna värden 0..100%. |
| [setRotation](#setRotation-float-) | <p> Hämtar eller ställer in rotationen för stämpeln i grader. </p> |
| [setStampId](#setStampId-int-) | Ställer in identifieraren för stämpeln. |

### Stamp {#Stamp--}
```
public Stamp()
```

Konstruktor för Stamp-objektet.

### bindImage {#bindImage-java.io.InputStream-}
Ställer in bilden som kommer att användas som stämpel.

### bindImage {#bindImage-java.lang.String-}
<p> Ställer in bilden som en stämpel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindLogo {#bindLogo-com.aspose.pdf.facades.FormattedText-}
Ställer in text som stämpel.

### bindPdf {#bindPdf-java.io.InputStream-int-}
<p> Ställer in PDF-filen och sidnumret som kommer att användas som stämpel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindPdf {#bindPdf-java.lang.String-int-}
<p> Ställer in PDF-filen och sidnumret som kommer att användas som stämpel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindTextState {#bindTextState-com.aspose.pdf.TextState-}
Ställer in texttillståndet för stämpeltexten.

### close {#close--}
```
public void close()
```

Stänger denna instans

### getBlendingSpace {#getBlendingSpace--}
```
public BlendingColorSpace getBlendingSpace()
```

Hämtar ett BlendingColorSpace-värde som definierar ett färgrymd som används för att utföra transparens- och blandningsoperationer på sidan.

**Returns:**
int‑värde @see BlendingColorSpace

### getOpacity {#getOpacity--}
```
public float getOpacity()
```

Hämtar opaciteten för stämpeln.

**Returns:**
flyttalsvärde

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Hämtar sidnummer.

**Returns:**
int‑värde

### getPages {#getPages--}
```
public int[] getPages()
```

Hämtar en array med sidnummer som kommer att påverkas av stämpeln.

**Returns:**
int-array

### getQuality {#getQuality--}
```
public int getQuality()
```

Hämtar kvaliteten på bildstämpeln i procent. Giltiga värden 0..100%.

**Returns:**
int‑värde

### getRotation {#getRotation--}
```
public float getRotation()
```

Hämtar rotationen för stämpeln i grader.

**Returns:**
flyttalsvärde

### getStampId {#getStampId--}
```
public int getStampId()
```

Hämtar identifieraren för stämpeln.

**Returns:**
int‑värde

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Hämtar bakgrundsstatus. Om true placeras stämpeln som bakgrund på den spampade sidan. Som standard är den satt till false.

**Returns:**
booleskt värde

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Ställer in bakgrundsstatus. Om true placeras stämpeln som bakgrund på den spampade sidan. Som standard är den satt till false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setBlendingSpace {#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-}
Ställer in ett BlendingColorSpace‑värde som definierar ett färgområde som används för att utföra transparens‑ och blandningsoperationer på sidan.

### setImageSize {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```

Ställer in storleken på bildstämpeln. Bilden kommer att skalas enligt de angivna värdena.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Bildbredd. |
| höjd |  | Bildhöjd. |

### setOpacity {#setOpacity-float-}
```
public void setOpacity(float value)
```

Ställer in opaciteten för stämpeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setOrigin {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```

Ställer in positionen på sidan där stämpeln kommer att placeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| originX |  | X‑koordinat för stämpeln. |
| originY |  | Y‑koordinat för stämpeln. |

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Ställer in sidnummer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setPages {#setPages-int:A-}
```
public void setPages(int[] value)
```

<p> Ställer in en array med sidnummer som kommer att påverkas av stämpeln. Om Pages = null påverkas alla sidor i dokumentet. </p>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑array <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.bindLogo(new FormattedText(text)); //put stamp only on 1st, 4th and 6th page. stamp.setPages(new int[] { 1, 4, 6 }); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Ställer in kvaliteten på bildstämpeln i procent. Tillåtna värden 0..100%.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setRotation {#setRotation-float-}
```
public void setRotation(float value)
```

<p> Hämtar eller ställer in rotationen för stämpeln i grader. </p>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | float‑värde <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindLogo(new FormattedText("STAMP")); stamp.setRotation(90); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Ställer in identifieraren för stämpeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |
