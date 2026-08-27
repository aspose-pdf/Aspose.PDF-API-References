---
title: "Matrix.Multiply"
second_title: "Aspose.PDF for .NET API 参考"
description: "Matrix 方法。将矩阵乘以另一个矩阵。"
type: docs
weight: 170
url: /zh/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply method

将矩阵与另一个矩阵相乘。

```csharp
public Matrix Multiply(Matrix other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | Matrix | 乘数矩阵。 |

### 返回值

乘法的结果。

## 示例

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### 另请参见

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


