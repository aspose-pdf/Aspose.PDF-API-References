---
title: "page_to_pdf"
second_title: "Aspose.PDF for Rust via C++"
description: "将指定页面转换并保存为 PDF-document。"
type: docs
url: /zh/rust-cpp/convert/page_to_pdf/
---

_将指定页面转换并保存为 PDF-document。_

```rust
pub fn page_to_pdf(&self, num: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // 转换并保存指定页面为 PDF-document
    pdf.page_to_pdf(1, "sample_page1.pdf")?;

    Ok(())
}

```