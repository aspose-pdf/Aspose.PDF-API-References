---
title: "PdfFileStamp"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 파일에 스탬프(워터마크 또는 배경)를 추가하는 클래스입니다."
type: docs
weight: 320
url: /ko/python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

PDF 파일에 스탬프(워터마크 또는 배경)를 추가하는 클래스입니다.

PdfFileStamp 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfFileStamp(input_file, output_file) | PdfFileStamp 클래스의 새 인스턴스를 초기화합니다 |
| PdfFileStamp(input_stream, output_stream) | PdfFileStamp 클래스의 새 인스턴스를 초기화합니다 |
| PdfFileStamp(input_file, output_file, keep_security) | PdfFileStamp 클래스의 새 인스턴스를 초기화합니다 |
| PdfFileStamp(input_stream, output_stream, keep_security) | PdfFileStamp 클래스의 새 인스턴스를 초기화합니다 |
| PdfFileStamp() | PdfFileStamp의 생성자.<br/>            입력 파일과 출력 파일은 해당 속성을 통해 지정할 수 있습니다. |
| PdfFileStamp(document) | PdfFileStamp 클래스의 새 인스턴스를 초기화합니다 |
| PdfFileStamp(document, output_file) | PdfFileStamp 클래스의 새 인스턴스를 초기화합니다 |
| PdfFileStamp(document, output_stream) | PdfFileStamp 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
| optimize_size | 최적화 플래그를 가져오거나 설정합니다. 결과 파일의 동일한 리소스 스트림은 이 플래그가 설정된 경우 하나의 PDF 객체로 병합됩니다. <br/>            이를 통해 결과 파일 크기를 줄일 수 있지만 실행 속도가 느려지고 메모리 요구량이 증가할 수 있습니다.<br/>            기본값: false. |
| keep_security | true인 경우 보안을 유지합니다. (이 기능은 다음 버전에서 구현될 예정입니다). |
| input_file | 입력 파일의 이름과 경로를 가져오거나 설정합니다. |
| input_stream | 입력 스트림을 가져오거나 설정합니다. |
| output_file | 출력 파일의 이름 및 경로를 가져오거나 설정합니다. |
| output_stream | 출력 스트림을 가져오거나 설정합니다. |
| page_number_rotation | 페이지 번호의 회전을 가져오거나 설정합니다. 회전은 각도로 표시됩니다. 기본값은 0입니다. |
| page_height | 소스 파일의 첫 페이지 높이를 가져옵니다. |
| page_width | 입력 파일의 첫 페이지 너비를 가져옵니다. |
| starting_number | 입력 파일의 첫 페이지에 대한 시작 번호를 가져오거나 설정합니다. 다음 페이지는 이 값부터 번호가 매겨집니다. <br/>            예를 들어 StartingNumber가 100으로 설정되면 문서 페이지 번호는 100, 101, 102가 됩니다... |
| numbering_style | 페이지 번호 매기기 스타일을 가져오거나 설정합니다. 가능한 값: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| stamp_id | 다음에 추가된 스탬프의 스탬프 ID (페이지 헤더/푸터/페이지 번호 포함). |
| POS_BOTTOM_MIDDLE | 하단 중앙 위치. |
| POS_BOTTOM_RIGHT | 하단 오른쪽 위치. |
| POS_UPPER_RIGHT | 상단 오른쪽 위치. |
| POS_SIDES_RIGHT | 오른쪽 위치. |
| POS_UPPER_MIDDLE | 상단 중앙 위치. |
| POS_BOTTOM_LEFT | 왼쪽 아래 위치. |
| POS_SIDES_LEFT | 왼쪽 위치. |
| POS_UPPER_LEFT | 왼쪽 위 위치. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(src_file) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_stream) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_doc) | PDF 문서를 편집용으로 바인딩합니다. |
| save(dest_file) | 결과를 지정된 파일에 저장합니다. |
| save(dest_stream) | 지정된 스트림에 문서를 저장합니다. |
| add_page_number(format_string) | 파일에 페이지 번호를 추가합니다. 페이지 번호 텍스트에 # 기호가 포함될 수 있으며, 이는 페이지 번호로 대체됩니다. <br/>            페이지 번호는 페이지 하단에 가로로 가운데 정렬되어 배치됩니다. |
| add_page_number(formatted_text) | 페이지에 페이지 번호를 추가합니다. 페이지 번호에 # 기호가 포함될 수 있으며, 이는 페이지 번호로 대체됩니다.<br/>            페이지 번호는 페이지 하단에 가로로 가운데 정렬되어 배치됩니다. |
| add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin) | 문서의 페이지에 페이지 번호를 추가합니다. |
| add_page_number(format_string, x, y) | 문서의 페이지에 페이지 번호를 추가합니다. |
| add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin) | 문서의 페이지에 페이지 번호를 추가합니다. |
| add_page_number(formatted_text, x, y) | 문서의 페이지에 페이지 번호를 추가합니다. |
| add_page_number(format_string, position) | 문서의 페이지에 페이지 번호를 추가합니다. |
| add_page_number(formatted_text, position) | 문서의 페이지에 페이지 번호를 추가합니다. |
| add_header(formatted_text, top_margin) | 페이지에 헤더를 추가합니다. |
| add_header(formatted_text, top_margin, left_margin, right_margin) | 페이지에 헤더를 추가합니다. |
| add_header(image_file, top_margin) | 파일의 페이지에 이미지를 헤더로 추가합니다. |
| add_header(image_file, top_margin, left_margin, right_margin) | 파일의 페이지에 이미지를 헤더로 추가합니다. |
| add_header(image_stream, top_margin) | 페이지에 이미지를 머리글로 추가합니다. |
| add_header(input_stream, top_margin, left_margin, right_margin) | 페이지에 이미지를 머리글로 추가합니다. |
| add_footer(formatted_text, bottom_margin) | 문서 페이지에 바닥글을 추가합니다. |
| add_footer(formatted_text, bottom_margin, left_margin, right_margin) | 문서 페이지에 바닥글을 추가합니다. |
| add_footer(image_file, bottom_margin) | 문서 페이지에 이미지를 바닥글로 추가합니다. |
| add_footer(image_file, bottom_margin, left_margin, right_margin) | 문서 페이지에 이미지를 바닥글로 추가합니다. |
| add_footer(image_stream, bottom_margin) | 페이지에 이미지를 바닥글로 추가합니다. |
| add_footer(image_stream, bottom_margin, left_margin, right_margin) | 페이지에 이미지를 바닥글로 추가합니다. |
| close() | 열린 파일을 닫고 변경 사항을 저장합니다. <br/>            경고. 입력 또는 출력 스트림이 지정된 경우 Close() 메서드에 의해 닫히지 않습니다. |
| add_stamp(stamp) | 파일에 스탬프를 추가합니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

