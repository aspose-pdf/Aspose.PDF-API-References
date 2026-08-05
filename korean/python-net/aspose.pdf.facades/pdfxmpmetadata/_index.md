---
title: "PdfXmpMetadata"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "XMP 메타데이터를 조작하는 클래스입니다."
type: docs
weight: 380
url: /ko/python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

XMP 메타데이터를 조작하는 클래스입니다.

PdfXmpMetadata 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfXmpMetadata() | PdfXmpMetadata의 생성자입니다. |
| PdfXmpMetadata(document) | PdfXmpMetadata 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
| keys | 사전에서 키를 가져옵니다. |
| values | 사전에서 값 컬렉션을 가져옵니다. |
| is_fixed_size | 컬렉션에 고정 크기가 있으면 true를 반환합니다. |
| is_synchronized | 컬렉션이 동기화되어 있으면 true를 반환합니다. |
| sync_root | 컬렉션의 동기화 객체를 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(src_file) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_stream) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_doc) | PDF 문서를 편집용으로 바인딩합니다. |
| save(dest_file) | PDF 문서를 지정된 파일에 저장합니다. |
| save(dest_stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| add(key, value) | XMP 메타데이터에 값을 추가합니다. |
| add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description) | 메타데이터에 확장 필드를 추가합니다. |
| add(key, value) | 딕셔너리 객체에 새 요소를 추가합니다. |
| add(key, value) | 메타데이터에 확장 필드를 추가합니다. |
| remove(key) | 지정된 키를 가진 요소를 제거합니다. |
| remove(key) | 딕셔너리에서 키를 제거합니다. |
| contains(key) | 딕셔너리가 지정된 키를 포함하는지 확인합니다. |
| contains(property) | 딕셔너리가 지정된 속성을 포함하는지 확인합니다. |
| get_xmp_metadata() | 입력 PDF의 XmpMetadata를 XML 형식으로 가져옵니다. |
| get_xmp_metadata(name) | 메타 이름에 따라 입력 PDF의 XmpMetadata 일부를 가져옵니다. |
| close() | 현재 파사드와 연관된 모든 리소스를 해제합니다. |
| register_namespace_uri(prefix, namespace_uri) | 네임스페이스 URI를 등록합니다. |
| get_namespace_uri_by_prefix(prefix) | 접두사로 네임스페이스 URI를 가져옵니다. |
| get_prefix_by_namespace_uri(namespace_uri) | 네임스페이스 URI로부터 접두사를 가져옵니다. |
| contains_key(key) | 이 사전이 지정된 키를 포함하고 있는지 확인합니다. |
| try_get_value(key, value) | 사전에서 키를 찾아서, 찾으면 값을 반환합니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

