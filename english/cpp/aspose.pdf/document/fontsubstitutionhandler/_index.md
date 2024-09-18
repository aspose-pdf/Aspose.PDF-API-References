---
title: Aspose::Pdf::Document::FontSubstitutionHandler typedef
linktitle: FontSubstitutionHandler
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Document::FontSubstitutionHandler typedef. Represents the method that will handle FontSubstitution event in C++.'
type: docs
weight: 11900
url: /cpp/aspose.pdf/document/fontsubstitutionhandler/
---
## FontSubstitutionHandler typedef


Represents the method that will handle FontSubstitution event.

```cpp
using Aspose::Pdf::Document::FontSubstitutionHandler =  System::MulticastDelegate<void(System::SharedPtr<Text::Font>, System::SharedPtr<Text::Font>)>
```

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

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
