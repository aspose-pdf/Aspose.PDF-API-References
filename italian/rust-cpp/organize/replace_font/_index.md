---
title: "replace_font"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Sostituisce il carattere in un PDF-document."
type: docs
url: /it/rust-cpp/organize/replace_font/
---

_Sostituisce il carattere in un PDF-document._

```rust
pub fn replace_font(&self, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Sostituisci il carattere in un documento PDF.
    pdf.replace_font("Helvetica", "Courier")?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_replace_font.pdf")?;

    Ok(())
}

```