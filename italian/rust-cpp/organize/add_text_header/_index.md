---
title: "add_text_header"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Aggiunge testo nell'intestazione di un PDF-document."
type: docs
url: /it/rust-cpp/organize/add_text_header/
---

_Aggiunge testo nell'intestazione di un PDF-document._

```rust
pub fn add_text_header(&self, header: &str) -> Result<(), PdfError>
```

**Arguments**
  * **header** - the pages header

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Aggiungi testo nell'intestazione di un documento PDF
    pdf.add_text_header("HEADER")?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_add_text_header.pdf")?;

    Ok(())
}

```