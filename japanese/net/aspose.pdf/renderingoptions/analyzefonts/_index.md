---
title: RenderingOptions.AnalyzeFonts
second_title: Aspose.PDF for .NET API Reference
description: RenderingOptions プロパティ。テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。フォント置換アルゴリズムは次の手順に従います。1. ユーザーが明示的に DefaultFontName プロパティを設定した場合、指定されたフォントが目的の文字を表示できるか確認します。2. ユーザー定義のフォントが設定されていない場合、!：FontRepository.Sources を介して追加されたフォントを検索します。3. テキストを分析して、そのアルファベットまたはスクリプトを特定し、それに応じてフォント名を提案します。これらのフォントをシステムから見つけて使用しようとします。4. フォールバックとして、必要な文字を表示できるフォントをシステムで検索します。
type: docs
weight: 20
url: /ja/net/aspose.pdf/renderingoptions/analyzefonts/
---
## RenderingOptions.AnalyzeFonts プロパティ

テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。フォント置換アルゴリズムは次の手順に従います：1. ユーザーが明示的に DefaultFontName プロパティを設定した場合、指定されたフォントが目的の文字を表示できるか確認します。2. ユーザー定義のフォントが設定されていない場合、!：FontRepository.Sources を介して追加されたフォントを検索します。3. テキストを分析して、そのアルファベットまたはスクリプトを特定し、それに応じてフォント名を提案します。これらのフォントをシステムから見つけて使用しようとします。4. フォールバックとして、必要な文字を表示できるフォントをシステムで検索します。

```csharp
public bool AnalyzeFonts { get; set; }
```

### 関連項目

* クラス [RenderingOptions](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)