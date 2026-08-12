---
title: "Aspose::Pdf::Devices::DocumentDevice::Process método"
linktitle: "Process"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Devices::DocumentDevice::Process método. Procesa todo el documento y guarda los resultados en el flujo en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.devices/documentdevice/process/
---
## DocumentDevice::Process(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Procesa todo el documento y guarda los resultados en un flujo.

```cpp
void Aspose::Pdf::Devices::DocumentDevice::Process(const System::SharedPtr<Aspose::Pdf::Document> &document, const System::SharedPtr<System::IO::Stream> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | const System::SharedPtr\<Aspose::Pdf::Document\>\& | El documento a procesar. |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Define el flujo donde se almacenan los resultados del procesamiento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentDevice::Process(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) method


Procesa todo el documento y guarda los resultados en un archivo.

```cpp
void Aspose::Pdf::Devices::DocumentDevice::Process(const System::SharedPtr<Aspose::Pdf::Document> &document, const System::String &outputFileName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | const System::SharedPtr\<Aspose::Pdf::Document\>\& | El documento a procesar. |
| outputFileName | const System::String\& | Define el archivo donde se almacenan los resultados del procesamiento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentDevice::Process(const System::SharedPtr\<Aspose::Pdf::Document\>\&, int32_t, int32_t, const System::String\&) method


Procesa ciertas páginas del documento y guarda los resultados en un archivo.

```cpp
void Aspose::Pdf::Devices::DocumentDevice::Process(const System::SharedPtr<Aspose::Pdf::Document> &document, int32_t fromPage, int32_t toPage, const System::String &outputFileName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | const System::SharedPtr\<Aspose::Pdf::Document\>\& | El documento a procesar. |
| fromPage | int32_t | La primera página para iniciar el procesamiento. |
| toPage | int32_t | La última página del procesamiento. |
| outputFileName | const System::String\& | Define el archivo donde se almacenan los resultados del procesamiento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentDevice::Process(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Cada dispositivo representa alguna operación en el documento, p. ej. podemos convertir el documento pdf a otro formato.

```cpp
virtual void Aspose::Pdf::Devices::DocumentDevice::Process(System::SharedPtr<Aspose::Pdf::Document> document, int32_t fromPage, int32_t toPage, System::SharedPtr<System::IO::Stream> output)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | System::SharedPtr\<Aspose::Pdf::Document\> | El documento a procesar. |
| fromPage | int32_t | Define la página desde la cual iniciar el procesamiento. |
| toPage | int32_t | Define la última página a procesar. |
| output | System::SharedPtr\<System::IO::Stream\> | Define el flujo donde se almacenan los resultados del procesamiento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
