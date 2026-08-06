---
title: "set_meta_info"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Imposta il valore delle meta informazioni del PDF-document."
type: docs
url: /it/rust-cpp/core/set_meta_info/
---

_Imposta il valore delle meta informazioni del PDF-document._

```rust
pub fn set_meta_info(&self, key: &str, value: &str) -> Result<(), PdfError>
```

**Arguments**
  * **key** - the key whose value to set
  * **value** - the value to be set

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Imposta il valore delle meta informazioni del PDF-document
    pdf.set_meta_info("Author", "Aspose")?;

    // Salva il PDF-document precedentemente aperto con un nuovo nome di file
    pdf.save_as("sample_set_meta_info.pdf")?;

    Ok(())
}

```