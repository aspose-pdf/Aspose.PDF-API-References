---
title: "PaginationArtifact"
linktitle: "PaginationArtifact"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "文書内のページ付けアーティファクトの抽象基底クラスを表します。"
type: docs
weight: 3460
url: /ja/java/com.aspose.pdf/paginationartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public abstract class PaginationArtifact extends Artifact
```

文書内のページ付けアーティファクトの抽象基底クラスを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEndPage](#getEndPage--) | アーティファクトの終了ページ番号を取得または設定します。値は 0 以上でなければなりません。0 未満の値が設定された場合、0 に調整されます。デフォルト値の 0 は、終了ページの境界がないことを意味します。 |
| [getStartPage](#getStartPage--) | アーティファクトの開始ページ番号を取得または設定します。値は 1 以上でなければなりません。1 未満の値が設定された場合、1 に調整されます。 |
| [getSubset](#getSubset--) | アーティファクトが適用されるページのサブセットを取得または設定します（例: すべてのページ、偶数ページ、奇数ページ）。 |
| [setEndPage](#setEndPage-int-) | アーティファクトの終了ページ番号を取得または設定します。値は 0 以上でなければなりません。0 未満の値が設定された場合、0 に調整されます。デフォルト値の 0 は、終了ページの境界がないことを意味します。 |
| [setStartPage](#setStartPage-int-) | アーティファクトの開始ページ番号を取得または設定します。値は 1 以上でなければなりません。1 未満の値が設定された場合、1 に調整されます。 |
| [setSubset](#setSubset-int-) | アーティファクトが適用されるページのサブセットを取得または設定します（例: すべてのページ、偶数ページ、奇数ページ）。 |

### getEndPage {#getEndPage--}
```
public final int getEndPage()
```

アーティファクトの終了ページ番号を取得または設定します。値は 0 以上でなければなりません。0 未満の値が設定された場合、0 に調整されます。デフォルト値の 0 は、終了ページの境界がないことを意味します。

**Returns:**
int 値です。

### getStartPage {#getStartPage--}
```
public final int getStartPage()
```

アーティファクトの開始ページ番号を取得または設定します。値は 1 以上でなければなりません。1 未満の値が設定された場合、1 に調整されます。

**Returns:**
int 値です。

### getSubset {#getSubset--}
```
public final int getSubset()
```

アーティファクトが適用されるページのサブセットを取得または設定します（例: すべてのページ、偶数ページ、奇数ページ）。

**Returns:**
int 値です。

### setEndPage {#setEndPage-int-}
```
public final void setEndPage(int value)
```

アーティファクトの終了ページ番号を取得または設定します。値は 0 以上でなければなりません。0 未満の値が設定された場合、0 に調整されます。デフォルト値の 0 は、終了ページの境界がないことを意味します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setStartPage {#setStartPage-int-}
```
public final void setStartPage(int value)
```

アーティファクトの開始ページ番号を取得または設定します。値は 1 以上でなければなりません。1 未満の値が設定された場合、1 に調整されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setSubset {#setSubset-int-}
```
public final void setSubset(int value)
```

アーティファクトが適用されるページのサブセットを取得または設定します（例: すべてのページ、偶数ページ、奇数ページ）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
