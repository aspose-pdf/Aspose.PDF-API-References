---
title: "クラス ToUnicodeProcessingRules"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.ToUnicodeProcessingRules クラス。このクラスは、Adobe Preflight エラー「Text cannot be mapped to Unicode」を解決するために使用できる規則を記述します。"
type: docs
weight: 11300
url: /ja/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class

このクラスは、Adobe Preflight エラー「Text cannot be mapped to Unicode」を解決するために使用できるルールを記述します。

```csharp
public class ToUnicodeProcessingRules
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | 新しい `ToUnicodeProcessingRules` クラスのインスタンスを初期化します。 |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | CMap 名からスペースを削除する指定オプションを使用して、`ToUnicodeProcessingRules` クラスの新しいインスタンスを初期化します。 |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | 指定されたオプションで `ToUnicodeProcessingRules` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | 一部のフォントは特定のテキストシンボルの Unicode 情報を提供しません。この情報不足によりエラー「Text cannot be mapped to Unicode」が発生します。このフラグを使用して、リンクされていないシンボルを Unicode の「スペース」(コード 32) にマップします。 |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | 一部のフォントは名前にスペースが含まれる ToUnicode 文字コードマップを持っています。これらのスペースが Unicode テキストマッピングでエラーを引き起こす可能性があります。このフラグは ToUnicode 文字コードマップの名前からスペースを削除するよう指示します。デフォルトは false です。 |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


