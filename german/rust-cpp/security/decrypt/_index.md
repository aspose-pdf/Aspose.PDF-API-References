---
title: "entschlüsseln"
second_title: "Aspose.PDF für Rust über C++"
description: "Entschlüssele das PDF-Dokument."
type: docs
url: /de/rust-cpp/security/decrypt/
---

_Entschlüsseln PDF-Dokument._

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
    // Öffnen Sie ein passwortgeschütztes PDF-Dokument
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Entschlüsseln PDF-Dokument
    pdf.decrypt()?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_decrypt.pdf")?;

    Ok(())
}

```