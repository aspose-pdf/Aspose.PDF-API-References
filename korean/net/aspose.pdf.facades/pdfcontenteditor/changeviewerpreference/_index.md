---
title: "PdfContentEditor.ChangeViewerPreference"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. 보기 기본 설정을 변경합니다."
type: docs
weight: 90
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference method

보기 기본 설정을 변경합니다.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| viewerAttribution | Int32 | ViewerPreference 클래스에 정의된 보기 속성. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


