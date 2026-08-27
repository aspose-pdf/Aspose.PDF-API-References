---
title: "remove_bookmarks"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Rimuove i segnalibri dal PDF-document."
type: docs
url: /it/rust-cpp/organize/remove_bookmarks/
---

_Rimuove i segnalibri dal PDF-document._

```rust
pub fn remove_bookmarks(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Rimuovi i segnalibri dal documento PDF
    pdf.remove_bookmarks()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_remove_bookmarks.pdf")?;

    Ok(())
}

```