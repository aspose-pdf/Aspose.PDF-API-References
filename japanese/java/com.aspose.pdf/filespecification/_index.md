---
title: "FileSpecification"
linktitle: "FileSpecification"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "埋め込みファイルを表すクラスです。"
type: docs
weight: 1510
url: /ja/java/com.aspose.pdf/filespecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileSpecification

```
public final class FileSpecification extends Object
```

埋め込みファイルを表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FileSpecification](#FileSpecification--) | 新しい空のファイル仕様を作成します。 |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-) | 新しい空のファイル仕様を作成します。 |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | 新しい空のファイル仕様を作成します。 |
| [FileSpecification](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | 新しい空のファイル仕様を作成します。 |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | 新しい空のファイル仕様を作成します。 |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | 新しい空のファイル仕様を作成します。 |
| [FileSpecification](#FileSpecification-java.lang.String-) | 新しい空のファイル仕様を作成します。 |
| [FileSpecification](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | 新しい空のファイル仕様を作成します。 |
| [FileSpecification](#FileSpecification-java.lang.String-java.lang.String-) | 新しい空のファイル仕様を作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAFRelationship](#getAFRelationship--) | 関連付けられたファイルのリレーションシップ。 |
| [getCollectionItem](#getCollectionItem--) | ファイル仕様のコレクション項目を取得します。 |
| [getContents](#getContents--) | ファイルの内容を取得します。 |
| [getContentsInternal](#getContentsInternal--) | ファイルの内容を取得します。 |
| [getDescription](#getDescription--) | ファイル仕様に関連付けられたテキストを取得します。 |
| [getEncoding](#getEncoding--) | エンコーディング形式を取得します。可能な値: Zip - ファイルはZIPで圧縮されます、None - ファイルは圧縮されません。 |
| [getEncryptedPayload](#getEncryptedPayload--) | 暗号化されたペイロードを取得します。 |
| [getEngineDict](#getEngineDict--) | ファイルに関する情報を含むPDF辞書。内部使用のみ |
| [getEngineObj](#getEngineObj--) | 内部のみ |
| [getFileSystem](#getFileSystem--) | ファイルシステムの名前を取得します。 |
| [getMIMEType](#getMIMEType--) | 埋め込みファイルのサブタイプを取得します。 |
| [getName](#getName--) | ファイル仕様の名前を取得します。 |
| [getParams](#getParams--) | ファイルパラメータを取得します。 |
| [getStreamContents](#getStreamContents--) | ファイルの内容をストリームとして取得します。内容はメモリにロードされないため、メモリ使用量を削減できます。ただし、このストリームは位置指定や Length プロパティをサポートしません。この機能が必要な場合は、代わりに Contents プロパティを使用してください。 |
| [getUnicodeName](#getUnicodeName--) | ファイル仕様の Unicode 名を取得します。 |
| [getValue](#getValue-java.lang.String-) | アプリケーション固有のパラメータを取得します。 |
| [isIncludeContents](#isIncludeContents--) | true の場合、ファイルの内容がファイル仕様に含まれます。 |
| [setAFRelationship](#setAFRelationship-com.aspose.pdf.AFRelationship-) | 関連付けられたファイルのリレーションシップ。 |
| [setContents](#setContents-byte:A-) | ファイルの内容を設定します。 |
| [setContents](#setContents-java.io.InputStream-) | ファイルの内容を設定します。 |
| [setDescription](#setDescription-java.lang.String-) | ファイル仕様に関連付けられたテキストを設定します。 |
| [setEncoding](#setEncoding-com.aspose.pdf.FileEncoding-) | エンコーディング形式を設定します。可能な値: Zip - ファイルはZIPで圧縮されます、None - ファイルは圧縮されません。 |
| [setFileSystem](#setFileSystem-java.lang.String-) | ファイルシステムの名前を設定します。 |
| [setIncludeContents](#setIncludeContents-boolean-) | true の場合、ファイルの内容がファイル仕様に含まれます。 |
| [setMIMEType](#setMIMEType-java.lang.String-) | MIMEタイプを設定します。 |
| [setName](#setName-java.lang.String-) | ファイル仕様の名前を設定します。 |
| [setParams](#setParams-com.aspose.pdf.FileParams-) | ファイルパラメータを設定します。 |
| [setUnicodeName](#setUnicodeName-java.lang.String-) | ファイル仕様の Unicode 名を設定します。 |
| [setValue](#setValue-java.lang.String-java.lang.String-) | アプリケーション固有のパラメータを設定します。 |

### FileSpecification {#FileSpecification--}
```
public FileSpecification()
```

新しい空のファイル仕様を作成します。

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-}
新しい空のファイル仕様を作成します。

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
新しい空のファイル仕様を作成します。

### FileSpecification {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
新しい空のファイル仕様を作成します。

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
新しい空のファイル仕様を作成します。

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
新しい空のファイル仕様を作成します。

### FileSpecification {#FileSpecification-java.lang.String-}
新しい空のファイル仕様を作成します。

### FileSpecification {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
新しい空のファイル仕様を作成します。

### FileSpecification {#FileSpecification-java.lang.String-java.lang.String-}
新しい空のファイル仕様を作成します。

### getAFRelationship {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```

関連付けられたファイルのリレーションシップ。

**Returns:**
AFRelationship 要素

### getCollectionItem {#getCollectionItem--}
```
public final CollectionItem getCollectionItem()
```

ファイル仕様のコレクション項目を取得します。

**Returns:**
CollectionItem インスタンス

### getContents {#getContents--}
```
public InputStream getContents()
```

ファイルの内容を取得します。

**Returns:**
InputStream オブジェクト

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

ファイルの内容を取得します。

**Returns:**
ストリーム オブジェクト

### getDescription {#getDescription--}
```
public String getDescription()
```

ファイル仕様に関連付けられたテキストを取得します。

**Returns:**
文字列値

### getEncoding {#getEncoding--}
```
public FileEncoding getEncoding()
```

エンコーディング形式を取得します。可能な値: Zip - ファイルはZIPで圧縮されます、None - ファイルは圧縮されません。

**Returns:**
int 値 @see FileEncoding

### getEncryptedPayload {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```

暗号化されたペイロードを取得します。

**Returns:**
EncryptedPayload インスタンス

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

ファイルに関する情報を含むPDF辞書。内部使用のみ

**Returns:**
IPdfDictionary オブジェクト

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

内部のみ

**Returns:**
IPdfObject オブジェクト

### getFileSystem {#getFileSystem--}
```
public String getFileSystem()
```

ファイルシステムの名前を取得します。

**Returns:**
文字列値

### getMIMEType {#getMIMEType--}
```
public String getMIMEType()
```

埋め込みファイルのサブタイプを取得します。

**Returns:**
string 値

### getName {#getName--}
```
public String getName()
```

ファイル仕様の名前を取得します。

**Returns:**
文字列値

### getParams {#getParams--}
```
public FileParams getParams()
```

ファイルパラメータを取得します。

**Returns:**
FileParams オブジェクト

### getStreamContents {#getStreamContents--}
```
public InputStream getStreamContents()
```

ファイルの内容をストリームとして取得します。内容はメモリにロードされないため、メモリ使用量を削減できます。ただし、このストリームは位置指定や Length プロパティをサポートしません。この機能が必要な場合は、代わりに Contents プロパティを使用してください。

**Returns:**
InputStream オブジェクト

### getUnicodeName {#getUnicodeName--}
```
public String getUnicodeName()
```

ファイル仕様の Unicode 名を取得します。

**Returns:**
文字列値

### getValue {#getValue-java.lang.String-}
アプリケーション固有のパラメータを取得します。

### isIncludeContents {#isIncludeContents--}
```
public boolean isIncludeContents()
```

true の場合、ファイルの内容がファイル仕様に含まれます。

**Returns:**
ブール値

### setAFRelationship {#setAFRelationship-com.aspose.pdf.AFRelationship-}
関連付けられたファイルのリレーションシップ。

### setContents {#setContents-byte:A-}
```
public void setContents(byte[] value)
```

ファイルの内容を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | バイト配列 |

### setContents {#setContents-java.io.InputStream-}
ファイルの内容を設定します。

### setDescription {#setDescription-java.lang.String-}
ファイル仕様に関連付けられたテキストを設定します。

### setEncoding {#setEncoding-com.aspose.pdf.FileEncoding-}
エンコーディング形式を設定します。可能な値: Zip - ファイルはZIPで圧縮されます、None - ファイルは圧縮されません。

### setFileSystem {#setFileSystem-java.lang.String-}
ファイルシステムの名前を設定します。

### setIncludeContents {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```

true の場合、ファイルの内容がファイル仕様に含まれます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMIMEType {#setMIMEType-java.lang.String-}
MIMEタイプを設定します。

### setName {#setName-java.lang.String-}
ファイル仕様の名前を設定します。

### setParams {#setParams-com.aspose.pdf.FileParams-}
ファイルパラメータを設定します。

### setUnicodeName {#setUnicodeName-java.lang.String-}
ファイル仕様の Unicode 名を設定します。

### setValue {#setValue-java.lang.String-java.lang.String-}
アプリケーション固有のパラメータを設定します。
