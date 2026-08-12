---
title: "extract_text"
second_title: "Aspose.PDF för Rust via C++"
description: "Returnerar PDF-documentets innehåll som vanlig text."
type: docs
url: /sv/rust-cpp/core/extract_text/
---

_Returnerar PDF-documentets innehåll som vanlig text._

```rust
pub fn extract_text(&self) -> Result<String, PdfError>
```

**Arguments**


**Returns**
  * **Ok(String)** - if the operation succeeds
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