---
title: "add_text_footer"
second_title: "Aspose.PDF für Rust über C++"
description: "Fügt Text in die Fußzeile einer PDF-document ein."
type: docs
url: /de/rust-cpp/organize/add_text_footer/
---

_Fügt Text in die Fußzeile einer PDF-document ein._

```rust
pub fn add_text_footer(&self, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Fügen Sie Text in die Fußzeile eines PDF-Dokuments ein
    pdf.add_text_footer("FOOTER")?;

    // Das zuvor geöffnete PDF-Dokument mit neuem Dateinamen speichern
    pdf.save_as("sample_add_text_footer.pdf")?;

    Ok(())
}

```