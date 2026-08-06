---
title: "über"
second_title: "Aspose.PDF für Rust über C++"
description: "Gibt Metadateninformationen über das Aspose.PDF für Rust über C++ zurück."
type: docs
url: /de/rust-cpp/miscellaneous/about/
---

_Gibt Metadateninformationen über das Aspose.PDF für Rust über C++ zurück._

```rust
pub fn about(&self) -> Result<ProductInfo, PdfError>
```

**Arguments**


**Returns**
  * **Ok(ProductInfo)** - if the operation succeeds
```rust
#[derive(Debug, Deserialize)]
pub struct ProductInfo {
    #[serde(rename = "product")]
    pub product: String,

    #[serde(rename = "family")]
    pub family: String,

    #[serde(rename = "version")]
    pub version: String,

    #[serde(rename = "releasedate")]
    pub release_date: String,

    #[serde(rename = "producer")]
    pub producer: String,

    #[serde(rename = "islicensed")]
    pub is_licensed: bool,
}
```

  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Erstelle ein neues PDF-Dokument
    let pdf = Document::new()?;

    // Gibt Metadateninformationen über das Aspose.PDF für Go über C++ zurück.
    let info = pdf.about()?;

    // Metadatenfelder drucken
    println!("Product Info:");
    println!("  Product:      {}", info.product);
    println!("  Family:       {}", info.family);
    println!("  Version:      {}", info.version);
    println!("  ReleaseDate:  {}", info.release_date);
    println!("  Producer:     {}", info.producer);
    println!("  IsLicensed:   {}", info.is_licensed);

    Ok(())
}

```