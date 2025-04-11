---
title: Class AnnotationSelector
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AnnotationSelector 클래스. 이 클래스는 Visitor 템플릿 아이디어를 사용하여 주석을 선택하는 데 사용됩니다.
type: docs
weight: 1450
url: /ko/net/aspose.pdf.annotations/annotationselector/
---
## AnnotationSelector 클래스

이 클래스는 Visitor 템플릿 아이디어를 사용하여 주석을 선택하는 데 사용됩니다.

```csharp
public sealed class AnnotationSelector : IAnnotationVisitor
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [AnnotationSelector](annotationselector/#constructor)() | AnnotationSelector 클래스의 새 인스턴스를 초기화합니다. |
| [AnnotationSelector](annotationselector/#constructor_1)(Annotation) | 새 `AnnotationSelector` 객체를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Selected](../../aspose.pdf.annotations/annotationselector/selected/) { get; } | 선택된 객체의 목록입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit)(BleedMarkAnnotation) | `AnnotationSelector`가 [`BleedMarkAnnotation`](../bleedmarkannotation/) 객체로 초기화된 경우 *bleedMark*를 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_1)(CaretAnnotation) | AnnotationSelector가 CaretAnnotation 객체로 초기화된 경우 커서 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_2)(CircleAnnotation) | AnnotationSelector가 CircleAnnotation 객체로 초기화된 경우 원 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_3)(ColorBarAnnotation) | AnnotationSelector가 ColorBar 객체로 초기화된 경우 ColorBar 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_4)(FileAttachmentAnnotation) | AnnotationSelector가 FileAttachmentAnnotation 객체로 초기화된 경우 첨부 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_5)(FreeTextAnnotation) | AnnotationSelector가 FreeTextAnnotation 객체로 초기화된 경우 자유 텍스트 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_6)(HighlightAnnotation) | AnnotationSelector가 FreeTextAnnotation 객체로 초기화된 경우 첨부 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_7)(InkAnnotation) | AnnotationSelector가 InkAnnotation 객체로 초기화된 경우 잉크 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_8)(LineAnnotation) | AnnotationSelector가 LineAnnotation 객체로 초기화된 경우 선 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_9)(LinkAnnotation) | AnnotationSelector가 LinkAnnotation 객체로 초기화된 경우 링크 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_10)(MovieAnnotation) | AnnotationSelector가 MovieAnnotation 객체로 초기화된 경우 영화 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_11)(PageInformationAnnotation) | `AnnotationSelector`가 [`PageInformationAnnotation`](../pageinformationannotation/) 객체로 초기화된 경우 *pageInformation*을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_12)(PDF3DAnnotation) | AnnotationSelector가 PDF3DAnnotation 객체로 초기화된 경우 PDF3D 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_13)(PolygonAnnotation) | AnnotationSelector가 PolygonAnnotation 객체로 초기화된 경우 다각형 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_14)(PolylineAnnotation) | AnnotationSelector가 PolylineAnnotation 객체로 초기화된 경우 폴리라인 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_15)(PopupAnnotation) | AnnotationSelector가 PopupAnnotation 객체로 초기화된 경우 팝업 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_16)(RedactionAnnotation) | AnnotationSelector가 RedactAnnotation 객체로 초기화된 경우 수정 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_17)(RegistrationMarkAnnotation) | `AnnotationSelector`가 [`RegistrationMarkAnnotation`](../registrationmarkannotation/) 객체로 초기화된 경우 *registrationMark*를 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_18)(RichMediaAnnotation) | AnnotationSelector가 RichMedia 주석 객체로 초기화된 경우 영화 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_19)(ScreenAnnotation) | AnnotationSelector가 ScreenAnnotation 객체로 초기화된 경우 화면 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_20)(SquareAnnotation) | AnnotationSelector가 SquareAnnotation 객체로 초기화된 경우 사각형 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_21)(SquigglyAnnotation) | AnnotationSelector가 SquigglyAnnotation 객체로 초기화된 경우 물결 모양 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_22)(StampAnnotation) | AnnotationSelector가 StampAnnotation 객체로 초기화된 경우 스탬프 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_23)(StrikeOutAnnotation) | AnnotationSelector가 StrikeOutAnnotation 객체로 초기화된 경우 취소선 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_24)(TextAnnotation) | AnnotationSelector가 TextAnnotation 객체로 초기화된 경우 텍스트 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_25)(TrimMarkAnnotation) | `AnnotationSelector`가 [`TrimMarkAnnotation`](../trimmarkannotation/) 객체로 초기화된 경우 *trimMark*를 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_26)(UnderlineAnnotation) | AnnotationSelector가 UnderlineAnnotation 객체로 초기화된 경우 밑줄 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_27)(WatermarkAnnotation) | AnnotationSelector가 WatermarkAnnotation 객체로 초기화된 경우 워터마크 주석을 선택합니다. |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_28)(WidgetAnnotation) | AnnotationSelector가 WidgetAnnotation 객체로 초기화된 경우 위젯 주석을 선택합니다. |

### 참조

* 인터페이스 [IAnnotationVisitor](../iannotationvisitor/)
* 네임스페이스 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* 어셈블리 [Aspose.PDF](../../)