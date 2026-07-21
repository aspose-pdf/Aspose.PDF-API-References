---
title: "Aspose::Pdf::Document::Convert método"
linktitle: "Convertir"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Document::Convert método. Convierte el documento usando las opciones de conversión especificadas en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf/document/convert/
---
## Document::Convert(const System::SharedPtr\<PdfFormatConversionOptions\>\&) method


Convierte el documento usando las opciones de conversión especificadas.

```cpp
bool Aspose::Pdf::Document::Convert(const System::SharedPtr<PdfFormatConversionOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| opciones | const System::SharedPtr\<PdfFormatConversionOptions\>\& | conjunto de opciones para convertir documento PDF |

### ReturnValue

El resultado de la operación

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat, ConvertErrorAction) method


Convierte el documento y guarda los errores en el flujo especificado.

```cpp
bool Aspose::Pdf::Document::Convert(const System::SharedPtr<System::IO::Stream> &outputLogStream, Aspose::Pdf::PdfFormat format, ConvertErrorAction action)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputLogStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream donde se almacenarán los comentarios. |
| format | Aspose::Pdf::PdfFormat | [Pdf](../../) formato. |
| acción | ConvertErrorAction | Acción para objetos que no pueden convertirse |

### ReturnValue

El resultado de la operación

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) method


Convierte el documento y guarda los errores en el archivo especificado.

```cpp
bool Aspose::Pdf::Document::Convert(const System::SharedPtr<System::IO::Stream> &outputLogStream, Aspose::Pdf::PdfFormat format, ConvertErrorAction action, ConvertTransparencyAction transparencyAction)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputLogStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream donde se almacenarán los comentarios. |
| formato | Aspose::Pdf::PdfFormat | El formato pdf. |
| acción | ConvertErrorAction | Acción para objetos que no pueden convertirse |
| transparencyAction | ConvertTransparencyAction | Acción para objetos enmascarados por imagen |

### ReturnValue

El resultado de la operación

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Enum [ConvertTransparencyAction](../../converttransparencyaction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::String\&, Aspose::Pdf::PdfFormat, ConvertErrorAction) method


Convierte el documento y guarda los errores en el archivo especificado.

```cpp
bool Aspose::Pdf::Document::Convert(const System::String &outputLogFileName, Aspose::Pdf::PdfFormat format, ConvertErrorAction action)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputLogFileName | const System::String\& | Ruta al archivo donde se almacenarán los comentarios. |
| formato | Aspose::Pdf::PdfFormat | El formato pdf. |
| acción | ConvertErrorAction | Acción para objetos que no pueden convertirse |

### ReturnValue

El resultado de la operación

## Ver también

* Class [String](../../../system/string/)
* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::String\&, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) method


Convierte el documento y guarda los errores en el archivo especificado.

```cpp
bool Aspose::Pdf::Document::Convert(const System::String &outputLogFileName, Aspose::Pdf::PdfFormat format, ConvertErrorAction action, ConvertTransparencyAction transparencyAction)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputLogFileName | const System::String\& | Ruta al archivo donde se almacenarán los comentarios. |
| formato | Aspose::Pdf::PdfFormat | El formato pdf. |
| acción | ConvertErrorAction | Acción para objetos que no pueden convertirse |
| transparencyAction | ConvertTransparencyAction | Acción para objetos enmascarados por imagen |

### ReturnValue

El resultado de la operación

## Ver también

* Class [String](../../../system/string/)
* Enum [PdfFormat](../../pdfformat/)
* Enum [ConvertErrorAction](../../converterroraction/)
* Enum [ConvertTransparencyAction](../../converttransparencyaction/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Document::CallBackGetHocr, bool) method


Reconoce imágenes dentro del documento y agrega cadenas hocr sobre él.

```cpp
bool Aspose::Pdf::Document::Convert(Document::CallBackGetHocr callback, bool flattenImages=false)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | Document::CallBackGetHocr | Acción para imágenes que serán procesadas por hocr recognize. |
| flattenImages | bool | [Text](../../../aspose.pdf.text/) en imágenes pdf puede ser pintado usando la mecánica de máscaras, en cuyo caso las imágenes deben ser aplanadas. |

### ReturnValue

El resultado de la operación. Si no hay imágenes en el documento devuelve [false](../).

## Ver también

* Typedef [CallBackGetHocr](../callbackgethocr/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Document::CallBackGetHocrWithPage, bool) method


Reconoce imágenes dentro del documento y agrega cadenas hocr sobre él.

