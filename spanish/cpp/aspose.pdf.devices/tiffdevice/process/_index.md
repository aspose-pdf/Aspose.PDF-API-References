---
title: "Aspose::Pdf::Devices::TiffDevice::Process método"
linktitle: "Process"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Devices::TiffDevice::Process método. Convierte ciertas páginas del documento a tiff y las guarda en el flujo de salida en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf.devices/tiffdevice/process/
---
## TiffDevice::Process(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Convierte ciertas páginas del documento a TIFF y las guarda en el flujo de salida.

```cpp
void Aspose::Pdf::Devices::TiffDevice::Process(System::SharedPtr<Aspose::Pdf::Document> document, int32_t fromPage, int32_t toPage, System::SharedPtr<System::IO::Stream> output) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | System::SharedPtr\<Aspose::Pdf::Document\> | El documento a convertir. |
| fromPage | int32_t | Define el número de página desde la cual comenzará la conversión. |
| toPage | int32_t | Define el número de página que finalizará la conversión. |
| output | System::SharedPtr\<System::IO::Stream\> | Flujo de salida con imagen tiff. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## TiffDevice::Process(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) method


Realiza alguna operación en la página dada, p. ej., convierte la página en una imagen gráfica.

```cpp
void Aspose::Pdf::Devices::TiffDevice::Process(System::SharedPtr<Page> page, System::SharedPtr<System::IO::Stream> output) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | System::SharedPtr\<Page\> | La página a procesar. |
| output | System::SharedPtr\<System::IO::Stream\> | Este flujo contiene los resultados del procesamiento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
