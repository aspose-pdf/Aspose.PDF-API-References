---
title: "클래스 PdfAnnotationEditor"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.PdfAnnotationEditor 클래스. PDF 문서 주석 및 댓글 작업을 위한 클래스를 나타냅니다."
type: docs
weight: 4530
url: /ko/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

PDF 문서 주석(댓글) 작업을 위한 클래스를 나타냅니다.

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | `PdfAnnotationEditor` 새 객체를 초기화합니다. |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | `PdfAnnotationEditor` 새 객체를 *document*를 기반으로 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 Document 파사드를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Facade를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Facade를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Facade를 초기화합니다. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Facade와 연결된 Aspose.Pdf.Document를 해제합니다. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | 지정된 주석 이름을 가진 주석을 삭제합니다. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | 문서의 모든 주석을 삭제합니다. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | 문서에서 지정된 유형의 모든 주석을 삭제합니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Facade를 해제합니다. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | 주석을 스트림으로 내보냅니다. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | 지정된 주석 유형의 내용을 XFDF로 내보냅니다. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | 지정된 주석 유형의 내용을 XFDF로 내보냅니다. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | 지정된 유형의 주석 목록을 가져옵니다. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | 지정된 유형의 주석 목록을 가져옵니다. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | 문서의 모든 주석을 평탄화합니다. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | 문서의 모든 주석을 평탄화합니다. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | 지정된 유형의 주석을 평탄화합니다. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | XFDF 데이터 스트림에서 지정된 주석을 가져옵니다. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | XFDF 파일에서 지정된 주석을 가져옵니다. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | 다른 PDF 문서 스트림 배열에서 문서로 주석을 가져옵니다. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | 다른 PDF 문서 배열에서 문서로 주석을 가져옵니다. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | 다른 PDF 문서 스트림 배열에서 지정된 주석을 문서로 가져옵니다. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | 다른 PDF 문서 배열에서 지정된 주석을 문서로 가져옵니다. |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | FDF 파일에서 모든 주석을 가져옵니다. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | XFDF 데이터 스트림에서 모든 주석을 가져옵니다. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | XFDF 파일에서 모든 주석을 가져옵니다. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | 지정된 페이지 범위에서 지정된 유형의 주석을 수정합니다. 다음 주석 속성을 수정할 수 있습니다: Modified, Title, Contents, Color, Subject 및 Open. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | 지정된 페이지 범위에서 주석의 작성자를 수정합니다. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | 지정된 페이지에서 영역을 가립니다. 모든 내용이 제거됩니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF 문서를 지정된 파일에 저장합니다. |

### 또 보기

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


