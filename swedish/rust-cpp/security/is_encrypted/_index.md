---
title: "is_encrypted"
second_title: "Aspose.PDF för Rust via C++"
description: "Hämta krypteringsstatus för PDF-dokument."
type: docs
url: /sv/rust-cpp/security/is_encrypted/
---

_Hämta krypteringsstatus för PDF-dokumentet._

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
    // Öppna ett lösenordsskyddat PDF-dokument
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Hämta krypteringsstatus för PDF-dokumentet
    if pdf.is_encrypted()? {
        println!("The document is encrypted.");
    }

    Ok(())
}

```