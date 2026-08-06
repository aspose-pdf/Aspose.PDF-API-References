---
title: "remove_text_headers"
second_title: "Aspose.PDF för Rust via C++"
description: "Tar bort textrubriker från PDF-dokumentet."
type: docs
url: /sv/rust-cpp/organize/remove_text_headers/
---

_Tar bort textrubriker från PDF-dokumentet._

```rust
pub fn remove_text_headers(&self) -> Result<(), PdfError>
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

    // Ta bort textrubriker från PDF-dokumentet
    pdf.remove_text_headers()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_remove_text_headers.pdf")?;

    Ok(())
}

```