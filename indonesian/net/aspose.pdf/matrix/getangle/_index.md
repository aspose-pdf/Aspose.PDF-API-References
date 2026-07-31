---
title: "Matrix.GetAngle"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Matrix. Menerjemahkan rotasi menjadi derajat sudut"
type: docs
weight: 240
url: /id/net/aspose.pdf/matrix/getangle/
---
## Matrix.GetAngle method

Menerjemahkan rotasi menjadi sudut (derajat)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotasi | Rotation | Nilai rotasi. |

### Nilai Kembalian

Nilai sudut.

## Contoh

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Lihat Juga

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


