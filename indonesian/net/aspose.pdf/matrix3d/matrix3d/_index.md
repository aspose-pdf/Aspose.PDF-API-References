---
title: Matrix3D.Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Konstruktor Matrix3D. Konstruktor membuat matriks standar 1 ke 1 A B C D E F G H I Tx Ty Tz 1 0 0 0 1 0 0 0 1 0 0 0
type: docs
weight: 10
url: /id/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

Konstruktor membuat matriks standar 1 ke 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## Contoh

```csharp
Matrix3D m = new Matrix3D();
```

### Lihat Juga

* kelas [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

Konstruktor menerima matriks dengan representasi array berikut: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix3DArray | Double[] | Array data matriks. |

## Contoh

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### Lihat Juga

* kelas [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

Konstruktor menerima matriks untuk membuat salinan

```csharp
public Matrix3D(Matrix3D matrix)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | Matrix3D | Objek Matrix3D. |

### Lihat Juga

* kelas [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Menginisialisasi matriks transformasi dengan koefisien yang ditentukan.

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | Double | Nilai matriks A. |
| b | Double | Nilai matriks B. |
| c | Double | Nilai matriks C. |
| d | Double | Nilai matriks D. |
| e | Double | Nilai matriks E. |
| f | Double | Nilai matriks F. |
| g | Double | Nilai matriks G. |
| h | Double | Nilai matriks H. |
| i | Double | Nilai matriks I. |
| tx | Double | Nilai matriks TX. |
| ty | Double | Nilai matriks TY. |
| tz | Double | Nilai matriks TZ. |

## Contoh

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Lihat Juga

* kelas [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)