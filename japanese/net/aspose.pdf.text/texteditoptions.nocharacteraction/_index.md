---
title: Enum TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptionsNoCharacterAction 列挙型。フォントに必要な文字が含まれていない場合に実行するアクション
type: docs
weight: 10860
url: /ja/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction 列挙型

フォントに必要な文字が含まれていない場合に実行するアクション

```csharp
public enum NoCharacterAction
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| ThrowException | `0` | 例外をスロー |
| UseStandardFont | `1` | 必要な文字を含む標準フォントにフォントを置き換え |
| ReplaceAnyway | `2` | フォントの置き換えなしでテキストをとにかく置き換え |
| ReplaceFonts | `3` | テキスト内のすべての文字が表示できるように必要に応じてフォントを置き換えます。フォント置き換えアルゴリズムは次の手順に従います：1. ユーザーが明示的に Font プロパティを設定した場合、指定されたフォントが目的の文字を表示できるか確認します。2. ユーザー定義のフォントが設定されていない場合、[`Sources`](../fontrepository/sources/) を介して追加されたフォントを検索します。3. テキストを分析してそのアルファベットまたはスクリプトを特定し、それに応じてフォント名を提案します。これらのフォントをシステムから見つけて使用しようとします。4. フォールバックとして、必要な文字を表示できるフォントをシステム内で検索します。 |
| UseCustomReplacementFont | `4` | 定義された置き換えフォントにフォントを置き換え |

### 参照

* クラス [TextEditOptions](../texteditoptions/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)