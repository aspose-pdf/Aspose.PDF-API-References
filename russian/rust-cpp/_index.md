---
title: "Aspose.PDF для Rust через C++"
description: "Aspose.PDF для Rust через C++"
keywords:  "Rust, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /ru/rust-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Rust via C++ allows developers manipulate them PDF files directly in the Rust.

# Структуры

## Document
Document представляет PDF‑документ.

```rust
pub struct Document { /* private fields */ }
```

# Implementations

## Convert from PDF functions

| Функция | Описание |
| -------- | ----------- |
| [save_docx](./convert/save_docx/) | Конвертировать и сохранить ранее открытый PDF‑документ как документ DocX. |
| [save_doc](./convert/save_doc/) | Конвертировать и сохранить ранее открытый PDF‑документ как документ Doc. |
| [save_xlsx](./convert/save_xlsx/) | Конвертировать и сохранить ранее открытый PDF‑документ как документ XlsX. |
| [save_txt](./convert/save_txt/) | Конвертировать и сохранить ранее открытый PDF‑документ как документ Txt. |
| [save_pptx](./convert/save_pptx/) | Конвертировать и сохранить ранее открытый PDF‑документ как документ PptX. |
| [save_xps](./convert/save_xps/) | Конвертировать и сохранить ранее открытый PDF‑документ как документ Xps. |
| [save_tex](./convert/save_tex/) | Конвертировать и сохранить ранее открытый PDF‑документ как документ TeX. |
| [save_epub](./convert/save_epub/) | Конвертировать и сохранить ранее открытый PDF‑документ как документ Epub. |
| [save_booklet](./convert/save_booklet/) | Конвертировать и сохранить ранее открытый PDF‑документ в виде буклетного PDF‑документа. |
| [save_n_up](./convert/save_n_up/) | Конвертировать и сохранить ранее открытый PDF‑документ как N‑Up PDF‑документ. |
| [save_markdown](./convert/save_markdown/) | Конвертировать и сохранить ранее открытый PDF‑документ как документ Markdown. |
| [save_tiff](./convert/save_tiff/) | Конвертировать и сохранить ранее открытый PDF‑документ как документ Tiff. |
| [save_docx_enhanced](./convert/save_docx_enhanced/) | Конвертировать и сохранить ранее открытый PDF‑документ как документ DocX с расширенным режимом распознавания (полностью редактируемые таблицы и абзацы). |
| [save_svg_zip](./convert/save_svg_zip/) | Конвертировать и сохранить ранее открытый PDF‑документ как SVG‑архив. |
| [export_fdf](./convert/export_fdf/) | Экспортировать из ранее открытого PDF‑документа с AcroForm в документ FDF. |
| [export_xfdf](./convert/export_xfdf/) | Экспортировать из ранее открытого PDF‑документа с AcroForm в документ XFDF. |
| [export_xml](./convert/export_xml/) | Экспортировать из ранее открытого PDF‑документа с AcroForm в документ XML. |
| [page_to_jpg](./convert/page_to_jpg/) | Конвертировать и сохранить указанную страницу как изображение Jpg. |
| [page_to_png](./convert/page_to_png/) | Конвертировать и сохранить указанную страницу как изображение Png. |
| [page_to_bmp](./convert/page_to_bmp/) | Конвертировать и сохранить указанную страницу как изображение Bmp. |
| [page_to_tiff](./convert/page_to_tiff/) | Преобразовать и сохранить указанную страницу как Tiff-изображение. |
| [page_to_svg](./convert/page_to_svg/) | Преобразовать и сохранить указанную страницу как Svg-изображение. |
| [page_to_pdf](./convert/page_to_pdf/) | Преобразовать и сохранить указанную страницу как PDF-документ. |
| [page_to_dicom](./convert/page_to_dicom/) | Преобразовать и сохранить указанную страницу как DICOM-изображение. |


## Organize PDF functions

