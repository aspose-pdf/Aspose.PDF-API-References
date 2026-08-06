---
title: "page_count"
second_title: "Aspose.PDF for Rust via C++"
description: "返回 PDF 文档的页数。"
type: docs
url: /zh/rust-cpp/core/page_count/
---

_返回 PDF 文档的页数。_

```rust
pub fn page_count(&self) -> Result<i32, PdfError>
```

**Arguments**


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 从文件打开 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 返回 PDF 文档的页数
    let count = pdf.page_count()?;

    // 打印页数
    println!("Count: {}", count);

    Ok(())
}

```