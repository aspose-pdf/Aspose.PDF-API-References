---
title: "is_encrypted"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Dapatkan status terenkripsi dari dokumen PDF."
type: docs
url: /id/rust-cpp/security/is_encrypted/
---

_Dapatkan status terenkripsi dari PDF-document._

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
    // Buka PDF-document yang dilindungi kata sandi
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Dapatkan status terenkripsi dari PDF-document
    if pdf.is_encrypted()? {
        println!("The document is encrypted.");
    }

    Ok(())
}

```