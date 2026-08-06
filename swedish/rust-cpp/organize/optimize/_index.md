---
title: "optimize"
second_title: "Aspose.PDF för Rust via C++"
description: "Optimerar PDF-dokumentets innehåll."
type: docs
url: /sv/rust-cpp/organize/optimize/
---

_Optimerar PDF-dokumentets innehåll._

```rust
pub fn optimize(&self) -> Result<(), PdfError>
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

    // Optimera PDF-dokumentets innehåll
    pdf.optimize()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_optimize.pdf")?;

    Ok(())
}

```