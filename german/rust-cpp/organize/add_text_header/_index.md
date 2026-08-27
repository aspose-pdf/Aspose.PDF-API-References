---
title: "add_text_header"
second_title: "Aspose.PDF für Rust über C++"
description: "Fügt Text in die Kopfzeile eines PDF-Dokuments ein."
type: docs
url: /de/rust-cpp/organize/add_text_header/
---

_Fügt Text in die Kopfzeile eines PDF-Dokuments ein._

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
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Fügen Sie Text in die Kopfzeile eines PDF-Dokuments ein
    pdf.add_text_header("HEADER")?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_add_text_header.pdf")?;

    Ok(())
}

```