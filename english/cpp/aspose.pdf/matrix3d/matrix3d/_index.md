---
title: Aspose::Pdf::Matrix3D::Matrix3D constructor
linktitle: Matrix3D
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Matrix3D::Matrix3D constructor. Constructor creates standard 1 to 1 matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] in C++.'
type: docs
weight: 2500
url: /cpp/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D::Matrix3D() constructor


Constructor creates standard 1 to 1 matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0].

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Matrix3D::Matrix3D()
```

## See Also

* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(System::ArrayPtr\<double\>) constructor


Constructor accepts a matrix with following array representation: [ A B C D E F G H I Tx Ty Tz].

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Matrix3D::Matrix3D(System::ArrayPtr<double> matrix3DArray)
```


| Parameter | Type | Description |
| --- | --- | --- |
| matrix3DArray | System::ArrayPtr\<double\> | [Matrix](../../matrix/) data array. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>matrix3DArray</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_matrix" kindref="compound">Matrix</ref> data array.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(System::SharedPtr\<Matrix3D\>) constructor


Constructor accepts a matrix to create a copy.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Matrix3D::Matrix3D(System::SharedPtr<Matrix3D> matrix)
```


| Parameter | Type | Description |
| --- | --- | --- |
| matrix | System::SharedPtr\<Matrix3D\> | [Matrix3D](../) object. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>matrix</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_matrix3_d" kindref="compound">Matrix3D</ref> object.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Matrix3D](../)
* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Matrix3D::Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) constructor


Initializes transformation matrix with specified coefficients.

```cpp
ASPOSE_PDF_SHARED_API Aspose::Pdf::Matrix3D::Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```


| Parameter | Type | Description |
| --- | --- | --- |
| a | double | A matrix value. |
| b | double | B matrix value. |
| c | double | C matrix value. |
| d | double | D matrix value. |
| e | double | E matrix value. |
| f | double | F matrix value. |
| g | double | G matrix value. |
| h | double | H matrix value. |
| i | double | I matrix value. |
| tx | double | TX matrix value. |
| ty | double | TY matrix value. |
| tz | double | TZ matrix value. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>a</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A matrix value.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>b</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>B matrix value.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>c</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>C matrix value.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>d</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>D matrix value.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>e</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>E matrix value.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>f</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>F matrix value.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>g</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>G matrix value.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>h</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>H matrix value.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>i</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>I matrix value.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>tx</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>TX matrix value.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ty</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>TY matrix value.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>tz</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>TZ matrix value.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Matrix3D](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
