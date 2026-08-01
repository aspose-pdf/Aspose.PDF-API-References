---
title: "PdfContentEditor.ChangeViewerPreference"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。ビューの設定を変更します。"
type: docs
weight: 90
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference method

ビュー設定を変更します。

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| viewerAttribution | Int32 | ViewerPreference クラスで定義されたビュー属性。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


