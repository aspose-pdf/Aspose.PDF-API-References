---
title: "Aspose::Pdf::Devices::PageDevice::Process método"
linktitle: "Process"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Devices::PageDevice::Process método. Realiza alguna operación en la página dada y guarda los resultados en el archivo en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.devices/pagedevice/process/
---
## PageDevice::Process(const System::SharedPtr\<Page\>\&, const System::String\&) method


Realiza alguna operación en la página dada y guarda los resultados en el archivo.

```cpp
void Aspose::Pdf::Devices::PageDevice::Process(const System::SharedPtr<Page> &page, const System::String &outputFileName)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | const System::SharedPtr\<Page\>\& | La página a procesar. |
| outputFileName | const System::String\& | Este archivo contiene los resultados del procesamiento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [PageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## PageDevice::Process(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) method


Realiza alguna operación en la página dada, p. ej., convierte la página en una imagen gráfica.

```cpp
virtual void Aspose::Pdf::Devices::PageDevice::Process(System::SharedPtr<Page> page, System::SharedPtr<System::IO::Stream> output)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | System::SharedPtr\<Page\> | La página a procesar. |
| output | System::SharedPtr\<System::IO::Stream\> | Este flujo contiene los resultados del procesamiento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Stream](../../../system.io/stream/)
* Class [PageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
