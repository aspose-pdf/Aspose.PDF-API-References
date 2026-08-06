---
title: "is_signed"
second_title: "Aspose.PDF für Rust über C++"
description: "Erhalte den signierten Status des PDF-Dokuments."
type: docs
url: /de/rust-cpp/security/is_signed/
---

_Den Signaturstatus des PDF-Dokuments abrufen._

```rust
pub fn is_signed(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffnen Sie ein PDF-Dokument mit dem Namen "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Signaturstatus des PDF-Dokuments abrufen
    if pdf.is_signed()? {
        println!("The document is signed.");
    }

    Ok(())
}

```