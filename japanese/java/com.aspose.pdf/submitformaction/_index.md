---
title: "SubmitFormAction"
linktitle: "SubmitFormAction"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "submit-form アクションを記述するクラスです。"
type: docs
weight: 4690
url: /ja/java/com.aspose.pdf/submitformaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.SubmitFormAction, com.aspose.pdf.PdfAction, com.aspose.pdf.SubmitFormAction

**All Implemented Interfaces:**
IAppointment

```
public final class SubmitFormAction extends PdfAction
```

submit-form アクションを記述するクラスです。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL_FORMAT) | 設定されている場合、日付を表す送信されたフィールド値は標準形式に変換されます。 |
| [EMBED_FORM](#EMBED_FORM) | 設定されている場合、送信された FDF の F エントリは、FDF が送信される元の PDF ファイルを表す埋め込みファイルストリームを含むファイル指定になります。 |
| [EXCL_F_KEY](#EXCL_F_KEY) | 設定されている場合、送信された FDF は F エントリを除外します。 |
| [EXCL_NON_USER_ANNOTS](#EXCL_NON_USER_ANNOTS) | 設定されている場合、現在のユーザー名と一致する T エントリを持つマークアップ注釈のみが含まれます。 |
| [EXCLUDE](#EXCLUDE) | クリアされている場合、Fields 配列は送信に含めるフィールドを指定します。 |
| [EXPORT_FORMAT](#EXPORT_FORMAT) | 設定されている場合、フィールド名と値は HTML フォーム形式で送信されます。 |
| [GET_METHOD](#GET_METHOD) | 設定されている場合、フィールド名と値は HTTP GET リクエストを使用して送信されます。 |
| [INCLUDE_ANNOTATIONS](#INCLUDE_ANNOTATIONS) | 設定されている場合、送信された FDF ファイルには基礎となる PDF ドキュメント内のすべてのマークアップ注釈が含まれます。 |
| [INCLUDE_APPEND_SAVES](#INCLUDE_APPEND_SAVES) | 設定されている場合、送信された FDF ファイルにはすべての増分更新の内容が含まれます。 |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE_NO_VALUE_FIELDS) | 設定されている場合、Fields 配列と Include/Exclude フラグで指定されたすべてのフィールドが送信されます。 |
| [SUBMIT_COORDINATES](#SUBMIT_COORDINATES) | 設定されている場合、submit-form アクションを引き起こしたマウスクリックの座標がフォームデータの一部として送信されます。 |
| [SUBMIT_PDF](#SUBMIT_PDF) | 設定されている場合、ドキュメントは MIME コンテンツタイプ application/pdf を使用して PDF として送信されます。 |
| [XFDF](#XFDF) | 設定されている場合、フィールド名と値は XFDF として送信されます。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SubmitFormAction](#SubmitFormAction--) | SubmitFormAction オブジェクトを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFlags](#getFlags--) | 送信アクションのフラグを取得します。 |
| [getUrl](#getUrl--) | 宛先 URL。 |
| [setFlags](#setFlags-int-) | 送信アクションのフラグを設定します。 |
| [setUrl](#setUrl-com.aspose.pdf.FileSpecification-) | 宛先 URL。 |

### CANONICAL_FORMAT {#CANONICAL_FORMAT}
```
public static final int CANONICAL_FORMAT
```

設定されている場合、日付を表す送信されたフィールド値は標準形式に変換されます。

### EMBED_FORM {#EMBED_FORM}
```
public static final int EMBED_FORM
```

設定されている場合、送信された FDF の F エントリは、FDF が送信される元の PDF ファイルを表す埋め込みファイルストリームを含むファイル指定になります。

### EXCL_F_KEY {#EXCL_F_KEY}
```
public static final int EXCL_F_KEY
```

設定されている場合、送信された FDF は F エントリを除外します。

### EXCL_NON_USER_ANNOTS {#EXCL_NON_USER_ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```

設定されている場合、現在のユーザー名と一致する T エントリを持つマークアップ注釈のみが含まれます。

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```

クリアされている場合、Fields 配列は送信に含めるフィールドを指定します。

### EXPORT_FORMAT {#EXPORT_FORMAT}
```
public static final int EXPORT_FORMAT
```

設定されている場合、フィールド名と値は HTML フォーム形式で送信されます。

### GET_METHOD {#GET_METHOD}
```
public static final int GET_METHOD
```

設定されている場合、フィールド名と値は HTTP GET リクエストを使用して送信されます。

### INCLUDE_ANNOTATIONS {#INCLUDE_ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```

設定されている場合、送信された FDF ファイルには基礎となる PDF ドキュメント内のすべてのマークアップ注釈が含まれます。

### INCLUDE_APPEND_SAVES {#INCLUDE_APPEND_SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```

設定されている場合、送信された FDF ファイルにはすべての増分更新の内容が含まれます。

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE_NO_VALUE_FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```

設定されている場合、Fields 配列と Include/Exclude フラグで指定されたすべてのフィールドが送信されます。

### SUBMIT_COORDINATES {#SUBMIT_COORDINATES}
```
public static final int SUBMIT_COORDINATES
```

設定されている場合、submit-form アクションを引き起こしたマウスクリックの座標がフォームデータの一部として送信されます。

### SUBMIT_PDF {#SUBMIT_PDF}
```
public static final int SUBMIT_PDF
```

設定されている場合、ドキュメントは MIME コンテンツタイプ application/pdf を使用して PDF として送信されます。

### XFDF {#XFDF}
```
public static final int XFDF
```

設定されている場合、フィールド名と値は XFDF として送信されます。

### SubmitFormAction {#SubmitFormAction--}
```
public SubmitFormAction()
```

SubmitFormAction オブジェクトを初期化します。

### getFlags {#getFlags--}
```
public int getFlags()
```

送信アクションのフラグを取得します。

**Returns:**
int 値です。

### getUrl {#getUrl--}
```
public FileSpecification getUrl()
```

宛先 URL。

**Returns:**
FileSpecification 値

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

送信アクションのフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setUrl {#setUrl-com.aspose.pdf.FileSpecification-}
宛先 URL。
