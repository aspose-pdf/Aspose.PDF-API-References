---
title: "Document.Convert"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Document. Converte il documento e salva gli errori nel file specificato."
type: docs
weight: 600
url: /it/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

Converti il documento e salva gli errori nel file specificato.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputLogFileName | String | Percorso del file in cui verranno memorizzati i commenti. |
| format | PdfFormat | Il formato pdf. |
| azione | ConvertErrorAction | Azione per gli oggetti che non possono essere convertiti |
| transparencyAction | ConvertTransparencyAction | Azione per oggetti mascherati di immagine |

### Valore di ritorno

Il risultato dell'operazione

### Vedi anche

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

Converti il documento e salva gli errori nel file specificato.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputLogStream | Stream | Flusso in cui verranno memorizzati i commenti. |
| format | PdfFormat | Il formato pdf. |
| azione | ConvertErrorAction | Azione per gli oggetti che non possono essere convertiti |
| transparencyAction | ConvertTransparencyAction | Azione per oggetti mascherati di immagine |

### Valore di ritorno

Il risultato dell'operazione

### Vedi anche

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

Converti il documento e salva gli errori nel file specificato.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputLogFileName | String | Percorso del file in cui verranno memorizzati i commenti. |
| format | PdfFormat | Il formato pdf. |
| azione | ConvertErrorAction | Azione per gli oggetti che non possono essere convertiti |

### Valore di ritorno

Il risultato dell'operazione

### Vedi anche

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Converti il documento usando le opzioni di conversione specificate

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | PdfFormatConversionOptions | insieme di opzioni per convertire il documento PDF |

### Valore di ritorno

Il risultato dell'operazione

### Vedi anche

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Riconosci le immagini all'interno del documento e aggiungi le stringhe hocr sopra di esse.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | Azione per le immagini che saranno elaborate dal riconoscimento hocr. |
| flattenImages | Boolean | Il testo nelle immagini pdf può essere dipinto usando la meccanica delle maschere, nel qual caso le immagini devono essere appiattite. |

### Valore di ritorno

Il risultato dell'operazione. Se non ci sono immagini nel documento restituisce !:false.

### Vedi anche

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

Riconosci le immagini all'interno del documento e aggiungi le stringhe hocr sopra di esse.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | CallBackGetHocr | Azione per le immagini che saranno elaborate dal riconoscimento hocr. |
| flattenImages | Boolean | Il testo nelle immagini pdf può essere dipinto usando la meccanica delle maschere, nel qual caso le immagini devono essere appiattite. |

### Valore di ritorno

Il risultato dell'operazione. Se non ci sono immagini nel documento restituisce !:false.

### Vedi anche

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

Converti il documento e salva gli errori nello stream specificato.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputLogStream | Stream | Flusso in cui verranno memorizzati i commenti. |
| format | PdfFormat | Formato Pdf. |
| azione | ConvertErrorAction | Azione per gli oggetti che non possono essere convertiti |

### Valore di ritorno

Il risultato dell'operazione

### Vedi anche

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Converti il documento applicando il Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fixup | Fixup | Il tipo Fixup. |
| outputLog | Stream | Il log del processo. |
| onlyValidation | Boolean | Solo convalida del documento. |
| parametri | Object[] | Proprietà per Fixup che non possono essere impostate. |

### Valore di ritorno

Il risultato dell'operazione.

### Vedi anche

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Converti il documento applicando il Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fixup | Fixup | Il tipo Fixup. |
| outputLog | String | Il log del processo. |
| onlyValidation | Boolean | Solo convalida del documento. |
| parametri | Object[] | Proprietà per Fixup che non possono essere impostate. |

### Valore di ritorno

Il risultato dell'operazione.

### Vedi anche

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Converte il file di origine nel formato di origine in un file di destinazione nel formato di destinazione.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Il nome del file di origine. |
| loadOptions | LoadOptions | Il formato del file di origine. |
| dstFileName | String | Il nome del file di destinazione. |
| saveOptions | SaveOptions | Il formato del file di destinazione. |

### Vedi anche

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Converte lo stream nel formato sorgente in un file di destinazione nel formato di destinazione.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcStream | Stream | Il flusso di origine. |
| loadOptions | LoadOptions | Il formato del flusso di origine. |
| dstFileName | String | Il nome del file di destinazione. |
| saveOptions | SaveOptions | Il formato del file di destinazione. |

### Vedi anche

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Converte il file sorgente nel formato sorgente in uno stream nel formato di destinazione.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcFileName | String | Il nome del file di origine. |
| loadOptions | LoadOptions | Il formato del file di origine. |
| dstStream | Stream | Il flusso di destinazione. |
| saveOptions | SaveOptions | Il formato del flusso di destinazione. |

### Vedi anche

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Converte lo stream nel formato sorgente in uno stream nel formato di destinazione.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcStream | Stream | Il flusso di origine. |
| loadOptions | LoadOptions | Il formato del flusso di origine. |
| dstStream | Stream | Il flusso di destinazione. |
| saveOptions | SaveOptions | Il formato del file di destinazione. |

### Vedi anche

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


