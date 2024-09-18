---
title: Aspose::Pdf::Vector::Extraction::SvgExtractor::Extract method
linktitle: Extract
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Vector::Extraction::SvgExtractor::Extract method. Exracts svg image to string from graphic elements represents by absorber with a predicate filter in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.vector.extraction/svgextractor/extract/
---
## SvgExtractor::Extract(System::SharedPtr\<GraphicsAbsorber\>, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, System::SharedPtr\<Page\>) method


Exracts svg image to string from graphic elements represents by [absorber](../) with a predicate filter.

```cpp
ASPOSE_PDF_SHARED_API System::String Aspose::Pdf::Vector::Extraction::SvgExtractor::Extract(System::SharedPtr<GraphicsAbsorber> absorber, System::Predicate<System::SharedPtr<GraphicElement>> filter, System::SharedPtr<Page> page)
```


| Parameter | Type | Description |
| --- | --- | --- |
| absorber | System::SharedPtr\<GraphicsAbsorber\> | The [GraphicsAbsorber](../../../aspose.pdf.vector/graphicsabsorber/) object that contains the graphic elements. |
| filter | System::Predicate\<System::SharedPtr\<GraphicElement\>\> | A predicate function used to filter the graphic elements. |
| page | System::SharedPtr\<Page\> | The page where the absorber gets graphic elements. |

### ReturnValue

The string with SVG content.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>absorber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The <ref refid="class_aspose_1_1_pdf_1_1_vector_1_1_graphics_absorber" kindref="compound">GraphicsAbsorber</ref> object that contains the graphic elements.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>filter</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A predicate function used to filter the graphic elements.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page where the absorber gets graphic elements.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>PdfException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If an error occurred when converting to SVG.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [GraphicsAbsorber](../../../aspose.pdf.vector/graphicsabsorber/)
* Class [GraphicElement](../../../aspose.pdf.vector/graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector::Extraction](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(System::SharedPtr\<GraphicsAbsorber\>, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, System::SharedPtr\<Page\>, System::String) method


Exracts svg image to file from graphic elements represents by [absorber](../) with a predicate filter.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Vector::Extraction::SvgExtractor::Extract(System::SharedPtr<GraphicsAbsorber> absorber, System::Predicate<System::SharedPtr<GraphicElement>> filter, System::SharedPtr<Page> page, System::String svgFilePath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| absorber | System::SharedPtr\<GraphicsAbsorber\> | The [GraphicsAbsorber](../../../aspose.pdf.vector/graphicsabsorber/) object that contains the graphic elements. |
| filter | System::Predicate\<System::SharedPtr\<GraphicElement\>\> | A predicate function used to filter the graphic elements. |
| page | System::SharedPtr\<Page\> | The page where the absorber gets graphic elements. |
| svgFilePath | System::String | The target SVG file path. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>absorber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The <ref refid="class_aspose_1_1_pdf_1_1_vector_1_1_graphics_absorber" kindref="compound">GraphicsAbsorber</ref> object that contains the graphic elements.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>filter</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A predicate function used to filter the graphic elements.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page where the absorber gets graphic elements.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>svgFilePath</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The target SVG file path.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>PdfException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If an error occurred when converting to SVG.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [GraphicsAbsorber](../../../aspose.pdf.vector/graphicsabsorber/)
* Class [GraphicElement](../../../aspose.pdf.vector/graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector::Extraction](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>, System::SharedPtr\<Page\>) method


Extracts graphic elements into a SVG string. Options ignored - grouping, extracting from rectangle.

```cpp
ASPOSE_PDF_SHARED_API System::String Aspose::Pdf::Vector::Extraction::SvgExtractor::Extract(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<GraphicElement>>> elements, System::SharedPtr<Page> page)
```


| Parameter | Type | Description |
| --- | --- | --- |
| elements | System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\> | The graphic elements to convert. |
| page | System::SharedPtr\<Page\> | The page where the absorber gets graphic elements. |

### ReturnValue

The string with SVG content.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>elements</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The graphic elements to convert.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page where the absorber gets graphic elements.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>PdfException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If an error occurred when converting to SVG.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [GraphicElement](../../../aspose.pdf.vector/graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector::Extraction](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>, System::SharedPtr\<Page\>, System::String) method


Extracts graphic elements into a single SVG file. Options ignored - grouping, extracting from rectangle.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Vector::Extraction::SvgExtractor::Extract(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<GraphicElement>>> elements, System::SharedPtr<Page> page, System::String svgFilePath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| elements | System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\> | The graphic elements to convert. |
| page | System::SharedPtr\<Page\> | The page where the absorber gets graphic elements. |
| svgFilePath | System::String | The target SVG file path. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>elements</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The graphic elements to convert.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page where the absorber gets graphic elements.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>svgFilePath</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The target SVG file path.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>PdfException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If an error occurred when converting to SVG.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [GraphicElement](../../../aspose.pdf.vector/graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector::Extraction](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(System::SharedPtr\<Page\>) method


Extracts Svg images from a page to strings.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<System::Collections::Generic::List<System::String>> Aspose::Pdf::Vector::Extraction::SvgExtractor::Extract(System::SharedPtr<Page> page)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | The page to extract. |

### ReturnValue

The list of SVG content strings.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page to extract.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>PdfException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If an error occurred when converting to SVG.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector::Extraction](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(System::SharedPtr\<Page\>, System::String) method


Extracts Svg images from a page to files.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Vector::Extraction::SvgExtractor::Extract(System::SharedPtr<Page> page, System::String directory)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | The page to extract. |
| directory | System::String | The target directory to place SVG images. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>page</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The page to extract.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>directory</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The target directory to place SVG images.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>PdfException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If an error occurred when converting to SVG.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector::Extraction](../../)
* Library [Aspose.PDF for C++](../../../)
