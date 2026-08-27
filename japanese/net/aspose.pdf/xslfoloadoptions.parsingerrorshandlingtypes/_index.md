---
title: "列挙型 XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes 列挙型。ソース XSLFO ドキュメントには書式エラーが含まれる可能性があります。この列挙型は、そのような書式エラーの処理に利用できる戦略を列挙します。"
type: docs
weight: 11730
url: /ja/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumeration

Source XSLFO Document は書式エラーを含む可能性があります。この列挙型は、そのような書式エラーの処理に対する可能な戦略を列挙します。

```csharp
public enum ParsingErrorsHandlingTypes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| TryIgnore | `0` | この場合、コンバータは変換を続行し、検出された書式エラーを無視するよう指示されます。ただし、この場合の成功は保証されず、コンバータ内で後に深刻な問題が発生する可能性があり、そのような場合には検出された書式エラーの一覧を含む例外がスローされます。 |
| ThrowExceptionImmediately | `1` | この場合、変換は直ちに停止され、最初の書式エラーが検出された直後に例外がスローされます。 |
| InvokeCustomHandler | `2` | これは最も柔軟な方法です。カスタムコードは (WarningCallback プロパティ) に、書式エラーが検出されたときに呼び出される特別なハンドラを提供しなければなりません。そのハンドラは例えばエラーをログに記録したりカウントしたりでき、エラーごとに処理を継続するかどうかの判断を提供します。 |

### 関連項目

* class [XslFoLoadOptions](../xslfoloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


