---
title: "PdfAnnotationEditor"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 문서 주석(댓글) 작업을 위한 클래스를 나타냅니다."
type: docs
weight: 170
url: /ko/python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

PDF 문서 주석(댓글) 작업을 위한 클래스를 나타냅니다.

PdfAnnotationEditor 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfAnnotationEditor() | 새로운 [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/) 객체를 초기화합니다. |
| PdfAnnotationEditor(document) | PdfAnnotationEditor 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(src_file) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_stream) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_doc) | PDF 문서를 편집용으로 바인딩합니다. |
| save(dest_file) | PDF 문서를 지정된 파일에 저장합니다. |
| save(dest_stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| import_annotations_from_xfdf(xfdf_file) | XFDF 파일에서 모든 주석을 가져옵니다. |
| import_annotations_from_xfdf(xfdf_stream) | XFDF 데이터 스트림에서 모든 주석을 가져옵니다. |
| import_annotation_from_xfdf(xfdf_file) | XFDF 파일에서 모든 주석을 가져옵니다. |
| import_annotation_from_xfdf(xfdf_file, annot_type) | XFDF 파일에서 지정된 주석을 가져옵니다. |
| import_annotation_from_xfdf(xfdf_stream, annot_type) | XFDF 데이터 스트림에서 지정된 주석을 가져옵니다. |
| import_annotation_from_xfdf(xfdf_stream) | XFDF 데이터 스트림에서 지정된 주석을 가져옵니다. |
| import_annotations(annot_file, annot_type) | 다른 PDF 문서 배열에서 지정된 주석을 문서에 가져옵니다. |
| import_annotations(annot_file) | 다른 PDF 문서 배열에서 지정된 주석을 문서에 가져옵니다. |
| import_annotations(annot_file_stream, annot_type) | 다른 PDF 문서 스트림 배열에서 지정된 주석을 문서에 가져옵니다. |
| import_annotations(annot_file_stream) | 다른 PDF 문서 스트림 배열에서 지정된 주석을 문서에 가져옵니다. |
| flattening_annotations() | 문서의 모든 주석을 평탄화합니다. |
| flattening_annotations(flatten_settings) | 문서의 모든 주석을 평탄화합니다. |
| flattening_annotations(start, end, annot_type) | 지정된 유형의 주석을 평탄화합니다. |
| delete_annotations() | 문서의 모든 주석을 삭제합니다. |
| delete_annotations(annot_type) | 문서에서 지정된 유형의 모든 주석을 삭제합니다. |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | 지정된 주석 유형의 내용을 XFDF로 내보냅니다. |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | 지정된 주석 유형의 내용을 XFDF로 내보냅니다. |
| extract_annotations(start, end, annot_types) | 지정된 유형의 주석 목록을 가져옵니다. |
| extract_annotations(start, end, annot_types) | 지정된 유형의 주석 목록을 가져옵니다. |
| close() | 현재 파사드와 연관된 모든 리소스를 해제합니다. |
| modify_annotations_author(start, end, src_author, des_author) | 지정된 페이지 범위에 있는 주석의 작성자를 수정합니다. |
| delete_annotation(annot_name) | 문서에서 지정된 유형의 모든 주석을 삭제합니다. |
| export_annotations_to_xfdf(xml_output_stream) | 주석을 스트림으로 내보냅니다. |
| modify_annotations(start, end, annotation) | 지정된 페이지 범위에 있는 지정된 유형의 주석을 수정합니다.<br/>            다음 주석 속성을 수정할 수 있습니다: Modified, Title, Contents, Color, Subject 및 Open. |
| redact_area(page_index, rect, color) | 지정된 페이지의 영역을 가립니다. 모든 내용이 제거됩니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

