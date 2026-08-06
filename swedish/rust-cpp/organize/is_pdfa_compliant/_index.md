---
title: "is_pdfa_compliant"
second_title: "Aspose.PDF för Rust via C++"
description: "Hämtar om ett PDF-dokument är PDF/A-kompatibelt."
type: docs
url: /sv/rust-cpp/organize/is_pdfa_compliant/
---

_Hämtar om ett PDF-dokument är PDF/A-kompatibelt._

```rust
pub fn is_pdfa_compliant(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Hämta PDF/A-kompatibilitetsstatus för PDF-dokument
    if pdf.is_pdfa_compliant()? {
        println!("The document is PDF/A compliant.");
    } else {
        println!("The document is not PDF/A compliant.");
    }

    Ok(())
}

```