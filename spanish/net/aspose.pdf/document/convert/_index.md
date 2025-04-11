---
title: Document.Convert
second_title: Aspose.PDF for .NET API Reference
description: Método de documento. Convertir documento y guardar errores en el archivo especificado
type: docs
weight: 580
url: /es/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

Convertir documento y guardar errores en el archivo especificado.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputLogFileName | String | Ruta al archivo donde se almacenarán los comentarios. |
| format | PdfFormat | El formato pdf. |
| action | ConvertErrorAction | Acción para objetos que no se pueden convertir |
| transparencyAction | ConvertTransparencyAction | Acción para objetos de imagen enmascarados |

### Valor de retorno

El resultado de la operación

### Véase también

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

Convertir documento y guardar errores en el archivo especificado.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputLogStream | Stream | Flujo donde se almacenarán los comentarios. |
| format | PdfFormat | El formato pdf. |
| action | ConvertErrorAction | Acción para objetos que no se pueden convertir |
| transparencyAction | ConvertTransparencyAction | Acción para objetos de imagen enmascarados |

### Valor de retorno

El resultado de la operación

### Véase también

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

Convertir documento y guardar errores en el archivo especificado.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputLogFileName | String | Ruta al archivo donde se almacenarán los comentarios. |
| format | PdfFormat | El formato pdf. |
| action | ConvertErrorAction | Acción para objetos que no se pueden convertir |

### Valor de retorno

El resultado de la operación

### Véase también

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Convertir documento utilizando las opciones de conversión especificadas

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | PdfFormatConversionOptions | conjunto de opciones para convertir el documento PDF |

### Valor de retorno

El resultado de la operación

### Véase también

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Reconocer imágenes dentro del documento y agregar cadenas hocr sobre él.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | Acción para imágenes que serán procesadas por el reconocimiento hocr. |
| flattenImages | Boolean | El texto en imágenes pdf puede ser pintado usando la mecánica de máscaras, en cuyo caso las imágenes deben ser aplanadas. |

### Valor de retorno

El resultado de la operación. Si no hay imágenes en el documento, devuelve !:false.

### Véase también

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

Reconocer imágenes dentro del documento y agregar cadenas hocr sobre él.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | CallBackGetHocr | Acción para imágenes que serán procesadas por el reconocimiento hocr. |
| flattenImages | Boolean | El texto en imágenes pdf puede ser pintado usando la mecánica de máscaras, en cuyo caso las imágenes deben ser aplanadas. |

### Valor de retorno

El resultado de la operación. Si no hay imágenes en el documento, devuelve !:false.

### Véase también

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

Convertir documento y guardar errores en el flujo especificado.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputLogStream | Stream | Flujo donde se almacenarán los comentarios. |
| format | PdfFormat | Formato pdf. |
| action | ConvertErrorAction | Acción para objetos que no se pueden convertir |

### Valor de retorno

El resultado de la operación

### Véase también

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Convertir documento aplicando el Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fixup | Fixup | El tipo de Fixup. |
| outputLog | Stream | El registro del proceso. |
| onlyValidation | Boolean | Solo validación del documento. |
| parameters | Object[] | Propiedades para Fixup que no se pueden establecer. |

### Valor de retorno

El resultado de la operación.

### Véase también

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Convertir documento aplicando el Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fixup | Fixup | El tipo de Fixup. |
| outputLog | String | El registro del proceso. |
| onlyValidation | Boolean | Solo validación del documento. |
| parameters | Object[] | Propiedades para Fixup que no se pueden establecer. |

### Valor de retorno

El resultado de la operación.

### Véase también

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Convierte el archivo fuente en formato fuente en el archivo de destino en formato de destino.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcFileName | String | El nombre del archivo fuente. |
| loadOptions | LoadOptions | El formato del archivo fuente. |
| dstFileName | String | El nombre del archivo de destino. |
| saveOptions | SaveOptions | El formato del archivo de destino. |

### Véase también

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Convierte el flujo en formato fuente en el archivo de destino en formato de destino.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcStream | Stream | El flujo fuente. |
| loadOptions | LoadOptions | El formato del flujo fuente. |
| dstFileName | String | El nombre del archivo de destino. |
| saveOptions | SaveOptions | El formato del archivo de destino. |

### Véase también

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Convierte el archivo fuente en formato fuente en el flujo en formato de destino.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcFileName | String | El nombre del archivo fuente. |
| loadOptions | LoadOptions | El formato del archivo fuente. |
| dstStream | Stream | El flujo de destino. |
| saveOptions | SaveOptions | El formato del flujo de destino. |

### Véase también

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Convierte el flujo en formato fuente en el flujo en formato de destino.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcStream | Stream | El flujo fuente. |
| loadOptions | LoadOptions | El formato del flujo fuente. |
| dstStream | Stream | El flujo de destino. |
| saveOptions | SaveOptions | El formato del archivo de destino. |

### Véase también

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)