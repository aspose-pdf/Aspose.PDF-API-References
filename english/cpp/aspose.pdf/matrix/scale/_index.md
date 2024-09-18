---
title: Aspose::Pdf::Matrix::Scale method
linktitle: Scale
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Matrix::Scale method. Scales x and y with the matrix using the following formula: x1 = A*x + C*y; y1 = B*x + D*y; in C++.'
type: docs
weight: 1700
url: /cpp/aspose.pdf/matrix/scale/
---
## Matrix::Scale(double, double, double\&, double\&) method


Scales x and y with the matrix using the following formula: x1 = A*x + C*y; y1 = B*x + D*y;.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Matrix::Scale(double x, double y, double &x1, double &y1)
```


| Parameter | Type | Description |
| --- | --- | --- |
| x | double | Input X coordinate |
| y | double | Input Y coordinate |
| x1 | double\& | Output X coordinate |
| y1 | double\& | Output Y coordinate |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>x</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input X coordinate</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input Y coordinate</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>x1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output X coordinate</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output Y coordinate</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix::Scale(double, double, System::SharedPtr\<Matrix\>) method


Applies scaling to the given matrix.

```cpp
static ASPOSE_PDF_SHARED_API System::SharedPtr<Matrix> Aspose::Pdf::Matrix::Scale(double sx, double sy, System::SharedPtr<Matrix> source)
```


| Parameter | Type | Description |
| --- | --- | --- |
| sx | double | The scaling factor for the X-axis. |
| sy | double | The scaling factor for the Y-axis. |
| source | System::SharedPtr\<Matrix\> | The matrix to scale. |

### ReturnValue

A new matrix that is the result of scaling the source matrix.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>sx</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The scaling factor for the X-axis.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>sy</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The scaling factor for the Y-axis.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>source</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The matrix to scale.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Matrix](../)
* Class [Matrix](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
