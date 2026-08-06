---
title: "is_signed"
second_title: "Aspose.PDF för Rust via C++"
description: "Hämta signeringsstatus för PDF-dokument."
type: docs
url: /sv/rust-cpp/security/is_signed/
---

_Hämta signeringsstatus för PDF-dokument._

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
    // Öppna ett PDF-dokument med namnet "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Hämta signeringsstatus för PDF-dokument
    if pdf.is_signed()? {
        println!("The document is signed.");
    }

    Ok(())
}

```