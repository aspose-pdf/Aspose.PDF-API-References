---
title: Matrix3D.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Metode Matrix3D. Menerjemahkan rotasi menjadi derajat sudut
type: docs
weight: 180
url: /id/net/aspose.pdf/matrix3d/getangle/
---
## Metode Matrix3D.GetAngle

Menerjemahkan rotasi menjadi sudut (derajat)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotasi | Rotasi | Nilai rotasi. |

### Nilai Kembali

Nilai sudut.

## Contoh

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Lihat Juga

* enum [Rotasi](../../rotation/)
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)