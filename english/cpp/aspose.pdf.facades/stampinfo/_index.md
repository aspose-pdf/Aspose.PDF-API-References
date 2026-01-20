---
title: Aspose::Pdf::Facades::StampInfo class
linktitle: StampInfo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::StampInfo class. Class representing stamp information in C++.'
type: docs
weight: 3600
url: /cpp/aspose.pdf.facades/stampinfo/
---
## StampInfo class


Class representing stamp information.

```cpp
class StampInfo : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Form](./get_form/)() const | Gets [XForm](../../aspose.pdf/xform/) of the stamp. |
| [get_Image](./get_image/)() const | Gets image of stamp. May be null if stamp does not contain images (for example for text stamp). |
| [get_IndexOnPage](./get_indexonpage/)() const | Gets stamp index on the page. |
| [get_Rectangle](./get_rectangle/)() const | Gets rectangle where stamp is placed. |
| [get_StampId](./get_stampid/)() const | Gets identifier of the stamp. |
| [get_StampType](./get_stamptype/)() const | Gets stamp type (image / form). |
| [get_Text](./get_text/)() | Gets text in the stamp. |
| [get_Visible](./get_visible/)() const | Gets visibility of stamp. If false then stamp is hidden (with HideStampById). Hidden stamp may be restored by ShowStampById. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
