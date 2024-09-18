---
title: Aspose::Pdf::Matrix::Transform method
linktitle: Transform
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Matrix::Transform method. Transforms point using this matrix in C++.'
type: docs
weight: 2100
url: /cpp/aspose.pdf/matrix/transform/
---
## Matrix::Transform(System::SharedPtr\<Point\>) method


Transforms point using this matrix.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Point> Aspose::Pdf::Matrix::Transform(System::SharedPtr<Point> p)
```


| Parameter | Type | Description |
| --- | --- | --- |
| p | System::SharedPtr\<Point\> | [Point](../../point/) which will be transformed. |

### ReturnValue

Transformation result.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>p</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_point" kindref="compound">Point</ref> which will be transformed.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Point](../../point/)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Transform(double, double, double\&, double\&) method


Transforms coordinates using this matrix.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Matrix::Transform(double x, double y, double &x1, double &y1)
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | double | X coordinate. |
| y | double | Y coordinate. |
| x1 | double\& | Transformed X coordinate. |
| y1 | double\& | Transformed Y coordinate. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>x</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>X coordinate.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Y coordinate.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>x1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Transformed X coordinate.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Transformed Y coordinate.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Transform(System::SharedPtr\<Aspose::Pdf::Rectangle\>) method


Transformes rectangle. If angle is not 90 * N degrees then bounding rectangle is returned.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Aspose::Pdf::Rectangle> Aspose::Pdf::Matrix::Transform(System::SharedPtr<Aspose::Pdf::Rectangle> rect)
```


| Parameter | Type | Description |
| --- | --- | --- |
| rect | System::SharedPtr\<Aspose::Pdf::Rectangle\> | [Rectangle](../../rectangle/) to be transformed. |

### ReturnValue

Transformed rectangle.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>rect</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_rectangle" kindref="compound">Rectangle</ref> to be transformed.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Rectangle](../../rectangle/)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
