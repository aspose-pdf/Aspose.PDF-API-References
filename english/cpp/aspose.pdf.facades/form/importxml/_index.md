---
title: Aspose::Pdf::Facades::Form::ImportXml method
linktitle: ImportXml
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::Form::ImportXml method. Imports the content of the fields from the xml file and put them into the new pdf in C++.'
type: docs
weight: 3700
url: /cpp/aspose.pdf.facades/form/importxml/
---
## Form::ImportXml(System::SharedPtr\<System::IO::Stream\>) method


Imports the content of the fields from the xml file and put them into the new pdf.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::Form::ImportXml(System::SharedPtr<System::IO::Stream> inputXmlStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | System::SharedPtr\<System::IO::Stream\> | Stream from which XML for import is read. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputXmlStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream from which XML for import is read.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::ImportXml(System::SharedPtr\<System::IO::Stream\>, bool) method


Imports the content of the fields from the xml file and put them into the new pdf.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::Form::ImportXml(System::SharedPtr<System::IO::Stream> inputXmlStream, bool IgnoreFormTemplateChanges)
```


| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | System::SharedPtr\<System::IO::Stream\> | The input xml stream. |
| IgnoreFormTemplateChanges | bool | If this parameter is true then all changes of the XFA form template will not be saved |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>inputXmlStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The input xml stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>IgnoreFormTemplateChanges</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If this parameter is true then all changes of the XFA form template will not be saved</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
