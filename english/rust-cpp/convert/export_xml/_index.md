---
title: "export_xml"
second_title: Aspose.PDF for Rust via C++
description: "Exports from previously opened PDF-document with AcroForm to XML-document with filename."
type: docs
url: /rust-cpp/convert/export_xml/
---

_Exports from previously opened PDF-document with AcroForm to XML-document with filename._

```rust
pub fn export_xml(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** – the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Open a PDF-document with filename
    let pdf = Document::open("sample.pdf")?;

    // Export from the previously opened PDF-document with AcroForm to XML-document
    pdf.export_xml("sample.xml")?;

    Ok(())
}

```