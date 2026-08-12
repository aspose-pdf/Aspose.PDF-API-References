---
title: "C++를 통해 Rust용 Aspose.PDF"
description: "C++를 통해 Rust용 Aspose.PDF"
keywords:  "Rust, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /ko/rust-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Rust via C++ allows developers manipulate them PDF files directly in the Rust.

# 구조체

## Document
Document는 PDF-document를 나타냅니다.

```rust
pub struct Document { /* private fields */ }
```

# Implementations

## Convert from PDF functions

| 함수 | 설명 |
| -------- | ----------- |
| [save_docx](./convert/save_docx/) | 이전에 열었던 PDF-document를 DocX-document로 변환하고 저장합니다. |
| [save_doc](./convert/save_doc/) | 이전에 열었던 PDF-document를 Doc-document로 변환하고 저장합니다. |
| [save_xlsx](./convert/save_xlsx/) | 이전에 열었던 PDF-document를 XlsX-document로 변환하고 저장합니다. |
| [save_txt](./convert/save_txt/) | 이전에 열었던 PDF-document를 Txt-document로 변환하고 저장합니다. |
| [save_pptx](./convert/save_pptx/) | 이전에 열었던 PDF-document를 PptX-document로 변환하고 저장합니다. |
| [save_xps](./convert/save_xps/) | 이전에 열었던 PDF-document를 Xps-document로 변환하고 저장합니다. |
| [save_tex](./convert/save_tex/) | 이전에 열었던 PDF-document를 TeX-document로 변환하고 저장합니다. |
| [save_epub](./convert/save_epub/) | 이전에 열었던 PDF-document를 Epub-document로 변환하고 저장합니다. |
| [save_booklet](./convert/save_booklet/) | 이전에 열었던 PDF-document를 소책자 PDF-document로 변환하고 저장합니다. |
| [save_n_up](./convert/save_n_up/) | 이전에 열었던 PDF-document를 N-Up PDF-document로 변환하고 저장합니다. |
| [save_markdown](./convert/save_markdown/) | 이전에 열었던 PDF-document를 Markdown-document로 변환하고 저장합니다. |
| [save_tiff](./convert/save_tiff/) | 이전에 열었던 PDF-document를 Tiff-document로 변환하고 저장합니다. |
| [save_docx_enhanced](./convert/save_docx_enhanced/) | 이전에 열었던 PDF-document를 향상된 인식 모드가 적용된 DocX-document로 변환하고 저장합니다(완전히 편집 가능한 표와 단락). |
| [save_svg_zip](./convert/save_svg_zip/) | 이전에 열었던 PDF-document를 SVG-archive로 변환하고 저장합니다. |
| [export_fdf](./convert/export_fdf/) | AcroForm이 포함된 이전에 열었던 PDF-document를 FDF-document로 내보냅니다. |
| [export_xfdf](./convert/export_xfdf/) | AcroForm이 포함된 이전에 열었던 PDF-document를 XFDF-document로 내보냅니다. |
| [export_xml](./convert/export_xml/) | AcroForm이 포함된 이전에 열었던 PDF-document를 XML-document로 내보냅니다. |
| [page_to_jpg](./convert/page_to_jpg/) | 지정된 페이지를 Jpg-image로 변환하고 저장합니다. |
| [page_to_png](./convert/page_to_png/) | 지정된 페이지를 Png-image로 변환하고 저장합니다. |
| [page_to_bmp](./convert/page_to_bmp/) | 지정된 페이지를 Bmp-image로 변환하고 저장합니다. |
| [page_to_tiff](./convert/page_to_tiff/) | 지정된 페이지를 Tiff 이미지로 변환하고 저장합니다. |
| [page_to_svg](./convert/page_to_svg/) | 지정된 페이지를 Svg 이미지로 변환하고 저장합니다. |
| [page_to_pdf](./convert/page_to_pdf/) | 지정된 페이지를 PDF 문서로 변환하고 저장합니다. |
| [page_to_dicom](./convert/page_to_dicom/) | 지정된 페이지를 DICOM 이미지로 변환하고 저장합니다. |


