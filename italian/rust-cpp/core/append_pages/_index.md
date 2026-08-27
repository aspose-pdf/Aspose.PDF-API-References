---
title: "append_pages"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Aggiunge le pagine selezionate da un altro PDF-document."
type: docs
url: /it/rust-cpp/core/append_pages/
---

_Aggiunge le pagine selezionate da un altro PDF-document._

```rust
pub fn append_pages(&self, other: &Document, page_range: &str) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from
  * **page_range** - a string defining the page ranges to append (e.g. "-2,4,6-8,10-")

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri il PDF-document principale
    let pdf = Document::open("sample1page.pdf")?;

    // Apri un altro PDF-document da aggiungere
    let another_pdf = Document::open("sample.pdf")?;

    // Aggiungi le pagine specifiche (1 e 3) da un altro PDF-document
    pdf.append_pages(&another_pdf, "1,3")?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_append_pages.pdf")?;

    Ok(())
}

```