---
title: "Aspose::Pdf::Document::SendTo método"
linktitle: "SendTo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Document::SendTo. Envía todo el documento al dispositivo de documento para su procesamiento en C++."
type: docs
weight: 8500
url: /es/cpp/aspose.pdf/document/sendto/
---
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Envía todo el documento al dispositivo de documento para su procesamiento.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, const System::SharedPtr<System::IO::Stream> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) dispositivo que se utiliza para procesar el documento. |
| output | const System::SharedPtr\<System::IO::Stream\>\& | El flujo de salida contiene los resultados del procesamiento del documento con el dispositivo dado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::String\&) method


Envía todo el documento al dispositivo de documento para su procesamiento.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, const System::String &outputFileName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) dispositivo que se utiliza para procesar el documento. |
| outputFileName | const System::String\& | Nombre del archivo de salida con los resultados del procesamiento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Envía ciertas páginas del documento al dispositivo de documento para su procesamiento.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, int32_t fromPage, int32_t toPage, const System::SharedPtr<System::IO::Stream> &output)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) dispositivo que se utiliza para procesar el documento. |
| fromPage | int32_t | La primera página para el procesamiento. |
| toPage | int32_t | La última página para el procesamiento. |
| output | const System::SharedPtr\<System::IO::Stream\>\& | El flujo de salida contiene los resultados del procesamiento de las páginas del documento con el dispositivo dado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::String\&) method


Envía todo el documento al dispositivo de documento para su procesamiento.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, int32_t fromPage, int32_t toPage, const System::String &outputFileName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) dispositivo que se utiliza para procesar el documento. |
| fromPage | int32_t | La primera página para el procesamiento. |
| toPage | int32_t | La última página para el procesamiento. |
| outputFileName | const System::String\& | Nombre del archivo de salida con los resultados del procesamiento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
