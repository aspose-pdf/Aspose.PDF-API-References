---
title: "Aspose.PDF for Rust via C++"
description: "Aspose.PDF for Rust via C++"
keywords:  "Rust, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /zh/rust-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Rust via C++ allows developers manipulate them PDF files directly in the Rust.

# 结构体

## Document
Document 表示一个 PDF 文档。

```rust
pub struct Document { /* private fields */ }
```

# Implementations

## Convert from PDF functions

| 函数 | 描述 |
| -------- | ----------- |
| [save_docx](./convert/save_docx/) | 将先前打开的 PDF 文档转换并保存为 DocX 文档。 |
| [save_doc](./convert/save_doc/) | 将先前打开的 PDF 文档转换并保存为 Doc 文档。 |
| [save_xlsx](./convert/save_xlsx/) | 将先前打开的 PDF 文档转换并保存为 XlsX 文档。 |
| [save_txt](./convert/save_txt/) | 将先前打开的 PDF 文档转换并保存为 Txt 文档。 |
| [save_pptx](./convert/save_pptx/) | 将先前打开的 PDF 文档转换并保存为 PptX 文档。 |
| [save_xps](./convert/save_xps/) | 将先前打开的 PDF 文档转换并保存为 Xps 文档。 |
| [save_tex](./convert/save_tex/) | 将先前打开的 PDF 文档转换并保存为 TeX 文档。 |
| [save_epub](./convert/save_epub/) | 将先前打开的 PDF 文档转换并保存为 Epub 文档。 |
| [save_booklet](./convert/save_booklet/) | 将先前打开的 PDF 文档转换并保存为小册子 PDF 文档。 |
| [save_n_up](./convert/save_n_up/) | 将先前打开的 PDF 文档转换并保存为 N-Up PDF 文档。 |
| [save_markdown](./convert/save_markdown/) | 将先前打开的 PDF 文档转换并保存为 Markdown 文档。 |
| [save_tiff](./convert/save_tiff/) | 将先前打开的 PDF 文档转换并保存为 Tiff 文档。 |
| [save_docx_enhanced](./convert/save_docx_enhanced/) | 将先前打开的 PDF 文档转换并保存为 DocX 文档，使用增强识别模式（完全可编辑的表格和段落）。 |
| [save_svg_zip](./convert/save_svg_zip/) | 将先前打开的 PDF 文档转换并保存为 SVG 档案。 |
| [export_fdf](./convert/export_fdf/) | 从先前打开的带有 AcroForm 的 PDF 文档导出为 FDF 文档。 |
| [export_xfdf](./convert/export_xfdf/) | 从先前打开的带有 AcroForm 的 PDF 文档导出为 XFDF 文档。 |
| [export_xml](./convert/export_xml/) | 从先前打开的带有 AcroForm 的 PDF 文档导出为 XML 文档。 |
| [page_to_jpg](./convert/page_to_jpg/) | 将指定页面转换并保存为 Jpg 图像。 |
| [page_to_png](./convert/page_to_png/) | 将指定页面转换并保存为 Png 图像。 |
| [page_to_bmp](./convert/page_to_bmp/) | 将指定页面转换并保存为 Bmp 图像。 |
| [page_to_tiff](./convert/page_to_tiff/) | 将指定页面转换并保存为 Tiff-图像。 |
| [page_to_svg](./convert/page_to_svg/) | 将指定页面转换并保存为 Svg-图像。 |
| [page_to_pdf](./convert/page_to_pdf/) | 将指定页面转换并保存为 PDF-文档。 |
| [page_to_dicom](./convert/page_to_dicom/) | 将指定页面转换并保存为 DICOM-图像。 |


## Organize PDF functions