## Organize PDF functions

| 함수 | 설명 |
| -------- | ----------- |
| [optimize](./organize/optimize/) | PDF 문서 내용을 최적화합니다. |
| [optimize_resource](./organize/optimize_resource/) | PDF 문서의 리소스를 최적화합니다. |
| [grayscale](./organize/grayscale/) | PDF 문서를 흑백으로 변환합니다. |
| [rotate](./organize/rotate/) | PDF 문서를 회전합니다. |
| [set_background](./organize/set_background/) | RGB 값을 사용하여 PDF 문서 배경 색을 설정합니다. |
| [repair](./organize/repair/) | PDF 문서를 복구합니다. |
| [replace_text](./organize/replace_text/) | PDF 문서의 텍스트를 교체합니다 |
| [add_page_num](./organize/add_page_num/) | PDF 문서에 페이지 번호를 추가합니다 |
| [add_text_header](./organize/add_text_header/) | PDF 문서 헤더에 텍스트를 추가합니다 |
| [add_text_footer](./organize/add_text_footer/) | PDF 문서 푸터에 텍스트를 추가합니다 |
| [flatten](./organize/flatten/) | PDF 문서를 평면화합니다 |
| [remove_annotations](./organize/remove_annotations/) | PDF 문서에서 주석을 제거합니다 |
| [remove_attachments](./organize/remove_attachments/) | PDF 문서에서 첨부 파일을 제거합니다 |
| [remove_blank_pages](./organize/remove_blank_pages/) | PDF 문서에서 빈 페이지를 제거합니다 |
| [remove_bookmarks](./organize/remove_bookmarks/) | PDF 문서에서 북마크를 제거합니다 |
| [remove_hidden_text](./organize/remove_hidden_text/) | PDF 문서에서 숨겨진 텍스트를 제거합니다 |
| [remove_images](./organize/remove_images/) | PDF 문서에서 이미지를 제거합니다 |
| [remove_javascripts](./organize/remove_javascripts/) | PDF 문서에서 자바스크립트를 제거합니다 |
| [remove_tables](./organize/remove_tables/) | PDF 문서에서 표를 제거합니다. |
| [remove_watermarks](./organize/remove_watermarks/) | PDF 문서에서 워터마크를 제거합니다. |
| [add_watermark](./organize/add_watermark/) | PDF 문서에 워터마크를 추가합니다. |
| [embed_fonts](./organize/embed_fonts/) | PDF-document에 글꼴을 삽입합니다. |
| [unembed_fonts](./organize/unembed_fonts/) | PDF-document에서 글꼴 삽입을 해제합니다. |
| [optimize_file_size](./organize/optimize_file_size/) | 이미지 압축 품질을 사용하여 PDF-document의 크기를 최적화합니다. |
| [remove_text_headers](./organize/remove_text_headers/) | PDF-document에서 텍스트 머리글을 제거합니다. |
| [remove_text_footers](./organize/remove_text_footers/) | PDF-document에서 텍스트 바닥글을 제거합니다. |
| [crop](./organize/crop/) | PDF-document의 페이지를 자릅니다. |
| [replace_font](./organize/replace_font/) | PDF-document의 글꼴을 교체합니다. |
| [convert](./organize/convert/) | PDF-document를 지정된 PDF 형식의 PDF-document로 변환합니다 |
| [validate](./organize/validate/) | PDF-document가 PDF 형식에 준수하는지 검증합니다 |
| [remove_pdfa_compliance](./organize/remove_pdfa_compliance/) | PDF-document에서 PDF/A 준수를 제거합니다 |
| [remove_pdfua_compliance](./organize/remove_pdfua_compliance/) | PDF-document에서 PDF/UA 준수를 제거합니다 |
| [is_pdfa_compliant](./organize/is_pdfa_compliant/) | PDF-document가 PDF/A 규격을 준수하는지 확인합니다 |
| [is_pdfua_compliant](./organize/is_pdfua_compliant/) | PDF-document가 PDF/UA 규격을 준수하는지 확인합니다 |
| [page_rotate](./organize/page_rotate/) | PDF-document의 페이지를 회전합니다. |
| [page_set_size](./organize/page_set_size/) | PDF-document의 페이지 크기를 설정합니다. |
| [page_grayscale](./organize/page_grayscale/) | 페이지를 흑백으로 변환합니다. |
| [page_add_text](./organize/page_add_text/) | 페이지에 텍스트를 추가합니다. |
| [page_replace_text](./organize/page_replace_text/) | 페이지의 텍스트를 교체합니다 |
| [page_add_page_num](./organize/page_add_page_num/) | 페이지에 페이지 번호를 추가합니다 |
| [page_add_text_header](./organize/page_add_text_header/) | 페이지 머리글에 텍스트를 추가합니다 |
| [page_add_text_footer](./organize/page_add_text_footer/) | 페이지 바닥글에 텍스트를 추가합니다 |
| [page_remove_annotations](./organize/page_remove_annotations/) | 페이지의 주석을 제거합니다. |
| [page_remove_hidden_text](./organize/page_remove_hidden_text/) | 페이지의 숨겨진 텍스트를 제거합니다. |
| [page_remove_images](./organize/page_remove_images/) | 페이지의 이미지를 제거합니다. |
| [page_remove_tables](./organize/page_remove_tables/) | 페이지의 표를 제거합니다. |
| [page_remove_watermarks](./organize/page_remove_watermarks/) | 페이지에서 워터마크를 제거합니다. |
| [page_add_watermark](./organize/page_add_watermark/) | 페이지에 워터마크를 추가합니다. |
| [page_remove_text_headers](./organize/page_remove_text_headers/) | 페이지에서 텍스트 헤더를 제거합니다. |
| [page_remove_text_footers](./organize/page_remove_text_footers/) | 페이지에서 텍스트 푸터를 제거합니다. |
| [page_crop](./organize/page_crop/) | 페이지를 자릅니다. |
| [page_replace_font](./organize/page_replace_font/) | 페이지의 글꼴을 교체합니다. |
| [page_merge_layers](./organize/page_merge_layers/) | 페이지의 모든 레이어를 지정된 새 레이어 이름으로 단일 레이어로 병합합니다. |
| [page_layers](./organize/page_layers/) | 페이지의 레이어 이름을 가져옵니다. |


