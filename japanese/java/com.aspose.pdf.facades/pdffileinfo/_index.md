---
title: "PdfFileInfo"
linktitle: "PdfFileInfo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントのメタ情報にアクセスするクラスを表します。"
type: docs
weight: 490
url: /ja/java/com.aspose.pdf.facades/pdffileinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileInfo

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileInfo extends SaveableFacade
```

PDF ドキュメントのメタ情報にアクセスするクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfFileInfo](#PdfFileInfo--) | com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [PdfFileInfo](#PdfFileInfo-com.aspose.pdf.IDocument-) | com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-) | com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-) | com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-) | com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-) | com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。 |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | ファサードを初期化します。 |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | ファサードを初期化します。 |
| [clearInfo](#clearInfo--) | PDF ドキュメントのすべてのメタ情報をクリアします。 |
| [close](#close--) | このドキュメントで使用されているすべてのリソースを閉じます。 |
| [dispose](#dispose--) | このインスタンスが使用するすべてのリソースを閉じます。このメソッドは廃止予定です。代わりに close() を使用してください。 |
| [getAuthor](#getAuthor--) | PDF ドキュメントの Author 情報を取得します。 |
| [getCreationDate](#getCreationDate--) | PDF ドキュメントの CreationDate 情報を取得します。 |
| [getCreator](#getCreator--) | PDF ドキュメントの Creator 情報を取得します。 |
| [getDocumentPrivilege](#getDocumentPrivilege--) | PDF ドキュメントの特権設定を取得します。 |
| [getHeader](#getHeader--) | <p> PDF ドキュメントのカスタマイズされた情報を取得します。 </p> |
| [getInputFile](#getInputFile--) | 入力ファイルを取得します。 |
| [getInputStream](#getInputStream--) | 入力ストリームを取得します。 |
| [getKeywords](#getKeywords--) | PDFドキュメントのキーワード情報を取得します。 |
| [getMetaInfo](#getMetaInfo-java.lang.String-) | PDFドキュメントのプロパティ名でカスタマイズされた情報を取得します。該当するプロパティがない場合は空文字列を返します。 |
| [getModDate](#getModDate--) | PDFドキュメントのModDate日付情報を取得します。 |
| [getNumberOfPages](#getNumberOfPages--) | ドキュメントページ数を取得します。 |
| [getPageHeight](#getPageHeight-int-) | 指定されたページの高さを取得します。 |
| [getPageRotation](#getPageRotation-int-) | 指定されたページの回転角度を取得します。 |
| [getPageWidth](#getPageWidth-int-) | 指定されたページの幅を取得します。 |
| [getPageXOffset](#getPageXOffset-int-) | 指定されたページ表示領域の水平オフセットを取得します。 |
| [getPageYOffset](#getPageYOffset-int-) | 指定されたページ表示領域の垂直オフセットを取得します。 |
| [getPasswordType](#getPasswordType--) | PdfFileInfoインスタンス作成時に渡されたパスワードの種類を返します。可能な値は{@code PasswordType}をご参照ください。PDFドキュメントはユーザ（またはオープン）パスワードと所有者（または権限、編集）パスワードの両方で開くことができる点に注意してください。 |
| [getPdfVersion](#getPdfVersion--) | PDFドキュメントのバージョン情報を取得します。 |
| [getProducer](#getProducer--) | PDFドキュメントのProducer情報を取得します。 |
| [getSubject](#getSubject--) | PDFドキュメントのSubject情報を取得します。 |
| [getTitle](#getTitle--) | PDFドキュメントのTitle情報を取得します。 |
| [getUseStrictValidation](#getUseStrictValidation--) | {@code IsPdfFile}({@link #isPdfFile})プロパティを使用して厳格な検証ルールを適用します。 |
| [hasCollection](#hasCollection--) | 現在の入力ファイルがPDFファイルのコレクションを含む「Portfolio」ファイルである場合にtrueを返します。 |
| [hasEditPassword](#hasEditPassword--) | 権限またはドキュメントのセキュリティプロパティを変更するためにパスワードが必要な場合にtrueを返します。なお、このプロパティは{@code PdfFileInfo}コンストラクタで有効なパスワードが提供された場合にのみ読み取れます。PasswordTypeがInaccessible（無効なパスワードが提供されたことを意味する）場合、このプロパティの読み取りは{@code InvalidPasswordException}で失敗します。 |
| [hasOpenPassword](#hasOpenPassword--) | パスワードで保護されたPDFドキュメントを開くためにパスワードが必要な場合にtrueを返します。 |
| [isEncrypted](#isEncrypted--) | PDFドキュメントが暗号化されているかどうかをチェックします。 |
| [isPdfFile](#isPdfFile--) | ソース入力が有効なPDFファイルかどうかをチェックします。 |
| [save](#save-java.io.OutputStream-) | PDFドキュメントを指定されたファイルに保存します。 |
| [saveNewInfo](#saveNewInfo-java.io.OutputStream-) | 更新されたPDFドキュメントを指定されたストリームに保存します。 |
| [saveNewInfo](#saveNewInfo-java.lang.String-) | 更新されたPDFドキュメントを指定されたファイルに保存します。 |
| [saveNewInfoWithXmp](#saveNewInfoWithXmp-java.lang.String-) | ファイル情報を設定して明示的に指定されたプロパティを変更し、他のプロパティはそのまま残します。 |
| [setAuthor](#setAuthor-java.lang.String-) | PDFドキュメントのAuthor情報を設定します。 |
| [setCreationDate](#setCreationDate-java.lang.String-) | PDF ドキュメントの CreationDate 情報を設定します。 |
| [setCreator](#setCreator-java.lang.String-) | PDF ドキュメントの Creator 情報を設定します。 |
| [setHeader](#setHeader-java.util.Map-) | PDF ドキュメントのカスタマイズ情報を設定します。 |
| [setInputFile](#setInputFile-java.lang.String-) | 入力ファイルを設定します。 |
| [setInputStream](#setInputStream-java.io.InputStream-) | 入力ストリームを設定します。 |
| [setKeywords](#setKeywords-java.lang.String-) | PDF ドキュメントの Keywords 情報を設定します。 |
| [setMetaInfo](#setMetaInfo-java.lang.String-java.lang.String-) | PDF ドキュメントのカスタマイズ情報を設定します。 |
| [setModDate](#setModDate-java.lang.String-) | PDF ドキュメントの ModDate 日付情報を設定します。 |
| [setSubject](#setSubject-java.lang.String-) | PDF ドキュメントの Subject 情報を設定します。 |
| [setTitle](#setTitle-java.lang.String-) | PDF ドキュメントの Title 情報を設定します。 |
| [setUseStrictValidation](#setUseStrictValidation-boolean-) | {@code IsPdfFile}({@link #isPdfFile})プロパティを使用して厳格な検証ルールを適用します。 |

### PdfFileInfo {#PdfFileInfo--}
```
public PdfFileInfo()
```

com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。

### PdfFileInfo {#PdfFileInfo-com.aspose.pdf.IDocument-}
com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-}
com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-}
com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。

### PdfFileInfo {#PdfFileInfo-java.lang.String-}
com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-}
com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
com.aspose.pdf.facades.PdfFileInfo クラスの新しいインスタンスをデフォルト値で初期化します。

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
ファサードを初期化します。

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
ファサードを初期化します。

### clearInfo {#clearInfo--}
```
public void clearInfo()
```

PDF ドキュメントのすべてのメタ情報をクリアします。

### close {#close--}
```
public void close()
```

このドキュメントで使用されているすべてのリソースを閉じます。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

このインスタンスが使用するすべてのリソースを閉じます。このメソッドは廃止予定です。代わりに close() を使用してください。

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

PDF ドキュメントの Author 情報を取得します。

**Returns:**
文字列値

### getCreationDate {#getCreationDate--}
```
public String getCreationDate()
```

PDF ドキュメントの CreationDate 情報を取得します。

**Returns:**
文字列値

### getCreator {#getCreator--}
```
public String getCreator()
```

PDF ドキュメントの Creator 情報を取得します。

**Returns:**
文字列値

### getDocumentPrivilege {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```

