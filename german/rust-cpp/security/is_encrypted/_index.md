---
title: "is_encrypted"
second_title: "Aspose.PDF für Rust über C++"
description: "Erhalte den verschlüsselten Status des PDF-Dokuments."
type: docs
url: /de/rust-cpp/security/is_encrypted/
---

_Abrufen des verschlüsselten Status des PDF-Dokuments._

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
    // Öffnen Sie ein passwortgeschütztes PDF-Dokument
    let pdf = Document::open_with_password("sample_with_password.pdf", "ownerpass")?;

    // Abrufen des verschlüsselten Status des PDF-Dokuments
    if pdf.is_encrypted()? {
        println!("The document is encrypted.");
    }

    Ok(())
}

```