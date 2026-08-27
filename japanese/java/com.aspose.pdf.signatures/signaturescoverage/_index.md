---
title: "SignaturesCoverage"
linktitle: "SignaturesCoverage"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "文書におけるデジタル署名が提供するカバレッジレベルを表す列挙型です。"
type: docs
weight: 40
url: /ja/java/com.aspose.pdf.signatures/signaturescoverage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.Enum, com.aspose.pdf.signatures.SignaturesCoverage

```
public final class SignaturesCoverage extends com.aspose.ms.System.Enum
```

文書におけるデジタル署名が提供するカバレッジレベルを表す列挙型です。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [EntirelySigned](#EntirelySigned) | ドキュメントがデジタル署名で完全にカバーされていることを示します。この値は、ドキュメントのすべての必要な部分が署名され、署名が危殆化していないことを意味します。 |
| [PartiallySigned](#PartiallySigned) | ドキュメントが部分的に署名されていることを示します。つまり、コンテンツの一部はデジタル署名でカバーされていますが、すべてではありません。この値は、ドキュメントの特定の部分が未署名のままであるか、署名カバレッジから除外されている場合に使用されます。 |
| [Undefined](#Undefined) | ドキュメントにおけるデジタル署名のカバレッジ状態が未定義であることを示します。この値は、ドキュメント内の1つ以上の署名が危殆化しているか検証できない場合に使用され、署名カバレッジの明確な評価を妨げます。 |

### EntirelySigned {#EntirelySigned}
```
public static final int EntirelySigned
```

ドキュメントがデジタル署名で完全にカバーされていることを示します。この値は、ドキュメントのすべての必要な部分が署名され、署名が危殆化していないことを意味します。

### PartiallySigned {#PartiallySigned}
```
public static final int PartiallySigned
```

ドキュメントが部分的に署名されていることを示します。つまり、コンテンツの一部はデジタル署名でカバーされていますが、すべてではありません。この値は、ドキュメントの特定の部分が未署名のままであるか、署名カバレッジから除外されている場合に使用されます。

### Undefined {#Undefined}
```
public static final int Undefined
```

ドキュメントにおけるデジタル署名のカバレッジ状態が未定義であることを示します。この値は、ドキュメント内の1つ以上の署名が危殆化しているか検証できない場合に使用され、署名カバレッジの明確な評価を妨げます。