PDF ドキュメントの特権設定を取得します。

**Returns:**
PDF ドキュメントの権限設定。

### getHeader {#getHeader--}
```
public Map < String , String > getHeader()
```

<p> PDF ドキュメントのカスタマイズされた情報を取得します。 </p>

**Returns:**
{@code Map<String, String>} オブジェクト

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

入力ファイルを取得します。

**Returns:**
文字列値

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

入力ストリームを取得します。

**Returns:**
InputStream オブジェクト

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

PDFドキュメントのキーワード情報を取得します。

**Returns:**
文字列値

### getMetaInfo {#getMetaInfo-java.lang.String-}
PDFドキュメントのプロパティ名でカスタマイズされた情報を取得します。該当するプロパティがない場合は空文字列を返します。

### getModDate {#getModDate--}
```
public String getModDate()
```

PDFドキュメントのModDate日付情報を取得します。

**Returns:**
文字列値

### getNumberOfPages {#getNumberOfPages--}
```
public int getNumberOfPages()
```

ドキュメントページ数を取得します。

**Returns:**
int 値です。

### getPageHeight {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```

指定されたページの高さを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNum |  | ページ番号。 |

**Returns:**
ページの高さ。

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```

指定されたページの回転角度を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNum |  | ページ番号。 |

**Returns:**
ページの回転です。値は 0、90、180、270 のいずれかです。

### getPageWidth {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```

