---
title: Document.Convert
second_title: Aspose.PDF for .NET API Reference
description: Método do documento. Converta o documento e salve erros no arquivo especificado
type: docs
weight: 580
url: /pt/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

Converta o documento e salve erros no arquivo especificado.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputLogFileName | String | Caminho para o arquivo onde os comentários serão armazenados. |
| format | PdfFormat | O formato pdf. |
| action | ConvertErrorAction | Ação para objetos que não podem ser convertidos |
| transparencyAction | ConvertTransparencyAction | Ação para objetos de imagem mascarados |

### Valor de Retorno

O resultado da operação

### Veja Também

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

Converta o documento e salve erros no arquivo especificado.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputLogStream | Stream | Stream onde os comentários serão armazenados. |
| format | PdfFormat | O formato pdf. |
| action | ConvertErrorAction | Ação para objetos que não podem ser convertidos |
| transparencyAction | ConvertTransparencyAction | Ação para objetos de imagem mascarados |

### Valor de Retorno

O resultado da operação

### Veja Também

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

Converta o documento e salve erros no arquivo especificado.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputLogFileName | String | Caminho para o arquivo onde os comentários serão armazenados. |
| format | PdfFormat | O formato pdf. |
| action | ConvertErrorAction | Ação para objetos que não podem ser convertidos |

### Valor de Retorno

O resultado da operação

### Veja Também

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Converta o documento usando as opções de conversão especificadas

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | PdfFormatConversionOptions | conjunto de opções para converter o documento PDF |

### Valor de Retorno

O resultado da operação

### Veja Também

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Reconheça imagens dentro do documento e adicione strings hocr sobre ele.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | Ação para imagens que serão processadas pelo reconhecimento hocr. |
| flattenImages | Boolean | O texto nas imagens pdf pode ser pintado usando a mecânica de máscaras, nesse caso as imagens devem ser achatadas. |

### Valor de Retorno

O resultado da operação. Se não houver imagens no documento, retorna !:false.

### Veja Também

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

Reconheça imagens dentro do documento e adicione strings hocr sobre ele.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| callback | CallBackGetHocr | Ação para imagens que serão processadas pelo reconhecimento hocr. |
| flattenImages | Boolean | O texto nas imagens pdf pode ser pintado usando a mecânica de máscaras, nesse caso as imagens devem ser achatadas. |

### Valor de Retorno

O resultado da operação. Se não houver imagens no documento, retorna !:false.

### Veja Também

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

Converta o documento e salve erros no stream especificado.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputLogStream | Stream | Stream onde os comentários serão armazenados. |
| format | PdfFormat | Formato pdf. |
| action | ConvertErrorAction | Ação para objetos que não podem ser convertidos |

### Valor de Retorno

O resultado da operação

### Veja Também

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Converta o documento aplicando o Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fixup | Fixup | O tipo de Fixup. |
| outputLog | Stream | O log do processo. |
| onlyValidation | Boolean | Apenas validação do documento. |
| parameters | Object[] | Propriedades para Fixup que não podem ser definidas. |

### Valor de Retorno

O resultado da operação.

### Veja Também

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Converta o documento aplicando o Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fixup | Fixup | O tipo de Fixup. |
| outputLog | String | O log do processo. |
| onlyValidation | Boolean | Apenas validação do documento. |
| parameters | Object[] | Propriedades para Fixup que não podem ser definidas. |

### Valor de Retorno

O resultado da operação.

### Veja Também

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Converte o arquivo de origem no formato de origem para o arquivo de destino no formato de destino.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcFileName | String | O nome do arquivo de origem. |
| loadOptions | LoadOptions | O formato do arquivo de origem. |
| dstFileName | String | O nome do arquivo de destino. |
| saveOptions | SaveOptions | O formato do arquivo de destino. |

### Veja Também

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Converte o stream no formato de origem para o arquivo de destino no formato de destino.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcStream | Stream | O stream de origem. |
| loadOptions | LoadOptions | O formato do stream de origem. |
| dstFileName | String | O nome do arquivo de destino. |
| saveOptions | SaveOptions | O formato do arquivo de destino. |

### Veja Também

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Converte o arquivo de origem no formato de origem para o stream no formato de destino.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcFileName | String | O nome do arquivo de origem. |
| loadOptions | LoadOptions | O formato do arquivo de origem. |
| dstStream | Stream | O stream de destino. |
| saveOptions | SaveOptions | O formato do stream de destino. |

### Veja Também

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Converte o stream no formato de origem para o stream no formato de destino.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcStream | Stream | O stream de origem. |
| loadOptions | LoadOptions | O formato do stream de origem. |
| dstStream | Stream | O stream de destino. |
| saveOptions | SaveOptions | O formato do arquivo de destino. |

### Veja Também

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)