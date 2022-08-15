---
title: Convert
second_title: Aspose.PDF für .NET-API-Referenz
description: Konvertiert Quelldatei im Quellformat in Zieldatei im Zielformat.
type: docs
weight: 790
url: /de/net/aspose.pdf/document/convert/
---
## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Konvertiert Quelldatei im Quellformat in Zieldatei im Zielformat.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcFileName | String | Der Name der Quelldatei. |
| loadOptions | LoadOptions | Das Quelldateiformat. |
| dstFileName | String | Der Name der Zieldatei. |
| saveOptions | SaveOptions | Das Zieldateiformat. |

### Siehe auch

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Konvertiert Stream im Quellformat in Zieldatei im Zielformat.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcStream | Stream | Der Quellstrom. |
| loadOptions | LoadOptions | Das Quellstreamformat. |
| dstFileName | String | Der Name der Zieldatei. |
| saveOptions | SaveOptions | Das Zieldateiformat. |

### Siehe auch

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Konvertiert Quelldatei im Quellformat in Stream im Zielformat.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcFileName | String | Der Name der Quelldatei. |
| loadOptions | LoadOptions | Das Quelldateiformat. |
| dstStream | Stream | Der Zielstream. |
| saveOptions | SaveOptions | Das Ziel-Stream-Format. |

### Siehe auch

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Konvertiert Stream im Quellformat in Stream im Zielformat.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcStream | Stream | Der Quellstrom. |
| loadOptions | LoadOptions | Das Quellstreamformat. |
| dstStream | Stream | Der Zielstream. |
| saveOptions | SaveOptions | Das Zieldateiformat. |

### Siehe auch

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_7}

Dokument konvertieren und Fehler in der angegebenen Datei speichern.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputLogFileName | String | Pfad zur Datei, in der die Kommentare gespeichert werden. |
| format | PdfFormat | Das pdf-Format. |
| action | ConvertErrorAction | Aktion für Objekte, die nicht konvertiert werden können |
| transparencyAction | ConvertTransparencyAction | Aktion für bildmaskierte Objekte |

### Rückgabewert

Das Operationsergebnis

### Siehe auch

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_5}

Dokument konvertieren und Fehler in der angegebenen Datei speichern.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputLogStream | Stream | Stream, wo die Kommentare gespeichert werden. |
| format | PdfFormat | Das pdf-Format. |
| action | ConvertErrorAction | Aktion für Objekte, die nicht konvertiert werden können |
| transparencyAction | ConvertTransparencyAction | Aktion für bildmaskierte Objekte |

### Rückgabewert

Das Operationsergebnis

### Siehe auch

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_6}

Dokument konvertieren und Fehler in der angegebenen Datei speichern.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputLogFileName | String | Pfad zur Datei, in der die Kommentare gespeichert werden. |
| format | PdfFormat | Das pdf-Format. |
| action | ConvertErrorAction | Aktion für Objekte, die nicht konvertiert werden können |

### Rückgabewert

Das Operationsergebnis

### Siehe auch

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Dokument mit angegebenen Konvertierungsoptionen konvertieren

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | PdfFormatConversionOptions | Satz von Optionen zum Konvertieren von PDF-Dokumenten |

### Rückgabewert

Das Operationsergebnis

### Siehe auch

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr) {#convert_3}

Dokument konvertieren und Fehler in der angegebenen Datei speichern.

```csharp
public bool Convert(CallBackGetHocr callback)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | CallBackGetHocr | Aktion für Objekte, die nicht konvertiert werden können |

### Rückgabewert

Das Operationsergebnis

### Siehe auch

* delegate [CallBackGetHocr](../../document.callbackgethocr)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_4}

Dokument konvertieren und Fehler im angegebenen Stream speichern.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputLogStream | Stream | Stream, wo die Kommentare gespeichert werden. |
| format | PdfFormat | PDF-Format. |
| action | ConvertErrorAction | Aktion für Objekte, die nicht konvertiert werden können |

### Rückgabewert

Das Operationsergebnis

### Siehe auch

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Konvertieren Sie das Dokument, indem Sie das Fixup anwenden.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fixup | Fixup | Der Fixup-Typ. |
| outputLog | Stream | Das Protokoll des Prozesses. |
| onlyValidation | Boolean | Nur Dokumentenvalidierung. |
| parameters | Object[] | Eigenschaften für Fixup, die nicht festgelegt werden können. |

### Rückgabewert

Das Operationsergebnis.

### Siehe auch

* enum [Fixup](../../fixup)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Konvertieren Sie das Dokument, indem Sie das Fixup anwenden.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fixup | Fixup | Der Fixup-Typ. |
| outputLog | String | Das Protokoll des Prozesses. |
| onlyValidation | Boolean | Nur Dokumentenvalidierung. |
| parameters | Object[] | Eigenschaften für Fixup, die nicht festgelegt werden können. |

### Rückgabewert

Das Operationsergebnis.

### Siehe auch

* enum [Fixup](../../fixup)
* class [Document](../../document)
* namensraum [Aspose.Pdf](../../document)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
