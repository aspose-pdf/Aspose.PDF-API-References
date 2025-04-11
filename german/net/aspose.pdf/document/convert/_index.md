---
title: Document.Convert
second_title: Aspose.PDF for .NET API Reference
description: Dokumentmethode. Dokument konvertieren und Fehler in die angegebene Datei speichern
type: docs
weight: 580
url: /de/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

Dokument konvertieren und Fehler in die angegebene Datei speichern.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputLogFileName | String | Pfad zur Datei, in der die Kommentare gespeichert werden. |
| format | PdfFormat | Das PDF-Format. |
| action | ConvertErrorAction | Aktion für Objekte, die nicht konvertiert werden können |
| transparencyAction | ConvertTransparencyAction | Aktion für bildmaskierte Objekte |

### Rückgabewert

Das Ergebnis der Operation

### Siehe auch

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

Dokument konvertieren und Fehler in die angegebene Datei speichern.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputLogStream | Stream | Stream, in dem die Kommentare gespeichert werden. |
| format | PdfFormat | Das PDF-Format. |
| action | ConvertErrorAction | Aktion für Objekte, die nicht konvertiert werden können |
| transparencyAction | ConvertTransparencyAction | Aktion für bildmaskierte Objekte |

### Rückgabewert

Das Ergebnis der Operation

### Siehe auch

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

Dokument konvertieren und Fehler in die angegebene Datei speichern.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputLogFileName | String | Pfad zur Datei, in der die Kommentare gespeichert werden. |
| format | PdfFormat | Das PDF-Format. |
| action | ConvertErrorAction | Aktion für Objekte, die nicht konvertiert werden können |

### Rückgabewert

Das Ergebnis der Operation

### Siehe auch

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Dokument konvertieren unter Verwendung der angegebenen Konvertierungsoptionen

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | PdfFormatConversionOptions | Satz von Optionen zur Konvertierung des PDF-Dokuments |

### Rückgabewert

Das Ergebnis der Operation

### Siehe auch

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Bilder im Dokument erkennen und hocr-Strings darüber hinzufügen.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | Aktion für Bilder, die von hocr erkannt werden. |
| flattenImages | Boolean | Text in PDF-Bildern kann mit der Mechanik von Masken gemalt werden, in diesem Fall müssen die Bilder abgeflacht werden. |

### Rückgabewert

Das Ergebnis der Operation. Wenn keine Bilder im Dokument vorhanden sind, wird !:false zurückgegeben.

### Siehe auch

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

Bilder im Dokument erkennen und hocr-Strings darüber hinzufügen.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | CallBackGetHocr | Aktion für Bilder, die von hocr erkannt werden. |
| flattenImages | Boolean | Text in PDF-Bildern kann mit der Mechanik von Masken gemalt werden, in diesem Fall müssen die Bilder abgeflacht werden. |

### Rückgabewert

Das Ergebnis der Operation. Wenn keine Bilder im Dokument vorhanden sind, wird !:false zurückgegeben.

### Siehe auch

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

Dokument konvertieren und Fehler in den angegebenen Stream speichern.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputLogStream | Stream | Stream, in dem die Kommentare gespeichert werden. |
| format | PdfFormat | PDF-Format. |
| action | ConvertErrorAction | Aktion für Objekte, die nicht konvertiert werden können |

### Rückgabewert

Das Ergebnis der Operation

### Siehe auch

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Dokument konvertieren, indem das Fixup angewendet wird.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fixup | Fixup | Der Fixup-Typ. |
| outputLog | Stream | Das Protokoll des Prozesses. |
| onlyValidation | Boolean | Nur Dokumentvalidierung. |
| parameters | Object[] | Eigenschaften für Fixup, die nicht gesetzt werden können. |

### Rückgabewert

Das Ergebnis der Operation.

### Siehe auch

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Dokument konvertieren, indem das Fixup angewendet wird.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fixup | Fixup | Der Fixup-Typ. |
| outputLog | String | Das Protokoll des Prozesses. |
| onlyValidation | Boolean | Nur Dokumentvalidierung. |
| parameters | Object[] | Eigenschaften für Fixup, die nicht gesetzt werden können. |

### Rückgabewert

Das Ergebnis der Operation.

### Siehe auch

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Konvertiert die Quelldatei im Quellformat in die Zieldatei im Zielformat.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcFileName | String | Der Name der Quelldatei. |
| loadOptions | LoadOptions | Das Quellformat der Datei. |
| dstFileName | String | Der Name der Zieldatei. |
| saveOptions | SaveOptions | Das Zielformat der Datei. |

### Siehe auch

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Konvertiert den Stream im Quellformat in die Zieldatei im Zielformat.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcStream | Stream | Der Quellstream. |
| loadOptions | LoadOptions | Das Quellformat des Streams. |
| dstFileName | String | Der Name der Zieldatei. |
| saveOptions | SaveOptions | Das Zielformat der Datei. |

### Siehe auch

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Konvertiert die Quelldatei im Quellformat in den Stream im Zielformat.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcFileName | String | Der Name der Quelldatei. |
| loadOptions | LoadOptions | Das Quellformat der Datei. |
| dstStream | Stream | Der Zielstream. |
| saveOptions | SaveOptions | Das Zielformat des Streams. |

### Siehe auch

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Konvertiert den Stream im Quellformat in den Stream im Zielformat.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcStream | Stream | Der Quellstream. |
| loadOptions | LoadOptions | Das Quellformat des Streams. |
| dstStream | Stream | Der Zielstream. |
| saveOptions | SaveOptions | Das Zielformat der Datei. |

### Siehe auch

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)