---
title: "open_with_password"
second_title: Aspose.PDF for Rust via C++
description: "Open a password-protected PDF-document."
type: docs
url: /rust-cpp/security/open_with_password/
---

_Open a password-protected PDF-document._

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
    // Open a password-protected PDF-document
    let _pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // working...

    Ok(())
}

```