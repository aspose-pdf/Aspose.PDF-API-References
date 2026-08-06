---
title: "remove_signs"
second_title: "Aspose.PDF for Rust via C++"
description: "从 PDF-document 中移除签名。"
type: docs
url: /zh/rust-cpp/security/remove_signs/
---

_从 PDF 文档中移除签名。_

```rust
pub fn remove_signs(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the resulting PDF-document without signatures


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开名为 "sample_with_sign.pdf" 的 PDF 文档
    let pdf = Document::open("sample_with_sign.pdf")?;

    // 从 PDF 文档中移除签名
    pdf.remove_signs("sample_remove_signs.pdf")?;

    Ok(())
}

```