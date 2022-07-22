---
title: Convert
second_title: Aspose.PDF för .NET API Referens
description: Konverterar källfil i källformat till målfil i målformat.
type: docs
weight: 790
url: /sv/net/aspose.pdf/document/convert/
---
## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Konverterar källfil i källformat till målfil i målformat.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | String | Källfilens namn. |
| loadOptions | LoadOptions | Källfilens format. |
| dstFileName | String | Destinationsfilens namn. |
| saveOptions | SaveOptions | Målfilformatet. |

### Se även

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Konverterar ström i källformat till målfil i målformat.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcStream | Stream | Källströmmen. |
| loadOptions | LoadOptions | Källströmmens format. |
| dstFileName | String | Destinationsfilens namn. |
| saveOptions | SaveOptions | Målfilformatet. |

### Se även

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Konverterar källfil i källformat till stream i målformat.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | String | Källfilens namn. |
| loadOptions | LoadOptions | Källfilens format. |
| dstStream | Stream | Målströmmen. |
| saveOptions | SaveOptions | Destinationsströmformatet. |

### Se även

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Konverterar ström i källformat till ström i målformat.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcStream | Stream | Källströmmen. |
| loadOptions | LoadOptions | Källströmmens format. |
| dstStream | Stream | Målströmmen. |
| saveOptions | SaveOptions | Målfilformatet. |

### Se även

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_7}

Konvertera dokument och spara fel till den angivna filen.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogFileName | String | Sökväg till fil där kommentarerna kommer att lagras. |
| format | PdfFormat | Pdf-format. |
| action | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras |
| transparencyAction | ConvertTransparencyAction | Åtgärd för bildmaskerade objekt |

### Returvärde

Operationsresultatet

### Se även

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_5}

Konvertera dokument och spara fel till den angivna filen.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogStream | Stream | Streama där kommentarerna kommer att lagras. |
| format | PdfFormat | Pdf-format. |
| action | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras |
| transparencyAction | ConvertTransparencyAction | Åtgärd för bildmaskerade objekt |

### Returvärde

Operationsresultatet

### Se även

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_6}

Konvertera dokument och spara fel till den angivna filen.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogFileName | String | Sökväg till fil där kommentarerna kommer att lagras. |
| format | PdfFormat | Pdf-format. |
| action | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras |

### Returvärde

Operationsresultatet

### Se även

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Konvertera dokument med angivna konverteringsalternativ

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | PdfFormatConversionOptions | uppsättning alternativ för att konvertera PDF-dokument |

### Returvärde

Operationsresultatet

### Se även

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr) {#convert_3}

Konvertera dokument och spara fel till den angivna filen.

```csharp
public bool Convert(CallBackGetHocr callback)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | CallBackGetHocr | Åtgärd för objekt som inte kan konverteras |

### Returvärde

Operationsresultatet

### Se även

* delegate [CallBackGetHocr](../../document.callbackgethocr)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_4}

Konvertera dokument och spara fel i den angivna strömmen.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogStream | Stream | Streama där kommentarerna kommer att lagras. |
| format | PdfFormat | Pdf-format. |
| action | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras |

### Returvärde

Operationsresultatet

### Se även

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Konvertera dokument genom att använda Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fixup | Fixup | Fixup-typen. |
| outputLog | Stream | Loggen över processen. |
| onlyValidation | Boolean | Endast dokumentvalidering. |
| parameters | Object[] | Egenskaper för Fixup som inte kan ställas in. |

### Returvärde

Operationsresultatet.

### Se även

* enum [Fixup](../../fixup)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Konvertera dokument genom att använda Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fixup | Fixup | Fixup-typen. |
| outputLog | String | Loggen över processen. |
| onlyValidation | Boolean | Endast dokumentvalidering. |
| parameters | Object[] | Egenskaper för Fixup som inte kan ställas in. |

### Returvärde

Operationsresultatet.

### Se även

* enum [Fixup](../../fixup)
* class [Document](../../document)
* namnutrymme [Aspose.Pdf](../../document)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