## Core PDF functions

| 함수 | 설명 |
| -------- | ----------- |
| [new](./core/new/) | 새 PDF 문서를 생성합니다. |
| [open](./core/open/) | 파일 이름으로 PDF 문서를 엽니다. |
| [save](./core/save/) | 이전에 연 PDF 문서를 저장합니다. |
| [save_as](./core/save_as/) | 이전에 연 PDF 문서를 새 파일 이름으로 저장합니다. |
| [set_license](./core/set_license/) | 파일 이름으로 라이선스를 설정합니다. |
| [extract_text](./core/extract_text/) | PDF 문서 내용을 일반 텍스트로 반환합니다. |
| [word_count](./core/word_count/) | PDF 문서의 단어 수를 반환합니다. |
| [character_count](./core/character_count/) | PDF 문서의 문자 수를 반환합니다. |
| [append](./core/append/) | 다른 PDF 문서에서 페이지를 추가합니다. |
| [append_pages](./core/append_pages/) | 다른 PDF 문서에서 선택한 페이지를 추가합니다. |
| [merge_documents](./core/merge_documents/) | 제공된 PDF 문서를 병합하여 새 PDF 문서를 생성합니다. |
| [split_document](./core/split_document/) | 원본 PDF 문서에서 페이지를 추출하여 여러 개의 새 PDF 문서를 생성합니다. |
| [split](./core/split/) | 현재 PDF 문서에서 페이지를 추출하여 여러 개의 새 PDF 문서를 생성합니다. |
| [split_at_page](./core/split_at_page/) | PDF 문서를 두 개의 새 PDF 문서로 분할합니다. |
| [split_at](./core/split_at/) | 현재 PDF 문서를 두 개의 새 PDF 문서로 분할합니다. |
| [bytes](./core/bytes/) | PDF 문서의 내용을 바이트 벡터로 반환합니다. |
| [get_meta_info](./core/get_meta_info/) | PDF 문서의 메타 정보 값을 가져옵니다. |
| [set_meta_info](./core/set_meta_info/) | PDF-document의 메타 정보 값을 설정합니다. |
| [clear_meta_info](./core/clear_meta_info/) | PDF-document의 모든 메타 정보 값을 지웁니다. |
| [is_linearized](./core/is_linearized/) | 문서가 선형화되었는지 여부를 나타내는 값을 가져옵니다. |
| [page_add](./core/page_add/) | PDF-document에 새 페이지를 추가합니다. |
| [page_insert](./core/page_insert/) | PDF-document의 지정된 위치에 새 페이지를 삽입합니다. |
| [page_delete](./core/page_delete/) | PDF-document에서 지정된 페이지를 삭제합니다. |
| [page_count](./core/page_count/) | PDF-document의 페이지 수를 반환합니다. |
| [page_word_count](./core/page_word_count/) | PDF-document의 지정된 페이지에서 단어 수를 반환합니다. |
| [page_character_count](./core/page_character_count/) | PDF-document의 지정된 페이지에서 문자 수를 반환합니다. |
| [page_is_blank](./core/page_is_blank/) | PDF-document에서 페이지가 비어 있는지 반환합니다. |


