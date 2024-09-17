---
title: Aspose::Pdf::Text::IFontSubstitutionCallback::NotifyAboutSubstitution method
linktitle: NotifyAboutSubstitution
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::IFontSubstitutionCallback::NotifyAboutSubstitution method. Sends notification about font substitution via event mechanism in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.text/ifontsubstitutioncallback/notifyaboutsubstitution/
---
## IFontSubstitutionCallback::NotifyAboutSubstitution method


Sends notification about font substitution via event mechanism.

```cpp
virtual void Aspose::Pdf::Text::IFontSubstitutionCallback::NotifyAboutSubstitution(System::SharedPtr<Aspose::Pdf::Text::Font> oldFont, System::SharedPtr<Aspose::Pdf::Text::Font> newFont)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| oldFont | System::SharedPtr\<Aspose::Pdf::Text::Font\> | original font |
| newFont | System::SharedPtr\<Aspose::Pdf::Text::Font\> | new font |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>oldFont</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>original font</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>newFont</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>new font</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Font](../../font/)
* Class [IFontSubstitutionCallback](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
