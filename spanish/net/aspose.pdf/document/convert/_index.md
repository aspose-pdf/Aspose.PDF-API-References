---
title: Convert
second_title: Referencia de API de Aspose.PDF para .NET
description: Convierte el archivo de origen en formato de origen en un archivo de destino en formato de destino.
type: docs
weight: 790
url: /es/net/aspose.pdf/document/convert/
---
## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Convierte el archivo de origen en formato de origen en un archivo de destino en formato de destino.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcFileName | String | El nombre del archivo de origen. |
| loadOptions | LoadOptions | El formato del archivo fuente. |
| dstFileName | String | El nombre del archivo de destino. |
| saveOptions | SaveOptions | El formato de archivo de destino. |

### Ver también

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Convierte el flujo en formato de origen en un archivo de destino en formato de destino.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcStream | Stream | El flujo de origen. |
| loadOptions | LoadOptions | El formato de flujo de origen. |
| dstFileName | String | El nombre del archivo de destino. |
| saveOptions | SaveOptions | El formato de archivo de destino. |

### Ver también

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Convierte el archivo de origen en formato de origen en flujo en formato de destino.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcFileName | String | El nombre del archivo de origen. |
| loadOptions | LoadOptions | El formato del archivo fuente. |
| dstStream | Stream | El flujo de destino. |
| saveOptions | SaveOptions | El formato de flujo de destino. |

### Ver también

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Convierte flujo en formato de origen en flujo en formato de destino.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcStream | Stream | El flujo de origen. |
| loadOptions | LoadOptions | El formato de flujo de origen. |
| dstStream | Stream | El flujo de destino. |
| saveOptions | SaveOptions | El formato de archivo de destino. |

### Ver también

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_7}

Convierte el documento y guarda los errores en el archivo especificado.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputLogFileName | String | Ruta al archivo donde se almacenarán los comentarios. |
| format | PdfFormat | El formato pdf. |
| action | ConvertErrorAction | Acción para objetos que no se pueden convertir |
| transparencyAction | ConvertTransparencyAction | Acción para objetos con máscara de imagen |

### Valor_devuelto

El resultado de la operación

### Ver también

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_5}

Convierte el documento y guarda los errores en el archivo especificado.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputLogStream | Stream | Stream donde se almacenarán los comentarios. |
| format | PdfFormat | El formato pdf. |
| action | ConvertErrorAction | Acción para objetos que no se pueden convertir |
| transparencyAction | ConvertTransparencyAction | Acción para objetos con máscara de imagen |

### Valor_devuelto

El resultado de la operación

### Ver también

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_6}

Convierte el documento y guarda los errores en el archivo especificado.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputLogFileName | String | Ruta al archivo donde se almacenarán los comentarios. |
| format | PdfFormat | El formato pdf. |
| action | ConvertErrorAction | Acción para objetos que no se pueden convertir |

### Valor_devuelto

El resultado de la operación

### Ver también

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Convertir documento utilizando opciones de conversión especificadas

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| options | PdfFormatConversionOptions | conjunto de opciones para convertir documentos PDF |

### Valor_devuelto

El resultado de la operación

### Ver también

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr) {#convert_3}

Convierte el documento y guarda los errores en el archivo especificado.

```csharp
public bool Convert(CallBackGetHocr callback)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| callback | CallBackGetHocr | Acción para objetos que no se pueden convertir |

### Valor_devuelto

El resultado de la operación

### Ver también

* delegate [CallBackGetHocr](../../document.callbackgethocr)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_4}

Convierta el documento y guarde los errores en la secuencia especificada.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| outputLogStream | Stream | Stream donde se almacenarán los comentarios. |
| format | PdfFormat | formato pdf. |
| action | ConvertErrorAction | Acción para objetos que no se pueden convertir |

### Valor_devuelto

El resultado de la operación

### Ver también

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Convertir documento aplicando Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fixup | Fixup | El tipo de reparación. |
| outputLog | Stream | El registro de proceso. |
| onlyValidation | Boolean | Solo validación de documentos. |
| parameters | Object[] | Propiedades para Fixup que no se pueden establecer. |

### Valor_devuelto

El resultado de la operación.

### Ver también

* enum [Fixup](../../fixup)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Convertir documento aplicando Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fixup | Fixup | El tipo de reparación. |
| outputLog | String | El registro de proceso. |
| onlyValidation | Boolean | Solo validación de documentos. |
| parameters | Object[] | Propiedades para Fixup que no se pueden establecer. |

### Valor_devuelto

El resultado de la operación.

### Ver también

* enum [Fixup](../../fixup)
* class [Document](../../document)
* espacio de nombres [Aspose.Pdf](../../document)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