## Security
| 함수 | 설명 |
| -------- | ----------- |
| [open_with_password](./security/open_with_password/) | 비밀번호로 보호된 PDF-document를 엽니다. |
| [encrypt](./security/encrypt/) | PDF-document를 암호화합니다. |
| [decrypt](./security/decrypt/) | PDF-document를 복호화합니다. |
| [set_permissions](./security/set_permissions/) | PDF-document에 대한 권한을 설정합니다. |
| [get_permissions](./security/get_permissions/) | PDF-document의 현재 권한을 가져옵니다. |
| [is_encrypted](./security/is_encrypted/) | PDF-document의 암호화 상태를 가져옵니다. |
| [sign_pkcs7](./security/sign_pkcs7/) | PKCS#7 디지털 서명을 사용하여 PDF-document에 서명합니다. |
| [sign_pkcs7_detached](./security/sign_pkcs7_detached/) | PKCS#7 Detached 디지털 서명을 사용하여 PDF-document에 서명합니다. |
| [is_signed](./security/is_signed/) | PDF-document의 서명 상태를 가져옵니다. |
| [remove_signs](./security/remove_signs/) | PDF-document에서 서명을 제거합니다. |


## Miscellaneous

| 함수 | 설명 |
| -------- | ----------- |
| [about](./miscellaneous/about/) | C++를 통해 Aspose.PDF for Rust에 대한 메타데이터 정보를 반환합니다. |



# Structs secondary

## ProductInfo contains metadata about the Aspose.PDF for Rust via C++.
```rust
#[derive(Debug, Deserialize)]
pub struct ProductInfo {
    #[serde(rename = "product")]
    pub product: String,

    #[serde(rename = "family")]
    pub family: String,

    #[serde(rename = "version")]
    pub version: String,

    #[serde(rename = "releasedate")]
    pub release_date: String,

    #[serde(rename = "producer")]
    pub producer: String,

    #[serde(rename = "islicensed")]
    pub is_licensed: bool,
}
```

## Bitflag set representing PDF permission capabilities.
```rust
bitflags! {
    /// PDF 권한 기능을 나타내는 비트플래그 집합.
    #[derive(Copy, Clone, PartialEq, Eq)]
    pub struct Permissions: i32 {
        const PRINT_DOCUMENT                    = 1 << 2;  // 4
        const MODIFY_CONTENT                    = 1 << 3;  // 8
        const EXTRACT_CONTENT                   = 1 << 4;  // 16
        const MODIFY_TEXT_ANNOTATIONS           = 1 << 5;  // 32
        const FILL_FORM                         = 1 << 8;  // 256
        const EXTRACT_CONTENT_WITH_DISABILITIES = 1 << 9;  // 512
        const ASSEMBLE_DOCUMENT                 = 1 << 10; // 1024
        const PRINTING_QUALITY                  = 1 << 11; // 2048
    }
}
```

