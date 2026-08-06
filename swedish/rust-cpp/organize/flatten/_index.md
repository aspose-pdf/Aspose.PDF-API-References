---
title: "flatten"
second_title: "Aspose.PDF för Rust via C++"
description: "Plattar till PDF-dokumentet."
type: docs
url: /sv/rust-cpp/organize/flatten/
---

_Plattar till PDF-dokumentet._

```rust
pub fn flatten(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öppna ett PDF-dokument med filnamn
    let pdf = Document::open("sample.pdf")?;

    // Returnera PDF-documentets innehåll som vanlig text
    let txt = pdf.extract_text()?;

    // Skriv ut extraherad text
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```