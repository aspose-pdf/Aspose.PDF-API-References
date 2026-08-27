---
title: "PdfFileEditor.AddMargins"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。ページ内容のサイズを変更し、指定された余白を追加します。余白はデフォルトの空間単位で指定されます。"
type: docs
weight: 220
url: /ja/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

ページ内容のサイズを変更し、指定された余白を追加します。余白はデフォルトの空間単位で指定されます。

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| source | Stream | ソース ドキュメントを含むストリーム。 |
| destination | Stream | 結果のドキュメントが保存されるストリーム。 |
| pages | Int32[] | ページインデックスの配列。null の場合、すべてのドキュメントページが処理されます。 |
| leftMargin | Double | 左余白。 |
| rightMargin | Double | 右余白。 |
| topMargin | Double | 上余白。 |
| bottomMargin | Double | 下余白。 |

### 戻り値

操作が成功した場合は true。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //ページ 1, 2, 3 を処理する。
    new int[] { 1, 2, 3}, 
    //左余白は 10 ユニットです。
    10, 
    //右余白は 5 ユニットです。
    5, 
    //上余白は5単位です
    5, 
    //下余白は5単位です
    5);
    dest.Close();
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

ページ内容のサイズを変更し、指定された余白を追加します。余白はデフォルトの空間単位で指定されます。

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| source | String | ソース文書へのパスです。 |
| destination | String | 結果文書が保存されるパスです。 |
| pages | Int32[] | ページインデックスの配列。null の場合、すべてのドキュメントページが処理されます。 |
| leftMargin | Double | 左余白。 |
| rightMargin | Double | 右余白。 |
| topMargin | Double | 上余白。 |
| bottomMargin | Double | 下余白。 |

### 戻り値

リサイズが成功した場合は true です。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //ページ 1, 2, 3 を処理する。
    new int[] { 1, 2, 3}, 
    //左余白は 10 ユニットです。
    10, 
    //右余白は 5 ユニットです。
    5, 
    //上余白は5単位です
    5, 
    //下余白は5単位です
    5);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


