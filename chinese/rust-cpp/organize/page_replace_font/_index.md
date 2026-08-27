---
title: "page_replace_font"
second_title: "Aspose.PDF for Rust via C++"
description: "替换页面中的字体。"
type: docs
url: /zh/rust-cpp/organize/page_replace_font/
---

_替换页面中的字体._

```rust
pub fn page_replace_font(&self, num: i32, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // 替换页面中的字体
    pdf.page_replace_font(1, "Times-BoldItalic", "Helvetica-Bold")?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_page1_replace_font.pdf")?;

    Ok(())
}

```