---
title: "PdfFileEditor.TrySplitFromFirst"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor method. 最初のページから指定された場所まで Pdf ファイルを分割し、前半部分を新しいファイルとして保存します"
type: docs
weight: 460
url: /ja/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Pdf ファイルを最初のページから指定された位置まで分割し、前半部分を新しいファイルとして保存します。

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | ソース Pdf ファイル。 |
| location | Int32 | 分割点。 |
| outputFile | String | 出力 Pdf ファイル。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

TrySplitFromFirst メソッドは SplitFromFirst メソッドと同様ですが、操作が失敗した場合に TrySplitFromFirst メソッドは例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

開始位置から指定された位置まで分割し、前半部分を出力ストリームに保存します。

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソース Pdf ファイル ストリーム。 |
| location | Int32 | 分割点。 |
| outputStream | Stream | 出力ファイルストリーム。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

この操作の後、ストリームは閉じられません。TrySplitFromFirst メソッドは SplitFromFirst メソッドと同様ですが、操作が失敗した場合に TrySplitFromFirst メソッドは例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


