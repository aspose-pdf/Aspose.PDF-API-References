---
title: "クラス Tool"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.Tool クラス。モデルから呼び出すことができるツールを表します。"
type: docs
weight: 1280
url: /ja/net/aspose.pdf.ai/tool/
---
## Tool class

モデルから呼び出すことができるツールを表します。

```csharp
public class Tool
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Tool](tool/#constructor)() | `Tool` クラスの新しいインスタンスを初期化します。 |
| [Tool](tool/#constructor_1)(Function) | 指定された関数で `Tool` クラスの新しいインスタンスを初期化します。 |
| [Tool](tool/#constructor_2)(string) | 指定されたツールタイプで `Tool` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [CodeInterpreter](../../aspose.pdf.ai/tool/codeinterpreter/) { get; } | コードインタプリタを表すツールインスタンスを取得します。 |
| static [FileSearch](../../aspose.pdf.ai/tool/filesearch/) { get; } | ファイル検索ツールを表すツールインスタンスを取得します。 |
| [ToolFunction](../../aspose.pdf.ai/tool/toolfunction/) { get; set; } | モデルが呼び出すことのできる関数を取得または設定します。 |
| [ToolType](../../aspose.pdf.ai/tool/tooltype/) { get; set; } | ツールのタイプを取得または設定します。現在、function のみがサポートされています。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Function](../../aspose.pdf.ai/tool/function/)(Function) | 指定された関数で新しいツールインスタンスを作成します。 |

### 関連項目

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


