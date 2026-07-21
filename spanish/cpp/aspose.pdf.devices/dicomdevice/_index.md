---
title: "Clase Aspose::Pdf::Devices::DicomDevice"
linktitle: "DicomDevice"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Devices::DicomDevice. Representa un dispositivo de imagen que ayuda a guardar las páginas de documentos pdf en formato Dicom en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf.devices/dicomdevice/
---
## DicomDevice class


Representa un dispositivo de imagen que ayuda a guardar las páginas del documento PDF en formato Dicom.

```cpp
class DicomDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DicomDevice](./dicomdevice/)() | Inicializa una nueva instancia de la clase [DicomDevice](./) con resolución predeterminada. |
| [DicomDevice](./dicomdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [DicomDevice](./). |
| [DicomDevice](./dicomdevice/)(const System::SharedPtr\<PageSize\>\&) | Inicializa una nueva instancia de la clase [DicomDevice](./) con el tamaño de página proporcionado, con resolución predeterminada (=150). |
| [DicomDevice](./dicomdevice/)(int32_t, int32_t) | Inicializa una nueva instancia de la clase [DicomDevice](./) con las dimensiones de imagen proporcionadas, con resolución predeterminada (=150). |
| [DicomDevice](./dicomdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [DicomDevice](./) con el tamaño de página y la resolución proporcionados. |
| [DicomDevice](./dicomdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Inicializa una nueva instancia de la clase [DicomDevice](./) con las dimensiones de imagen y la resolución proporcionadas. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Convierte la página a Dicom y la guarda en el flujo de salida. |
## Ver también

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
