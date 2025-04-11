---
title: Matrix.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Metode matriks. Membuat matriks untuk sudut rotasi yang diberikan
type: docs
weight: 20
url: /id/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

Membuat matriks untuk sudut rotasi yang diberikan.

```csharp
public static Matrix Rotation(double alpha)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alpha | Double | Sudut rotasi dalam radian. |

### Return Value

Matriks transformasi.

## Contoh

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### Lihat Juga

* kelas [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

Membuat matriks untuk rotasi yang diberikan.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotation | Rotation | Rotasi. Nilai yang valid adalah: None, on90, on180, on270 |

### Return Value

Matriks dengan rotasi.

### Lihat Juga

* enum [Rotation](../../rotation/)
* kelas [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)