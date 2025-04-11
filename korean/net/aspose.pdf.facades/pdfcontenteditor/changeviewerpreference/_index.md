---
title: PdfContentEditor.ChangeViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 보기 기본 설정을 변경합니다.
type: docs
weight: 90
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference 메서드

보기 기본 설정을 변경합니다.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| viewerAttribution | Int32 | ViewerPreference 클래스에서 정의된 보기 기본 설정입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)