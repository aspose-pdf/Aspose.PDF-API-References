---
title: "page_delete"
second_title: "Aspose.PDF for Rust via C++"
description: "从 PDF-document 中删除指定的页面。"
type: docs
url: /zh/rust-cpp/core/page_delete/
---

_从 PDF-document 中删除指定的页面._

```rust
pub fn page_delete(&self, num: i32) -> Result<(), PdfError>
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

    // 删除 PDF-document 中指定的页面
    pdf.page_delete(1)?;

    // 保存先前打开的 PDF-document
    pdf.save()?;

    Ok(())
}

```