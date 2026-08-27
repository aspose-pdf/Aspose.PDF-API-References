---
title: "ValidationMode"
linktitle: "ValidationMode"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF 署名検証プロセスの検証モードを指定します。"
type: docs
weight: 20
url: /ja/java/com.aspose.pdf.security.certificatevalidation/validationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMode

```
public final class ValidationMode extends com.aspose.ms.System.Enum
```

PDF 署名検証プロセスの検証モードを指定します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [None](#None) | 検証が実行されないモードを表します。 |
| [OnlyCheck](#OnlyCheck) | 検証が行われるが、その結果がデジタル署名の検証に影響しないモードを表します。検証結果は自分で確認できます。 |
| [Strict](#Strict) | 検証が行われ、その結果がデジタル署名の検証に影響するモードを表します。証明書が検証できない場合、デジタル署名は無効と見なされます。検証結果は自分で確認できます。 |

### None {#None}
```
public static final int None
```

検証が実行されないモードを表します。

### OnlyCheck {#OnlyCheck}
```
public static final int OnlyCheck
```

検証が行われるが、その結果がデジタル署名の検証に影響しないモードを表します。検証結果は自分で確認できます。

### Strict {#Strict}
```
public static final int Strict
```

検証が行われ、その結果がデジタル署名の検証に影響するモードを表します。証明書が検証できない場合、デジタル署名は無効と見なされます。検証結果は自分で確認できます。
