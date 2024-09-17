---
title: Aspose::Pdf::Facades::SaveableFacade class
linktitle: SaveableFacade
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::SaveableFacade class. Base class for all saveable facades in C++.'
type: docs
weight: 3300
url: /cpp/aspose.pdf.facades/saveablefacade/
---
## SaveableFacade class


Base class for all saveable facades.

```cpp
class SaveableFacade : public Aspose::Pdf::Facades::Facade,
                       public Aspose::Pdf::Facades::ISaveableFacade
```

## Methods

| Method | Description |
| --- | --- |
| [BindPdf](../facade/bindpdf/)(System::String) override | Initializes the facade. |
| [BindPdf](../facade/bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Initializes the facade. |
| [BindPdf](../facade/bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Initializes the facade. |
| virtual [BindPdf](../ifacade/bindpdf/)(System::SharedPtr\<Document\>) | Binds PDF document for editing. |
| [Close](../facade/close/)() override | Disposes [Aspose.Pdf.Document](../../aspose.pdf/document/) bound with a facade. |
| [Dispose](../facade/dispose/)() override | Disposes the facade. |
| [get_Document](../facade/get_document/)() const | Gets the document facade is working on. |
| [Save](./save/)(System::String) override | Saves the PDF document to the specified file. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Saves the PDF document to the specified stream. |
## See Also

* Class [Facade](../facade/)
* Class [ISaveableFacade](../isaveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
