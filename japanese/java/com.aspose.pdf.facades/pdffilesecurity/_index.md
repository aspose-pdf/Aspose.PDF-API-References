---
title: "PdfFileSecurity"
linktitle: "PdfFileSecurity"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "所有者またはユーザーパスワードで PDF ファイルを暗号化または復号し、セキュリティ設定やパスワードを変更する機能を表します。"
type: docs
weight: 520
url: /ja/java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSecurity

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSecurity extends SaveableFacade implements com.aspose.ms.System.IDisposable
```

所有者またはユーザーパスワードで PDF ファイルを暗号化または復号し、セキュリティ設定やパスワードを変更する機能を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfFileSecurity](#PdfFileSecurity--) | PdfFileSecurity オブジェクトを初期化します。 |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-) | PdfFileSecurity オブジェクトを初期化します。 |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | PdfFileSecurity オブジェクトを初期化します。 |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | PdfFileSecurity オブジェクトを初期化します。 |
| [PdfFileSecurity](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | PdfFileSecurity オブジェクトを初期化します。 |
| [PdfFileSecurity](#PdfFileSecurity-java.lang.String-java.lang.String-) | PdfFileSecurity オブジェクトを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | ファサードを初期化します。 |
| [bindPdf](#bindPdf-java.lang.String-) | ファサードを初期化します。 |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | 所有者パスワードでユーザーパスワードと所有者パスワードを変更し、元のセキュリティ設定を保持します。新しいユーザーパスワードと新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダムな文字列に置き換えられます。処理に失敗した場合は例外がスローされます。string inFile = "D:\\\\input.pdf"; //TestPath は再割り当てされる可能性があります。 string outFile = "D:\\\\output.pdf"; //TestPath は再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner"); |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> 所有者パスワードでユーザーパスワードと所有者パスワードを変更し、PDF ドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードと新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダムな文字列に置き換えられます。 <p> 処理に失敗した場合は例外がスローされます。 </p> <hr> <pre> string inFile = "input.pdf"; // TestPath は再割り当てされる可能性があります。 string outFile = "output.pdf"; // TestPath は再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> 所有者パスワードでユーザーパスワードと所有者パスワードを変更し、PDF ドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードと新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダムな文字列に置き換えられます。KeySize と Algorithm の組み合わせは 6 通り可能です。ただし (KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効で、キットがこの組み合わせに遭遇した場合は対応する例外が発生します。処理に失敗した場合は例外がスローされます。 </p> <hr> <pre> string inFile = "input.pdf"; // TestPath は再割り当てされる可能性があります。 string outFile = "output.pdf"; // TestPath は再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [close](#close--) | ファサードを閉じます。 |
| [decryptFile](#decryptFile-java.lang.String-) | 所有者パスワードで暗号化された PDF ドキュメントを復号化します。ドキュメントに所有者パスワードがない場合はユーザーパスワードを使用できます。処理に失敗した場合は例外がスローされます。string inFile = "input.pdf"; //TestPath は再割り当てされる可能性があります。 string outFile = "output.pdf"; //TestPath は再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass"); |
| [dispose](#dispose--) | ファサードを閉じます。 |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> ユーザーパスワードと所有者パスワードで PDF ファイルを暗号化し、ドキュメントのアクセス権限を設定します。ユーザーパスワードと所有者パスワードは null または空にできます。入力された所有者パスワードが null または空の場合、所有者パスワードはランダムな文字列に置き換えられます。処理に失敗した場合は例外がスローされます。 </p> <hr> <pre> String inFile = "input.pdf"; // TestPath は再割り当てされる可能性があります。 String outFile = "output.pdf"; // TestPath は再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> ユーザーパスワードと所有者パスワードで PDF ファイルを暗号化し、ドキュメントのアクセス権限を設定します。ユーザーパスワードと所有者パスワードは null または空にできます。入力された所有者パスワードが null または空の場合、所有者パスワードはランダムな文字列に置き換えられます。KeySize と Algorithm の組み合わせは 6 通り可能です。ただし (KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効で、キットがこの組み合わせに遭遇した場合は対応する例外が発生します。処理に失敗した場合は例外がスローされます。 </p> <hr> <pre> String inFile = "input.pdf"; // TestPath は再割り当てされる可能性があります。 String outFile = "output.pdf"; // TestPath は再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [getAllowExceptions](#getAllowExceptions--) | この値が true に設定されている場合、操作が失敗すると例外がスローされます。false に設定されている場合、失敗時にメソッドは false を返し、最後の例外は LastException プロパティで確認できます。 |
| [getLastException](#getLastException--) | 最後の操作でスローされた例外を返します。 |
| [setAllowExceptions](#setAllowExceptions-boolean-) | この値が true に設定されている場合、操作が失敗すると例外がスローされます。false に設定されている場合、失敗時にメソッドは false を返し、最後の例外は LastException プロパティで確認できます。 |
| [setInputFile](#setInputFile-java.lang.String-) | 入力ファイルを設定します。Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setInputStream](#setInputStream-java.io.InputStream-) | 入力ストリームを設定します。Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setOutputFile](#setOutputFile-java.lang.String-) | 出力ファイルを設定します。Obsolete("Use save(outputStream) method for getting facade results.") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | 出力ストリームを設定します。Obsolete("Use save(outputStream) method for getting facade results.") |
| [setPrivilege](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | <p> ユーザー/オーナーパスワードが空の状態で PDF ファイルのセキュリティを設定します。オーナーパスワードはランダム文字列で追加されます。処理が失敗した場合は例外がスローされます。 </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre> |
| [setPrivilege](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | <p> 元のパスワードで PDF ファイルのセキュリティを設定します。処理が失敗した場合は例外がスローされます。 </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre> |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | 所有者パスワードでユーザーパスワードと所有者パスワードを変更し、元のセキュリティ設定を保持します。新しいユーザーパスワードと新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダム文字列に置き換えられます。処理が失敗しても例外はスローされません。 string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner"); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | 所有者パスワードでユーザーパスワードとパスワードを変更し、PDF ドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードと新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダム文字列に置き換えられます。処理が失敗しても例外はスローされません。 string inFile = ".D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | 所有者パスワードでユーザーパスワードとパスワードを変更し、PDF ドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードと新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダム文字列に置き換えられます。KeySize と Algorithm の組み合わせは 6 通り可能です。ただし (KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効で、キットがこの組み合わせに遭遇した場合は対応する例外が発生します。処理が失敗しても例外はスローされません。 string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES); |
| [tryDecryptFile](#tryDecryptFile-java.lang.String-) | 所有者パスワードで暗号化された PDF ドキュメントを復号化します。ドキュメントに所有者パスワードがない場合は、ユーザーパスワードを使用できます。処理が失敗しても例外はスローされません。 string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass"); |
| [tryEncryptFile](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | ユーザーパスワードと所有者パスワードで PDF ファイルを暗号化し、ドキュメントのアクセス権限を設定します。ユーザーパスワードと所有者パスワードは null または空にできます。入力された所有者パスワードが null または空の場合、所有者パスワードはランダム文字列に置き換えられます。処理が失敗しても例外はスローされません。 string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); |
| [trySetPrivilege](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | 元のパスワードで PDF ファイルのセキュリティを設定します。処理が失敗しても例外はスローされません。 string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print); |

### PdfFileSecurity {#PdfFileSecurity--}
```
public PdfFileSecurity()
```

PdfFileSecurity オブジェクトを初期化します。

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-}
PdfFileSecurity オブジェクトを初期化します。

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
PdfFileSecurity オブジェクトを初期化します。

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
PdfFileSecurity オブジェクトを初期化します。

### PdfFileSecurity {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
PdfFileSecurity オブジェクトを初期化します。

### PdfFileSecurity {#PdfFileSecurity-java.lang.String-java.lang.String-}
PdfFileSecurity オブジェクトを初期化します。

### bindPdf {#bindPdf-java.io.InputStream-}
ファサードを初期化します。

### bindPdf {#bindPdf-java.lang.String-}
ファサードを初期化します。

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
所有者パスワードでユーザーパスワードと所有者パスワードを変更し、元のセキュリティ設定を保持します。新しいユーザーパスワードと新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダム文字列に置き換えられます。処理が失敗した場合は例外がスローされます。 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner");

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> 所有者パスワードでユーザーパスワードと所有者パスワードを変更し、PDF ドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードと新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダムな文字列に置き換えられます。 <p> 処理に失敗した場合は例外がスローされます。 </p> <hr> <pre> string inFile = "input.pdf"; // TestPath は再割り当てされる可能性があります。 string outFile = "output.pdf"; // TestPath は再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre>

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> 所有者パスワードでユーザーパスワードと所有者パスワードを変更し、PDF ドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードと新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダムな文字列に置き換えられます。KeySize と Algorithm の組み合わせは 6 通り可能です。ただし (KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効で、キットがこの組み合わせに遭遇した場合は対応する例外が発生します。処理に失敗した場合は例外がスローされます。 </p> <hr> <pre> string inFile = "input.pdf"; // TestPath は再割り当てされる可能性があります。 string outFile = "output.pdf"; // TestPath は再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### close {#close--}
```
public void close()
```

ファサードを閉じます。

### decryptFile {#decryptFile-java.lang.String-}
所有者パスワードで暗号化された PDF ドキュメントを復号化します。ドキュメントに所有者パスワードがない場合はユーザーパスワードを使用できます。処理に失敗した場合は例外がスローされます。string inFile = "input.pdf"; //TestPath は再割り当てされる可能性があります。 string outFile = "output.pdf"; //TestPath は再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass");

### dispose {#dispose--}
```
public void dispose()
```

ファサードを閉じます。

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> ユーザーパスワードと所有者パスワードで PDF ファイルを暗号化し、ドキュメントのアクセス権限を設定します。ユーザーパスワードと所有者パスワードは null または空にできます。入力された所有者パスワードが null または空の場合、所有者パスワードはランダムな文字列に置き換えられます。処理に失敗した場合は例外がスローされます。 </p> <hr> <pre> String inFile = "input.pdf"; // TestPath は再割り当てされる可能性があります。 String outFile = "output.pdf"; // TestPath は再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre>

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> ユーザーパスワードと所有者パスワードで PDF ファイルを暗号化し、ドキュメントのアクセス権限を設定します。ユーザーパスワードと所有者パスワードは null または空にできます。入力された所有者パスワードが null または空の場合、所有者パスワードはランダムな文字列に置き換えられます。KeySize と Algorithm の組み合わせは 6 通り可能です。ただし (KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効で、キットがこの組み合わせに遭遇した場合は対応する例外が発生します。処理に失敗した場合は例外がスローされます。 </p> <hr> <pre> String inFile = "input.pdf"; // TestPath は再割り当てされる可能性があります。 String outFile = "output.pdf"; // TestPath は再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### getAllowExceptions {#getAllowExceptions--}
```
@Deprecated public final boolean getAllowExceptions()
```

この値が true に設定されている場合、操作が失敗すると例外がスローされます。false に設定されている場合、失敗時にメソッドは false を返し、最後の例外は LastException プロパティで確認できます。

**Returns:**
boolean 値 @deprecated このプロパティは非推奨であり、例外をスローするために使用できません。

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

最後の操作でスローされた例外を返します。

**Returns:**
java.lang.RuntimeException

### setAllowExceptions {#setAllowExceptions-boolean-}
```
@Deprecated public final void setAllowExceptions(boolean value)
```

この値が true に設定されている場合、操作が失敗すると例外がスローされます。false に設定されている場合、失敗時にメソッドは false を返し、最後の例外は LastException プロパティで確認できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | boolean 値 @deprecated このプロパティは非推奨であり、例外をスローするために使用できません。 |

### setInputFile {#setInputFile-java.lang.String-}
入力ファイルを設定します。Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setInputStream {#setInputStream-java.io.InputStream-}
入力ストリームを設定します。Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setOutputFile {#setOutputFile-java.lang.String-}
出力ファイルを設定します。Obsolete("Use save(outputStream) method for getting facade results.")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
出力ストリームを設定します。Obsolete("Use save(outputStream) method for getting facade results.")

### setPrivilege {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
<p> ユーザー/オーナーパスワードが空の状態で PDF ファイルのセキュリティを設定します。オーナーパスワードはランダム文字列で追加されます。処理が失敗した場合は例外がスローされます。 </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre>

### setPrivilege {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
<p> 元のパスワードで PDF ファイルのセキュリティを設定します。処理が失敗した場合は例外がスローされます。 </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre>

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
所有者パスワードでユーザーパスワードと所有者パスワードを変更し、元のセキュリティ設定を保持します。新しいユーザーパスワードと新しい所有者パスワードは null または空にすることができます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダム文字列に置き換えられます。処理が失敗しても例外はスローされません。 string inFile = "D:\\input.pdf"; //テストパスは再割り当てされる可能性があります。 string outFile = "D:\\output.pdf"; //テストパスは再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
所有者パスワードでユーザーパスワードとパスワードを変更し、PDFドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードと新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダム文字列に置き換えられます。処理が失敗しても例外はスローされません。 string inFile = ".D:\\input.pdf"; //テストパスは再割り当てされる可能性があります。 string outFile = "D:\\output.pdf"; //テストパスは再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
所有者パスワードでユーザーパスワードとパスワードを変更し、PDFドキュメントのセキュリティをリセットできるようにします。新しいユーザーパスワードと新しい所有者パスワードは null または空にできます。新しい所有者パスワードが null または空の場合、所有者パスワードはランダム文字列に置き換えられます。KeySize と Algorithm の組み合わせは 6 通り可能ですが、(KeySize.x40, Algorithm.AES) と (KeySize.x256, Algorithm.RC4) は無効であり、キットがこの組み合わせに遭遇した場合は対応する例外が発生します。処理が失敗しても例外はスローされません。 string inFile = "D:\\input.pdf"; //テストパスは再割り当てされる可能性があります。 string outFile = "D:\\output.pdf"; //テストパスは再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

### tryDecryptFile {#tryDecryptFile-java.lang.String-}
所有者パスワードで暗号化された PDF ドキュメントを復号化します。ドキュメントに所有者パスワードがない場合は、ユーザーパスワードを使用できます。処理が失敗しても例外はスローされません。 string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass");

### tryEncryptFile {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
ユーザーパスワードと所有者パスワードで PDF ファイルを暗号化し、ドキュメントのアクセス権限を設定します。ユーザーパスワードと所有者パスワードは null または空にできます。入力された所有者パスワードが null または空の場合、所有者パスワードはランダム文字列に置き換えられます。処理が失敗しても例外はスローされません。 string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);

### trySetPrivilege {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
元のパスワードで PDF ファイルのセキュリティを設定します。処理が失敗しても例外はスローされません。 string inFile = "D:\\input.pdf"; //テストパスは再割り当てされる可能性があります。 string outFile = "D:\\output.pdf"; //テストパスは再割り当てされる可能性があります。 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
