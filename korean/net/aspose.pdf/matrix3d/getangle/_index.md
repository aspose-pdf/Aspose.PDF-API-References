---
title: Matrix3D.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Matrix3D 메서드. 회전을 각도(도)로 변환합니다.
type: docs
weight: 180
url: /ko/net/aspose.pdf/matrix3d/getangle/
---
## Matrix3D.GetAngle 메서드

회전을 각도(도)로 변환합니다.

```csharp
public static double GetAngle(Rotation rotation)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rotation | Rotation | 회전 값. |

### 반환 값

각도 값.

## 예제

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### 참조

* enum [Rotation](../../rotation/)
* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)