---
title: Aspose::Pdf::Facades::Form::FillImageField method
linktitle: FillImageField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::Form::FillImageField method. Pastes an image onto the existing button field as its appearance according to its fully qualified field name in C++.'
type: docs
weight: 4900
url: /cpp/aspose.pdf.facades/form/fillimagefield/
---
## Form::FillImageField(System::String, System::String) method


Pastes an image onto the existing button field as its appearance according to its fully qualified field name.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::Form::FillImageField(System::String fieldName, System::String imageFileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | The fully qualified field name of the image button field. |
| imageFileName | System::String | The path of the image file, relative and absolute are both ok. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The fully qualified field name of the image button field.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>imageFileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The path of the image file, relative and absolute are both ok.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillImageField(System::String, System::SharedPtr\<System::IO::Stream\>) method


Overloads function of FillImageField. The input is a image stream.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::Form::FillImageField(System::String fieldName, System::SharedPtr<System::IO::Stream> imageStream)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | The fully qualified field name. |
| imageStream | System::SharedPtr\<System::IO::Stream\> | The image's stream. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The fully qualified field name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>imageStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The image's stream.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