| Функция | Описание |
| -------- | ----------- |
| [optimize](./organize/optimize/) | Оптимизировать содержимое PDF-документа. |
| [optimize_resource](./organize/optimize_resource/) | Оптимизировать ресурсы PDF-документа. |
| [grayscale](./organize/grayscale/) | Преобразовать PDF-документ в черно-белый. |
| [rotate](./organize/rotate/) | Повернуть PDF-документ. |
| [set_background](./organize/set_background/) | Установить цвет фона PDF-документа с использованием значений RGB. |
| [repair](./organize/repair/) | Восстановить PDF-документ. |
| [replace_text](./organize/replace_text/) | Заменить текст в PDF-документе |
| [add_page_num](./organize/add_page_num/) | Добавить номер страницы в PDF-документ |
| [add_text_header](./organize/add_text_header/) | Добавить текст в заголовок PDF-документа |
| [add_text_footer](./organize/add_text_footer/) | Добавить текст в нижний колонтитул PDF-документа |
| [flatten](./organize/flatten/) | Свести PDF-документ |
| [remove_annotations](./organize/remove_annotations/) | Удалить аннотации из PDF-документа |
| [remove_attachments](./organize/remove_attachments/) | Удалить вложения из PDF-документа |
| [remove_blank_pages](./organize/remove_blank_pages/) | Удалить пустые страницы из PDF-документа |
| [remove_bookmarks](./organize/remove_bookmarks/) | Удалить закладки из PDF-документа |
| [remove_hidden_text](./organize/remove_hidden_text/) | Удалить скрытый текст из PDF-документа |
| [remove_images](./organize/remove_images/) | Удалить изображения из PDF-документа |
| [remove_javascripts](./organize/remove_javascripts/) | Удалить JavaScript из PDF-документа |
| [remove_tables](./organize/remove_tables/) | Удалить таблицы из PDF-документа. |
| [remove_watermarks](./organize/remove_watermarks/) | Удалить водяные знаки из PDF-документа. |
| [add_watermark](./organize/add_watermark/) | Добавить водяной знак в PDF-документ. |
| [embed_fonts](./organize/embed_fonts/) | Встроить шрифты в PDF-документ. |
| [unembed_fonts](./organize/unembed_fonts/) | Удалить встроенные шрифты из PDF-документа. |
| [optimize_file_size](./organize/optimize_file_size/) | Оптимизировать размер PDF-документа с качеством сжатия изображений. |
| [remove_text_headers](./organize/remove_text_headers/) | Удалить текстовые заголовки из PDF-документа. |
| [remove_text_footers](./organize/remove_text_footers/) | Удалить текстовые колонтитулы из PDF-документа. |
| [crop](./organize/crop/) | Обрезать страницы PDF-документа. |
| [replace_font](./organize/replace_font/) | Заменить шрифт в PDF-документе. |
| [convert](./organize/convert/) | Конвертировать PDF-документ в PDF-документ с указанным форматом PDF |
| [validate](./organize/validate/) | Проверить PDF-документ на соответствие формату PDF |
| [remove_pdfa_compliance](./organize/remove_pdfa_compliance/) | Удалить соответствие PDF/A из PDF-документа |
| [remove_pdfua_compliance](./organize/remove_pdfua_compliance/) | Удалить соответствие PDF/UA из PDF-документа |
| [is_pdfa_compliant](./organize/is_pdfa_compliant/) | Получить, является ли PDF-документ соответствующим PDF/A |
| [is_pdfua_compliant](./organize/is_pdfua_compliant/) | Получить, является ли PDF-документ соответствующим PDF/UA |
| [page_rotate](./organize/page_rotate/) | Повернуть страницу в PDF-документе. |
| [page_set_size](./organize/page_set_size/) | Установить размер страницы в PDF-документе. |
| [page_grayscale](./organize/page_grayscale/) | Конвертировать страницу в черно-белый режим. |
| [page_add_text](./organize/page_add_text/) | Добавить текст на страницу. |
| [page_replace_text](./organize/page_replace_text/) | Заменить текст на странице |
| [page_add_page_num](./organize/page_add_page_num/) | Добавить номер страницы на страницу |
| [page_add_text_header](./organize/page_add_text_header/) | Добавить текст в заголовок страницы. |
| [page_add_text_footer](./organize/page_add_text_footer/) | Добавить текст в нижний колонтитул страницы. |
| [page_remove_annotations](./organize/page_remove_annotations/) | Удалить аннотации на странице. |
| [page_remove_hidden_text](./organize/page_remove_hidden_text/) | Удалить скрытый текст на странице. |
| [page_remove_images](./organize/page_remove_images/) | Удалить изображения на странице. |
| [page_remove_tables](./organize/page_remove_tables/) | Удалить таблицы на странице. |
| [page_remove_watermarks](./organize/page_remove_watermarks/) | Удалить водяные знаки на странице. |
| [page_add_watermark](./organize/page_add_watermark/) | Добавить водяной знак на страницу. |
| [page_remove_text_headers](./organize/page_remove_text_headers/) | Удалить текстовые заголовки на странице. |
| [page_remove_text_footers](./organize/page_remove_text_footers/) | Удалить текстовые колонтитулы на странице. |
| [page_crop](./organize/page_crop/) | Обрезать страницу. |
| [page_replace_font](./organize/page_replace_font/) | Заменить шрифт на странице. |
| [page_merge_layers](./organize/page_merge_layers/) | Объединить все слои на странице в один слой с указанным новым именем слоя. |
| [page_layers](./organize/page_layers/) | Получить имена слоёв на странице. |


