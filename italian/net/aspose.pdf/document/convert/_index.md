---
title: Document.Convert
second_title: Aspose.PDF for .NET API Reference
description: Metodo del documento. Converte il documento e salva gli errori nel file specificato
type: docs
weight: 580
url: /it/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

Converte il documento e salva gli errori nel file specificato.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter            | Type                         | Description                                                                 |
| -------------------- | ---------------------------- | --------------------------------------------------------------------------- |
| outputLogFileName    | String                       | Percorso del file in cui saranno memorizzati i commenti.                   |
| format               | PdfFormat                    | Il formato pdf.                                                             |
| action               | ConvertErrorAction           | Azione per gli oggetti che non possono essere convertiti                    |
| transparencyAction   | ConvertTransparencyAction    | Azione per oggetti con maschera d'immagine                                  |

### Return Value

Il risultato dell'operazione

### See Also

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

Converte il documento e salva gli errori nel file specificato.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter            | Type                         | Description                                                                 |
| -------------------- | ---------------------------- | --------------------------------------------------------------------------- |
| outputLogStream      | Stream                       | Stream in cui saranno memorizzati i commenti.                               |
| format               | PdfFormat                    | Il formato pdf.                                                             |
| action               | ConvertErrorAction           | Azione per gli oggetti che non possono essere convertiti                    |
| transparencyAction   | ConvertTransparencyAction    | Azione per oggetti con maschera d'immagine                                  |

### Return Value

Il risultato dell'operazione

### See Also

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

Converte il documento e salva gli errori nel file specificato.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parameter            | Type               | Description                                                              |
| -------------------- | ------------------ | ------------------------------------------------------------------------ |
| outputLogFileName    | String             | Percorso del file in cui saranno memorizzati i commenti.                |
| format               | PdfFormat          | Il formato pdf.                                                          |
| action               | ConvertErrorAction | Azione per gli oggetti che non possono essere convertiti                 |

### Return Value

Il risultato dell'operazione

### See Also

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Converte il documento utilizzando le opzioni di conversione specificate

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parameter | Type                           | Description                                        |
| --------- | ------------------------------ | -------------------------------------------------- |
| options   | PdfFormatConversionOptions     | Insieme di opzioni per convertire il documento PDF |

### Return Value

Il risultato dell'operazione

### See Also

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Riconosce le immagini all'interno del documento e aggiunge le stringhe hocr sopra di esse.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Parameter      | Type                          | Description                                                                             |
| -------------- | ----------------------------- | --------------------------------------------------------------------------------------- |
| callback       | CallBackGetHocrWithPage       | Azione per le immagini che saranno elaborate dal riconoscimento hocr.                   |
| flattenImages  | Boolean                       | Il testo nelle immagini pdf può essere rappresentato tramite l'uso di maschere, nel qual caso le immagini devono essere appiattite. |

### Return Value

Il risultato dell'operazione. Se non sono presenti immagini nel documento restituisce !:false.

### See Also

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

Riconosce le immagini all'interno del documento e aggiunge le stringhe hocr sopra di esse.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Parameter      | Type             | Description                                                                             |
| -------------- | ---------------- | --------------------------------------------------------------------------------------- |
| callback       | CallBackGetHocr  | Azione per le immagini che saranno elaborate dal riconoscimento hocr.                   |
| flattenImages  | Boolean          | Il testo nelle immagini pdf può essere rappresentato tramite l'uso di maschere, nel qual caso le immagini devono essere appiattite. |

### Return Value

Il risultato dell'operazione. Se non sono presenti immagini nel documento restituisce !:false.

### See Also

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

Converte il documento e salva gli errori nello stream specificato.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parameter         | Type               | Description                                                              |
| ----------------- | ------------------ | ------------------------------------------------------------------------ |
| outputLogStream   | Stream             | Stream in cui saranno memorizzati i commenti.                            |
| format            | PdfFormat          | Il formato pdf.                                                          |
| action            | ConvertErrorAction | Azione per gli oggetti che non possono essere convertiti                 |

### Return Value

Il risultato dell'operazione

### See Also

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Converte il documento applicando il Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter      | Type      | Description                                                   |
| -------------- | --------- | ------------------------------------------------------------- |
| fixup          | Fixup     | Il tipo di Fixup.                                             |
| outputLog      | Stream    | Il registro del processo.                                     |
| onlyValidation | Boolean   | Solo la validazione del documento.                            |
| parameters     | Object[]  | Proprietà per Fixup che non possono essere impostate.         |

### Return Value

Il risultato dell'operazione.

### See Also

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Converte il documento applicando il Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter      | Type      | Description                                                   |
| -------------- | --------- | ------------------------------------------------------------- |
| fixup          | Fixup     | Il tipo di Fixup.                                             |
| outputLog      | String    | Il registro del processo.                                     |
| onlyValidation | Boolean   | Solo la validazione del documento.                            |
| parameters     | Object[]  | Proprietà per Fixup che non possono essere impostate.         |

### Return Value

Il risultato dell'operazione.

### See Also

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Converte il file sorgente, nel formato sorgente, in un file di destinazione, nel formato di destinazione.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter   | Type         | Description                                    |
| ----------- | ------------ | ---------------------------------------------- |
| srcFileName | String       | Il nome del file sorgente.                     |
| loadOptions | LoadOptions  | Il formato del file sorgente.                  |
| dstFileName | String       | Il nome del file di destinazione.              |
| saveOptions | SaveOptions  | Il formato del file di destinazione.           |

### See Also

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Converte uno stream, nel formato sorgente, in un file di destinazione, nel formato di destinazione.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter   | Type         | Description                                    |
| ----------- | ------------ | ---------------------------------------------- |
| srcStream   | Stream       | Lo stream sorgente.                            |
| loadOptions | LoadOptions  | Il formato dello stream sorgente.              |
| dstFileName | String       | Il nome del file di destinazione.              |
| saveOptions | SaveOptions  | Il formato del file di destinazione.           |

### See Also

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Converte il file sorgente, nel formato sorgente, in uno stream di destinazione, nel formato di destinazione.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter   | Type         | Description                                    |
| ----------- | ------------ | ---------------------------------------------- |
| srcFileName | String       | Il nome del file sorgente.                     |
| loadOptions | LoadOptions  | Il formato del file sorgente.                  |
| dstStream   | Stream       | Lo stream di destinazione.                     |
| saveOptions | SaveOptions  | Il formato dello stream di destinazione.       |

### See Also

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Converte uno stream, nel formato sorgente, in uno stream, nel formato di destinazione.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter   | Type         | Description                                    |
| ----------- | ------------ | ---------------------------------------------- |
| srcStream   | Stream       | Lo stream sorgente.                            |
| loadOptions | LoadOptions  | Il formato dello stream sorgente.              |
| dstStream   | Stream       | Lo stream di destinazione.                     |
| saveOptions | SaveOptions  | Il formato del file di destinazione.           |

### See Also

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)