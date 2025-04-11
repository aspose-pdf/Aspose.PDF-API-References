---
title: Document.Convert
second_title: Aspose.PDF for .NET API Reference
description: Dokumentmetod. Konvertera dokument och spara fel i den angivna filen
type: docs
weight: 580
url: /sv/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

Konvertera dokument och spara fel i den angivna filen.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogFileName | Sträng | Sökväg till fil där kommentarerna kommer att lagras. |
| format | PdfFormat | PDF-formatet. |
| action | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras |
| transparencyAction | ConvertTransparencyAction | Åtgärd för bildmaskerade objekt |

### Returvärde

Operationens resultat

### Se Även

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

Konvertera dokument och spara fel i den angivna filen.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogStream | Ström | Ström där kommentarerna kommer att lagras. |
| format | PdfFormat | PDF-formatet. |
| action | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras |
| transparencyAction | ConvertTransparencyAction | Åtgärd för bildmaskerade objekt |

### Returvärde

Operationens resultat

### Se Även

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

Konvertera dokument och spara fel i den angivna filen.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogFileName | Sträng | Sökväg till fil där kommentarerna kommer att lagras. |
| format | PdfFormat | PDF-formatet. |
| action | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras |

### Returvärde

Operationens resultat

### Se Även

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

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

Operationens resultat

### Se Även

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Känna igen bilder inuti dokumentet och lägga till hocr-strängar över det.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | Åtgärd för bilder som kommer att behandlas av hocr-igenkänning. |
| flattenImages | Boolean | Text i PDF-bilder kan målas med hjälp av maskmekanik, i vilket fall bilderna måste plattas ut. |

### Returvärde

Operationens resultat. Om det inte finns några bilder i dokumentet returneras !:false.

### Se Även

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

Känna igen bilder inuti dokumentet och lägga till hocr-strängar över det.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | CallBackGetHocr | Åtgärd för bilder som kommer att behandlas av hocr-igenkänning. |
| flattenImages | Boolean | Text i PDF-bilder kan målas med hjälp av maskmekanik, i vilket fall bilderna måste plattas ut. |

### Returvärde

Operationens resultat. Om det inte finns några bilder i dokumentet returneras !:false.

### Se Även

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

Konvertera dokument och spara fel i den angivna strömmen.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogStream | Ström | Ström där kommentarerna kommer att lagras. |
| format | PdfFormat | PDF-format. |
| action | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras |

### Returvärde

Operationens resultat

### Se Även

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Konvertera dokument genom att tillämpa Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fixup | Fixup | Typen av Fixup. |
| outputLog | Ström | Loggen av processen. |
| onlyValidation | Boolean | Endast dokumentvalidering. |
| parameters | Object[] | Egenskaper för Fixup som inte kan ställas in. |

### Returvärde

Operationens resultat.

### Se Även

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Konvertera dokument genom att tillämpa Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fixup | Fixup | Typen av Fixup. |
| outputLog | Sträng | Loggen av processen. |
| onlyValidation | Boolean | Endast dokumentvalidering. |
| parameters | Object[] | Egenskaper för Fixup som inte kan ställas in. |

### Returvärde

Operationens resultat.

### Se Även

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Konverterar källfil i källformat till destinationsfil i destinationsformat.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | Sträng | Källfilens namn. |
| loadOptions | LoadOptions | Källfilens format. |
| dstFileName | Sträng | Destinationsfilens namn. |
| saveOptions | SaveOptions | Destinationsfilens format. |

### Se Även

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Konverterar ström i källformat till destinationsfil i destinationsformat.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcStream | Ström | Källströmmen. |
| loadOptions | LoadOptions | Källströmformatet. |
| dstFileName | Sträng | Destinationsfilens namn. |
| saveOptions | SaveOptions | Destinationsfilens format. |

### Se Även

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Konverterar källfil i källformat till ström i destinationsformat.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | Sträng | Källfilens namn. |
| loadOptions | LoadOptions | Källfilens format. |
| dstStream | Ström | Destinationsströmmen. |
| saveOptions | SaveOptions | Destinationsströmformatet. |

### Se Även

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Konverterar ström i källformat till ström i destinationsformat.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcStream | Ström | Källströmmen. |
| loadOptions | LoadOptions | Källströmformatet. |
| dstStream | Ström | Destinationsströmmen. |
| saveOptions | SaveOptions | Destinationsfilens format. |

### Se Även

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)