| 函数 | 描述 |
| -------- | ----------- |
| [optimize](./organize/optimize/) | 优化 PDF-文档的内容。 |
| [optimize_resource](./organize/optimize_resource/) | 优化 PDF-文档的资源。 |
| [grayscale](./organize/grayscale/) | 将 PDF-文档 转换为黑白。 |
| [rotate](./organize/rotate/) | 旋转 PDF-文档。 |
| [set_background](./organize/set_background/) | 使用 RGB 值设置 PDF-文档 的背景颜色。 |
| [repair](./organize/repair/) | 修复 PDF-文档。 |
| [replace_text](./organize/replace_text/) | 替换 PDF-文档 中的文本 |
| [add_page_num](./organize/add_page_num/) | 向 PDF-文档 添加页码 |
| [add_text_header](./organize/add_text_header/) | 在 PDF-文档 的页眉中添加文本 |
| [add_text_footer](./organize/add_text_footer/) | 在 PDF-文档 的页脚中添加文本 |
| [flatten](./organize/flatten/) | 扁平化 PDF-文档 |
| [remove_annotations](./organize/remove_annotations/) | 删除 PDF-文档 中的批注 |
| [remove_attachments](./organize/remove_attachments/) | 删除 PDF-文档 中的附件 |
| [remove_blank_pages](./organize/remove_blank_pages/) | 删除 PDF-文档 中的空白页 |
| [remove_bookmarks](./organize/remove_bookmarks/) | 删除 PDF-文档 中的书签 |
| [remove_hidden_text](./organize/remove_hidden_text/) | 删除 PDF-文档 中的隐藏文本 |
| [remove_images](./organize/remove_images/) | 删除 PDF-文档 中的图像 |
| [remove_javascripts](./organize/remove_javascripts/) | 删除 PDF-文档 中的 Java 脚本 |
| [remove_tables](./organize/remove_tables/) | 删除 PDF-文档 中的表格。 |
| [remove_watermarks](./organize/remove_watermarks/) | 删除 PDF-文档 中的水印。 |
| [add_watermark](./organize/add_watermark/) | 向 PDF-文档 添加水印。 |
| [embed_fonts](./organize/embed_fonts/) | 在 PDF 文档中嵌入字体。 |
| [unembed_fonts](./organize/unembed_fonts/) | 在 PDF 文档中取消嵌入字体。 |
| [optimize_file_size](./organize/optimize_file_size/) | 通过图像压缩质量优化 PDF 文档的大小。 |
| [remove_text_headers](./organize/remove_text_headers/) | 从 PDF 文档中移除文本页眉。 |
| [remove_text_footers](./organize/remove_text_footers/) | 从 PDF 文档中移除文本页脚。 |
| [crop](./organize/crop/) | 裁剪 PDF 文档的页面。 |
| [replace_font](./organize/replace_font/) | 在 PDF 文档中替换字体。 |
| [convert](./organize/convert/) | 将 PDF 文档转换为具有指定 PDF 格式的 PDF 文档 |
| [validate](./organize/validate/) | 验证 PDF 文档是否符合 PDF 格式的规范 |
| [remove_pdfa_compliance](./organize/remove_pdfa_compliance/) | 从 PDF 文档中移除 PDF/A 合规性 |
| [remove_pdfua_compliance](./organize/remove_pdfua_compliance/) | 从 PDF 文档中移除 PDF/UA 合规性 |
| [is_pdfa_compliant](./organize/is_pdfa_compliant/) | 获取 PDF 文档是否符合 PDF/A 标准 |
| [is_pdfua_compliant](./organize/is_pdfua_compliant/) | 获取 PDF 文档是否符合 PDF/UA 标准 |
| [page_rotate](./organize/page_rotate/) | 旋转 PDF 文档中的页面。 |
| [page_set_size](./organize/page_set_size/) | 设置 PDF 文档中页面的大小。 |
| [page_grayscale](./organize/page_grayscale/) | 将页面转换为黑白。 |
| [page_add_text](./organize/page_add_text/) | 在页面上添加文本。 |
| [page_replace_text](./organize/page_replace_text/) | 在页面上替换文本 |
| [page_add_page_num](./organize/page_add_page_num/) | 在页面上添加页码 |
| [page_add_text_header](./organize/page_add_text_header/) | 在页面页眉中添加文本 |
| [page_add_text_footer](./organize/page_add_text_footer/) | 在页面页脚中添加文本 |
| [page_remove_annotations](./organize/page_remove_annotations/) | 移除页面中的批注。 |
| [page_remove_hidden_text](./organize/page_remove_hidden_text/) | 移除页面中的隐藏文本。 |
| [page_remove_images](./organize/page_remove_images/) | 移除页面中的图像。 |
| [page_remove_tables](./organize/page_remove_tables/) | 移除页面中的表格。 |
| [page_remove_watermarks](./organize/page_remove_watermarks/) | 删除页面中的水印。 |
| [page_add_watermark](./organize/page_add_watermark/) | 在页面上添加水印。 |
| [page_remove_text_headers](./organize/page_remove_text_headers/) | 删除页面中的文本页眉。 |
| [page_remove_text_footers](./organize/page_remove_text_footers/) | 删除页面中的文本页脚。 |
| [page_crop](./organize/page_crop/) | 裁剪页面。 |
| [page_replace_font](./organize/page_replace_font/) | 替换页面中的字体。 |
| [page_merge_layers](./organize/page_merge_layers/) | 将页面上的所有图层合并为单个图层，并使用指定的新图层名称。 |
| [page_layers](./organize/page_layers/) | 获取页面上图层的名称。 |


