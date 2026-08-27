---
title: "CompromiseCheckResult"
linktitle: "CompromiseCheckResult"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "文書のデジタル署名が改ざんされていないかチェックするクラスを表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.signatures/compromisecheckresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.CompromiseCheckResult

```
public final class CompromiseCheckResult extends Object
```

文書のデジタル署名が改ざんされていないかチェックするクラスを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [CompromisedSignatures](#CompromisedSignatures) | 破損が確認されたデジタル署名のコレクションを取得します。このプロパティには、ドキュメント内で検出されたすべての破損した署名のリストが含まれます。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSignaturesCoverage](#getSignaturesCoverage--) | ドキュメント内のデジタル署名のカバレッジ状態を取得します。{@code SignaturesCoverage#Undefined} と等しい場合、署名の1つが危殆化しています。 |
| [hasCompromisedSignatures](#hasCompromisedSignatures--) | ドキュメントに危殆化したデジタル署名があるかどうかを示します。少なくとも1つの署名が危殆化している場合は true を返し、そうでなければ false を返します。 |

### CompromisedSignatures {#CompromisedSignatures}
```
public final List < SignatureName > CompromisedSignatures
```

破損が確認されたデジタル署名のコレクションを取得します。このプロパティには、ドキュメント内で検出されたすべての破損した署名のリストが含まれます。

### getSignaturesCoverage {#getSignaturesCoverage--}
```
public final int getSignaturesCoverage()
```

ドキュメント内のデジタル署名のカバレッジ状態を取得します。{@code SignaturesCoverage#Undefined} と等しい場合、署名の1つが危殆化しています。

**Returns:**
SignaturesCoverage 要素

### hasCompromisedSignatures {#hasCompromisedSignatures--}
```
public final boolean hasCompromisedSignatures()
```

ドキュメントに危殆化したデジタル署名があるかどうかを示します。少なくとも1つの署名が危殆化している場合は true を返し、そうでなければ false を返します。

**Returns:**
ブール値
