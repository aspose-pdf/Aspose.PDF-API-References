---
title: Aspose::Pdf::XForm class
linktitle: XForm
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XForm class. Class represent XForm in C++.'
type: docs
weight: 19200
url: /cpp/aspose.pdf/xform/
---
## XForm class


Class represent [XForm](./).

```cpp
class XForm : public System::IDisposable,
              public Aspose::Pdf::ISupportsMemoryCleanup,
              public Aspose::Pdf::IOperatorContainer
```

## Methods

| Method | Description |
| --- | --- |
| static [CreateNewForm](./createnewform/)(System::SharedPtr\<Page\>, System::SharedPtr\<Document\>) | Creates [XForm](./) which duplicates contents of the page. |
| [Dispose](./dispose/)() override | Frees up memory. |
| [FreeMemory](./freememory/)() override | Clears cached data. |
| [get_BBox](./get_bbox/)() | Gets form bounding box. |
| [get_Contents](./get_contents/)() override | Gets operators of the form. |
| [get_IT](./get_it/)() | Gets form IT. Form IT is a name describing the intent of the XObject. |
| [get_Matrix](./get_matrix/)() | Gets matrix of the form. |
| [get_Name](./get_name/)() | Gets form name. Form name is name which used to reference form in XObejct ductionary in page resources. |
| [get_Opi](./get_opi/)() | Gets The Open Prepress Interface (OPI). |
| [get_Rectangle](./get_rectangle/)() | Gets rectangel of the form. |
| [get_Resources](./get_resources/)() override | Gets Form XObject resources. |
| [get_Subtype](./get_subtype/)() | Gets form Subtype. |
| [GetResources](./getresources/)(bool) | Returns resources of Form X-Object. |
| [GetResources](./getresources/)() override | Returns resources of Form X-Object. If For does not have resources and allowCreate is true, [Resources](../resources/) will be automatically created for the form. |
| [set_BBox](./set_bbox/)(System::SharedPtr\<Aspose::Pdf::Rectangle\>) | Sets form bounding box. |
| [set_Matrix](./set_matrix/)(System::SharedPtr\<Aspose::Pdf::Matrix\>) | Sets matrix of the form. |
| [set_Name](./set_name/)(System::String) | Sets form name. Form name is name which used to reference form in XObejct ductionary in page resources. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Class [IOperatorContainer](../ioperatorcontainer/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
