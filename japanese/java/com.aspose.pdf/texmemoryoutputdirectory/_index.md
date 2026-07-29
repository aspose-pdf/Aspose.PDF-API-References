---
title: "TeXMemoryOutputDirectory"
linktitle: "TeXMemoryOutputDirectory"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "メモリから出力ストリームを取得する機能を実装します。たとえば、付随する出力（ログファイルなど）をディスクに書き込みたくないが、取得したい場合に使用できます。"
type: docs
weight: 4880
url: /ja/java/com.aspose.pdf/texmemoryoutputdirectory/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TeXMemoryOutputDirectory

**All Implemented Interfaces:**
ITeXInputDirectory, ITeXOutputDirectory, Closeable, AutoCloseable

```
public class TeXMemoryOutputDirectory extends Object implements ITeXOutputDirectory
```

メモリから出力ストリームを取得する機能を実装します。たとえば、付随する出力（ログファイルなど）をディスクに書き込まず、後でメモリから読み取りたい場合に使用できます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TeXMemoryOutputDirectory](#TeXMemoryOutputDirectory--) | 新しいインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [close](#close--) | インスタンスを破棄します。 @throws IOException I/O エラーが発生した場合に IOException 例外がスローされる可能性があります |
| [getFile](#getFile-java.lang.String-java.lang.String:A-) | 読み取り用のストリームを返します。サブディレクトリ内のファイルを検索しません。 |
| [getFile](#getFile-java.lang.String-java.lang.String:A-boolean-) | 読み取り用のストリームを返します。 |
| [getOutputFile](#getOutputFile-java.lang.String-java.lang.String:A-) | 書き込み用のストリームを返します。 |

### TeXMemoryOutputDirectory {#TeXMemoryOutputDirectory--}
```
public TeXMemoryOutputDirectory()
```

新しいインスタンスを作成します。

### close {#close--}
```
public void close() throws IOException
```

インスタンスを破棄します。 @throws IOException I/O エラーが発生した場合に IOException 例外がスローされる可能性があります

### getFile {#getFile-java.lang.String-java.lang.String:A-}
読み取り用のストリームを返します。サブディレクトリ内のファイルを検索しません。

### getFile {#getFile-java.lang.String-java.lang.String:A-boolean-}
読み取り用のストリームを返します。

### getOutputFile {#getOutputFile-java.lang.String-java.lang.String:A-}
書き込み用のストリームを返します。
