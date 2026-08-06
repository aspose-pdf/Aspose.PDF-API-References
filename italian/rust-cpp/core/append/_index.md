---
title: "append"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Aggiunge pagine da un altro PDF-document."
type: docs
url: /it/rust-cpp/core/append/
---

_Aggiunge pagine da un altro PDF-document._

```rust
pub fn append(&self, other: &Document) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri il PDF-document principale
    let pdf = Document::open("sample.pdf")?;

    // Apri un altro PDF-document da aggiungere
    let another_pdf = Document::open("sample1page.pdf")?;

    // Aggiungi pagine da un altro PDF-document
    pdf.append(&another_pdf)?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_append.pdf")?;

    Ok(())
}

```