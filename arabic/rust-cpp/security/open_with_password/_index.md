---
title: "open_with_password"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "فتح مستند PDF محمي بكلمة مرور."
type: docs
url: /ar/rust-cpp/security/open_with_password/
---

_فتح مستند PDF محمي بكلمة مرور._

```rust
pub fn open_with_password(filename: &str, password: &str) -> Result<Self, PdfError>
```

**Arguments**
  * **filename** - path to the PDF-document to open
  * **password** - user/owner password of the password-protected PDF-document

**Returns**
  * **Ok(Self)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF محمي بكلمة مرور
    let _pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // جارٍ العمل...

    Ok(())
}

```