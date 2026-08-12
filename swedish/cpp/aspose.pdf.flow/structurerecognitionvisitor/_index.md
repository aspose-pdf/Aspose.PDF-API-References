---
title: "Aspose::Pdf::Flow::StructureRecognitionVisitor klass"
linktitle: "StructureRecognitionVisitor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Flow::StructureRecognitionVisitor klass. Bas‑klass för en anpassad dokumentstruktur‑igenkänningsbesökare i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.flow/structurerecognitionvisitor/
---
## StructureRecognitionVisitor class


Bas‑klass för en anpassad dokumentstruktur‑igenkännings‑besökare.

```cpp
class StructureRecognitionVisitor : public Aspose::Pdf::Flow::IStructureRecognitionVisitor
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [EndDocument](./enddocument/)() override | Signaliserar slutet på dokumentbehandlingen. |
| virtual [Recognize](./recognize/)(System::SharedPtr\<Document\>) | Starta igenkänning av dokumentet. |
| virtual [Recognize](./recognize/)(System::SharedPtr\<Page\>) | Starta igenkänning av sidan. |
| [StartDocument](./startdocument/)() override | Kallas när dokumenttraverseringen startar. |
| [VisitParagraph](./visitparagraph/)(System::SharedPtr\<BaseParagraph\>) override | Kallas när en stycke‑nod besöks. |
| [VisitSectionEnd](./visitsectionend/)(System::SharedPtr\<MarginInfo\>) override | Besöker slutet på en identifierad sektion i dokumentet. |
| [VisitTable](./visittable/)(System::SharedPtr\<Table\>) override | Besöker en identifierad tabell i dokumentstrukturen. |
## Se även

* Class [IStructureRecognitionVisitor](../istructurerecognitionvisitor/)
* Namespace [Aspose::Pdf::Flow](../)
* Library [Aspose.PDF for C++](../../)
