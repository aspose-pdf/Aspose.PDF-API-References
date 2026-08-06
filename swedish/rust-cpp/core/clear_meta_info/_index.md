---
title: "clear_meta_info"
second_title: "Aspose.PDF för Rust via C++"
description: "Rensar alla metainformationsvärden för PDF-dokument."
type: docs
url: /sv/rust-cpp/core/clear_meta_info/
---

_Rensar alla metainformationsvärden för PDF-dokument._

```rust
pub fn clear_meta_info(&self) -> Result<(), PdfError>
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

    // Rensa alla metainformationsvärden för PDF-dokument
    pdf.clear_meta_info()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_clear_meta_info.pdf")?;

    Ok(())
}

```