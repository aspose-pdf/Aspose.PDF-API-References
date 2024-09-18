---
title: Aspose::Pdf::Utils::DictionaryEditor::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Utils::DictionaryEditor::Add method. Set ICosPdfPrimitive to dictionary in C++.'
type: docs
weight: 1200
url: /cpp/aspose.pdf.utils/dictionaryeditor/add/
---
## DictionaryEditor::Add(const System::String\&, const System::SharedPtr\<PublicData::ICosPdfPrimitive\>\&) method


Set [ICosPdfPrimitive](../) to dictionary.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Utils::DictionaryEditor::Add(const System::String &key, const System::SharedPtr<PublicData::ICosPdfPrimitive> &value) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Key. |
| value | const System::SharedPtr\<PublicData::ICosPdfPrimitive\>\& | Value. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>key</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Key.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>value</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Value.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Throw exception if key/value can't be edited or removed.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ICosPdfPrimitive](../../../aspose.pdf.utils.publicdata/icospdfprimitive/)
* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::Utils](../../)
* Library [Aspose.PDF for C++](../../../)
## DictionaryEditor::Add(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<PublicData::ICosPdfPrimitive\>\>\&) method


Set [ICosPdfPrimitive](../) to dictionary.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Utils::DictionaryEditor::Add(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<PublicData::ICosPdfPrimitive>> &item) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<PublicData::ICosPdfPrimitive\>\>\& | The pair with a key and a value. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>item</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The pair with a key and a value.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Throw exception if key/value can't be edited or removed.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ICosPdfPrimitive](../../../aspose.pdf.utils.publicdata/icospdfprimitive/)
* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::Utils](../../)
* Library [Aspose.PDF for C++](../../../)
