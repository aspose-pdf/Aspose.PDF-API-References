---
title: "is_encrypted"
second_title: "Aspose.PDF for Rust via C++"
description: "获取 PDF-document 的加密状态。"
type: docs
url: /zh/rust-cpp/security/is_encrypted/
---

_获取 PDF 文档的加密状态。_

```rust
pub fn is_encrypted(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开受密码保护的 PDF 文档
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // 获取 PDF 文档的加密状态
    if pdf.is_encrypted()? {
        println!("The document is encrypted.");
    }

    Ok(())
}

```