---
title: "replace_font"
second_title: "Aspose.PDF for Rust via C++"
description: "在 PDF-document 中替换字体。"
type: docs
url: /zh/rust-cpp/organize/replace_font/
---

_在 PDF-document 中替换字体._

```rust
pub fn replace_font(&self, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 在 PDF 文档中替换字体。
    pdf.replace_font("Helvetica", "Courier")?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_replace_font.pdf")?;

    Ok(())
}

```