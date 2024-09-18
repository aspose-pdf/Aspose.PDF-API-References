---
title: Aspose::Pdf::Text::FontRepository::OpenFont method
linktitle: OpenFont
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::FontRepository::OpenFont method. Opens font with specified font stream in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.text/fontrepository/openfont/
---
## FontRepository::OpenFont(System::SharedPtr\<System::IO::Stream\>, FontTypes) method


Opens font with specified font stream.

```cpp
static ASPOSE_PDF_SHARED_API System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(System::SharedPtr<System::IO::Stream> fontStream, FontTypes fontType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fontStream | System::SharedPtr\<System::IO::Stream\> | [Font](../../font/) stream. |
| fontType | FontTypes | [Font](../../font/) type value. |

### ReturnValue

[Font](../../font/) object.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fontStream</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_font" kindref="compound">Font</ref> stream.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>fontType</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_font" kindref="compound">Font</ref> type value.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Font](../../font/)
* Enum [FontTypes](../../fonttypes/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontRepository::OpenFont(System::String) method


Opens font with specified font file path.

```cpp
static ASPOSE_PDF_SHARED_API System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(System::String fontFilePath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | System::String | [Font](../../font/) file path. |

### ReturnValue

[Font](../../font/) object.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fontFilePath</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_font" kindref="compound">Font</ref> file path.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Font](../../font/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## FontRepository::OpenFont(System::String, System::String) method


Opens font with specified font file path and metrics file path.

```cpp
static ASPOSE_PDF_SHARED_API System::SharedPtr<Font> Aspose::Pdf::Text::FontRepository::OpenFont(System::String fontFilePath, System::String metricsFilePath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | System::String | [Font](../../font/) file path. |
| metricsFilePath | System::String | [Font](../../font/) metrics file patrh. |

### ReturnValue

[Font](../../font/) object.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fontFilePath</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_font" kindref="compound">Font</ref> file path.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>metricsFilePath</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_text_1_1_font" kindref="compound">Font</ref> metrics file patrh.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Font](../../font/)
* Class [FontRepository](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
