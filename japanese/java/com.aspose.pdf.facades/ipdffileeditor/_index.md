---
title: "IPdfFileEditor"
linktitle: "IPdfFileEditor"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ファイルに対する操作（結合、分割、ページ抽出、ブックレット作成など）を実装します。"
type: docs
weight: 290
url: /ja/java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

PDF ファイルに対する操作（結合、分割、ページ抽出、ブックレット作成など）を実装します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | ページ内容のサイズを変更し、指定された余白を追加します。 |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | ページ内容のサイズを変更し、指定された余白を追加します。 |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | ページ内容のサイズを変更し、指定された余白を追加します。 |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | ページ内容のサイズを変更し、指定された余白を追加します。 |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | portStreams のドキュメント配列から選択されたページを追加します。 |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | portStream から startPage から endPage の範囲で選択されたページを、firstInputStream の末尾にある portStream に追加します。 |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | portFiles のドキュメントから選択されたページを追加します。 |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | portFile から startPage から endPage の範囲で選択されたページを、firstInputFile の末尾にある portFile に追加します。 |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | ドキュメントを連結します。 |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | ファイルを連結します |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 2つの Pdf ドキュメントを交互にページを配置した新しい Pdf ドキュメントに結合し、空白の場所を空白ページで埋めます。 |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 2つのファイルを連結します。 |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | ファイルを1つのファイルに連結します。 |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | 2つのファイルを連結します。 |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 2つの Pdf ドキュメントを交互にページを配置した新しい Pdf ドキュメントに結合し、空白の場所を空白ページで埋めます。 |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | 入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。 |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | 番号配列で指定されたページを抽出し、新しい Pdf ファイルとして保存します。 |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | 入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。 |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | 番号配列で指定されたページを抽出し、新しい PDF ファイルとして保存します。 |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | 入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。 |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | Allow Concatenate Exceptions かどうか |
| [getAttachmentName](#getAttachmentName--) | 操作の結果が HttpServletResponse オブジェクトに添付ファイルとして格納されるときの添付ファイル名を取得します。 |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | true に設定すると、操作後にストリームが閉じられます。 |
| [getContentDisposition](#getContentDisposition--) | 操作の結果が HttpServletResponse オブジェクトに格納されるとき、コンテンツがどのように保存されるかを取得します。 |
| [getConversionLog](#getConversionLog--) | 変換プロセスのログを取得します。 |
| [getCorruptedFileAction](#getCorruptedFileAction--) | このプロパティは、連結処理中に破損したファイルに遭遇したときの動作を定義します。 |
| [getIncrementalUpdates](#getIncrementalUpdates--) | true の場合、連結中に増分更新が行われます。 |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | true の場合、フォームを連結するときにフィールド名が一意になるように作成されます。 |
| [getLastException](#getLastException--) | 最後に発生した例外を取得します。 |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | このプロパティが true の場合、同名の連結ドキュメントのオプションコンテンツが結果ドキュメントの1つのレイヤーにマージされます。 |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | true の場合、重複したアウトラインがマージされます。 |
| [getOwnerPassword](#getOwnerPassword--) | ソース入力 PDF ファイルが暗号化されている場合、所有者のパスワードを取得します。 |
| [getPreserveUserRights](#getPreserveUserRights--) | true の場合、最初のドキュメントのユーザー権限が連結ドキュメントに適用されます。 |
| [getRemoveSignatures](#getRemoveSignatures--) | true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）。そうでない場合、無効な署名が残る可能性があります。 |
| [getSaveOptions](#getSaveOptions--) | 結果が HttpServletResponse として保存されるときの保存オプションを取得または設定します。 |
| [getUniqueSuffix](#getUniqueSuffix--) | フォームを連結するときにフィールド名を一意にするために追加されるサフィックスの形式を取得します。 |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | 別のファイルからページを挿入して、入力 PDF ファイルに追加します。 |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | 別のファイルからページを挿入して、入力 PDF ファイルに追加します。 |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | 別のファイルからページを挿入して、入力 PDF ファイルに追加します。 |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | 別のファイルからページを指定位置に挿入して、PDF ファイルに追加します。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | InputStream から outputStream へブックレットを作成します。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | firstInputStream から outputStream へカスタマイズされたブックレットを作成します。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | 入力ストリームからブックレットを作成し、結果を出力ストリームに保存します。 |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | firstInputStream から outputStream へブックレットを作成します。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | 入力ファイルから出力ファイルへブックレットを作成します。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | firstInputFile から outputFile へカスタマイズされたブックレットを作成します。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | inputFile から outputFile へブックレットを作成します。 |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | firstInputFile から outputFile へカスタマイズされたブックレットを作成します。 |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | 複数の入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。 |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | 2 つの入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。 |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | 入力ストリームから N-Up ドキュメントを作成し、結果を出力ストリームに保存します。 |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | 最初の入力ストリームから output stream へ N-Up ドキュメントを作成します。 |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | 複数の入力 PDF ファイルから outputFile へ N-Up ドキュメントを作成します。 |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | firstInputFile から outputFile へ N-Up ドキュメントを作成します。 |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | 入力ファイルから outputFile へ N-Up ドキュメントを作成します。 |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | 2 つの入力 PDF ファイルから outputFile へ N-Up ドキュメントを作成します。 |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | ドキュメントページの内容のサイズを変更します。 |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | ドキュメントページの内容のサイズを変更します。 |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | ドキュメントページの内容のサイズを変更します。 |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | ドキュメントページの内容のサイズを変更します。 |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | true に設定すると、エラーが発生した場合に例外がスローされます。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 操作の結果が HttpServletResponse オブジェクトに添付ファイルとして保存されるときの添付ファイル名を設定します。 |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | true に設定すると、操作後にストリームが閉じられます。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 操作の結果が HttpServletResponse オブジェクトに格納される際のコンテンツの保存方法を設定します。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF ファイル形式を設定します。 |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | このプロパティは、連結処理中に破損したファイルに遭遇したときの動作を定義します。 |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | true の場合、連結中に増分更新が行われます。 |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | true の場合、フォームを連結するときにフィールド名が一意になるように作成されます。 |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | このプロパティが true の場合、同名の連結ドキュメントのオプションコンテンツが結果ドキュメントの1つのレイヤーにマージされます。 |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | true の場合、重複したアウトラインがマージされます。 |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | ソース入力 PDF ファイルが暗号化されている場合、所有者のパスワードを設定します。 |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | true の場合、最初のドキュメントのユーザー権限が連結ドキュメントに適用されます。 |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）。そうでない場合、無効な署名が残る可能性があります。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 結果が HttpServletResponse として格納される際の保存オプションを設定します。 |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | フォームが連結されるときにフィールド名が一意になるように付加されるサフィックスの形式を設定します。 |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | 開始位置から指定された場所まで分割し、前半部分を出力ストリームに保存します。 |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | PDF ファイルを最初のページから指定された場所まで分割し、前半部分を新しいファイルとして保存します。 |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | PDF ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにできます。 |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | PDF ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにできます。 |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | 指定された位置から分割し、後半部分を新しいファイルストリームとして保存します。 |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | 位置から分割し、後半部分を新しいファイルとして保存します。 |
| [splitToPages](#splitToPages-java.io.InputStream-) | PDF ファイルを単一ページのドキュメントに分割します。 |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。 |
| [splitToPages](#splitToPages-java.lang.String-) | PDFファイルを単一ページのドキュメントに分割します。 |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。 |

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
ページ内容のサイズを変更し、指定された余白を追加します。

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
ページ内容のサイズを変更し、指定された余白を追加します。

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
ページ内容のサイズを変更し、指定された余白を追加します。

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
ページ内容のサイズを変更し、指定された余白を追加します。

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
portStreams のドキュメント配列から選択されたページを追加します。

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
portStream から startPage から endPage の範囲で選択されたページを、firstInputStream の末尾にある portStream に追加します。

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
portFiles のドキュメントから選択されたページを追加します。

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
portFile から startPage から endPage の範囲で選択されたページを、firstInputFile の末尾にある portFile に追加します。

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
ドキュメントを連結します。

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
ファイルを連結します

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
2つの Pdf ドキュメントを交互にページを配置した新しい Pdf ドキュメントに結合し、空白の場所を空白ページで埋めます。

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
2つのファイルを連結します。

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
ファイルを1つのファイルに連結します。

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
2つのファイルを連結します。

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
2つの Pdf ドキュメントを交互にページを配置した新しい Pdf ドキュメントに結合し、空白の場所を空白ページで埋めます。

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。

### delete {#delete-java.lang.String-int:A-java.lang.String-}
入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
番号配列で指定されたページを抽出し、新しい Pdf ファイルとして保存します。

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。

### extract {#extract-java.lang.String-int:A-java.lang.String-}
番号配列で指定されたページを抽出し、新しい PDF ファイルとして保存します。

### extract {#extract-java.lang.String-int-int-java.lang.String-}
入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
boolean getAllowConcatenateExceptions()
```

Allow Concatenate Exceptions かどうか

**Returns:**
ブール値

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

操作の結果が HttpServletResponse オブジェクトに添付ファイルとして格納されるときの添付ファイル名を取得します。

**Returns:**
string 値

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
boolean getCloseConcatenatedStreams()
```

true に設定すると、操作後にストリームが閉じられます。

**Returns:**
ブール値

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

操作の結果が HttpServletResponse オブジェクトに格納されるとき、コンテンツがどのように保存されるかを取得します。

**Returns:**
ContentDisposition 要素

### getConversionLog {#getConversionLog--}
```
String getConversionLog()
```

変換プロセスのログを取得します。

**Returns:**
string 値

### getCorruptedFileAction {#getCorruptedFileAction--}
```
int getCorruptedFileAction()
```

このプロパティは、連結処理中に破損したファイルに遭遇したときの動作を定義します。

**Returns:**
ConcatenateCorruptedFileAction 要素

### getIncrementalUpdates {#getIncrementalUpdates--}
```
boolean getIncrementalUpdates()
```

true の場合、連結中に増分更新が行われます。

**Returns:**
ブール値

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
boolean getKeepFieldsUnique()
```

true の場合、フォームを連結するときにフィールド名が一意になるように作成されます。

**Returns:**
ブール値

### getLastException {#getLastException--}
```
Exception getLastException()
```

最後に発生した例外を取得します。

**Returns:**
java.lang.Exception オブジェクト

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
boolean getMergeDuplicateLayers()
```

このプロパティが true の場合、同名の連結ドキュメントのオプションコンテンツが結果ドキュメントの1つのレイヤーにマージされます。

**Returns:**
ブール値

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
boolean getMergeDuplicateOutlines()
```

true の場合、重複したアウトラインがマージされます。

**Returns:**
ブール値

### getOwnerPassword {#getOwnerPassword--}
```
String getOwnerPassword()
```

ソース入力 PDF ファイルが暗号化されている場合、所有者のパスワードを取得します。

**Returns:**
string 値

### getPreserveUserRights {#getPreserveUserRights--}
```
boolean getPreserveUserRights()
```

true の場合、最初のドキュメントのユーザー権限が連結ドキュメントに適用されます。

**Returns:**
ブール値

### getRemoveSignatures {#getRemoveSignatures--}
```
boolean getRemoveSignatures()
```

true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）。そうでない場合、無効な署名が残る可能性があります。

**Returns:**
ブール値

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

結果が HttpServletResponse として保存されるときの保存オプションを取得または設定します。

**Returns:**
SaveOptions オブジェクト

### getUniqueSuffix {#getUniqueSuffix--}
```
String getUniqueSuffix()
```

フォームを連結するときにフィールド名を一意にするために追加されるサフィックスの形式を取得します。

**Returns:**
string 値

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
別のファイルからページを挿入して、入力 PDF ファイルに追加します。

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
別のファイルからページを挿入して、入力 PDF ファイルに追加します。

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
別のファイルからページを挿入して、入力 PDF ファイルに追加します。

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
別のファイルからページを指定位置に挿入して、PDF ファイルに追加します。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
InputStream から outputStream へブックレットを作成します。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
firstInputStream から outputStream へカスタマイズされたブックレットを作成します。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
入力ストリームからブックレットを作成し、結果を出力ストリームに保存します。

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
firstInputStream から outputStream へブックレットを作成します。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
入力ファイルから出力ファイルへブックレットを作成します。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
firstInputFile から outputFile へカスタマイズされたブックレットを作成します。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
inputFile から outputFile へブックレットを作成します。

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
firstInputFile から outputFile へカスタマイズされたブックレットを作成します。

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
複数の入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
2 つの入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
入力ストリームから N-Up ドキュメントを作成し、結果を出力ストリームに保存します。

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
最初の入力ストリームから output stream へ N-Up ドキュメントを作成します。

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
複数の入力 PDF ファイルから outputFile へ N-Up ドキュメントを作成します。

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
firstInputFile から outputFile へ N-Up ドキュメントを作成します。

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
入力ファイルから outputFile へ N-Up ドキュメントを作成します。

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
2 つの入力 PDF ファイルから outputFile へ N-Up ドキュメントを作成します。

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
ドキュメントページの内容のサイズを変更します。

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
ドキュメントページの内容のサイズを変更します。

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
ドキュメントページの内容のサイズを変更します。

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
ドキュメントページの内容のサイズを変更します。

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
void setAllowConcatenateExceptions(boolean value)
```

true に設定すると、エラーが発生した場合に例外がスローされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setAttachmentName {#setAttachmentName-java.lang.String-}
操作の結果が HttpServletResponse オブジェクトに添付ファイルとして保存されるときの添付ファイル名を設定します。

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
void setCloseConcatenatedStreams(boolean value)
```

true に設定すると、操作後にストリームが閉じられます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
操作の結果が HttpServletResponse オブジェクトに格納される際のコンテンツの保存方法を設定します。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF ファイル形式を設定します。

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
void setCorruptedFileAction(int value)
```

このプロパティは、連結処理中に破損したファイルに遭遇したときの動作を定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ConcatenateCorruptedFileAction 要素 |

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
void setIncrementalUpdates(boolean value)
```

true の場合、連結中に増分更新が行われます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
void setKeepFieldsUnique(boolean value)
```

true の場合、フォームを連結するときにフィールド名が一意になるように作成されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
void setMergeDuplicateLayers(boolean value)
```

このプロパティが true の場合、同名の連結ドキュメントのオプションコンテンツが結果ドキュメントの1つのレイヤーにマージされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
void setMergeDuplicateOutlines(boolean value)
```

true の場合、重複したアウトラインがマージされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
ソース入力 PDF ファイルが暗号化されている場合、所有者のパスワードを設定します。

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
void setPreserveUserRights(boolean value)
```

true の場合、最初のドキュメントのユーザー権限が連結ドキュメントに適用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
void setRemoveSignatures(boolean value)
```

true の場合、すべての署名がフィールドから削除されます（フィールドは残ります）。そうでない場合、無効な署名が残る可能性があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
結果が HttpServletResponse として格納される際の保存オプションを設定します。

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
フォームが連結されるときにフィールド名が一意になるように付加されるサフィックスの形式を設定します。

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
開始位置から指定された場所まで分割し、前半部分を出力ストリームに保存します。

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
PDF ファイルを最初のページから指定された場所まで分割し、前半部分を新しいファイルとして保存します。

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
PDF ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにできます。

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
PDF ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにできます。

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
指定された位置から分割し、後半部分を新しいファイルストリームとして保存します。

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
位置から分割し、後半部分を新しいファイルとして保存します。

### splitToPages {#splitToPages-java.io.InputStream-}
PDF ファイルを単一ページのドキュメントに分割します。

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。

### splitToPages {#splitToPages-java.lang.String-}
PDFファイルを単一ページのドキュメントに分割します。

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。
