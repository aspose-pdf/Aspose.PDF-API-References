---
title: "replace_text"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Sostituisce il testo."
type: docs
url: /it/rust-cpp/organize/replace_text/
---

_Sostituisce il testo._

```rust
pub fn replace_text(&self, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Sostituisci il testo nel documento PDF
    pdf.replace_text("PDF", "TXT")?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_replace_text.pdf")?;

    Ok(())
}

```