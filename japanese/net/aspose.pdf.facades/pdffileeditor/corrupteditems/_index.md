---
title: "PdfFileEditor.CorruptedItems"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor プロパティ。結合が実行されたときに発生した問題の配列です。Concatenate 関数に渡された各破損ドキュメントについて、新しい CorruptedItem エントリが作成されます。このプロパティは CorruptedFileAction が ConcatenateIgnoringCorrupted の場合にのみ使用できます。"
type: docs
weight: 90
url: /ja/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems property

結合が実行されたときに発生した問題の配列です。Concatenate() 関数に渡された破損したドキュメントごとに新しい CorruptedItem エントリが作成されます。このプロパティは CorruptedFileAction が ConcatenateIgnoringCorrupted の場合にのみ使用できます。

```csharp
//ドキュメントを結合し、破損したドキュメントに関する情報を表示します。
PdfFileEditor pfe = new PdfFileEditor();
pfe.CorruptedFileAction = PdfFileEditor.ConcatenateCorruptedFileActions.ConcatenateIgnoringCorrupted;
if (pfe.CorruptedItems.Length >0)
{
  foreach(PdfFileEditor.CorruptedItem item in pfe.CorruptedItems)
  {
     Console.WriteLine(item.Index + " reason: " + item.Exception);
  }
}
```

```csharp
public CorruptedItem[] CorruptedItems { get; }
```

### 関連項目

* class [CorruptedItem](../../pdffileeditor.corrupteditem/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


