---
title: "set_meta_info"
second_title: "Aspose.PDF für Rust über C++"
description: "Setzt den Meta-Informationswert des PDF-documents."
type: docs
url: /de/rust-cpp/core/set_meta_info/
---

_Setzt den Meta-Informationswert des PDF-documents._

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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Setze Meta-Informationswert des PDF-documents
    pdf.set_meta_info("Author", "Aspose")?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_set_meta_info.pdf")?;

    Ok(())
}

```