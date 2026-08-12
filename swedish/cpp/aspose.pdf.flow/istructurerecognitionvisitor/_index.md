---
title: "Aspose::Pdf::Flow::IStructureRecognitionVisitor klass"
linktitle: "IStructureRecognitionVisitor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Flow::IStructureRecognitionVisitor klass. Basgränssnitt för en anpassad dokumentstruktur‑igenkänningsbesökare i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.pdf.flow/istructurerecognitionvisitor/
---
## IStructureRecognitionVisitor class


Basgränssnitt för en anpassad dokumentstruktur‑igenkännings‑besökare.

```cpp
class IStructureRecognitionVisitor : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [EndDocument](./enddocument/)() | Signaliserar slutet på dokumentbehandlingen. |
| virtual [StartDocument](./startdocument/)() | Kallas när dokumenttraverseringen startar. |
| virtual [VisitParagraph](./visitparagraph/)(System::SharedPtr\<BaseParagraph\>) | Kallas när en stycke‑nod besöks. |
| virtual [VisitSectionEnd](./visitsectionend/)(System::SharedPtr\<MarginInfo\>) | Besöker slutet på en identifierad sektion i dokumentet. |
| virtual [VisitTable](./visittable/)(System::SharedPtr\<Table\>) | Besöker en identifierad tabell i dokumentstrukturen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Flow](../)
* Library [Aspose.PDF for C++](../../)
