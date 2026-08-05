---
title: "PdfExtractor"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 문서에서 이미지와 텍스트를 추출하는 클래스."
type: docs
weight: 210
url: /ko/python-net/aspose.pdf.facades/pdfextractor/
---

## PdfExtractor class

PDF 문서에서 이미지와 텍스트를 추출하는 클래스.

PdfExtractor 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfExtractor() | 새로운 [PdfExtractor](/pdf/python-net/aspose.pdf.facades/pdfextractor/) 객체를 초기화합니다. |
| PdfExtractor(document) | PdfExtractor 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
| start_page | 추출 작업이 수행될 페이지 범위에서 시작 페이지를 가져오거나 설정합니다. |
| end_page | 추출 작업이 수행될 페이지 범위에서 종료 페이지를 가져오거나 설정합니다. |
| extract_text_mode | 텍스트 추출 결과의 모드를 설정합니다. |
| text_search_options | 텍스트 검색 옵션을 가져오거나 설정합니다. |
| extract_image_mode | 이미지 추출 프로세스의 모드를 설정합니다. |
| is_bidi | 텍스트에 히브리어 또는 아랍어 기호가 포함된 경우 true입니다. 이 경우는 문자열 함수가 동작을 변경하고 텍스트 처리를 오른쪽에서 왼쪽으로 시작하기 때문에 특별히 고려해야 합니다<br/>            (숫자와 기타 비텍스트 문자는 제외<br/>            ). |
| resolution | 추출된 이미지의 해상도를 설정하거나 가져옵니다.<br/>            기본값은 150입니다.<br/>            해상도 값이 높을수록 이미지가 더 선명해집니다.<br/>            그러나 해상도 값을 높이면 이미지 추출에 필요한 시간과 메모리가 증가합니다.<br/>            일반적으로 선명한 이미지를 얻으려면 해상도를 150 또는 300으로 설정하면 충분합니다. |
| password | 입력 파일의 비밀번호를 가져오거나 설정합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(input_file) | 입력 PDF 파일을 바인드합니다. |
| bind_pdf(input_stream) | 스트림에서 PDF 문서를 바인드합니다. |
| bind_pdf(src_doc) | 파사드를 초기화합니다. |
| extract_text() | Unicode 인코딩을 사용하여 PDF 문서에서 텍스트를 추출합니다. |
| extract_text(encoding) | 지정된 인코딩을 사용하여 PDF 문서에서 텍스트를 추출합니다. |
| get_text(output_file) | 텍스트를 파일에 저장합니다. 또한 보기:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream) | 텍스트를 스트림에 저장합니다. 또한 보기:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream, filter_not_ascii) | 텍스트를 스트림에 저장합니다. 또한 보기:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_next_image(output_file) | PDF 문서에서 다음 이미지를 가져옵니다. 참고: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다. |
| get_next_image(output_file, format) | 주어진 이미지 형식으로 PDF 문서에서 다음 이미지를 가져옵니다. 참고: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다. |
| get_next_image(output_stream, format) | PDF 파일에서 다음 이미지를 가져와 주어진 이미지 형식으로 스트림에 저장합니다. |
| get_next_image(output_stream) | PDF 파일에서 다음 이미지를 가져와 주어진 이미지 형식으로 스트림에 저장합니다. |
| extract_attachment() | PDF 문서에서 첨부 파일을 추출합니다. |
| extract_attachment(attachment_file_name) | 첨부 파일 이름으로 PDF 파일에서 첨부 파일을 추출합니다. |
| get_next_page_text(output_file) | 한 페이지의 텍스트를 파일에 저장합니다. |
| get_next_page_text(output_stream) | 한 페이지의 텍스트를 스트림에 저장합니다. |
| close() | Facade와 연결된 Aspose.Pdf.Document를 해제합니다. |
| extract_image() | PDF 파일에서 이미지를 추출합니다. |
| has_next_image() | PDF 문서에서 추가 이미지에 접근할 수 있는지 확인합니다. 참고: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다. |
| get_attach_names() | PDF 파일의 첨부 파일 목록을 반환합니다. 참고: 이 메서드를 사용하기 전에 ExtractAttachments를 호출해야 합니다. |
| get_attachment(output_path) | 첨부 파일을 파일에 저장합니다. |
| has_next_page_text() | 추가 텍스트를 가져올 수 있는지 여부를 나타냅니다. |
| get_attachment_info() | 첨부 파일 목록을 가져옵니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

