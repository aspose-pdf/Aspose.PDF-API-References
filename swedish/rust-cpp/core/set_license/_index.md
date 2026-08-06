---
title: "set_license"
second_title: "Aspose.PDF för Rust via C++"
description: "Ställer in licens med filnamn."
type: docs
url: /sv/rust-cpp/core/set_license/
---

_Ställer in licens med filnamn._

```rust
pub fn set_license(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the license-file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Ställ in licens med filnamn
    pdf.set_license("Aspose.PDF.RustViaCPP.lic")?;

    // Nu kan du arbeta med det licensierade PDF-dokumentet
    // ...

    Ok(())
}

```