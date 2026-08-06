---
title: "page_add_text_header"
second_title: "Aspose.PDF for Rust via C++"
description: "在页面标题中添加文本。"
type: docs
url: /zh/rust-cpp/organize/page_add_text_header/
---

_在页面标题中添加文本._

```rust
pub fn page_add_text_header(&self, num: i32, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开具有文件名的 PDF 文档
    let pdf = Document::open("sample.pdf")?;

    // 在页面页眉中添加文本
    pdf.page_add_text_header(1, "HEADER")?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_page1_add_text_header.pdf")?;

    Ok(())
}

```