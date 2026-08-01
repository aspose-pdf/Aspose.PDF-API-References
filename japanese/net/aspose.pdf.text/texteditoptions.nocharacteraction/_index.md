---
title: "列挙体 TextEditOptions.NoCharacterAction"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.TextEditOptionsNoCharacterAction 列挙体。フォントに必要な文字が含まれていない場合に実行するアクション"
type: docs
weight: 11040
url: /ja/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction enumeration

フォントに必要な文字が含まれていない場合に実行するアクション

```csharp
public enum NoCharacterAction
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| ThrowException | `0` | 例外をスローする |
| UseStandardFont | `1` | 必要な文字を含む標準フォントに置き換える |
| ReplaceAnyway | `2` | フォント置換せずにテキストを置き換える |
| ReplaceFonts | `3` | テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。フォント置換アルゴリズムは以下の手順で実行されます：1. ユーザーが Font プロパティを明示的に設定している場合、指定されたフォントが目的の文字を表示できるか確認します。2. ユーザー定義のフォントが設定されていない場合、[`Sources`](../fontrepository/sources/) で追加されたフォントを検索します。3. テキストを解析し、アルファベットまたはスクリプトを特定し、それに応じたフォント名を提案します。システムからこれらのフォントを見つけて使用します。4. フォールバックとして、必要な文字を表示できる任意のフォントをシステムで検索します。 |
| UseCustomReplacementFont | `4` | 定義された置換フォントにフォントを置き換えます |

### 関連項目

* class [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


