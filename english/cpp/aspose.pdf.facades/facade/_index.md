---
title: Aspose::Pdf::Facades::Facade class
linktitle: Facade
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::Facade class. Base facade class in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.facades/facade/
---
## Facade class


Base facade class.

```cpp
class Facade : public virtual Aspose::Pdf::Facades::IFacade,
               public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Methods

| Method | Description |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Initializes the facade. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Initializes the facade. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Initializes the facade. |
| [Close](./close/)() override | Disposes [Aspose.Pdf.Document](../../aspose.pdf/document/) bound with a facade. |
| [Dispose](./dispose/)() override | Disposes the facade. |
| [get_Document](./get_document/)() const | Gets the document facade is working on. |
## See Also

* Class [IFacade](../ifacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
