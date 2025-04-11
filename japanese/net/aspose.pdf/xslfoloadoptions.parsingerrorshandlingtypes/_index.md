---
title: Enum XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes 列挙型。ソース XSLFO ドキュメントにはフォーマットエラーが含まれている可能性があります。この列挙型は、そのようなフォーマットエラーの処理方法の可能な戦略を列挙します。
type: docs
weight: 11540
url: /ja/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes 列挙型

ソース XSLFO ドキュメントにはフォーマットエラーが含まれている可能性があります。この列挙型は、そのようなフォーマットエラーの処理方法の可能な戦略を列挙します。

```csharp
public enum ParsingErrorsHandlingTypes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| TryIgnore | `0` | この場合、コンバータは変換を続行し、見つかったフォーマットエラーを無視するよう指示されます。この場合、成功は保証されず、コンバータ内で深刻な問題が発生する可能性があり、その場合は見つかったフォーマットエラーのリストと共に例外がスローされます。 |
| ThrowExceptionImmediately | `1` | この場合、変換は直ちに停止し、最初のフォーマットエラーを検出した後に直ちに例外がスローされます。 |
| InvokeCustomHandler | `2` | これは最も柔軟な方法です - カスタムコードは (WarningCallback プロパティで) フォーマットエラーが検出されたときに呼び出される特別なハンドラを提供する必要があります。そのハンドラは、例えばエラーをログに記録したりカウントしたりすることができ、どのエラーについて処理を続行できるかの決定を提供します。 |

### 参照

* クラス [XslFoLoadOptions](../xslfoloadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)