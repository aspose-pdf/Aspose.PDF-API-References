---
title: "Aspose::Pdf::XForm klass"
linktitle: "XForm"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::XForm klass. Klassen representerar XForm i C++."
type: docs
weight: 19500
url: /sv/cpp/aspose.pdf/xform/
---
## XForm class


Klassen representerar [XForm](./).

```cpp
class XForm : public System::IDisposable,
              public Aspose::Pdf::ISupportsMemoryCleanup,
              public Aspose::Pdf::IOperatorContainer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [CreateNewForm](./createnewform/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Document\>\&) | Skapar [XForm](./) som duplicerar sidans innehåll. |
| [Dispose](./dispose/)() override | Frigör minne. |
| [FreeMemory](./freememory/)() override | Rensar cachelagrad data. |
| [get_BBox](./get_bbox/)() | Hämtar formulärets avgränsningsruta. |
| [get_Contents](./get_contents/)() override | Hämtar formulärets operatorer. |
| [get_IT](./get_it/)() | Hämtar formulär‑IT. Form IT är ett namn som beskriver avsikten med XObject. |
| [get_Matrix](./get_matrix/)() | Hämtar formulärets matris. |
| [get_Name](./get_name/)() | Hämtar formulärnamn. Formnamn är namnet som används för att referera till formuläret i XObejct ductionary i sidresurser. |
| [get_Opi](./get_opi/)() | Hämtar The Open Prepress Interface (OPI). |
| [get_Rectangle](./get_rectangle/)() | Hämtar rektangel för formuläret. |
| [get_Resources](./get_resources/)() override | Hämtar Form XObject‑resurser. |
| [get_Subtype](./get_subtype/)() | Hämtar formulär Subtype. |
| [GetResources](./getresources/)(bool) | Returnerar resurser för Form X-Object. |
| [GetResources](./getresources/)() override | Returnerar resurser för Form X-Object. Om Form inte har resurser och allowCreate är true, [Resources](../resources/) kommer automatiskt att skapas för formuläret. |
| [set_BBox](./set_bbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Ställer in formulärets avgränsningsruta. |
| [set_Matrix](./set_matrix/)(const System::SharedPtr\<Aspose::Pdf::Matrix\>\&) | Ställer in formulärets matris. |
| [set_Name](./set_name/)(const System::String\&) | Ställer in formulärnamn. Formnamn är namnet som används för att referera till formuläret i XObejct ductionary i sidresurser. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Class [IOperatorContainer](../ioperatorcontainer/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
