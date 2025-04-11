---
title: Interface IOperationResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.IOperationResult インターフェース。具体的なプラグイン操作結果が実装すべき共通メソッドを定義する一般的な操作結果インターフェース
type: docs
weight: 8850
url: /ja/net/aspose.pdf.plugins/ioperationresult/
---
## IOperationResult インターフェース

具体的なプラグイン操作結果が実装すべき共通メソッドを定義する一般的な操作結果インターフェースです。

```csharp
public interface IOperationResult
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Data](../../aspose.pdf.plugins/ioperationresult/data/) { get; } | 生データを取得します。 |
| [IsFile](../../aspose.pdf.plugins/ioperationresult/isfile/) { get; } | 結果が出力ファイルへのパスであるかどうかを示します。 |
| [IsStream](../../aspose.pdf.plugins/ioperationresult/isstream/) { get; } | 結果が出力ストリームであるかどうかを示します。 |
| [IsString](../../aspose.pdf.plugins/ioperationresult/isstring/) { get; } | 結果がテキスト文字列であるかどうかを示します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | 結果をファイルに変換しようとします。 |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | 結果をストリームオブジェクトに変換しようとします。 |

### 参照

* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)