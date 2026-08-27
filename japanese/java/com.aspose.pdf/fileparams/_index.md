---
title: "FileParams"
linktitle: "FileParams"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "埋め込みファイルパラメータ辞書を定義し、追加のファイル固有情報を含めます。"
type: docs
weight: 1490
url: /ja/java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileParams

```
public final class FileParams extends Object
```

埋め込みファイルパラメータ辞書を定義し、追加のファイル固有情報を含めます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FileParams](#FileParams-com.aspose.pdf.FileSpecification-) | FileParams クラスのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCheckSum](#getCheckSum--) | 非圧縮の埋め込みファイルのバイトのチェックサムである 16 バイトの文字列です。チェックサムは、埋め込みファイルストリームのバイトに標準的な MD5 メッセージダイジェストアルゴリズムを適用して計算されます。 |
| [getCreationDate](#getCreationDate--) | 埋め込みファイルが作成された日時を取得します。 |
| [getModDate](#getModDate--) | 埋め込みファイルが最後に変更された日時を取得します。 |
| [getSize](#getSize--) | 非圧縮の埋め込みファイルのサイズ（バイト単位）。 |
| [setCreationDate](#setCreationDate-java.util.Date-) | 埋め込みファイルが作成された日時を設定します。 |
| [setModDate](#setModDate-java.util.Date-) | 埋め込みファイルが最後に変更された日時を設定します。 |

### FileParams {#FileParams-com.aspose.pdf.FileSpecification-}
FileParams クラスのコンストラクタです。

### getCheckSum {#getCheckSum--}
```
public String getCheckSum()
```

非圧縮の埋め込みファイルのバイトのチェックサムである 16 バイトの文字列です。チェックサムは、埋め込みファイルストリームのバイトに標準的な MD5 メッセージダイジェストアルゴリズムを適用して計算されます。

**Returns:**
文字列値

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

埋め込みファイルが作成された日時を取得します。

**Returns:**
Date オブジェクト

### getModDate {#getModDate--}
```
public Date getModDate()
```

埋め込みファイルが最後に変更された日時を取得します。

**Returns:**
Date オブジェクト

### getSize {#getSize--}
```
public int getSize()
```

非圧縮の埋め込みファイルのサイズ（バイト単位）。

**Returns:**
int 値です。

### setCreationDate {#setCreationDate-java.util.Date-}
埋め込みファイルが作成された日時を設定します。

### setModDate {#setModDate-java.util.Date-}
埋め込みファイルが最後に変更された日時を設定します。