## Core PDF functions

| Функция | Описание |
| -------- | ----------- |
| [new](./core/new/) | Создать новый PDF-документ. |
| [open](./core/open/) | Открыть PDF-документ с именем файла. |
| [save](./core/save/) | Сохранить ранее открытый PDF-документ. |
| [save_as](./core/save_as/) | Сохранить ранее открытый PDF-документ с новым именем файла. |
| [set_license](./core/set_license/) | Установить лицензию с именем файла. |
| [extract_text](./core/extract_text/) | Вернуть содержимое PDF-документа в виде простого текста. |
| [word_count](./core/word_count/) | Вернуть количество слов в PDF-документе. |
| [character_count](./core/character_count/) | Вернуть количество символов в PDF-документе. |
| [append](./core/append/) | Добавить страницы из другого PDF-документа. |
| [append_pages](./core/append_pages/) | Добавить выбранные страницы из другого PDF-документа. |
| [merge_documents](./core/merge_documents/) | Создать новый PDF-документ, объединив предоставленные PDF-документы. |
| [split_document](./core/split_document/) | Создать несколько новых PDF-документов, извлекая страницы из исходного PDF-документа. |
| [split](./core/split/) | Создать несколько новых PDF-документов, извлекая страницы из текущего PDF-документа. |
| [split_at_page](./core/split_at_page/) | Разделить PDF-документ на два новых PDF-документа. |
| [split_at](./core/split_at/) | Разделить текущий PDF-документ на два новых PDF-документа. |
| [bytes](./core/bytes/) | Вернуть содержимое PDF-документа в виде вектора байтов. |
| [get_meta_info](./core/get_meta_info/) | Получить значение мета-информации PDF-документа. |
| [set_meta_info](./core/set_meta_info/) | Установить значение метаинформации PDF-документа. |
| [clear_meta_info](./core/clear_meta_info/) | Очистить все значения метаинформации PDF-документа. |
| [is_linearized](./core/is_linearized/) | Получить значение, указывающее, линейризирован ли документ. |
| [page_add](./core/page_add/) | Добавить новую страницу в PDF-документ. |
| [page_insert](./core/page_insert/) | Вставить новую страницу в указанную позицию в PDF-документе. |
| [page_delete](./core/page_delete/) | Удалить указанную страницу в PDF-документе. |
| [page_count](./core/page_count/) | Вернуть количество страниц в PDF-документе. |
| [page_word_count](./core/page_word_count/) | Вернуть количество слов на указанной странице в PDF-документе. |
| [page_character_count](./core/page_character_count/) | Вернуть количество символов на указанной странице в PDF-документе. |
| [page_is_blank](./core/page_is_blank/) | Вернуть, является ли страница пустой в PDF-документе. |


## Security
| Функция | Описание |
| -------- | ----------- |
| [open_with_password](./security/open_with_password/) | Открыть защищённый паролем PDF-документ. |
| [encrypt](./security/encrypt/) | Зашифровать PDF-документ. |
| [decrypt](./security/decrypt/) | Расшифровать PDF-документ. |
| [set_permissions](./security/set_permissions/) | Установить разрешения для PDF-документа. |
| [get_permissions](./security/get_permissions/) | Получить текущие разрешения PDF-документа. |
| [is_encrypted](./security/is_encrypted/) | Получить статус шифрования PDF-документа. |
| [sign_pkcs7](./security/sign_pkcs7/) | Подписать PDF-документ с использованием цифровых подписей PKCS#7. |
| [sign_pkcs7_detached](./security/sign_pkcs7_detached/) | Подписать PDF-документ с использованием откреплённых цифровых подписей PKCS#7. |
| [is_signed](./security/is_signed/) | Получить статус подписания PDF-документа. |
| [remove_signs](./security/remove_signs/) | Удалить подписи из PDF-документа. |


