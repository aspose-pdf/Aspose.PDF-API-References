---
title: "informazioni"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Restituisce informazioni sui metadati di Aspose.PDF per Rust tramite C++."
type: docs
url: /it/rust-cpp/miscellaneous/about/
---

_Restituisce informazioni sui metadati di Aspose.PDF per Rust tramite C++._

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
    // Crea un nuovo PDF-document
    let pdf = Document::new()?;

    // Restituisci informazioni sui metadati di Aspose.PDF per Go tramite C++.
    let info = pdf.about()?;

    // Stampa i campi dei metadati
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