```cpp
bool Aspose::Pdf::Document::Convert(Document::CallBackGetHocrWithPage callback, bool flattenImages=false)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | Document::CallBackGetHocrWithPage | Acción para imágenes que serán procesadas por hocr recognize. |
| flattenImages | bool | [Text](../../../aspose.pdf.text/) en imágenes pdf puede ser pintado usando la mecánica de máscaras, en cuyo caso las imágenes deben ser aplanadas. |

### ReturnValue

El resultado de la operación. Si no hay imágenes en el documento devuelve [false](../).

## Ver también

* Typedef [CallBackGetHocrWithPage](../callbackgethocrwithpage/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Fixup, const System::SharedPtr\<System::IO::Stream\>\&, bool, const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) method


Convertir documento aplicando el [Fixup](../../fixup/).

```cpp
bool Aspose::Pdf::Document::Convert(Fixup fixup, const System::SharedPtr<System::IO::Stream> &outputLog, bool onlyValidation=false, const System::ArrayPtr<System::SharedPtr<System::Object>> &parameters=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fixup | Fixup | El tipo de [Fixup](../../fixup/). |
| outputLog | const System::SharedPtr\<System::IO::Stream\>\& | El registro del proceso. |
| onlyValidation | bool | Solo validación del documento. |
| parameters | const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\& | Propiedades de [Fixup](../../fixup/) que no pueden ser establecidas. |

### ReturnValue

El resultado de la operación.

## Ver también

* Enum [Fixup](../../fixup/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(Fixup, const System::String\&, bool, const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) method


Convertir documento aplicando el [Fixup](../../fixup/).

```cpp
bool Aspose::Pdf::Document::Convert(Fixup fixup, const System::String &outputLog, bool onlyValidation=false, const System::ArrayPtr<System::SharedPtr<System::Object>> &parameters=nullptr)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fixup | Fixup | El tipo de [Fixup](../../fixup/). |
| outputLog | const System::String\& | El registro del proceso. |
| onlyValidation | bool | Solo validación del documento. |
| parameters | const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\& | Propiedades de [Fixup](../../fixup/) que no pueden ser establecidas. |

### ReturnValue

El resultado de la operación.

## Ver también

* Enum [Fixup](../../fixup/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<SaveOptions\>) method


Convierte el flujo en formato origen al flujo en formato destino.

```cpp
static void Aspose::Pdf::Document::Convert(const System::SharedPtr<System::IO::Stream> &srcStream, const System::SharedPtr<LoadOptions> &loadOptions, const System::SharedPtr<System::IO::Stream> &dstStream, System::SharedPtr<SaveOptions> saveOptions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo de origen. |
| loadOptions | const System::SharedPtr\<LoadOptions\>\& | El formato del flujo de origen. |
| dstStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo de destino. |
| saveOptions | System::SharedPtr\<SaveOptions\> | El formato del archivo de destino. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&, const System::String\&, System::SharedPtr\<SaveOptions\>) method


Convierte el flujo en formato origen al archivo de destino en formato destino.

```cpp
static void Aspose::Pdf::Document::Convert(const System::SharedPtr<System::IO::Stream> &srcStream, const System::SharedPtr<LoadOptions> &loadOptions, const System::String &dstFileName, System::SharedPtr<SaveOptions> saveOptions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo de origen. |
| loadOptions | const System::SharedPtr\<LoadOptions\>\& | El formato del flujo de origen. |
| dstFileName | const System::String\& | El nombre del archivo de destino. |
| saveOptions | System::SharedPtr\<SaveOptions\> | El formato del archivo de destino. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [String](../../../system/string/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::String\&, const System::SharedPtr\<LoadOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<SaveOptions\>) method


Convierte el archivo de origen en formato origen al flujo en formato destino.

```cpp
static void Aspose::Pdf::Document::Convert(const System::String &srcFileName, const System::SharedPtr<LoadOptions> &loadOptions, const System::SharedPtr<System::IO::Stream> &dstStream, System::SharedPtr<SaveOptions> saveOptions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcFileName | const System::String\& | El nombre del archivo de origen. |
| loadOptions | const System::SharedPtr\<LoadOptions\>\& | El formato del archivo de origen. |
| dstStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo de destino. |
| saveOptions | System::SharedPtr\<SaveOptions\> | El formato del flujo de destino. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LoadOptions](../../loadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Convert(const System::String\&, const System::SharedPtr\<LoadOptions\>\&, const System::String\&, System::SharedPtr\<SaveOptions\>) method


Convierte el archivo de origen en formato origen al archivo de destino en formato destino.

```cpp
static void Aspose::Pdf::Document::Convert(const System::String &srcFileName, const System::SharedPtr<LoadOptions> &loadOptions, const System::String &dstFileName, System::SharedPtr<SaveOptions> saveOptions)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcFileName | const System::String\& | El nombre del archivo de origen. |
| loadOptions | const System::SharedPtr\<LoadOptions\>\& | El formato del archivo de origen. |
| dstFileName | const System::String\& | El nombre del archivo de destino. |
| saveOptions | System::SharedPtr\<SaveOptions\> | El formato del archivo de destino. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LoadOptions](../../loadoptions/)
* Class [SaveOptions](../../saveoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
