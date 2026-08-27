---
title: "インターフェイス IOperationResult"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.IOperationResult インターフェイス。具体的なプラグインの操作結果が実装すべき共通メソッドを定義する汎用的な操作結果インターフェイスです。"
type: docs
weight: 8980
url: /ja/net/aspose.pdf.plugins/ioperationresult/
---
## IOperationResult interface

具体的なプラグイン操作結果が実装すべき共通メソッドを定義する汎用操作結果インターフェイスです。

```csharp
public interface IOperationResult
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Data](../../aspose.pdf.plugins/ioperationresult/data/) { get; } | 生データを取得します。 |
| [IsFile](../../aspose.pdf.plugins/ioperationresult/isfile/) { get; } | 結果が出力ファイルへのパスかどうかを示します。 |
| [IsStream](../../aspose.pdf.plugins/ioperationresult/isstream/) { get; } | 結果が出力ストリームかどうかを示します。 |
| [IsString](../../aspose.pdf.plugins/ioperationresult/isstring/) { get; } | 結果がテキスト文字列かどうかを示します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | 結果をファイルに変換しようとします。 |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | 結果をストリームオブジェクトに変換しようとします。 |

### 関連項目

* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


