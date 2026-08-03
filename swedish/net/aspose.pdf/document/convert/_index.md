---
title: "Document.Convert"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Document-metod. Konvertera dokumentet och spara fel i den angivna filen"
type: docs
weight: 600
url: /sv/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

Konvertera document och spara fel i den angivna filen.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogFileName | String | Sökväg till filen där kommentarerna kommer att lagras. |
| format | PdfFormat | pdf-formatet. |
| åtgärd | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras. |
| transparencyAction | ConvertTransparencyAction | Åtgärd för bildmaskerade objekt |

### Returvärde

Resultatet av operationen

### Se även

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

Konvertera document och spara fel i den angivna filen.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogStream | Stream | Ström där kommentarerna kommer att lagras. |
| format | PdfFormat | pdf-formatet. |
| åtgärd | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras. |
| transparencyAction | ConvertTransparencyAction | Åtgärd för bildmaskerade objekt |

### Returvärde

Resultatet av operationen

### Se även

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

Konvertera document och spara fel i den angivna filen.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogFileName | String | Sökväg till filen där kommentarerna kommer att lagras. |
| format | PdfFormat | pdf-formatet. |
| åtgärd | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras. |

### Returvärde

Resultatet av operationen

### Se även

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Konvertera document med angivna konverteringsalternativ.

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | PdfFormatConversionOptions | uppsättning av alternativ för att konvertera PDF-dokument |

### Returvärde

Resultatet av operationen

### Se även

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Känn igen bilder i document och lägg till hocr‑strängar ovanpå dem.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | Åtgärd för bilder som kommer att bearbetas av hocr-igenkänning. |
| flattenImages | Boolean | Text i pdf-bilder kan målas med maskmekaniken, i så fall måste bilderna plattas ut. |

### Returvärde

Resultatet av operationen. Om det inte finns några bilder i dokumentet returneras !:false.

### Se även

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

Känn igen bilder i document och lägg till hocr‑strängar ovanpå dem.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | CallBackGetHocr | Åtgärd för bilder som kommer att bearbetas av hocr-igenkänning. |
| flattenImages | Boolean | Text i pdf-bilder kan målas med maskmekaniken, i så fall måste bilderna plattas ut. |

### Returvärde

Resultatet av operationen. Om det inte finns några bilder i dokumentet returneras !:false.

### Se även

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

Konvertera document och spara fel i den angivna streamen.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputLogStream | Stream | Ström där kommentarerna kommer att lagras. |
| format | PdfFormat | Pdf-format. |
| åtgärd | ConvertErrorAction | Åtgärd för objekt som inte kan konverteras. |

### Returvärde

Resultatet av operationen

### Se även

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Konvertera document genom att tillämpa Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fixup | Fixup | Fixup-typen. |
| outputLog | Stream | Loggen för processen. |
| onlyValidation | Boolean | Endast dokumentvalidering. |
| parametrar | Object[] | Egenskaper för Fixup som inte kan ställas in. |

### Returvärde

Resultatet av operationen.

### Se även

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Konvertera document genom att tillämpa Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fixup | Fixup | Fixup-typen. |
| outputLog | String | Loggen för processen. |
| onlyValidation | Boolean | Endast dokumentvalidering. |
| parametrar | Object[] | Egenskaper för Fixup som inte kan ställas in. |

### Returvärde

Resultatet av operationen.

### Se även

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

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
| saveOptions | SaveOptions | Destinationsfilens format. |

### Se även

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

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
| saveOptions | SaveOptions | Destinationsfilens format. |

### Se även

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Konverterar källfil i källformat till ström i målformat.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| srcFileName | String | Källfilens namn. |
| loadOptions | LoadOptions | Källfilens format. |
| dstStream | Stream | Den destinationströmmen. |
| saveOptions | SaveOptions | Destinationsströmmens format. |

### Se även

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

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
| dstStream | Stream | Den destinationströmmen. |
| saveOptions | SaveOptions | Destinationsfilens format. |

### Se även

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


