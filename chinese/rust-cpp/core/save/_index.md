---
title: "save"
second_title: "Aspose.PDF for Rust via C++"
description: "保存先前打开的 PDF-document。"
type: docs
url: /zh/rust-cpp/core/save/
---

_保存先前打开的 PDF-document._

```rust
pub fn save(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开名为 "sample.pdf" 的 PDF-document
    let pdf = Document::open("sample.pdf")?;

    // 保存先前打开的 PDF-document
    pdf.save()?;

    Ok(())
}

```