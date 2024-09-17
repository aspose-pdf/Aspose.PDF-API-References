---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateBookmarksAction method
linktitle: CreateBookmarksAction
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateBookmarksAction method. Creates a bookmark with the specified action in C++.'
type: docs
weight: 3100
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor::CreateBookmarksAction method


Creates a bookmark with the specified action.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::PdfContentEditor::CreateBookmarksAction(System::String title, System::Drawing::Color color, bool boldFlag, bool italicFlag, System::String file, System::String actionType, System::String destination)
```


| Parameter | Type | Description |
| --- | --- | --- |
| title | System::String | The title of the bookmark. |
| color | System::Drawing::Color | The colour of the bookmark's title. |
| boldFlag | bool | The flag of bold attribution. |
| italicFlag | bool | The flag of italic attribution. |
| file | System::String | Another file or application required when the action type is "GoToR" or "Launch". |
| actionType | System::String | The action type. The value can be: "GoToR", "Launch", "GoTo", "URI". |
| destination | System::String | The local destination or remote destination or URL. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>title</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The title of the bookmark.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>color</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The colour of the bookmark's title.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>boldFlag</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The flag of bold attribution.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>italicFlag</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The flag of italic attribution.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>file</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Another file or application required when the action type is "GoToR" or "Launch".</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>actionType</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The action type. The value can be: "GoToR", "Launch", "GoTo", "URI".</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>destination</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The local destination or remote destination or URL.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
