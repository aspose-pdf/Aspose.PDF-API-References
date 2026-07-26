---
title: "XImage"
linktitle: "XImage"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die ein Bild-X-Objekt darstellt."
type: docs
weight: 5610
url: /de/java/com.aspose.pdf/ximage/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImage

```
public final class XImage extends Object
```

Klasse, die ein Bild-X-Objekt darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XImage](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | Nur für den internen Gebrauch. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addStencilMask](#addStencilMask-java.io.InputStream-) | Fügt der XImage eine Schablonenmaske hinzu. |
| [containsTransparency](#containsTransparency--) | Wenn das Bild Transparenz enthält, wird true zurückgegeben; andernfalls false. |
| [delete](#delete--) | Löscht das Bild aus der übergeordneten Sammlung. |
| [detectColorType](#detectColorType-java.awt.image.BufferedImage-) | Gibt den Farbtyp des Bildes zurück. |
| [getAlternativeText](#getAlternativeText-com.aspose.pdf.Page-) | Gibt eine Liste von Zeichenketten mit Alternativtext für ein XImage zurück. |
| [getColorType](#getColorType--) | Gibt den Farbtyp des Bildes zurück. |
| [getEngineImg](#getEngineImg--) | IPdfImage-Objekt, das das Bild beschreibt. Nur intern. |
| [getFilterType](#getFilterType--) | Ermittelt den Bildfiltertyp. |
| [getGrayscaled](#getGrayscaled--) | Ermittelt die Graustufen-Version des Bildes. |
| [getHeight](#getHeight--) | Ermittelt die Höhe des Bildes. |
| [getImage](#getImage--) | Nur für den internen Gebrauch. |
| [getMetadata](#getMetadata--) | Metadaten des Bildes. |
| [getName](#getName--) | Ermittelt den Bildnamen. Bitte beachten Sie, dass das Ändern des Namens eines Bildes, das in Seiteninhalten referenziert wird, das Dokument inkorrekt machen kann. Verwenden Sie in diesem Fall die Methode XImage.Rename. |
| [getNameInCollection](#getNameInCollection--) | Gibt den Namen des Bildes in seiner Sammlung zurück. |
| [getRawBytes](#getRawBytes--) | Gibt die rohen Bytes des Bildes ohne Dekodierung zurück. |
| [getRawImageData](#getRawImageData--) | Ruft die rohen Bilddaten aus dem Quellbild ab. |
| [getRawParameters](#getRawParameters--) | Ermittelt die rohen Bildparameter |
| [getWidth](#getWidth--) | Ermittelt die Breite des Bildes. |
| [isImage](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | Gibt true zurück, wenn das Primitive ein Bild ist. |
| [isImageMask](#isImageMask--) | Liefert ein Flag, das angibt, ob das Bild als Bildmaske behandelt werden soll (siehe 8.9.6, "Masked Images"). Wenn dieses Flag true ist, muss der Wert von BitsPerComponent 1 sein und Mask und ColorSpace dürfen nicht angegeben werden; nicht maskierte Bereiche werden mit der aktuellen Nicht‑Strich‑Farbe gemalt. Standardwert: false. Wert: True ist, wenn das Bild eine Bildmaske ist. |
| [isTheSameObject](#isTheSameObject-com.aspose.pdf.XImage-) | Gibt true zurück, wenn beide Bilder auf dasselbe Objekt verweisen. |
| [rename](#rename-java.lang.String-) | Benennt das Bild um und ersetzt alle Verweise auf das Bild durch den neuen Namen. |
| [replace](#replace-java.io.InputStream-) | Ersetzt das Bild im Stream, der in {@code image} angegeben ist. * |
| [save](#save-java.io.OutputStream-) | Speichert Bilddaten in den Stream als JPEG-Bild. |
| [save](#save-java.io.OutputStream-float-float-) | Speichert das Bild in den Stream im gewünschten Format. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Speichert das Bild in den Stream im gewünschten Format. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Speichert das Bild in den Stream im gewünschten Format. |
| [save](#save-java.io.OutputStream-int-) | Speichert das Bild in den Stream im gewünschten Format mit angegebener Auflösung. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-) | Speichert das Bild in den Stream im gewünschten Format. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | Speichert Bilddaten in den Stream als JPEG-Bild mit angegebener Auflösung. |
| [setName](#setName-java.lang.String-) | Setzt den Bildnamen. Bitte beachten Sie, dass das Ändern des Namens eines Bildes, das Verweise im Seiteninhalt hat, das Dokument inkorrekt machen kann. Bitte verwenden Sie in diesem Fall die Methode XImage.Rename. |
| [toStream](#toStream--) | Gibt den ursprünglichen Bild-Stream zurück. |
| [toString](#toString--) | Gibt eine String‑Darstellung der Eigenschaften des XImage‑Objekts zurück. |
| [trySetAlternativeText](#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-) | Setzt den Alternativtext für ein XImage auf der Seite. |

### XImage {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
Nur für den internen Gebrauch.

### addStencilMask {#addStencilMask-java.io.InputStream-}
Fügt der XImage eine Schablonenmaske hinzu.

### containsTransparency {#containsTransparency--}
```
public boolean containsTransparency()
```

Wenn das Bild Transparenz enthält, wird true zurückgegeben; andernfalls false.

**Returns:**
boolescher Wert

### delete {#delete--}
```
public void delete()
```

Löscht das Bild aus der übergeordneten Sammlung.

### detectColorType {#detectColorType-java.awt.image.BufferedImage-}
Gibt den Farbtyp des Bildes zurück.

### getAlternativeText {#getAlternativeText-com.aspose.pdf.Page-}
Gibt eine Liste von Zeichenketten mit Alternativtext für ein XImage zurück.

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Gibt den Farbtyp des Bildes zurück.

**Returns:**
Der Farbtypwert.

### getEngineImg {#getEngineImg--}
```
public com.aspose.pdf.engine.data.IPdfDataStream getEngineImg()
```

IPdfImage-Objekt, das das Bild beschreibt. Nur intern.

**Returns:**
IPdfDataStream

### getFilterType {#getFilterType--}
```
public final ImageFilterType getFilterType()
```

Ermittelt den Bildfiltertyp.

**Returns:**
ImageFilterType‑Element

### getGrayscaled {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```

Ermittelt die Graustufen-Version des Bildes.

**Returns:**
BufferedImage

### getHeight {#getHeight--}
```
public int getHeight()
```

Ermittelt die Höhe des Bildes.

**Returns:**
int-Wert

### getImage {#getImage--}
```
public com.aspose.ms.System.Drawing.Bitmap getImage()
```

Nur für den internen Gebrauch.

**Returns:**
Bild

### getMetadata {#getMetadata--}
```
public final Metadata getMetadata()
```

Metadaten des Bildes.

**Returns:**
Metadata‑Instanz

### getName {#getName--}
```
public String getName()
```

Ermittelt den Bildnamen. Bitte beachten Sie, dass das Ändern des Namens eines Bildes, das in Seiteninhalten referenziert wird, das Dokument inkorrekt machen kann. Verwenden Sie in diesem Fall die Methode XImage.Rename.

**Returns:**
String

### getNameInCollection {#getNameInCollection--}
```
public String getNameInCollection()
```

Gibt den Namen des Bildes in seiner Sammlung zurück.

**Returns:**
Bildschlüssel (Name).

### getRawBytes {#getRawBytes--}
```
public byte[] getRawBytes()
```

Gibt die rohen Bytes des Bildes ohne Dekodierung zurück.

**Returns:**
Byte‑Array

### getRawImageData {#getRawImageData--}
```
public final byte[] getRawImageData()
```

Ruft die rohen Bilddaten aus dem Quellbild ab.

**Returns:**
Ein {@link byte[]} mit den ursprünglichen Bilddaten.

### getRawParameters {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```

Ermittelt die rohen Bildparameter

**Returns:**
RawParameters‑Instanz

### getWidth {#getWidth--}
```
public int getWidth()
```

Ermittelt die Breite des Bildes.

**Returns:**
int-Wert

### isImage {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
Gibt true zurück, wenn das Primitive ein Bild ist.

### isImageMask {#isImageMask--}
```
public final boolean isImageMask()
```

Liefert ein Flag, das angibt, ob das Bild als Bildmaske behandelt werden soll (siehe 8.9.6, "Masked Images"). Wenn dieses Flag true ist, muss der Wert von BitsPerComponent 1 sein und Mask und ColorSpace dürfen nicht angegeben werden; nicht maskierte Bereiche werden mit der aktuellen Nicht‑Strich‑Farbe gemalt. Standardwert: false. Wert: True ist, wenn das Bild eine Bildmaske ist.

**Returns:**
boolescher Wert

### isTheSameObject {#isTheSameObject-com.aspose.pdf.XImage-}
Gibt true zurück, wenn beide Bilder auf dasselbe Objekt verweisen.

### rename {#rename-java.lang.String-}
Benennt das Bild um und ersetzt alle Verweise auf das Bild durch den neuen Namen.

### replace {#replace-java.io.InputStream-}
Ersetzt das Bild im Stream, der in {@code image} angegeben ist. *

### save {#save-java.io.OutputStream-}
Speichert Bilddaten in den Stream als JPEG-Bild.

### save {#save-java.io.OutputStream-float-float-}
Speichert das Bild in den Stream im gewünschten Format.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Speichert das Bild in den Stream im gewünschten Format.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Speichert das Bild in den Stream im gewünschten Format.

### save {#save-java.io.OutputStream-int-}
Speichert das Bild in den Stream im gewünschten Format mit angegebener Auflösung.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-}
Speichert das Bild in den Stream im gewünschten Format.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}


### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
Speichert Bilddaten in den Stream als JPEG-Bild mit angegebener Auflösung.

### setName {#setName-java.lang.String-}
Setzt den Bildnamen. Bitte beachten Sie, dass das Ändern des Namens eines Bildes, das Verweise im Seiteninhalt hat, das Dokument inkorrekt machen kann. Bitte verwenden Sie in diesem Fall die Methode XImage.Rename.

### toStream {#toStream--}
```
public InputStream toStream()
```

Gibt den ursprünglichen Bild-Stream zurück.

**Returns:**
Der ursprüngliche Bild-Stream.

### toString {#toString--}
```
public String toString()
```

Gibt eine String‑Darstellung der Eigenschaften des XImage‑Objekts zurück.

**Returns:**
String‑Instanz

### trySetAlternativeText {#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-}
Setzt den Alternativtext für ein XImage auf der Seite.
