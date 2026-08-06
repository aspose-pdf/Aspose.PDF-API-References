---
title: "解密"
second_title: "Aspose.PDF for Rust via C++"
description: "解密 PDF-document。"
type: docs
url: /zh/rust-cpp/security/decrypt/
---

_解密 PDF 文档。_

```rust
pub fn decrypt(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 打开受密码保护的 PDF 文档
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // 解密 PDF 文档
    pdf.decrypt()?;

    // 使用新文件名保存先前打开的 PDF 文档
    pdf.save_as("sample_decrypt.pdf")?;

    Ok(())
}

```