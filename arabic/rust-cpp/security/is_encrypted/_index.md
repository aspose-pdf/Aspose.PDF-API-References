---
title: "is_encrypted"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "الحصول على حالة التشفير لمستند PDF."
type: docs
url: /ar/rust-cpp/security/is_encrypted/
---

_احصل على حالة التشفير لمستند PDF._

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
    // فتح مستند PDF محمي بكلمة مرور
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // احصل على حالة التشفير لمستند PDF
    if pdf.is_encrypted()? {
        println!("The document is encrypted.");
    }

    Ok(())
}

```