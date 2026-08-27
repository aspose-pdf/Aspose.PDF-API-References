---
title: "add_page_num"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Aggiunge il numero di pagina a un documento PDF."
type: docs
url: /it/rust-cpp/organize/add_page_num/
---

_Aggiunge il numero di pagina a un documento PDF._

```rust
pub fn add_page_num(&self) -> Result<(), PdfError>
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

    // Aggiungi il numero di pagina a un documento PDF
    pdf.add_page_num()?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_add_page_num.pdf")?;

    Ok(())
}

```