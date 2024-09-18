---
title: Aspose::Pdf::EmbeddedFileCollection::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::EmbeddedFileCollection::Add method. Adds embedded file specification into collection in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf/embeddedfilecollection/add/
---
## EmbeddedFileCollection::Add(const System::SharedPtr\<FileSpecification\>\&) method


Adds embedded file specification into collection.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::EmbeddedFileCollection::Add(const System::SharedPtr<FileSpecification> &file) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| file | const System::SharedPtr\<FileSpecification\>\& | [FileSpecification](../../filespecification/) which should be added into colleciton. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>file</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_file_specification" kindref="compound">FileSpecification</ref> which should be added into colleciton.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [FileSpecification](../../filespecification/)
* Class [EmbeddedFileCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## EmbeddedFileCollection::Add(System::String, System::SharedPtr\<FileSpecification\>) method


Adds file to embedded files with the specified key.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::EmbeddedFileCollection::Add(System::String key, System::SharedPtr<FileSpecification> file)
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | System::String | Key in the embedded files. |
| file | System::SharedPtr\<FileSpecification\> | File specification. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>key</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Key in the embedded files.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>file</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>File specification.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [FileSpecification](../../filespecification/)
* Class [EmbeddedFileCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
