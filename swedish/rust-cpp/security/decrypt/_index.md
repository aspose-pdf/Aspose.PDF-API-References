---
title: "dekryptera"
second_title: "Aspose.PDF för Rust via C++"
description: "Dekryptera PDF-dokument."
type: docs
url: /sv/rust-cpp/security/decrypt/
---

_Dekryptera PDF-dokument._

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
    // Öppna ett lösenordsskyddat PDF-dokument
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Dekryptera PDF-dokument
    pdf.decrypt()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_decrypt.pdf")?;

    Ok(())
}

```