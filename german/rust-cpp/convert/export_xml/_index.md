---
title: "export_xml"
second_title: "Aspose.PDF für Rust über C++"
description: "Exportiert aus zuvor geöffnetem PDF-Dokument mit AcroForm zu XML-Dokument mit Dateiname."
type: docs
url: /de/rust-cpp/convert/export_xml/
---

_Exportiert aus zuvor geöffnetem PDF-Dokument mit AcroForm zu XML-Dokument mit Dateiname._

```rust
pub fn export_xml(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Export aus dem zuvor geöffneten PDF-Dokument mit AcroForm zu XML-Dokument
    pdf.export_xml("sample.xml")?;

    Ok(())
}

```