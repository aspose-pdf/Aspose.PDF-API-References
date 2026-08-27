---
title: "PdfViewer"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF를 보기 또는 인쇄하는 클래스를 나타냅니다."
type: docs
weight: 370
url: /ko/python-net/aspose.pdf.facades/pdfviewer/
---

## PdfViewer class

PDF를 보기 또는 인쇄하는 클래스를 나타냅니다.

PdfViewer 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfViewer() | 새로운 [PdfViewer](/pdf/python-net/aspose.pdf.facades/pdfviewer/) 객체를 초기화합니다. |
| PdfViewer(document) | PdfViewer 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| show_hidden_areas | 페이지에서 숨겨진 영역의 표시 여부를 제어하는 플래그를 가져오거나 설정합니다. |
| print_status | 인쇄 작업의 결과를 가져옵니다. 성공하면 null이며, 그렇지 않으면 예외 객체를 반환합니다. |
| use_intermidiate_image | 파일 모드에서 인쇄할 때 pdf 페이지를 중간 png 파일로 변환하는 사용 여부를 가져오거나 설정합니다. 출력 파일 크기가 중요한 경우에 사용하십시오. |
| coordinate_type | 페이지 좌표 유형 (Media/Crop 박스)을 가져오거나 설정합니다. 기본값으로 CropBox 값이 사용됩니다. |
| print_as_image | PdfViewer가 이미지를 인쇄하도록 하는 모드를 설정하거나 가져옵니다. |
| page_count | 현재 Pdf 파일의 페이지 수를 가져옵니다. |
| password | 입력 문서 비밀번호를 가져오거나 설정합니다. |
| print_page_dialog | 인쇄 시 페이지 번호 대화 상자를 표시할지 여부를 나타내는 bool 값을 가져오거나 설정합니다. |
| print_as_grayscale | 페이지를 그레이스케일로 인쇄할지 여부를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다. |
| printer_job_name | 문서가 인쇄될 때 프린터 큐에 있는 문서 이름을 가져오거나 설정합니다. 기본값은 파일 이름입니다. |
| form_presentation_mode | 폼 프레젠테이션 모드를 가져오거나 설정합니다. |
| rendering_options | 렌더링 옵션을 가져오거나 설정합니다. |
| vertical_alignment | 수직 정렬을 나타내는 값을 가져오거나 설정합니다. |
| horizontal_alignment | 수평 정렬을 나타내는 값을 가져오거나 설정합니다. |
| auto_resize | 파일이 최적화된 크기로 인쇄될지 여부를 나타내는 bool 값을 가져오거나 설정합니다. |
| auto_rotate | 파일이 자동 회전으로 인쇄되는지를 나타내는 bool 값을 가져오거나 설정합니다. |
| auto_rotate_mode | 회전 방향을 나타내는 AutoRotateMode 값을 가져오거나 설정합니다. |
| resolution | 보기 및 인쇄 중 해상도를 가져오거나 설정합니다. 해상도가 높을수록 속도가 느려집니다. 기본값은 150입니다. |
| scale_factor | 배율을 나타내는 부동 소수점 값을 가져오거나 설정합니다. 기본값은 1.0입니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| print_large_pdf(file_path) | 큰 Pdf 파일을 열고 인쇄합니다. Pdf 파일에 수백 페이지 이상이 있거나 크기가 <br/>             3 MB보다 크면, 더 나은 성능을 위해 이 메서드를 사용하는 것이 권장됩니다. |
| print_large_pdf(input_stream) | 큰 Pdf 스트림을 열고 인쇄합니다. Pdf 파일에 수백 페이지 이상이 있거나 크기가 <br/>             3 MB보다 크면, 더 나은 성능을 위해 이 메서드를 사용하는 것이 권장됩니다. |
| print_large_pdf(file_path, printer_settings) | 지정된 프린터 설정으로 큰 Pdf 파일을 열고 인쇄합니다. Pdf 파일에 수백 <br/>             페이지 이상이 있거나 크기가 3 MB보다 크면, 더 나은 성능을 위해 이 메서드를 사용하는 것이 권장됩니다. |
| print_large_pdf(input_stream, printer_settings) | 지정된 프린터 설정으로 큰 Pdf 스트림을 열고 인쇄합니다. Pdf 파일에 수백 <br/>             페이지 이상이 있거나 크기가 3 MB보다 크면, 더 나은 성능을 위해 이 메서드를 사용하는 것이 권장됩니다. |
| print_large_pdf(file_path, page_settings, printer_settings) | 지정된 페이지 설정 및 프린터 설정으로 큰 Pdf 파일을 열고 인쇄합니다. Pdf <br/>             파일에 수백 페이지 이상이 있거나 크기가 3 MB보다 크면, 이 메서드는 <br/>             더 나은 성능을 위해 권장됩니다. |
| print_large_pdf(input_stream, page_settings, printer_settings) | 지정된 페이지 설정 및 프린터 설정으로 큰 Pdf 스트림을 열고 인쇄합니다. Pdf <br/>             파일에 수백 페이지 이상이 있거나 크기가 3 MB보다 크면, 이 메서드는 <br/>             더 나은 성능을 위해 권장됩니다. |
| print_document_with_settings(page_settings, printer_settings) | 설정으로 Pdf 문서를 인쇄합니다. 문서 크기가 페이지 크기에 맞지 않으면 pdf.kit이 페이지 크기에 맞게 확장합니다. |
| print_document_with_settings(printer_settings) | 설정으로 Pdf 문서를 인쇄합니다. 문서 크기가 페이지 크기에 맞지 않으면 pdf.kit이 페이지 크기에 맞게 확장합니다. |
| open_pdf_file(file_path) | Pdf 파일을 열지만 실제로 Pdf 파일의 페이지를 디코딩하지는 않습니다. |
| open_pdf_file(input_stream) | Pdf 파일 스트림을 엽니다. 하지만 실제로 Pdf 파일의 페이지를 디코딩하지는 않습니다. |
| bind_pdf(src_file) | 파사드를 초기화합니다. |
| bind_pdf(src_stream) | 파사드를 초기화합니다. |
| bind_pdf(src_doc) | 파사드를 초기화합니다. |
| save(dest_file) | 결과 PDF 문서를 파일에 저장합니다. |
| save(dest_stream) | 결과 PDF 문서를 스트림에 저장합니다. |
| decode_all_pages() | 현재 PDF 파일의 페이지를 가져옵니다. |
| decode_page(page_number) | PDF 파일 하나의 페이지를 디코드합니다. |
| print_document_with_setup() | 설정 대화 상자를 사용하여 PDF 문서를 인쇄합니다. 대화 상자를 통해 프린터를 선택하십시오. |
| print_document() | 설정 대화 상자를 사용하여 PDF 문서를 인쇄합니다. 대화 상자를 통해 프린터를 선택하십시오. |
| get_default_page_settings() | 기본 페이지 설정을 가져옵니다. |
| get_default_printer_settings() | 기본 프린터 설정을 가져옵니다. |
| close_pdf_file() | 현재 PDF 파일을 닫습니다. |
| close() | 현재 PDF 파일을 닫습니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

