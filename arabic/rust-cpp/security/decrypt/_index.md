---
title: "فك التشفير"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "فك تشفير مستند PDF."
type: docs
url: /ar/rust-cpp/security/decrypt/
---

_فك تشفير مستند PDF._

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
    // فتح مستند PDF محمي بكلمة مرور
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // فك تشفير مستند PDF
    pdf.decrypt()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_decrypt.pdf")?;

    Ok(())
}

```