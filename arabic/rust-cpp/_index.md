---
title: "Aspose.PDF لـ Rust عبر C++"
description: "Aspose.PDF لـ Rust عبر C++"
keywords:  "Rust, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /ar/rust-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Rust via C++ allows developers manipulate them PDF files directly in the Rust.

# الهياكل

## Document
المستند يمثل مستند PDF.

```rust
pub struct Document { /* private fields */ }
```

# Implementations

## Convert from PDF functions

| دالة | الوصف |
| -------- | ----------- |
| [save_docx](./convert/save_docx/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كملف DocX. |
| [save_doc](./convert/save_doc/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كملف Doc. |
| [save_xlsx](./convert/save_xlsx/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كملف XlsX. |
| [save_txt](./convert/save_txt/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كملف Txt. |
| [save_pptx](./convert/save_pptx/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كملف PptX. |
| [save_xps](./convert/save_xps/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كملف Xps. |
| [save_tex](./convert/save_tex/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كملف TeX. |
| [save_epub](./convert/save_epub/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كملف Epub. |
| [save_booklet](./convert/save_booklet/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كملف PDF ككتيب. |
| [save_n_up](./convert/save_n_up/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كملف PDF N-Up. |
| [save_markdown](./convert/save_markdown/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كملف Markdown. |
| [save_tiff](./convert/save_tiff/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كملف Tiff. |
| [save_docx_enhanced](./convert/save_docx_enhanced/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كملف DocX مع وضع التعرف المحسن (جداول وفقرة قابلة للتحرير بالكامل). |
| [save_svg_zip](./convert/save_svg_zip/) | تحويل وحفظ مستند PDF المفتوح مسبقًا كأرشيف SVG. |
| [export_fdf](./convert/export_fdf/) | تصدير من مستند PDF المفتوح مسبقًا مع AcroForm إلى ملف FDF. |
| [export_xfdf](./convert/export_xfdf/) | تصدير من مستند PDF المفتوح مسبقًا مع AcroForm إلى ملف XFDF. |
| [export_xml](./convert/export_xml/) | تصدير من مستند PDF المفتوح مسبقًا مع AcroForm إلى ملف XML. |
| [page_to_jpg](./convert/page_to_jpg/) | تحويل وحفظ الصفحة المحددة كصورة Jpg. |
| [page_to_png](./convert/page_to_png/) | تحويل وحفظ الصفحة المحددة كصورة Png. |
| [page_to_bmp](./convert/page_to_bmp/) | تحويل وحفظ الصفحة المحددة كصورة Bmp. |
| [page_to_tiff](./convert/page_to_tiff/) | تحويل وحفظ الصفحة المحددة كـ Tiff-image. |
| [page_to_svg](./convert/page_to_svg/) | تحويل وحفظ الصفحة المحددة كـ Svg-image. |
| [page_to_pdf](./convert/page_to_pdf/) | تحويل وحفظ الصفحة المحددة كـ PDF-document. |
| [page_to_dicom](./convert/page_to_dicom/) | تحويل وحفظ الصفحة المحددة كـ DICOM-image. |


## Organize PDF functions

| دالة | الوصف |
| -------- | ----------- |
| [optimize](./organize/optimize/) | تحسين محتوى PDF-document. |
| [optimize_resource](./organize/optimize_resource/) | تحسين موارد PDF-document. |
| [grayscale](./organize/grayscale/) | تحويل PDF-document إلى أبيض وأسود. |
| [rotate](./organize/rotate/) | تدوير PDF-document. |
| [set_background](./organize/set_background/) | تعيين لون خلفية PDF-document باستخدام قيم RGB. |
| [repair](./organize/repair/) | إصلاح PDF-document. |
| [replace_text](./organize/replace_text/) | استبدال النص في PDF-document |
| [add_page_num](./organize/add_page_num/) | إضافة رقم الصفحة إلى PDF-document |
| [add_text_header](./organize/add_text_header/) | إضافة نص في رأس PDF-document |
| [add_text_footer](./organize/add_text_footer/) | إضافة نص في تذييل PDF-document |
| [flatten](./organize/flatten/) | تسوية PDF-document |
| [remove_annotations](./organize/remove_annotations/) | إزالة التعليقات التوضيحية من PDF-document |
| [remove_attachments](./organize/remove_attachments/) | إزالة المرفقات من PDF-document |
| [remove_blank_pages](./organize/remove_blank_pages/) | إزالة الصفحات الفارغة من PDF-document |
| [remove_bookmarks](./organize/remove_bookmarks/) | إزالة العلامات المرجعية من PDF-document |
| [remove_hidden_text](./organize/remove_hidden_text/) | إزالة النص المخفي من PDF-document |
| [remove_images](./organize/remove_images/) | إزالة الصور من PDF-document |
| [remove_javascripts](./organize/remove_javascripts/) | إزالة سكريبتات جافا من PDF-document |
| [remove_tables](./organize/remove_tables/) | إزالة الجداول من PDF-document. |
| [remove_watermarks](./organize/remove_watermarks/) | إزالة العلامات المائية من PDF-document. |
| [add_watermark](./organize/add_watermark/) | إضافة علامة مائية إلى PDF-document. |
| [embed_fonts](./organize/embed_fonts/) | تضمين الخطوط في PDF-document. |
| [unembed_fonts](./organize/unembed_fonts/) | إزالة تضمين الخطوط في PDF-document. |
| [optimize_file_size](./organize/optimize_file_size/) | تحسين حجم PDF-document باستخدام جودة ضغط الصور. |
| [remove_text_headers](./organize/remove_text_headers/) | إزالة رؤوس النص من PDF-document. |
| [remove_text_footers](./organize/remove_text_footers/) | إزالة تذييلات النص من PDF-document. |
| [crop](./organize/crop/) | قص صفحات PDF-document. |
| [replace_font](./organize/replace_font/) | استبدال الخط في PDF-document. |
| [convert](./organize/convert/) | تحويل PDF-document إلى PDF-document بالتنسيق PDF المحدد |
| [validate](./organize/validate/) | التحقق من توافق PDF-document مع تنسيق PDF |
| [remove_pdfa_compliance](./organize/remove_pdfa_compliance/) | إزالة الامتثال لـ PDF/A من PDF-document |
| [remove_pdfua_compliance](./organize/remove_pdfua_compliance/) | إزالة الامتثال لـ PDF/UA من PDF-document |
| [is_pdfa_compliant](./organize/is_pdfa_compliant/) | تحقق ما إذا كان PDF-document متوافقًا مع PDF/A |
| [is_pdfua_compliant](./organize/is_pdfua_compliant/) | تحقق ما إذا كان PDF-document متوافقًا مع PDF/UA |
| [page_rotate](./organize/page_rotate/) | تدوير صفحة في PDF-document. |
| [page_set_size](./organize/page_set_size/) | تحديد حجم صفحة في PDF-document. |
| [page_grayscale](./organize/page_grayscale/) | تحويل الصفحة إلى أبيض وأسود. |
| [page_add_text](./organize/page_add_text/) | إضافة نص على الصفحة. |
| [page_replace_text](./organize/page_replace_text/) | استبدال النص على الصفحة |
| [page_add_page_num](./organize/page_add_page_num/) | إضافة رقم الصفحة إلى الصفحة |
| [page_add_text_header](./organize/page_add_text_header/) | إضافة نص في رأس الصفحة |
| [page_add_text_footer](./organize/page_add_text_footer/) | إضافة نص في تذييل الصفحة |
| [page_remove_annotations](./organize/page_remove_annotations/) | إزالة التعليقات التوضيحية في الصفحة. |
| [page_remove_hidden_text](./organize/page_remove_hidden_text/) | إزالة النص المخفي في الصفحة. |
| [page_remove_images](./organize/page_remove_images/) | إزالة الصور في الصفحة. |
| [page_remove_tables](./organize/page_remove_tables/) | إزالة الجداول في الصفحة. |
| [page_remove_watermarks](./organize/page_remove_watermarks/) | إزالة العلامات المائية في الصفحة. |
| [page_add_watermark](./organize/page_add_watermark/) | إضافة علامة مائية على الصفحة. |
| [page_remove_text_headers](./organize/page_remove_text_headers/) | إزالة رؤوس النص في الصفحة. |
| [page_remove_text_footers](./organize/page_remove_text_footers/) | إزالة تذييلات النص في الصفحة. |
| [page_crop](./organize/page_crop/) | قص صفحة. |
| [page_replace_font](./organize/page_replace_font/) | استبدال الخط في الصفحة. |
| [page_merge_layers](./organize/page_merge_layers/) | دمج جميع الطبقات على الصفحة في طبقة واحدة بالاسم الجديد المحدد للطبقة. |
| [page_layers](./organize/page_layers/) | الحصول على أسماء الطبقات في الصفحة. |


## Core PDF functions

| دالة | الوصف |
| -------- | ----------- |
| [new](./core/new/) | إنشاء مستند PDF جديد. |
| [open](./core/open/) | فتح مستند PDF باستخدام اسم الملف. |
| [save](./core/save/) | حفظ مستند PDF المفتوح مسبقًا. |
| [save_as](./core/save_as/) | حفظ مستند PDF المفتوح مسبقًا باسم ملف جديد. |
| [set_license](./core/set_license/) | تعيين الترخيص باستخدام اسم الملف. |
| [extract_text](./core/extract_text/) | إرجاع محتويات مستند PDF كنص عادي. |
| [word_count](./core/word_count/) | إرجاع عدد الكلمات في مستند PDF. |
| [character_count](./core/character_count/) | إرجاع عدد الأحرف في مستند PDF. |
| [append](./core/append/) | إضافة صفحات من مستند PDF آخر. |
| [append_pages](./core/append_pages/) | إضافة الصفحات المحددة من مستند PDF آخر. |
| [merge_documents](./core/merge_documents/) | إنشاء مستند PDF جديد بدمج مستندات PDF المقدمة. |
| [split_document](./core/split_document/) | إنشاء عدة مستندات PDF جديدة باستخراج صفحات من مستند PDF المصدر. |
| [split](./core/split/) | إنشاء عدة مستندات PDF جديدة باستخراج صفحات من مستند PDF الحالي. |
| [split_at_page](./core/split_at_page/) | تقسيم مستند PDF إلى مستندين PDF جديدين. |
| [split_at](./core/split_at/) | تقسيم مستند PDF الحالي إلى مستندين PDF جديدين. |
| [bytes](./core/bytes/) | إرجاع محتويات مستند PDF كمتجه بايت. |
| [get_meta_info](./core/get_meta_info/) | الحصول على قيمة معلومات التعريف لمستند PDF. |
| [set_meta_info](./core/set_meta_info/) | تعيين قيمة المعلومات الوصفية لمستند PDF. |
| [clear_meta_info](./core/clear_meta_info/) | مسح جميع قيم المعلومات الوصفية لمستند PDF. |
| [is_linearized](./core/is_linearized/) | الحصول على قيمة تشير إلى ما إذا كان المستند مُخططًا خطيًا. |
| [page_add](./core/page_add/) | إضافة صفحة جديدة إلى مستند PDF. |
| [page_insert](./core/page_insert/) | إدراج صفحة جديدة في الموضع المحدد في مستند PDF. |
| [page_delete](./core/page_delete/) | حذف الصفحة المحددة في مستند PDF. |
| [page_count](./core/page_count/) | إرجاع عدد الصفحات في مستند PDF. |
| [page_word_count](./core/page_word_count/) | إرجاع عدد الكلمات في الصفحة المحددة في مستند PDF. |
| [page_character_count](./core/page_character_count/) | إرجاع عدد الأحرف في الصفحة المحددة في مستند PDF. |
| [page_is_blank](./core/page_is_blank/) | إرجاع ما إذا كانت الصفحة فارغة في مستند PDF. |


## Security
| دالة | الوصف |
| -------- | ----------- |
| [open_with_password](./security/open_with_password/) | فتح مستند PDF محمي بكلمة مرور. |
| [encrypt](./security/encrypt/) | تشفير مستند PDF. |
| [decrypt](./security/decrypt/) | فك تشفير مستند PDF. |
| [set_permissions](./security/set_permissions/) | تعيين الأذونات لمستند PDF. |
| [get_permissions](./security/get_permissions/) | الحصول على الأذونات الحالية لمستند PDF. |
| [is_encrypted](./security/is_encrypted/) | الحصول على حالة التشفير لمستند PDF. |
| [sign_pkcs7](./security/sign_pkcs7/) | توقيع مستند PDF باستخدام توقيعات رقمية PKCS#7. |
| [sign_pkcs7_detached](./security/sign_pkcs7_detached/) | توقيع مستند PDF باستخدام توقيعات رقمية منفصلة PKCS#7. |
| [is_signed](./security/is_signed/) | الحصول على حالة التوقيع لمستند PDF. |
| [remove_signs](./security/remove_signs/) | إزالة التوقيعات من مستند PDF. |


## Miscellaneous

| دالة | الوصف |
| -------- | ----------- |
| [about](./miscellaneous/about/) | إرجاع معلومات البيانات الوصفية حول Aspose.PDF لـ Rust عبر C++. |



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
    /// مجموعة علمية تمثل قدرات أذونات PDF.
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
    /// حجم A0.
    A0 = 0,
    /// حجم A1.
    A1 = 1,
    /// حجم A2.
    A2 = 2,
    /// حجم A3.
    A3 = 3,
    /// حجم A4.
    A4 = 4,
    /// حجم A5.
    A5 = 5,
    /// حجم A6.
    A6 = 6,
    /// حجم B5.
    B5 = 7,
    /// حجم PageLetter.
    PageLetter = 8,
    /// حجم PageLegal.
    PageLegal = 9,
    /// حجم PageLedger.
    PageLedger = 10,
    /// حجم P11x17.
    P11x17 = 11,
}
```

## Enumeration of possible rotation values.
```rust
pub enum Rotation {
    /// غير مدور.
    None = 0,
    /// مدور بزاوية 90 درجة باتجاه عقارب الساعة.
    On90 = 1,
    /// مدور بزاوية 180 درجة.
    On180 = 2,
    /// مدور بزاوية 270 درجة باتجاه عقارب الساعة.
    On270 = 3,
    /// مدور بزاوية 360 درجة باتجاه عقارب الساعة.
    On360 = 4,
}
```

## An enumeration of possible crypto algorithms.
```rust
pub enum CryptoAlgorithm {
    /// RC4 بطول مفتاح 40.
    RC4x40 = 0,
    /// RC4 بطول مفتاح 128.
    RC4x128 = 1,
    /// AES بطول مفتاح 128.
    AESx128 = 2,
    /// AES بطول مفتاح 256.
    AESx256 = 3,
}
```

## An enumeration of possible PDF format standards.
```rust
pub enum PdfFormat {
    /// تنسيق PDF/A-1a.
    PDF_A_1A = 0,
    /// تنسيق PDF/A-1b.
    PDF_A_1B = 1,
    /// تنسيق PDF/A-2a.
    PDF_A_2A = 2,
    /// تنسيق PDF/A-3a.
    PDF_A_3A = 3,
    /// تنسيق PDF/A-2b.
    PDF_A_2B = 4,
    /// تنسيق PDF/A-2u.
    PDF_A_2U = 5,
    /// تنسيق PDF/A-3b.
    PDF_A_3B = 6,
    /// تنسيق PDF/A-3u.
    PDF_A_3U = 7,
    /// إصدار Adobe 1.0.
    V_1_0 = 8,
    /// إصدار Adobe 1.1.
    V_1_1 = 9,
    /// إصدار Adobe 1.2.
    V_1_2 = 10,
    /// إصدار Adobe 1.3.
    V_1_3 = 11,
    /// إصدار Adobe 1.4.
    V_1_4 = 12,
    /// إصدار Adobe 1.5.
    V_1_5 = 13,
    /// إصدار Adobe 1.6.
    V_1_6 = 14,
    /// إصدار Adobe 1.7.
    V_1_7 = 15,
    /// معيار ISO PDF 2.0.
    V_2_0 = 16,
    /// تنسيق PDF/UA-1.
    PDF_UA_1 = 17,
    /// تنسيق PDF/X-1a:2001.
    PDF_X_1A_2001 = 18,
    /// تنسيق PDF/X-1a.
    PDF_X_1A = 19,
    /// تنسيق PDF/X-3.
    PDF_X_3 = 20,
    /// تنسيق ZUGFeRD.
    ZUGFeRD = 21,
    /// تنسيق PDF/A-4.
    PDF_A_4 = 22,
    /// تنسيق PDF/A-4e.
    PDF_A_4E = 23,
    /// تنسيق PDF/A-4f.
    PDF_A_4F = 24,
    /// تنسيق PDF/X-4.
    PDF_X_4 = 25,
    /// تنسيق PDF/E-1 (PDF 1.6).
    PDF_E_1 = 26,
}
```

## An enumeration of actions to take when a conversion error occurs.
```rust
pub enum ConvertErrorAction {
    /// حذف العناصر غير المتوافقة.
    Delete = 0,
    /// لا تفعل شيئًا، احتفظ بالعناصر غير المتوافقة.
    None = 1,
}
```

