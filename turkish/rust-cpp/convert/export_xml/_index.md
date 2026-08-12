---
title: "export_xml"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Önceden açılmış PDF-belgesinden AcroForm ile XML-belgesine dosya adıyla dışa aktarır."
type: docs
url: /tr/rust-cpp/convert/export_xml/
---

_Önceden açılmış PDF-belgesinden AcroForm ile XML-belgesine dosya adıyla dışa aktarır._

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
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Önceden açılmış PDF-belgesinden AcroForm ile XML-belgesine dışa aktar.
    pdf.export_xml("sample.xml")?;

    Ok(())
}

```