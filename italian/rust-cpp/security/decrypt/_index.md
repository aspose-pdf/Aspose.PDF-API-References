---
title: "decrittare"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Decifra il PDF-document."
type: docs
url: /it/rust-cpp/security/decrypt/
---

_Decripta PDF-document._

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
    // Apri un PDF-document protetto da password
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Decripta PDF-document
    pdf.decrypt()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_decrypt.pdf")?;

    Ok(())
}

```