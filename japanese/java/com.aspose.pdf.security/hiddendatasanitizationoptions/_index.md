---
title: "HiddenDataSanitizationOptions"
linktitle: "HiddenDataSanitizationOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ドキュメント内の隠しデータをサニタイズするための構成オプションを表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.security/hiddendatasanitizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizationOptions

```
public final class HiddenDataSanitizationOptions extends Object
```

ドキュメント内の隠しデータをサニタイズするための構成オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HiddenDataSanitizationOptions](#HiddenDataSanitizationOptions--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [all](#all--) | すべてのサニタイズオプションが設定された {@link HiddenDataSanitizationOptions} クラスの新しいインスタンスを作成します。これには、アノテーション、JavaScript、メタデータ、添付ファイル、検索インデックス、プライベート情報の削除を有効にし、フォームとレイヤーのフラット化を行い、ページを画像に変換するオプションを無効にすることが含まれます。{@code ImageCompressionOptions}（{@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}）や {@code ConvertPagesToImages}（{@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}）などのオプション構成は、インスタンス取得後に手動で変更できますが、デフォルトでは有効ではありません。 |
| [getConvertPagesToImages](#getConvertPagesToImages--) | ページを画像に変換するオプションを取得します。このオプションが有効な場合、ImageCompressionOptions オプションは無視されます。必要な場合は、{@code #All()} メソッドを使用する際に手動でこのオプションを有効にする必要があります。ページを画像に変換する処理は、他のオプションで制御される主要な隠しデータのクリア後に実行されます。 |
| [getFlattenForms](#getFlattenForms--) | サニタイズ処理中にドキュメント内のフォームをフラット化すべきかどうかを示す値を取得します。フォームのフラット化は、インタラクティブなフォームフィールドを静的なコンテンツに変換し、編集や入力ができないようにします。 |
| [getFlattenLayers](#getFlattenLayers--) | PDF ドキュメントのレイヤーをフラット化するオプションを取得します。有効にすると、ドキュメント内のすべてのレイヤーが単一のレイヤーに統合され、個別の構造が削除されます。このオプションは、コンテンツを簡素化し、レイヤー内に隠しデータが残らないようにすることで、ドキュメントのサニタイズに役立ちます。 |
| [getImageCompressionOptions](#getImageCompressionOptions--) | ドキュメントの画像変換オプションを取得します。必要な場合は、{@code #All()} メソッドを使用する際に手動でこのオプションを有効にする必要があります。 |
| [getImageDpi](#getImageDpi--) | 変換中にページ画像を解決するオプションを取得します。 |
| [getRemoveAnnotations](#getRemoveAnnotations--) | ドキュメントからアノテーションを削除すべきかどうかを示す値を取得します。有効にすると、サニタイズ処理中にドキュメント内のすべてのアノテーションが削除され、マスクアノテーションが適用されます。 |
| [getRemoveAttachments](#getRemoveAttachments--) | ドキュメントからすべての添付ファイルを削除するオプションを取得します。有効にすると、PDF 内のすべての添付ファイルがサニタイズ処理中に除去されます。 |
| [getRemoveJavaScriptsAndActions](#getRemoveJavaScriptsAndActions--) | ドキュメントから JavaScript および関連するアクションを削除すべきかどうかを示す値を取得します。このオプションは、埋め込みスクリプトによってもたらされる潜在的なセキュリティ脆弱性を排除するのに役立ちます。 |
| [getRemoveMetadata](#getRemoveMetadata--) | ドキュメントからメタデータを削除するオプションを取得します。true に設定すると、ドキュメントプロパティや追加の埋め込みメタデータ情報などのメタデータがサニタイズ中に削除されます。 |
| [getRemoveSearchIndexAndPrivateInfo](#getRemoveSearchIndexAndPrivateInfo--) | ドキュメントから検索インデックスとプライベート情報を削除すべきかどうかを示す値を取得します。埋め込み検索インデックスとプライベートデータの削除を有効にし、ドキュメントのセキュリティとプライバシーを向上させます。 |
| [setConvertPagesToImages](#setConvertPagesToImages-boolean-) | ページを画像に変換するオプションを設定します。このオプションが有効な場合、ImageCompressionOptions オプションは無視されます。必要な場合は、{@code #All()} メソッドを使用する際に手動でこのオプションを有効にする必要があります。ページを画像に変換する処理は、他のオプションで制御される主要な隠しデータのクリア後に実行されます。 |
| [setFlattenForms](#setFlattenForms-boolean-) | サニタイズ処理中にドキュメント内のフォームをフラット化すべきかどうかを示す値を設定します。フォームのフラット化は、インタラクティブなフォームフィールドを静的なコンテンツに変換し、編集や入力ができないようにします。 |
| [setFlattenLayers](#setFlattenLayers-boolean-) | PDF ドキュメントのレイヤーをフラット化するオプションを設定します。有効にすると、ドキュメント内のすべてのレイヤーが単一のレイヤーに統合され、個別の構造が削除されます。このオプションは、コンテンツを簡素化し、レイヤー内に隠しデータが残らないようにすることで、ドキュメントのサニタイズに役立ちます。 |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | ドキュメントの画像変換オプションを設定します。必要な場合は、{@code #All()} メソッドを使用する際に手動でこのオプションを有効にする必要があります。 |
| [setImageDpi](#setImageDpi-int-) | 変換中にページ画像を解決するオプションを設定します。 |
| [setRemoveAnnotations](#setRemoveAnnotations-boolean-) | ドキュメントからアノテーションを削除すべきかどうかを示す値を設定します。有効にすると、サニタイズ処理中にドキュメント内のすべてのアノテーションが削除され、マスクアノテーションが適用されます。 |
| [setRemoveAttachments](#setRemoveAttachments-boolean-) | ドキュメントからすべての添付ファイルを削除するオプションを設定します。有効にすると、PDF 内のすべての添付ファイルがサニタイズ処理中に除去されます。 |
| [setRemoveJavaScriptsAndActions](#setRemoveJavaScriptsAndActions-boolean-) | ドキュメントから JavaScript および関連するアクションを削除すべきかどうかを示す値を設定します。このオプションは、埋め込みスクリプトによってもたらされる潜在的なセキュリティ脆弱性を排除するのに役立ちます。 |
| [setRemoveMetadata](#setRemoveMetadata-boolean-) | ドキュメントからメタデータを削除するオプションを設定します。true に設定すると、ドキュメントプロパティや追加の埋め込みメタデータ情報などのメタデータがサニタイズ中に削除されます。 |
| [setRemoveSearchIndexAndPrivateInfo](#setRemoveSearchIndexAndPrivateInfo-boolean-) | ドキュメントから検索インデックスとプライベート情報を削除すべきかどうかを示す値を設定します。埋め込み検索インデックスとプライベートデータの削除を有効にし、ドキュメントのセキュリティとプライバシーを向上させます。 |

### HiddenDataSanitizationOptions {#HiddenDataSanitizationOptions--}
```
public HiddenDataSanitizationOptions()
```



### all {#all--}
```
public static HiddenDataSanitizationOptions all()
```

すべてのサニタイズオプションが設定された {@link HiddenDataSanitizationOptions} クラスの新しいインスタンスを作成します。これには、アノテーション、JavaScript、メタデータ、添付ファイル、検索インデックス、プライベート情報の削除を有効にし、フォームとレイヤーのフラット化を行い、ページを画像に変換するオプションを無効にすることが含まれます。{@code ImageCompressionOptions}（{@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}）や {@code ConvertPagesToImages}（{@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}）などのオプション構成は、インスタンス取得後に手動で変更できますが、デフォルトでは有効ではありません。

**Returns:**
すべてのサニタイズオプションが事前に構成された {@link HiddenDataSanitizationOptions} インスタンスです。

### getConvertPagesToImages {#getConvertPagesToImages--}
```
public final boolean getConvertPagesToImages()
```

ページを画像に変換するオプションを取得します。このオプションが有効な場合、ImageCompressionOptions オプションは無視されます。必要な場合は、{@code #All()} メソッドを使用する際に手動でこのオプションを有効にする必要があります。ページを画像に変換する処理は、他のオプションで制御される主要な隠しデータのクリア後に実行されます。

**Returns:**
ページを画像に変換するオプション。

### getFlattenForms {#getFlattenForms--}
```
public final boolean getFlattenForms()
```

サニタイズ処理中にドキュメント内のフォームをフラット化すべきかどうかを示す値を取得します。フォームのフラット化は、インタラクティブなフォームフィールドを静的なコンテンツに変換し、編集や入力ができないようにします。

**Returns:**
文書内のフォームをサニタイズ処理中にフラット化するかどうかを示す値です。

### getFlattenLayers {#getFlattenLayers--}
```
public final boolean getFlattenLayers()
```

PDF ドキュメントのレイヤーをフラット化するオプションを取得します。有効にすると、ドキュメント内のすべてのレイヤーが単一のレイヤーに統合され、個別の構造が削除されます。このオプションは、コンテンツを簡素化し、レイヤー内に隠しデータが残らないようにすることで、ドキュメントのサニタイズに役立ちます。

**Returns:**
PDF 文書のレイヤーをフラット化するオプションです。

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

ドキュメントの画像変換オプションを取得します。必要な場合は、{@code #All()} メソッドを使用する際に手動でこのオプションを有効にする必要があります。

**Returns:**
文書画像変換オプションです。

### getImageDpi {#getImageDpi--}
```
public final int getImageDpi()
```

変換中にページ画像を解決するオプションを取得します。

**Returns:**
変換中にページ画像を解決するオプションです。

### getRemoveAnnotations {#getRemoveAnnotations--}
```
public final boolean getRemoveAnnotations()
```

ドキュメントからアノテーションを削除すべきかどうかを示す値を取得します。有効にすると、サニタイズ処理中にドキュメント内のすべてのアノテーションが削除され、マスクアノテーションが適用されます。

**Returns:**
文書から注釈を削除するかどうかを示す値です。

### getRemoveAttachments {#getRemoveAttachments--}
```
public final boolean getRemoveAttachments()
```

ドキュメントからすべての添付ファイルを削除するオプションを取得します。有効にすると、PDF 内のすべての添付ファイルがサニタイズ処理中に除去されます。

**Returns:**
文書からすべての添付ファイルを削除するオプションです。

### getRemoveJavaScriptsAndActions {#getRemoveJavaScriptsAndActions--}
```
public final boolean getRemoveJavaScriptsAndActions()
```

ドキュメントから JavaScript および関連するアクションを削除すべきかどうかを示す値を取得します。このオプションは、埋め込みスクリプトによってもたらされる潜在的なセキュリティ脆弱性を排除するのに役立ちます。

**Returns:**
文書から JavaScript と関連アクションを削除するかどうかを示す値です。

### getRemoveMetadata {#getRemoveMetadata--}
```
public final boolean getRemoveMetadata()
```

ドキュメントからメタデータを削除するオプションを取得します。true に設定すると、ドキュメントプロパティや追加の埋め込みメタデータ情報などのメタデータがサニタイズ中に削除されます。

**Returns:**
文書からメタデータを削除するオプションです。

### getRemoveSearchIndexAndPrivateInfo {#getRemoveSearchIndexAndPrivateInfo--}
```
public final boolean getRemoveSearchIndexAndPrivateInfo()
```

ドキュメントから検索インデックスとプライベート情報を削除すべきかどうかを示す値を取得します。埋め込み検索インデックスとプライベートデータの削除を有効にし、ドキュメントのセキュリティとプライバシーを向上させます。

**Returns:**
文書から検索インデックスとプライベート情報を削除するかどうかを示す値です。

### setConvertPagesToImages {#setConvertPagesToImages-boolean-}
```
public final void setConvertPagesToImages(boolean value)
```

ページを画像に変換するオプションを設定します。このオプションが有効な場合、ImageCompressionOptions オプションは無視されます。必要な場合は、{@code #All()} メソッドを使用する際に手動でこのオプションを有効にする必要があります。ページを画像に変換する処理は、他のオプションで制御される主要な隠しデータのクリア後に実行されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ページを画像に変換するオプション。 |

### setFlattenForms {#setFlattenForms-boolean-}
```
public final void setFlattenForms(boolean value)
```

サニタイズ処理中にドキュメント内のフォームをフラット化すべきかどうかを示す値を設定します。フォームのフラット化は、インタラクティブなフォームフィールドを静的なコンテンツに変換し、編集や入力ができないようにします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 文書内のフォームをサニタイズ処理中にフラット化するかどうかを示す値です。 |

### setFlattenLayers {#setFlattenLayers-boolean-}
```
public final void setFlattenLayers(boolean value)
```

PDF ドキュメントのレイヤーをフラット化するオプションを設定します。有効にすると、ドキュメント内のすべてのレイヤーが単一のレイヤーに統合され、個別の構造が削除されます。このオプションは、コンテンツを簡素化し、レイヤー内に隠しデータが残らないようにすることで、ドキュメントのサニタイズに役立ちます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | PDF 文書のレイヤーをフラット化するオプションです。 |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
ドキュメントの画像変換オプションを設定します。必要な場合は、{@code #All()} メソッドを使用する際に手動でこのオプションを有効にする必要があります。

### setImageDpi {#setImageDpi-int-}
```
public final void setImageDpi(int value)
```

変換中にページ画像を解決するオプションを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 変換中にページ画像を解決するオプションです。 |

### setRemoveAnnotations {#setRemoveAnnotations-boolean-}
```
public final void setRemoveAnnotations(boolean value)
```

ドキュメントからアノテーションを削除すべきかどうかを示す値を設定します。有効にすると、サニタイズ処理中にドキュメント内のすべてのアノテーションが削除され、マスクアノテーションが適用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 文書から注釈を削除するかどうかを示す値です。 |

### setRemoveAttachments {#setRemoveAttachments-boolean-}
```
public final void setRemoveAttachments(boolean value)
```

ドキュメントからすべての添付ファイルを削除するオプションを設定します。有効にすると、PDF 内のすべての添付ファイルがサニタイズ処理中に除去されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 文書からすべての添付ファイルを削除するオプションです。 |

### setRemoveJavaScriptsAndActions {#setRemoveJavaScriptsAndActions-boolean-}
```
public final void setRemoveJavaScriptsAndActions(boolean value)
```

ドキュメントから JavaScript および関連するアクションを削除すべきかどうかを示す値を設定します。このオプションは、埋め込みスクリプトによってもたらされる潜在的なセキュリティ脆弱性を排除するのに役立ちます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 文書から JavaScript と関連アクションを削除するかどうかを示す値です。 |

### setRemoveMetadata {#setRemoveMetadata-boolean-}
```
public final void setRemoveMetadata(boolean value)
```

ドキュメントからメタデータを削除するオプションを設定します。true に設定すると、ドキュメントプロパティや追加の埋め込みメタデータ情報などのメタデータがサニタイズ中に削除されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 文書からメタデータを削除するオプションです。 |

### setRemoveSearchIndexAndPrivateInfo {#setRemoveSearchIndexAndPrivateInfo-boolean-}
```
public final void setRemoveSearchIndexAndPrivateInfo(boolean value)
```

ドキュメントから検索インデックスとプライベート情報を削除すべきかどうかを示す値を設定します。埋め込み検索インデックスとプライベートデータの削除を有効にし、ドキュメントのセキュリティとプライバシーを向上させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 文書から検索インデックスとプライベート情報を削除するかどうかを示す値です。 |