## Core PDF functions

| 函数 | 描述 |
| -------- | ----------- |
| [new](./core/new/) | 创建一个新的 PDF 文档。 |
| [open](./core/open/) | 使用文件名打开 PDF 文档。 |
| [save](./core/save/) | 保存先前打开的 PDF 文档。 |
| [save_as](./core/save_as/) | 使用新文件名保存先前打开的 PDF 文档。 |
| [set_license](./core/set_license/) | 使用文件名设置许可证。 |
| [extract_text](./core/extract_text/) | 以纯文本返回 PDF 文档的内容。 |
| [word_count](./core/word_count/) | 返回 PDF 文档中的单词计数。 |
| [character_count](./core/character_count/) | 返回 PDF 文档中的字符计数。 |
| [append](./core/append/) | 追加来自另一个 PDF 文档的页面。 |
| [append_pages](./core/append_pages/) | 追加来自另一个 PDF 文档的选定页面。 |
| [merge_documents](./core/merge_documents/) | 通过合并提供的 PDF 文档创建一个新的 PDF 文档。 |
| [split_document](./core/split_document/) | 通过从源 PDF 文档中提取页面创建多个新的 PDF 文档。 |
| [split](./core/split/) | 通过从当前 PDF 文档中提取页面创建多个新的 PDF 文档。 |
| [split_at_page](./core/split_at_page/) | 将 PDF 文档拆分为两个新的 PDF 文档。 |
| [split_at](./core/split_at/) | 将当前 PDF 文档拆分为两个新的 PDF 文档。 |
| [bytes](./core/bytes/) | 以字节向量返回 PDF 文档的内容。 |
| [get_meta_info](./core/get_meta_info/) | 获取 PDF 文档的元信息值。 |
| [set_meta_info](./core/set_meta_info/) | 设置 PDF-document 的元信息值。 |
| [clear_meta_info](./core/clear_meta_info/) | 清除 PDF-document 的所有元信息值。 |
| [is_linearized](./core/is_linearized/) | 获取指示文档是否已线性化的值。 |
| [page_add](./core/page_add/) | 在 PDF-document 中添加新页面。 |
| [page_insert](./core/page_insert/) | 在 PDF-document 中的指定位置插入新页面。 |
| [page_delete](./core/page_delete/) | 删除 PDF-document 中指定的页面。 |
| [page_count](./core/page_count/) | 返回 PDF-document 的页数。 |
| [page_word_count](./core/page_word_count/) | 返回 PDF-document 中指定页面的单词计数。 |
| [page_character_count](./core/page_character_count/) | 返回 PDF-document 中指定页面的字符计数。 |
| [page_is_blank](./core/page_is_blank/) | 返回 PDF-document 中页面是否为空白。 |


## Security
| 函数 | 描述 |
| -------- | ----------- |
| [open_with_password](./security/open_with_password/) | 打开受密码保护的 PDF-document。 |
| [encrypt](./security/encrypt/) | 加密 PDF-document。 |
| [decrypt](./security/decrypt/) | 解密 PDF-document。 |
| [set_permissions](./security/set_permissions/) | 设置 PDF-document 的权限。 |
| [get_permissions](./security/get_permissions/) | 获取 PDF-document 的当前权限。 |
| [is_encrypted](./security/is_encrypted/) | 获取 PDF-document 的加密状态。 |
| [sign_pkcs7](./security/sign_pkcs7/) | 使用 PKCS#7 数字签名对 PDF-document 进行签名。 |
| [sign_pkcs7_detached](./security/sign_pkcs7_detached/) | 使用 PKCS#7 分离式数字签名对 PDF-document 进行签名。 |
| [is_signed](./security/is_signed/) | 获取 PDF-document 的签名状态。 |
| [remove_signs](./security/remove_signs/) | 从 PDF-document 中移除签名。 |


