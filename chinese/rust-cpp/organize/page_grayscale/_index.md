---
title: "page_grayscale"
second_title: "Aspose.PDF for Rust via C++"
description: "将页面转换为黑白。"
type: docs
url: /zh/rust-cpp/organize/page_grayscale/
---

_将页面转换为黑白。_

```rust
pub fn page_grayscale(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 从文件打开 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 将页面转换为黑白
    pdf.page_grayscale(1)?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_page1_grayscale.pdf")?;

    Ok(())
}

```