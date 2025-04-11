---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Id クラス。ファイル識別子構造を表します
type: docs
weight: 5850
url: /ja/net/aspose.pdf/id/
---
## Id クラス

ファイル識別子構造を表します。

```csharp
public class Id
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | 最後に更新された時点での文書の内容に基づいて識別子を変更します。 |
| [Original](../../aspose.pdf/id/original/) { get; } | 元々作成された時点での文書の内容に基づく永続的な識別子です。 |

## 例

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)