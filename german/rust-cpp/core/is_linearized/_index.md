---
title: "is_linearized"
second_title: "Aspose.PDF für Rust über C++"
description: "Ermittelt einen Wert, der angibt, ob das Dokument linearisiert ist."
type: docs
url: /de/rust-cpp/core/is_linearized/
---

_Ermittelt einen Wert, der angibt, ob das Dokument linearisiert ist._

```rust
pub fn is_linearized(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Öffne ein PDF-Dokument mit Dateiname
    let pdf = Document::open("sample.pdf")?;

    // Erhalte einen Wert, der angibt, ob das Dokument linearisiert ist
    if pdf.is_linearized()? {
        println!("The PDF-document is linearized.");
    } else {
        println!("The PDF-document is non-linearized.");
    }

    Ok(())
}

```