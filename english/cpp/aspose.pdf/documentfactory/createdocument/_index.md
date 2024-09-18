---
title: Aspose::Pdf::DocumentFactory::CreateDocument method
linktitle: CreateDocument
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DocumentFactory::CreateDocument method. Create document in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf/documentfactory/createdocument/
---
## DocumentFactory::CreateDocument(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<LoadOptions\>) method


Create document.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(System::SharedPtr<System::IO::Stream> input, System::SharedPtr<LoadOptions> options)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Input stream. |
| options | System::SharedPtr\<LoadOptions\> | [Document](../../document/) load options. |

### ReturnValue

Created document.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>input</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>options</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_document" kindref="compound">Document</ref> load options.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../document/)
* Class [LoadOptions](../../loadoptions/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument() method


Create empty document.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument()
```


### ReturnValue

Created document.

## See Also

* Class [Document](../../document/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(System::SharedPtr\<System::IO::Stream\>) method


Load document from a stream.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(System::SharedPtr<System::IO::Stream> input)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Input stream. |

### ReturnValue

Created document.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>input</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input stream.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../document/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(System::SharedPtr\<System::IO::Stream\>, System::String) method


Load password protected document from a stream.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(System::SharedPtr<System::IO::Stream> input, System::String password)
```


| Parameter | Type | Description |
| --- | --- | --- |
| input | System::SharedPtr\<System::IO::Stream\> | Source stream. |
| password | System::String | Passowrd for access to document. |

### ReturnValue

Created document.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>input</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Source stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>password</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Passowrd for access to document.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../document/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(System::String) method


Load document from a file.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(System::String fileName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fileName | System::String | Name of PDF file. |

### ReturnValue

Created document.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fileName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Name of PDF file.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Document](../../document/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
