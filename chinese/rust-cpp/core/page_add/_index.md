---
title: "page_add"
second_title: "Aspose.PDF for Rust via C++"
description: "向 PDF-document 添加新页面。"
type: docs
url: /zh/rust-cpp/core/page_add/
---

_向 PDF-document 添加新页面。_

```rust
pub fn page_add(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 从文件打开 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 在 PDF-document 中添加新页面
    pdf.page_add()?;

    // 保存先前打开的 PDF-document
    pdf.save()?;

    Ok(())
}

```