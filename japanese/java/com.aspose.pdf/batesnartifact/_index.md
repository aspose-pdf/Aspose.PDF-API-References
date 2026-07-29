---
title: "BatesNArtifact"
linktitle: "BatesNArtifact"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "クラスはBates番号付けアーティファクトを説明します。"
type: docs
weight: 290
url: /ja/java/com.aspose.pdf/batesnartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.PaginationArtifact, com.aspose.pdf.BatesNArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class BatesNArtifact extends PaginationArtifact
```

クラスはBates番号付けアーティファクトを説明します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BatesNArtifact](#BatesNArtifact--) | 新しい {@link BatesNArtifact} クラスのインスタンスを初期化します。このコンストラクタは内部用で、デフォルト値を持つヘッダーアーティファクトのインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getNumberOfDigits](#getNumberOfDigits--) | Bates 番号付けの桁数を取得または設定します。値は 3 から 15 の範囲でなければなりません。3 未満の値が設定された場合は 3 に調整され、15 を超える値が設定された場合は 15 に調整されます。デフォルト値は 6 です。 |
| [getPrefix](#getPrefix--) | Bates 番号に追加されるプレフィックスを取得または設定します。 |
| [getStartNumber](#getStartNumber--) | Bates 番号付けの開始番号を取得または設定します。値は 1 以上でなければなりません。1 未満の値が設定された場合は 1 に調整されます。 |
| [getSuffix](#getSuffix--) | Bates 番号に追加されるサフィックスを取得または設定します。 |
| [setNumberOfDigits](#setNumberOfDigits-int-) | Bates 番号付けの桁数を取得または設定します。値は 3 から 15 の範囲でなければなりません。3 未満の値が設定された場合は 3 に調整され、15 を超える値が設定された場合は 15 に調整されます。デフォルト値は 6 です。 |
| [setPrefix](#setPrefix-java.lang.String-) | Bates 番号に追加されるプレフィックスを取得または設定します。 |
| [setStartNumber](#setStartNumber-int-) | Bates 番号付けの開始番号を取得または設定します。値は 1 以上でなければなりません。1 未満の値が設定された場合は 1 に調整されます。 |
| [setSuffix](#setSuffix-java.lang.String-) | Bates 番号に追加されるサフィックスを取得または設定します。 |

### BatesNArtifact {#BatesNArtifact--}
```
public BatesNArtifact()
```

新しい {@link BatesNArtifact} クラスのインスタンスを初期化します。このコンストラクタは内部用で、デフォルト値を持つヘッダーアーティファクトのインスタンスを作成します。

### getNumberOfDigits {#getNumberOfDigits--}
```
public final int getNumberOfDigits()
```

Bates 番号付けの桁数を取得または設定します。値は 3 から 15 の範囲でなければなりません。3 未満の値が設定された場合は 3 に調整され、15 を超える値が設定された場合は 15 に調整されます。デフォルト値は 6 です。

**Returns:**
int 値です。

### getPrefix {#getPrefix--}
```
public final String getPrefix()
```

Bates 番号に追加されるプレフィックスを取得または設定します。

**Returns:**
文字列値

### getStartNumber {#getStartNumber--}
```
public final int getStartNumber()
```

Bates 番号付けの開始番号を取得または設定します。値は 1 以上でなければなりません。1 未満の値が設定された場合は 1 に調整されます。

**Returns:**
int 値です。

### getSuffix {#getSuffix--}
```
public final String getSuffix()
```

Bates 番号に追加されるサフィックスを取得または設定します。

**Returns:**
文字列値

### setNumberOfDigits {#setNumberOfDigits-int-}
```
public final void setNumberOfDigits(int value)
```

Bates 番号付けの桁数を取得または設定します。値は 3 から 15 の範囲でなければなりません。3 未満の値が設定された場合は 3 に調整され、15 を超える値が設定された場合は 15 に調整されます。デフォルト値は 6 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setPrefix {#setPrefix-java.lang.String-}
Bates 番号に追加されるプレフィックスを取得または設定します。

### setStartNumber {#setStartNumber-int-}
```
public final void setStartNumber(int value)
```

Bates 番号付けの開始番号を取得または設定します。値は 1 以上でなければなりません。1 未満の値が設定された場合は 1 に調整されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setSuffix {#setSuffix-java.lang.String-}
Bates 番号に追加されるサフィックスを取得または設定します。
