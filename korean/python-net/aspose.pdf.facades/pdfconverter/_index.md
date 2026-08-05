---
title: "PdfConverter"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 파일의 각 페이지를 이미지로 변환하는 클래스를 나타내며, 현재 BMP, JPEG, PNG 및 TIFF를 지원합니다.<br/>            PDF의 그림, 양식, 주석을 지원합니다."
type: docs
weight: 200
url: /ko/python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

PDF 파일의 각 페이지를 이미지로 변환하는 클래스를 나타냅니다. 현재 BMP, JPEG, PNG 및 TIFF를 지원합니다.<br/>            PDF에서 지원되는 콘텐츠: 그림, 양식, 주석.

PdfConverter 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfConverter() | 새로운 [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/) 객체를 초기화합니다. |
| PdfConverter(document) | PdfConverter 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
| coordinate_type | 페이지 좌표 유형 (Media/Crop 박스)을 가져오거나 설정합니다. 기본값으로 CropBox 값이 사용됩니다. |
| show_hidden_areas | 페이지에서 숨겨진 영역의 표시 여부를 제어하는 플래그를 가져오거나 설정합니다. |
| rendering_options | 렌더링 옵션을 가져오거나 설정합니다. |
| form_presentation_mode | 폼 프레젠테이션 모드를 가져오거나 설정합니다. |
| resolution | 변환 중 해상도를 가져오거나 설정합니다. 해상도가 높을수록 변환 속도가 느려집니다. 기본값은 150입니다. |
| start_page | 변환하려는 시작 위치를 가져오거나 설정합니다. 최소값은 1입니다. |
| end_page | 변환하려는 종료 위치를 가져오거나 설정합니다. |
| password | 문서 OwnerPassword를 가져오거나 설정합니다. |
| user_password | 문서 UserPassword를 가져오거나 설정합니다. |
| page_count | 페이지 수를 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(input_file) | 변환을 위해 Pdf 파일을 바인딩합니다. |
| bind_pdf(input_stream) | 변환을 위해 Pdf 스트림을 바인딩합니다. |
| bind_pdf(src_doc) | 파사드를 초기화합니다. |
| save_as_tiff(output_file) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| save_as_tiff(output_file, compression_type) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| save_as_tiff(output_file, image_width, image_height) | PDF 문서의 각 페이지를 크기와 함께 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| save_as_tiff(output_file, page_size) | PDF 문서의 각 페이지를 페이지 크기로 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| save_as_tiff(output_file, page_size, settings) | PDF 문서의 각 페이지를 페이지 크기로 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| save_as_tiff(output_file, image_width, image_height, compression_type) | PDF 문서의 각 페이지를 크기와 함께 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| save_as_tiff(output_file, image_width, image_height, settings) | PDF 문서의 각 페이지를 크기와 함께 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| save_as_tiff(output_file, image_width, image_height, settings, converter) | PDF 문서의 각 페이지를 크기와 함께 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| save_as_tiff(output_stream) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 스트림에 저장합니다. |
| save_as_tiff(output_stream, compression_type) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| save_as_tiff(output_stream, page_size) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 스트림에 저장합니다. |
| save_as_tiff(output_stream, page_size, settings) | PDF 문서의 각 페이지를 페이지 크기로 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| save_as_tiff(output_stream, image_width, image_height) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 스트림에 저장합니다. |
| save_as_tiff(output_stream, image_width, image_height, compression_type) | PDF 문서의 각 페이지를 크기와 함께 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| save_as_tiff(output_stream, image_width, image_height, settings) | PDF 문서의 각 페이지를 크기와 함께 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| save_as_tiff(output_stream, image_width, image_height, settings, converter) | PDF 문서의 각 페이지를 크기와 함께 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| save_as_tiff(output_file, settings) | PDF 문서의 각 페이지를 페이지 크기로 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| save_as_tiff(output_file, settings, converter) | PDF 문서의 각 페이지를 크기와 함께 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| save_as_tiff(output_stream, settings) | PDF 문서의 각 페이지를 페이지 크기로 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| save_as_tiff(output_stream, settings, converter) | PDF 문서의 각 페이지를 크기와 함께 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| save_as_tiff_class_f(output_file, image_width, image_height) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 파일에 저장합니다. |
| save_as_tiff_class_f(output_file, page_size) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 파일에 저장합니다. |
| save_as_tiff_class_f(output_stream, image_width, image_height) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 스트림에 저장합니다. |
| save_as_tiff_class_f(output_stream, page_size) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 스트림에 저장합니다. |
| save_as_tiff_class_f(output_file) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 파일에 저장합니다. |
| save_as_tiff_class_f(output_stream) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 스트림에 저장합니다. |
| get_next_image(output_file) | 이미지를 기본 이미지 형식인 jpeg으로 파일에 저장합니다. |
| get_next_image(output_file, page_size) | 이미지를 주어진 페이지 크기로, 기본 이미지 형식인 jpeg으로 파일에 저장합니다. |
| get_next_image(output_file, format) | 이미지를 지정된 이미지 형식으로 파일에 저장합니다. |
| get_next_image(output_file, page_size, format) | 이미지를 지정된 페이지 크기와 이미지 형식으로 파일에 저장합니다. |
| get_next_image(output_stream) | 이미지를 기본 이미지 형식인 jpeg으로 스트림에 저장합니다. |
| get_next_image(output_stream, page_size) | 이미지를 지정된 페이지 크기로 스트림에 저장합니다. |
| get_next_image(output_stream, format) | 이미지를 지정된 이미지 형식으로 스트림에 저장합니다. |
| get_next_image(output_stream, page_size, format) | 이미지를 지정된 페이지 크기로 스트림에 저장합니다. |
| get_next_image(output_file, format, image_width, image_height, quality) | 이미지를 지정된 이미지 형식, 차원 및 품질로 파일에 저장합니다. |
| get_next_image(output_stream, format, image_width, image_height, quality) | 이미지를 지정된 이미지 형식, 차원 및 품질로 스트림에 저장합니다. |
| get_next_image(output_file, format, image_width, image_height, quality) | 이미지를 지정된 이미지 형식, 이미지 크기 및 품질로 파일에 저장합니다. |
| get_next_image(output_stream, format, image_width, image_height, quality) | 이미지를 지정된 이미지 형식, 크기 및 품질로 스트림에 저장합니다. |
| get_next_image(output_file, format, image_width, image_height) | 이미지를 지정된 이미지 형식, 차원 및 품질로 파일에 저장합니다. |
| get_next_image(output_stream, format, image_width, image_height) | 이미지를 지정된 이미지 형식, 차원 및 품질로 스트림에 저장합니다. |
| get_next_image(output_stream, format, quality) | 이미지를 지정된 이미지 형식, 차원 및 품질로 스트림에 저장합니다. |
| get_next_image(output_stream, page_size, format, quality) | 이미지를 지정된 페이지 크기, 이미지 형식 및 품질로 스트림에 저장합니다. |
| get_next_image(output_file, format, quality) | 이미지를 지정된 이미지 형식, 차원 및 품질로 파일에 저장합니다. |
| get_next_image(output_file, page_size, format, quality) | 이미지를 지정된 페이지 크기, 이미지 형식 및 품질로 파일에 저장합니다. |
| close() | PdfConverter 인스턴스를 닫고 리소스를 해제합니다. |
| do_convert() | PDF 문서를 이미지로 변환하기 위한 초기 작업을 수행합니다. |
| has_next_image() | PDF 파일에 추가 이미지가 있는지 여부를 나타냅니다. |
| merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical) | 없음 |
| merge_images_as_tiff(input_images_streams) | 여러 TIFF 스트림 목록을 하나의 다중 프레임 TIFF 스트림으로 병합합니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

