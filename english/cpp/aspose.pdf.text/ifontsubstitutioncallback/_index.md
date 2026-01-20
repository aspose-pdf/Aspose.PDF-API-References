---
title: Aspose::Pdf::Text::IFontSubstitutionCallback class
linktitle: IFontSubstitutionCallback
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::IFontSubstitutionCallback class. This interface declares a callback mechanism to send notifications in C++.'
type: docs
weight: 1800
url: /cpp/aspose.pdf.text/ifontsubstitutioncallback/
---
## IFontSubstitutionCallback class


This interface declares a callback mechanism to send notifications.

```cpp
class IFontSubstitutionCallback : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_NotifyAboutFontSubstitutions](./get_notifyaboutfontsubstitutions/)() | Returns true if font substitutions are enabled. |
| virtual [get_Registrar](./get_registrar/)() | IRegistrar for current document. |
| virtual [NotifyAboutSubstitution](./notifyaboutsubstitution/)(System::SharedPtr\<Aspose::Pdf::Text::Font\>, System::SharedPtr\<Aspose::Pdf::Text::Font\>) | Sends notification about font substitution via event mechanism. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
