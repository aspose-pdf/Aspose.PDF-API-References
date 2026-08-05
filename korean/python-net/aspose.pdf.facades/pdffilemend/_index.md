---
title: "PdfFileMend"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "기존 PDF 문서 페이지에 텍스트와 이미지를 추가하는 클래스를 나타냅니다."
type: docs
weight: 280
url: /ko/python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

기존 PDF 문서 페이지에 텍스트와 이미지를 추가하는 클래스를 나타냅니다.

PdfFileMend 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfFileMend() | 생성자. |
| PdfFileMend(input_file_name, output_file_name) | PdfFileMend 클래스의 새 인스턴스를 초기화합니다. |
| PdfFileMend(input_stream, output_stream) | PdfFileMend 클래스의 새 인스턴스를 초기화합니다. |
| PdfFileMend(document) | PdfFileMend 클래스의 새 인스턴스를 초기화합니다. |
| PdfFileMend(document, output_file_name) | PdfFileMend 클래스의 새 인스턴스를 초기화합니다. |
| PdfFileMend(document, dest_stream) | PdfFileMend 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
| input_stream | 입력 스트림을 설정합니다. |
| output_stream | 출력 스트림을 설정합니다. |
| input_file | 입력 파일을 설정합니다. |
| output_file | 출력 파일을 설정합니다. |
| wrap_mode | 단어 줄바꿈 알고리즘을 설정하거나 가져옵니다. WordWrapMode 및 IsWordWrap를 참조하십시오. |
| text_positioning_mode | 텍스트 위치 지정 전략을 설정하거나 가져옵니다. [PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            기본 모드는 Legacy입니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(src_file) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_stream) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_doc) | PDF 문서를 편집용으로 바인딩합니다. |
| save(dest_file) | PDF 문서를 지정된 파일에 저장합니다. |
| save(dest_stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 지정된 좌표에 PDF 문서의 지정된 페이지에 이미지를 추가합니다. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | 지정된 좌표에 PDF 문서의 지정된 페이지에 이미지를 추가합니다. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 지정된 좌표에 PDF 문서의 지정된 페이지들에 이미지를 추가합니다. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | 지정된 좌표에 PDF 문서의 지정된 페이지들에 이미지를 추가합니다. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 지정된 좌표에 PDF 문서의 지정된 페이지에 이미지를 추가합니다. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | 지정된 좌표에 PDF 문서의 지정된 페이지에 이미지를 추가합니다. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 지정된 좌표에 PDF 문서의 지정된 페이지들에 이미지를 추가합니다. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | 지정된 좌표에 PDF 문서의 지정된 페이지들에 이미지를 추가합니다. |
| add_text(text, page_num, lower_left_x, lower_left_y) | 구현되지 않음. |
| add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 구현되지 않음. |
| add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | 구현되지 않음. |
| close() | PdfFileMend 객체를 닫습니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

