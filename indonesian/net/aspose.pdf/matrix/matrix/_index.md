---
title: "Matrix.Matrix"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Konstruktor Matrix. Konstruktor membuat matriks standar 1 ke 1  A B C D E F    1 0 0 1 0 0"
type: docs
weight: 10
url: /id/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

Konstruktor membuat Matrix standar 1 ke 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## Contoh

```csharp
Matrix m = new Matrix();
```

### Lihat Juga

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

Konstruktor menerima sebuah Matrix dengan representasi array berikut: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrixArray | Double[] | Array data Matrix. |

## Contoh

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### Lihat Juga

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

Konstruktor menerima sebuah Matrix dengan representasi array berikut: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrixArray | Single[] | Array data Matrix. |

### Lihat Juga

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

Konstruktor menerima sebuah Matrix untuk membuat salinan

```csharp
public Matrix(Matrix matrix)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | Matrix | Objek Matrix. |

### Lihat Juga

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Menginisialisasi Matrix transformasi dengan koefisien yang ditentukan.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | Double | Nilai matriks. |
| b | Double | Nilai matriks B. |
| c | Double | Nilai matriks C. |
| d | Double | Nilai matriks D. |
| e | Double | Nilai matriks E. |
| f | Double | Nilai matrix F. |

## Contoh

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Lihat Juga

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


