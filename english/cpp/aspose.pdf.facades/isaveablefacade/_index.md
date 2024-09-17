---
title: Aspose::Pdf::Facades::ISaveableFacade class
linktitle: ISaveableFacade
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::ISaveableFacade class. Facade interface that defines methods common for all saveable facades in C++.'
type: docs
weight: 1300
url: /cpp/aspose.pdf.facades/isaveablefacade/
---
## ISaveableFacade class


[Facade](../facade/) interface that defines methods common for all saveable facades.

```cpp
class ISaveableFacade : public virtual Aspose::Pdf::Facades::IFacade
```

## Methods

| Method | Description |
| --- | --- |
| virtual [BindPdf](../ifacade/bindpdf/)(System::String) | Binds PDF document for editing. |
| virtual [BindPdf](../ifacade/bindpdf/)(System::SharedPtr\<System::IO::Stream\>) | Binds PDF document for editing. |
| virtual [BindPdf](../ifacade/bindpdf/)(System::SharedPtr\<Document\>) | Binds PDF document for editing. |
| virtual [Close](../ifacade/close/)() | Releases any resources associates with the current facade. |
| virtual [Save](./save/)(System::String) | Saves the result PDF document to file. |
| virtual [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) | Saves the result PDF document to stream. |
## See Also

* Class [IFacade](../ifacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