## Miscellaneous

| 函数 | 描述 |
| -------- | ----------- |
| [about](./miscellaneous/about/) | 返回关于通过 C++ 使用的 Aspose.PDF for Rust 的元数据信息。 |



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
    /// 表示 PDF 权限功能的位标志集合。
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
    /// A0 尺寸。
    A0 = 0,
    /// A1 尺寸。
    A1 = 1,
    /// A2 尺寸。
    A2 = 2,
    /// A3 尺寸。
    A3 = 3,
    /// A4 尺寸。
    A4 = 4,
    /// A5 尺寸。
    A5 = 5,
    /// A6 尺寸。
    A6 = 6,
    /// B5 尺寸。
    B5 = 7,
    /// PageLetter 尺寸。
    PageLetter = 8,
    /// PageLegal 尺寸。
    PageLegal = 9,
    /// PageLedger 尺寸。
    PageLedger = 10,
    /// P11x17 尺寸。
    P11x17 = 11,
}
```

## Enumeration of possible rotation values.
```rust
pub enum Rotation {
    /// 未旋转。
    None = 0,
    /// 顺时针旋转 90 度。
    On90 = 1,
    /// 旋转 180 度。
    On180 = 2,
    /// 顺时针旋转 270 度。
    On270 = 3,
    /// 顺时针旋转 360 度。
    On360 = 4,
}
```

## An enumeration of possible crypto algorithms.
```rust
pub enum CryptoAlgorithm {
    /// RC4，密钥长度为 40。
    RC4x40 = 0,
    /// RC4，密钥长度为 128。
    RC4x128 = 1,
    /// AES，密钥长度为 128。
    AESx128 = 2,
    /// AES，密钥长度为 256。
    AESx256 = 3,
}
```

## An enumeration of possible PDF format standards.
```rust
pub enum PdfFormat {
    /// PDF/A-1a 格式。
    PDF_A_1A = 0,
    /// PDF/A-1b 格式。
    PDF_A_1B = 1,
    /// PDF/A-2a 格式。
    PDF_A_2A = 2,
    /// PDF/A-3a 格式。
    PDF_A_3A = 3,
    /// PDF/A-2b 格式。
    PDF_A_2B = 4,
    /// PDF/A-2u 格式。
    PDF_A_2U = 5,
    /// PDF/A-3b 格式。
    PDF_A_3B = 6,
    /// PDF/A-3u 格式.
    PDF_A_3U = 7,
    /// Adobe 版本 1.0.
    V_1_0 = 8,
    /// Adobe 版本 1.1.
    V_1_1 = 9,
    /// Adobe 版本 1.2.
    V_1_2 = 10,
    /// Adobe 版本 1.3.
    V_1_3 = 11,
    /// Adobe 版本 1.4.
    V_1_4 = 12,
    /// Adobe 版本 1.5.
    V_1_5 = 13,
    /// Adobe 版本 1.6.
    V_1_6 = 14,
    /// Adobe 版本 1.7.
    V_1_7 = 15,
    /// ISO 标准 PDF 2.0.
    V_2_0 = 16,
    /// PDF/UA-1 格式.
    PDF_UA_1 = 17,
    /// PDF/X-1a:2001 格式.
    PDF_X_1A_2001 = 18,
    /// PDF/X-1a 格式.
    PDF_X_1A = 19,
    /// PDF/X-3 格式.
    PDF_X_3 = 20,
    /// ZUGFeRD 格式.
    ZUGFeRD = 21,
    /// PDF/A-4 格式.
    PDF_A_4 = 22,
    /// PDF/A-4e 格式.
    PDF_A_4E = 23,
    /// PDF/A-4f 格式.
    PDF_A_4F = 24,
    /// PDF/X-4 格式.
    PDF_X_4 = 25,
    /// PDF/E-1 (PDF 1.6) 格式.
    PDF_E_1 = 26,
}
```

## An enumeration of actions to take when a conversion error occurs.
```rust
pub enum ConvertErrorAction {
    /// 删除不符合规范的元素.
    Delete = 0,
    /// 不执行任何操作，保留不符合规范的元素.
    None = 1,
}
```