# Enums

## Enumeration of possible page size values.
```rust
pub enum PageSize {
    /// A0 크기.
    A0 = 0,
    /// A1 크기.
    A1 = 1,
    /// A2 크기.
    A2 = 2,
    /// A3 크기.
    A3 = 3,
    /// A4 크기.
    A4 = 4,
    /// A5 크기.
    A5 = 5,
    /// A6 크기.
    A6 = 6,
    /// B5 크기.
    B5 = 7,
    /// PageLetter 크기.
    PageLetter = 8,
    /// PageLegal 크기.
    PageLegal = 9,
    /// PageLedger 크기.
    PageLedger = 10,
    /// P11x17 크기.
    P11x17 = 11,
}
```

## Enumeration of possible rotation values.
```rust
pub enum Rotation {
    /// 회전되지 않음.
    None = 0,
    /// 시계 방향으로 90도 회전.
    On90 = 1,
    /// 180도 회전.
    On180 = 2,
    /// 시계 방향으로 270도 회전.
    On270 = 3,
    /// 시계 방향으로 360도 회전.
    On360 = 4,
}
```

## An enumeration of possible crypto algorithms.
```rust
pub enum CryptoAlgorithm {
    /// 키 길이 40인 RC4.
    RC4x40 = 0,
    /// 키 길이 128인 RC4.
    RC4x128 = 1,
    /// 키 길이 128인 AES.
    AESx128 = 2,
    /// 키 길이 256인 AES.
    AESx256 = 3,
}
```

## An enumeration of possible PDF format standards.
```rust
pub enum PdfFormat {
    /// PDF/A-1a 형식.
    PDF_A_1A = 0,
    /// PDF/A-1b 형식.
    PDF_A_1B = 1,
    /// PDF/A-2a 형식.
    PDF_A_2A = 2,
    /// PDF/A-3a 형식.
    PDF_A_3A = 3,
    /// PDF/A-2b 형식.
    PDF_A_2B = 4,
    /// PDF/A-2u 형식.
    PDF_A_2U = 5,
    /// PDF/A-3b 형식.
    PDF_A_3B = 6,
    /// PDF/A-3u 형식.
    PDF_A_3U = 7,
    /// Adobe 버전 1.0.
    V_1_0 = 8,
    /// Adobe 버전 1.1.
    V_1_1 = 9,
    /// Adobe 버전 1.2.
    V_1_2 = 10,
    /// Adobe 버전 1.3.
    V_1_3 = 11,
    /// Adobe 버전 1.4.
    V_1_4 = 12,
    /// Adobe 버전 1.5.
    V_1_5 = 13,
    /// Adobe 버전 1.6.
    V_1_6 = 14,
    /// Adobe 버전 1.7.
    V_1_7 = 15,
    /// ISO 표준 PDF 2.0.
    V_2_0 = 16,
    /// PDF/UA-1 형식.
    PDF_UA_1 = 17,
    /// PDF/X-1a:2001 형식.
    PDF_X_1A_2001 = 18,
    /// PDF/X-1a 형식.
    PDF_X_1A = 19,
    /// PDF/X-3 형식.
    PDF_X_3 = 20,
    /// ZUGFeRD 형식.
    ZUGFeRD = 21,
    /// PDF/A-4 형식.
    PDF_A_4 = 22,
    /// PDF/A-4e 형식.
    PDF_A_4E = 23,
    /// PDF/A-4f 형식.
    PDF_A_4F = 24,
    /// PDF/X-4 형식.
    PDF_X_4 = 25,
    /// PDF/E-1 (PDF 1.6) 형식.
    PDF_E_1 = 26,
}
```

## An enumeration of actions to take when a conversion error occurs.
```rust
pub enum ConvertErrorAction {
    /// 비규격 요소 삭제.
    Delete = 0,
    /// 아무것도 하지 않음, 비규격 요소 유지.
    None = 1,
}
```