指定されたページの幅を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNum |  | ページ番号。 |

**Returns:**
ページの幅。

### getPageXOffset {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```

指定されたページ表示領域の水平オフセットを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNum |  | ページ番号。 |

**Returns:**
ページ左側からの水平オフセット。

### getPageYOffset {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```

指定されたページ表示領域の垂直オフセットを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNum |  | ページ番号。 |

**Returns:**
ページ表示領域の垂直オフセット。

### getPasswordType {#getPasswordType--}
```
public PasswordType getPasswordType()
```

PdfFileInfoインスタンス作成時に渡されたパスワードの種類を返します。可能な値は{@code PasswordType}をご参照ください。PDFドキュメントはユーザ（またはオープン）パスワードと所有者（または権限、編集）パスワードの両方で開くことができる点に注意してください。

**Returns:**
PasswordType 要素 @see PasswordType

### getPdfVersion {#getPdfVersion--}
```
public String getPdfVersion()
```

PDFドキュメントのバージョン情報を取得します。

**Returns:**
バージョン文字列。

### getProducer {#getProducer--}
```
public String getProducer()
```

PDFドキュメントのProducer情報を取得します。

**Returns:**
文字列値

### getSubject {#getSubject--}
```
public String getSubject()
```

PDFドキュメントのSubject情報を取得します。

**Returns:**
文字列値

### getTitle {#getTitle--}
```
public String getTitle()
```

PDFドキュメントのTitle情報を取得します。

**Returns:**
文字列値

### getUseStrictValidation {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```

{@code IsPdfFile}({@link #isPdfFile})プロパティを使用して厳格な検証ルールを適用します。

**Returns:**
ブール値

### hasCollection {#hasCollection--}
```
public boolean hasCollection()
```

現在の入力ファイルがPDFファイルのコレクションを含む「Portfolio」ファイルである場合にtrueを返します。

**Returns:**
ブール値

### hasEditPassword {#hasEditPassword--}
```
public boolean hasEditPassword()
```

権限またはドキュメントのセキュリティプロパティを変更するためにパスワードが必要な場合にtrueを返します。なお、このプロパティは{@code PdfFileInfo}コンストラクタで有効なパスワードが提供された場合にのみ読み取れます。PasswordTypeがInaccessible（無効なパスワードが提供されたことを意味する）場合、このプロパティの読み取りは{@code InvalidPasswordException}で失敗します。

**Returns:**
ブール値

### hasOpenPassword {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```

パスワードで保護されたPDFドキュメントを開くためにパスワードが必要な場合にtrueを返します。

**Returns:**
ブール値

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

PDFドキュメントが暗号化されているかどうかをチェックします。

**Returns:**
ブール値

### isPdfFile {#isPdfFile--}
```
public boolean isPdfFile()
```

ソース入力が有効なPDFファイルかどうかをチェックします。

**Returns:**
ブール値

### save {#save-java.io.OutputStream-}
PDFドキュメントを指定されたファイルに保存します。

### saveNewInfo {#saveNewInfo-java.io.OutputStream-}
更新されたPDFドキュメントを指定されたストリームに保存します。

### saveNewInfo {#saveNewInfo-java.lang.String-}
更新されたPDFドキュメントを指定されたファイルに保存します。

### saveNewInfoWithXmp {#saveNewInfoWithXmp-java.lang.String-}
ファイル情報を設定して明示的に指定されたプロパティを変更し、他のプロパティはそのまま残します。

### setAuthor {#setAuthor-java.lang.String-}
PDFドキュメントのAuthor情報を設定します。

### setCreationDate {#setCreationDate-java.lang.String-}
PDF ドキュメントの CreationDate 情報を設定します。

### setCreator {#setCreator-java.lang.String-}
PDF ドキュメントの Creator 情報を設定します。

### setHeader {#setHeader-java.util.Map-}
PDF ドキュメントのカスタマイズ情報を設定します。

### setInputFile {#setInputFile-java.lang.String-}
入力ファイルを設定します。

### setInputStream {#setInputStream-java.io.InputStream-}
入力ストリームを設定します。

### setKeywords {#setKeywords-java.lang.String-}
PDF ドキュメントの Keywords 情報を設定します。

### setMetaInfo {#setMetaInfo-java.lang.String-java.lang.String-}
PDF ドキュメントのカスタマイズ情報を設定します。

### setModDate {#setModDate-java.lang.String-}
PDF ドキュメントの ModDate 日付情報を設定します。

### setSubject {#setSubject-java.lang.String-}
PDF ドキュメントの Subject 情報を設定します。

### setTitle {#setTitle-java.lang.String-}
PDF ドキュメントの Title 情報を設定します。

### setUseStrictValidation {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```

{@code IsPdfFile}({@link #isPdfFile})プロパティを使用して厳格な検証ルールを適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
