---
title: "Aspose::Pdf::Devices::DocumentDevice class"
linktitle: "DocumentDevice"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Devices::DocumentDevice. Clase abstracta para todos los dispositivos que se utilizan para procesar todo el documento pdf en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf.devices/documentdevice/
---
## DocumentDevice class


Clase abstracta para todos los dispositivos que se utiliza para procesar todo el documento PDF.

```cpp
class DocumentDevice : public Aspose::Pdf::Devices::PageDevice
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DocumentDevice](./documentdevice/)() |  |
| virtual [Process](./process/)(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) | Cada dispositivo representa alguna operación en el documento, p. ej. podemos convertir el documento pdf a otro formato. |
| [Process](./process/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Procesa todo el documento y guarda los resultados en un flujo. |
| [Process](./process/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Procesa todo el documento y guarda los resultados en un archivo. |
| [Process](./process/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, int32_t, int32_t, const System::String\&) | Procesa ciertas páginas del documento y guarda los resultados en un archivo. |
## Ver también

* Class [PageDevice](../pagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
