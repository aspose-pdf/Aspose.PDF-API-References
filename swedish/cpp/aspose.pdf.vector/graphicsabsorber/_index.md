---
title: "Aspose::Pdf::Vector::GraphicsAbsorber klass"
linktitle: "GraphicsAbsorber"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Vector::GraphicsAbsorber klass. Representerar ett absorberingsobjekt för grafikelement. Utför grafiksökning och ger åtkomst till sökresultaten via samlingen GraphicsAbsorber::Elements i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf.vector/graphicsabsorber/
---
## GraphicsAbsorber class


Representerar ett absorberande objekt för grafikelement. Utför grafiksökning och ger åtkomst till sökresultat via samlingen [GraphicsAbsorber::Elements](../).

```cpp
class GraphicsAbsorber : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Dispose](./dispose/)() override | Frigör alla resurser som används av klassen [GraphicsAbsorber](./). |
| [get_Elements](./get_elements/)() const | Hämtar en samling av sökförekomster som presenteras med objekt av typen [GraphicElement](../graphicelement/). |
| [GraphicsAbsorber](./graphicsabsorber/)() |  |
|  | [ResumeUpdate](./resumeupdate/)() | Återuppta uppdatering för [Page::Contents](../) och alla [XForm::Contents](../). Gjordes för att öka prestanda, se även |
[OperatorCollection::ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/)


. |
|  | [SuppressUpdate](./suppressupdate/)() | Undertrycker uppdatering för [Page::Contents](../) och alla [XForm::Contents](../). Gjordes för att öka prestanda, se även |
[OperatorCollection::SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)


. |
| [Visit](./visit/)(const System::SharedPtr\<Page\>\&) | Utför sökning på den angivna sidan. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
