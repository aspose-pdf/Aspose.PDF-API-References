---
title: "remove_tables"
second_title: "Aspose.PDF för Rust via C++"
description: "Tar bort tabeller från PDF-dokument."
type: docs
url: /sv/rust-cpp/organize/remove_tables/
---

_Tar bort tabeller från PDF-dokument._

```rust
pub fn remove_tables(&self) -> Result<(), PdfError>
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

    // Ta bort tabeller från PDF-dokument
    pdf.remove_tables()?;

    // Spara det tidigare öppnade PDF-document med nytt filnamn
    pdf.save_as("sample_remove_tables.pdf")?;

    Ok(())
}

```