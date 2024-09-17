---
title: Aspose::Pdf::Matrix::UnScale method
linktitle: UnScale
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Matrix::UnScale method. Scales back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); in C++.'
type: docs
weight: 1800
url: /cpp/aspose.pdf/matrix/unscale/
---
## Matrix::UnScale method


Scales back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Matrix::UnScale(double x1, double y1, double &x, double &y)
```


| Parameter | Type | Description |
| --- | --- | --- |
| x1 | double | Input X coordinate |
| y1 | double | Input Y coordinate |
| x | double\& | Output X coordinate |
| y | double\& | Output Y coordinate |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>x1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input X coordinate</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y1</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Input Y coordinate</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>x</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Output X coordinate</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>y</parametername>
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