## Miscellaneous

| Функция | Описание |
| -------- | ----------- |
| [about](./miscellaneous/about/) | Вернуть информацию о метаданных Aspose.PDF for Rust через C++. |



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
    /// Набор битовых флагов, представляющих возможности разрешений PDF.
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
    /// Размер A0.
    A0 = 0,
    /// Размер A1.
    A1 = 1,
    /// Размер A2.
    A2 = 2,
    /// размер A3.
    A3 = 3,
    /// размер A4.
    A4 = 4,
    /// размер A5.
    A5 = 5,
    /// размер A6.
    A6 = 6,
    /// размер B5.
    B5 = 7,
    /// размер PageLetter.
    PageLetter = 8,
    /// размер PageLegal.
    PageLegal = 9,
    /// размер PageLedger.
    PageLedger = 10,
    /// размер P11x17.
    P11x17 = 11,
}
```

## Enumeration of possible rotation values.
```rust
pub enum Rotation {
    /// Без поворота.
    None = 0,
    /// Повернут на 90 градусов по часовой стрелке.
    On90 = 1,
    /// Повернут на 180 градусов.
    On180 = 2,
    /// Повернут на 270 градусов по часовой стрелке.
    On270 = 3,
    /// Повернут на 360 градусов по часовой стрелке.
    On360 = 4,
}
```

## An enumeration of possible crypto algorithms.
```rust
pub enum CryptoAlgorithm {
    /// RC4 с длиной ключа 40.
    RC4x40 = 0,
    /// RC4 с длиной ключа 128.
    RC4x128 = 1,
    /// AES с длиной ключа 128.
    AESx128 = 2,
    /// AES с длиной ключа 256.
    AESx256 = 3,
}
```

## An enumeration of possible PDF format standards.
```rust
pub enum PdfFormat {
    /// формат PDF/A-1a.
    PDF_A_1A = 0,
    /// формат PDF/A-1b.
    PDF_A_1B = 1,
    /// формат PDF/A-2a.
    PDF_A_2A = 2,
    /// формат PDF/A-3a.
    PDF_A_3A = 3,
    /// формат PDF/A-2b.
    PDF_A_2B = 4,
    /// формат PDF/A-2u.
    PDF_A_2U = 5,
    /// формат PDF/A-3b.
    PDF_A_3B = 6,
    /// формат PDF/A-3u.
    PDF_A_3U = 7,
    /// версия Adobe 1.0.
    V_1_0 = 8,
    /// версия Adobe 1.1.
    V_1_1 = 9,
    /// версия Adobe 1.2.
    V_1_2 = 10,
    /// версия Adobe 1.3.
    V_1_3 = 11,
    /// версия Adobe 1.4.
    V_1_4 = 12,
    /// версия Adobe 1.5.
    V_1_5 = 13,
    /// версия Adobe 1.6.
    V_1_6 = 14,
    /// версия Adobe 1.7.
    V_1_7 = 15,
    /// ISO Стандарт PDF 2.0.
    V_2_0 = 16,
    /// формат PDF/UA-1.
    PDF_UA_1 = 17,
    /// формат PDF/X-1a:2001.
    PDF_X_1A_2001 = 18,
    /// формат PDF/X-1a.
    PDF_X_1A = 19,
    /// формат PDF/X-3.
    PDF_X_3 = 20,
    /// формат ZUGFeRD.
    ZUGFeRD = 21,
    /// формат PDF/A-4.
    PDF_A_4 = 22,
    /// формат PDF/A-4e.
    PDF_A_4E = 23,
    /// формат PDF/A-4f.
    PDF_A_4F = 24,
    /// формат PDF/X-4.
    PDF_X_4 = 25,
    /// формат PDF/E-1 (PDF 1.6).
    PDF_E_1 = 26,
}
```

## An enumeration of actions to take when a conversion error occurs.
```rust
pub enum ConvertErrorAction {
    /// Удалить несоответствующие элементы.
    Delete = 0,
    /// Ничего не делать, сохранять несоответствующие элементы.
    None = 1,
}
```

