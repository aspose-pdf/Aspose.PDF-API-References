---
title: "Matrix.Rotation"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Matrix. Membuat matriks untuk sudut rotasi yang diberikan"
type: docs
weight: 20
url: /id/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

Membuat Matrix untuk sudut rotasi yang diberikan.

```csharp
public static Matrix Rotation(double alpha)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alpha | Double | Sudut rotasi dalam radian. |

### Nilai Kembalian

Matriks transformasi.

## Contoh

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### Lihat Juga

* class [Matrix](../)
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
| rotasi | Rotation | Rotasi. Nilai yang valid adalah: None, on90, on180, on270 |

### Nilai Kembalian

Matriks dengan rotasi.

### Lihat Juga

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


