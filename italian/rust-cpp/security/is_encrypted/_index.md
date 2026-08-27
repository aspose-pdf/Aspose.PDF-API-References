---
title: "is_encrypted"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Ottieni lo stato di cifratura del PDF-document."
type: docs
url: /it/rust-cpp/security/is_encrypted/
---

_Ottieni lo stato di crittografia del PDF-document._

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
    // Apri un PDF-document protetto da password
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Ottieni lo stato di crittografia del PDF-document
    if pdf.is_encrypted()? {
        println!("The document is encrypted.");
    }

    Ok(())
}

```