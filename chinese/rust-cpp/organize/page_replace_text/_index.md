---
title: "page_replace_text"
second_title: "Aspose.PDF for Rust via C++"
description: "替换页面上的文本。"
type: docs
url: /zh/rust-cpp/organize/page_replace_text/
---

_替换页面上的文本。_

```rust
pub fn page_replace_text(&self, num: i32, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 在页面上替换文本
    pdf.page_replace_text(1, "PDF", "TXT")?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_page1_replace_text.pdf")?;

    Ok(())
}

```