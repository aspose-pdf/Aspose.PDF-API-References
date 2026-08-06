---
title: "page_add_text"
second_title: "Aspose.PDF for Rust via C++"
description: "向页面添加文本。"
type: docs
url: /zh/rust-cpp/organize/page_add_text/
---

_向页面添加文本._

```rust
pub fn page_add_text(&self, num: i32, add_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **add_text** - the text to add

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 从文件打开 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 在页面上添加文本
    pdf.page_add_text(1, "added text")?;

    // 保存先前打开的 PDF-document
    pdf.save()?;

    Ok(())
}

```