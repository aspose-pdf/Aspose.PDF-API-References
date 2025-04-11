---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ToUnicodeProcessingRules クラス。このクラスは、Adobe Preflight エラー「テキストを Unicode にマッピングできません」を解決するために使用できるルールを説明します。
type: docs
weight: 11110
url: /ja/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules クラス

このクラスは、Adobe Preflight エラー「テキストを Unicode にマッピングできません」を解決するために使用できるルールを説明します。

```csharp
public class ToUnicodeProcessingRules
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | `ToUnicodeProcessingRules` クラスの新しいインスタンスを初期化します。 |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | CMap 名からスペースを削除するオプションを指定して、`ToUnicodeProcessingRules` クラスの新しいインスタンスを初期化します。 |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | 指定されたオプションで `ToUnicodeProcessingRules` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | 一部のフォントは、特定のテキストシンボルの Unicode に関する情報を提供しません。この情報の欠如は「テキストを Unicode にマッピングできません」というエラーを引き起こします。このフラグを使用して、非リンクシンボルを Unicode の「スペース」（コード 32）にマッピングします。 |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | 一部のフォントには、名前にスペースが含まれる ToUnicode 文字コードマップがあります。これらのスペースは、Unicode テキストマッピングにエラーを引き起こす可能性があります。このフラグは、ToUnicode 文字コードマップの名前からスペースを削除するよう指示します。デフォルトは false です。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)