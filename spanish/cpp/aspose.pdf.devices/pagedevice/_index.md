---
title: "Aspose::Pdf::Devices::PageDevice class"
linktitle: "PageDevice"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Devices::PageDevice class. Clase abstracta para todos los dispositivos que se utilizan para procesar una página determinada del documento PDF en C++."
type: docs
weight: 1000
url: /es/cpp/aspose.pdf.devices/pagedevice/
---
## PageDevice class


Clase abstracta para todos los dispositivos que se utilizan para procesar una página específica del documento pdf.

```cpp
class PageDevice : public Aspose::Pdf::Devices::Device
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) | Realiza alguna operación en la página dada, p. ej., convierte la página en una imagen gráfica. |
| [Process](./process/)(const System::SharedPtr\<Page\>\&, const System::String\&) | Realiza alguna operación en la página dada y guarda los resultados en el archivo. |
## Ver también

* Class [Device](../device/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
