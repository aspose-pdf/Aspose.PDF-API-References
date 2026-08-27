---
title: "page_insert"
second_title: "Aspose.PDF for Rust via C++"
description: "在 PDF-document 的指定位置插入新页面."
type: docs
url: /zh/rust-cpp/core/page_insert/
---

_在 PDF-document 的指定位置插入新页面._

```rust
pub fn page_insert(&self, num: i32) -> Result<(), PdfError>
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

    // 在 PDF-document 的指定位置插入新页面
    pdf.page_insert(1)?;

    // 保存先前打开的 PDF-document
    pdf.save()?;

    Ok(())
}

```