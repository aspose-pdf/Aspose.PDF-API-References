---
title: "is_encrypted"
second_title: Aspose.PDF for Rust via C++
description: "Get encrypted status of PDF-document."
type: docs
url: /rust-cpp/security/is_encrypted/
---

_Get encrypted status of PDF-document._

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
    // Open a password-protected PDF-document
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Get encrypted status of PDF-document
    if pdf.is_encrypted()? {
        println!("The document is encrypted.");
    }

    Ok(())
}

```