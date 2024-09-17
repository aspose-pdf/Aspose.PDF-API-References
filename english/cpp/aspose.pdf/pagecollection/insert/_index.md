---
title: Aspose::Pdf::PageCollection::Insert method
linktitle: Insert
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PageCollection::Insert method. Insert empty apge into collection at the specified position in C++.'
type: docs
weight: 1200
url: /cpp/aspose.pdf/pagecollection/insert/
---
## PageCollection::Insert(int32_t) method


Insert empty apge into collection at the specified position.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Page> Aspose::Pdf::PageCollection::Insert(int32_t pageNumber)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int32_t | Position of the new page. |

### ReturnValue

Inserted page.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>pageNumber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Position of the new page.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, System::SharedPtr\<Page\>) method


Inserts page into page collection at specified place.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Page> Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, System::SharedPtr<Page> entity)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int32_t | Required page index in collection. |
| entity | System::SharedPtr\<Page\> | [Page](../../page/) to be inserted. |

### ReturnValue

Inserted page.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>pageNumber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Required page index in collection.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>entity</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> to be inserted.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\>) method


Inserts pages from the collection into document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Page>>> pages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int32_t | Starting position of the new pages. |
| pages | System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Page\>\>\> | Pages collection. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>pageNumber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Starting position of the new pages.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Pages collection.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## PageCollection::Insert(int32_t, System::ArrayPtr\<System::SharedPtr\<Page\>\>) method


Inserts pages of the array into document.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::PageCollection::Insert(int32_t pageNumber, System::ArrayPtr<System::SharedPtr<Page>> pages)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int32_t | Starting number of the new pages. |
| pages | System::ArrayPtr\<System::SharedPtr\<Page\>\> | Array of pages which will be inserted. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>pageNumber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Starting number of the new pages. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pages</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of pages which will be inserted.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../page/)
* Class [PageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
