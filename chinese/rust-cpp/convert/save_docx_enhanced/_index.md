---
title: "save_docx_enhanced"
second_title: "Aspose.PDF for Rust via C++"
description: "将先前打开的 PDF-document 转换并保存为 DOCX-document，使用增强识别模式（完全可编辑的表格和段落）。"
type: docs
url: /zh/rust-cpp/convert/save_docx_enhanced/
---

_将先前打开的 PDF-document 转换并保存为 DOCX-document，使用增强识别模式（完全可编辑的表格和段落）。_

```rust
pub fn save_docx_enhanced(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 转换并保存先前打开的 PDF-document 为 DocX-document，使用增强识别模式（完全可编辑的表格和段落）
    pdf.save_docx_enhanced("sample_enhanced.docx")?;

    Ok(())
}

```