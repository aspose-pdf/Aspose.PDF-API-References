---
title: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
linktitle: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ソース XSLFO ドキュメントには書式エラーが含まれる可能性があります。この列挙型は、そのような書式エラーの処理方法として可能な戦略を列挙します。"
type: docs
weight: 5790
url: /ja/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.Enum, com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends com.aspose.ms.System.Enum
```

ソース XSLFO ドキュメントには書式エラーが含まれる可能性があります。この列挙型は、そのような書式エラーの処理方法として可能な戦略を列挙します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [InvokeCustomHandler](#InvokeCustomHandler) | これは最も柔軟なメソッドです。カスタムコードは (WarningCallback プロパティで) フォーマットエラーが検出されたときに呼び出される特別なハンドラを提供しなければなりません。そのハンドラは例えばエラーをログに記録したりカウントしたりでき、処理をこのエラーまたはそのエラーで続行できるかどうかの判断を提供します。 |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | この場合、変換は直ちに停止し、最初のフォーマットエラーが検出された直後に例外がスローされます。 |
| [TryIgnore](#TryIgnore) | この場合、コンバータは変換を続行し、検出されたフォーマットエラーを無視するよう指示されます。ただし、成功は保証されず、コンバータ内で後に重大な問題が発生する可能性があります。そのような場合、検出されたフォーマットエラーの一覧を含む例外がスローされます。 |

### InvokeCustomHandler {#InvokeCustomHandler}
```
public static final int InvokeCustomHandler
```

これは最も柔軟なメソッドです。カスタムコードは (WarningCallback プロパティで) フォーマットエラーが検出されたときに呼び出される特別なハンドラを提供しなければなりません。そのハンドラは例えばエラーをログに記録したりカウントしたりでき、処理をこのエラーまたはそのエラーで続行できるかどうかの判断を提供します。

### ThrowExceptionImmediately {#ThrowExceptionImmediately}
```
public static final int ThrowExceptionImmediately
```

この場合、変換は直ちに停止し、最初のフォーマットエラーが検出された直後に例外がスローされます。

### TryIgnore {#TryIgnore}
```
public static final int TryIgnore
```

この場合、コンバータは変換を続行し、検出されたフォーマットエラーを無視するよう指示されます。ただし、成功は保証されず、コンバータ内で後に重大な問題が発生する可能性があります。そのような場合、検出されたフォーマットエラーの一覧を含む例外がスローされます。
