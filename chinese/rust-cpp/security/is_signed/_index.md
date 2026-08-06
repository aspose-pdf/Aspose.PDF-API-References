---
title: "is_signed"
second_title: "Aspose.PDF for Rust via C++"
description: "获取 PDF-document 的签名状态。"
type: docs
url: /zh/rust-cpp/security/is_signed/
---

_获取 PDF 文档的签名状态._

```rust
pub fn is_signed(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开名为 "sample_with_sign.pdf" 的 PDF 文档
    let pdf = Document::open("sample_with_sign.pdf")?;

    // 获取 PDF 文档的签名状态
    if pdf.is_signed()? {
        println!("The document is signed.");
    }

    Ok(())
}

```