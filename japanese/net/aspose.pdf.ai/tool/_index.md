---
title: Class Tool
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.Toolクラス。モデルによって呼び出されるツールを表します。
type: docs
weight: 1190
url: /ja/net/aspose.pdf.ai/tool/
---
## ツールクラス

モデルによって呼び出されるツールを表します。

```csharp
public class Tool
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Tool](tool/#constructor)() | `Tool`クラスの新しいインスタンスを初期化します。 |
| [Tool](tool/#constructor_1)(Function) | 指定された関数で`Tool`クラスの新しいインスタンスを初期化します。 |
| [Tool](tool/#constructor_2)(string) | 指定されたツールタイプで`Tool`クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [CodeInterpreter](../../aspose.pdf.ai/tool/codeinterpreter/) { get; } | コードインタープリタを表すツールインスタンスを取得します。 |
| static [FileSearch](../../aspose.pdf.ai/tool/filesearch/) { get; } | ファイル検索ツールを表すツールインスタンスを取得します。 |
| [ToolFunction](../../aspose.pdf.ai/tool/toolfunction/) { get; set; } | モデルが呼び出すことができる関数を取得または設定します。 |
| [ToolType](../../aspose.pdf.ai/tool/tooltype/) { get; set; } | ツールのタイプを取得または設定します。現在、関数のみがサポートされています。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Function](../../aspose.pdf.ai/tool/function/)(Function) | 指定された関数で新しいツールインスタンスを作成します。 |

### 参照

* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)