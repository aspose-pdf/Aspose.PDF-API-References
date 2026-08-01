---
title: "PdfContentEditor.GetViewerPreference"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。表示設定を返します。"
type: docs
weight: 390
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## PdfContentEditor.GetViewerPreference method

表示設定を返します。

```csharp
public int GetViewerPreference()
```

### 戻り値

ViewerPrefernece フラグのセットを返します。

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


