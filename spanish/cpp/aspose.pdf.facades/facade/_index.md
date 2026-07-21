---
title: "Aspose::Pdf::Facades::Facade clase"
linktitle: "Facade"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::Facade clase. Clase base de fachada en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf.facades/facade/
---
## Facade class


Clase fachada base.

```cpp
class Facade : public virtual Aspose::Pdf::Facades::IFacade,
               public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Inicializa la fachada. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Inicializa la fachada. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Inicializa la fachada. |
| [Close](./close/)() override | Descarta [Aspose.Pdf.Document](../../aspose.pdf/document/) vinculado con una fachada. |
| [Dispose](./dispose/)() override | Descarta la fachada. |
| [get_Document](./get_document/)() const | Obtiene la fachada del documento en la que está trabajando. |
## Ver también

* Class [IFacade](../ifacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
