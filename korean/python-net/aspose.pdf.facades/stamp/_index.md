---
title: "Stamp"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "스탬프를 나타내는 클래스입니다."
type: docs
weight: 410
url: /ko/python-net/aspose.pdf.facades/stamp/
---

## Stamp class

스탬프를 나타내는 클래스입니다.

Stamp 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| Stamp() | Stamp 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| stamp_id | 스탬프 식별자를 가져오거나 설정합니다. |
| quality | 이미지 스탬프의 품질을 백분율로 가져오거나 설정합니다. 허용 값은 0..100%입니다. |
| opacity | 스탬프의 불투명도를 가져오거나 설정합니다. |
| page_number | 페이지 번호를 가져오거나 설정합니다. |
| pages | 스탬프가 적용될 페이지 번호 배열을 가져오거나 설정합니다. <br/>            Pages가 null이면 문서의 모든 페이지에 적용됩니다. |
| rotation | 스탬프의 회전을 도 단위로 가져오거나 설정합니다. |
| is_background | 배경 상태를 가져오거나 설정합니다. true인 경우 스탬프가 스캔된 페이지의 배경으로 배치됩니다.<br/>            기본값은 false로 설정됩니다. |
| blending_space | BlendingColorSpace 값을 가져오거나 설정합니다. 이 값은 색 공간을 정의하며 <br/>            페이지에서 투명도 및 블렌딩 작업을 수행하는 데 사용됩니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(pdf_file, page_number) | 스탬프로 사용할 PDF 파일과 페이지 번호를 설정합니다. |
| bind_pdf(pdf_stream, page_number) | 스탬프로 사용할 PDF 파일과 페이지 번호를 설정합니다. |
| bind_image(image_file) | 이미지를 스탬프로 설정합니다. |
| bind_image(image) | 스탬프로 사용할 이미지를 설정합니다. |
| bind_logo(formatted_text) | 텍스트를 스탬프로 설정합니다. |
| bind_text_state(text_state) | 스탬프 텍스트의 텍스트 상태를 설정합니다. |
| set_origin(origin_x, origin_y) | 스탬프가 배치될 페이지상의 위치를 설정합니다. |
| set_image_size(width, height) | 이미지 스탬프의 크기를 설정합니다. 이미지는 지정된 값에 따라 스케일됩니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

