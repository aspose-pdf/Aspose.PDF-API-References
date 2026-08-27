---
title: "save"
second_title: "Aspose.PDF für Rust über C++"
description: "Speichert das zuvor geöffnete PDF-Dokument."
type: docs
url: /de/rust-cpp/core/save/
---

_Speichert das zuvor geöffnete PDF-Dokument._

```rust
pub fn save(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-document mit dem Namen "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // Speichere das zuvor geöffnete PDF-document
    pdf.save()?;

    Ok(())
}

```