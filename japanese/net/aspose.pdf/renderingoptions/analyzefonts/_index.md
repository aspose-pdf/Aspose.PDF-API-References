---
title: "RenderingOptions.AnalyzeFonts"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "RenderingOptions プロパティ。テキスト内のすべての文字が表示できるように必要に応じてフォントを置き換えます。フォント置換アルゴリズムは次の手順で実行されます。1. ユーザーが DefaultFontName プロパティを明示的に設定している場合、指定されたフォントが目的の文字を表示できるか確認します。2. ユーザー定義フォントが設定されていない場合、FontRepository.Sources で追加されたフォントを検索します。3. テキストを解析してアルファベットまたはスクリプトを特定し、それに応じたフォント名を提案します。システムからこれらのフォントを見つけて使用しようとします。4. フォールバックとして、必要な文字を表示できる任意のフォントをシステムで検索します。"
type: docs
weight: 20
url: /ja/net/aspose.pdf/renderingoptions/analyzefonts/
---
## RenderingOptions.AnalyzeFonts property

必要に応じてフォントを置き換え、テキスト内のすべての文字が表示できるようにします。フォント置換アルゴリズムは以下の手順で実行されます：1. ユーザーが DefaultFontName プロパティを明示的に設定した場合、指定されたフォントが目的の文字を表示できるか確認します。2. ユーザー定義フォントが設定されていない場合、!:FontRepository.Sources で追加されたフォントを検索します。3. テキストを解析してアルファベットまたはスクリプトを特定し、それに応じたフォント名を提案します。システムからこれらのフォントを見つけて使用しようとします。4. フォールバックとして、必要な文字を表示できる任意のフォントをシステムで検索します。

```csharp
public bool AnalyzeFonts { get; set; }
```

### 関連項目

* class [RenderingOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


