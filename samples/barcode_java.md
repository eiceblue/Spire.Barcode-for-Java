# Spire.Barcode Java QR Code with Logo
## Generate a QR code with a logo image
```java
// Create a BarcodeSettings object to set the parameters for the barcode
BarcodeSettings settings = new BarcodeSettings();

// Set the data content of the barcode to "ABC 123456789"
settings.setData("ABC 123456789");

// Set the type of the barcode to QR_Code (QR Code)
settings.setType(BarCodeType.QR_Code);

// Set whether the barcode should display text, here it is set to not display
settings.setShowText(false);

// Set whether the barcode should have a border, here it is set to have a border
settings.hasBorder(true);

// Read an image file and convert it to a BufferedImage object
BufferedImage image = ImageIO.read(new File("data/E-iceblueLogo.png"));

// Set the read image as the logo image for the QR code
settings.setQRCodeLogoImage(image);

// Create a BarCodeGenerator object for generating barcode images
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);

// Generate the barcode image using the generateImage() method
BufferedImage bufferedImage = barCodeGenerator.generateImage();

// Write the generated barcode image to a file in PNG format
ImageIO.write(bufferedImage, "png", new File("QR_CODE_Logo_Image.png"));
```

---

# Spire.Barcode AZTEC Generator
## Generate AZTEC barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set the code property
settings.setData("ABC 123456789");
//Set the Symbology property
settings.setType(BarCodeType.Aztec);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Set the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode CODABAR Generation
## Generate CODABAR barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("2030405060");
//Set the Symbology property
settings.setType(BarCodeType.Codabar);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Set the CodabarStartChar and CodabarStopChar
settings.setCodabarStartChar(CodabarChar.B);
settings.setCodabarStopChar(CodabarChar.D);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode CODE_11 Generation
## Generate CODE_11 barcode using Spire.Barcode library
```java
// Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
// Set Data
settings.setData("12345-67890");
// Set the Symbology property
settings.setType(BarCodeType.Code_11);
// Set ShowText location on bottom
settings.setShowTextOnBottom(true);
// Set Border is visible
settings.hasBorder(true);
// Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
// Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode CODE_128 Generation
## Generate a CODE_128 barcode with specific settings and save as PNG image
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("ABCD 12345 abcd");
//Set the Symbology property
settings.setType(BarCodeType.Code_128);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
//Save the image
ImageIO.write(bufferedImage,"png",new File("CODE_128.png"));
```

---

# Spire Barcode CODE_25 Generation
## Generate CODE_25 barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("123456789");
//Set the Symbology property
settings.setType(BarCodeType.Code_25);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire Barcode CODE_39 Generation
## Generate CODE_39 barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("ABC 123456789");
//Set the Symbology property
settings.setType(BarCodeType.Code_39);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire Barcode CODE 39 Extended Generation
## Generate CODE 39 Extended barcode with custom settings
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("(abc) 123456789");
//Set the Symbology property
settings.setType(BarCodeType.Code_39_Extended);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode CODE_93 Generation
## Generate CODE_93 barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("ABC123456789");
//Set the Symbology property
settings.setType(BarCodeType.Code_93);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode CODE_93_EXTENDED Generation
## Generate a CODE_93_EXTENDED barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("(abc) 123456789");
//Set the Symbology property
settings.setType(BarCodeType.Code_93_Extended);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire Barcode Generator
## Generate DATA MATRIX Barcode
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("ABC 123456789");
//Set the Symbology property
settings.setType(BarCodeType.Data_Matrix);
//Set Border is visible
settings.hasBorder(true);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode Deutsche Post Identcode Generator
## Generate Deutsche Post Identcode barcode using Spire.Barcode library
```java
// Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
// Set data for the barcode
settings.setData("56400000005");
// Set the symbology type
settings.setType(BarCodeType.Deutsche_Post_Identcode);
// Set show text location on bottom
settings.setShowTextOnBottom(true);
// Set border visibility
settings.hasBorder(true);
// Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
// Generate the barcode image
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode Deutsche Post Leitcode Generation
## Generate Deutsche Post Leitcode barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set the Symbology property
settings.setType(BarCodeType.Deutsche_Post_Leitcode);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Set the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# spire.barcode EAN-128 generation
## Generate EAN-128 barcode with custom settings
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("800500036510123456");
//Set the Symbology property
settings.setType(BarCodeType.EAN_128);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Java EAN-13 Barcode Generation
## Generate EAN-13 barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("501234567890");
//Set the Symbology property
settings.setType(BarCodeType.EAN_13);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# spire.barcode EAN-14 generation
## Generate EAN-14 barcode with specific settings
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("1061414100041");
//Set the Symbology property
settings.setType(BarCodeType.EAN_14);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# spire.barcode EAN-8 generation
## Generate EAN-8 barcode with custom settings
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("2012345");
//Set the Symbology property
settings.setType(BarCodeType.EAN_8);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire Barcode Java Generator
## Generate INTERLEAVED 25 barcode
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("1234567890123");
//Set the Symbology property
settings.setType(BarCodeType.Interleaved_25);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire Barcode ITF-14 Generation
## Generate ITF-14 barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("1540014128876");
//Set the Symbology property
settings.setType(BarCodeType.ITF_14);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# spire.barcode java ITF-6 generation
## Generate ITF-6 barcode with custom settings
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("15432");
//Set the Symbology property
settings.setType(BarCodeType.ITF_6);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
//Save the image
ImageIO.write(bufferedImage,"png",new File("ITF_6.png"));
```

---

# Spire.Barcode Java MSI Generator
## Generate MSI barcode with custom settings
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("123456789");
//Set the Symbology property
settings.setType(BarCodeType.MSI);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode OPC Generation
## Generate an OPC barcode with custom settings
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("020711721");
//Set the Symbology property
settings.setType(BarCodeType.OPC);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
//Save the image
ImageIO.write(bufferedImage,"png",new File("OPC.png"));
```

---

# Spire.Barcode PDF_417 Generation
## Generate PDF_417 barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("DATA");
//Set the Symbology property
settings.setType(BarCodeType.Pdf_417);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode PDF_417 Macro Generation
## Generate PDF_417 Macro barcode with customizable settings
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("123456789");
//Set the Symbology property
settings.setType(BarCodeType.Pdf_417_Macro);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire Barcode PLANET Generator
## Generate PLANET barcode using Spire.Barcode library
```java
// Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
// Set Data
settings.setData("4012345235636");
// Set the Symbology property
settings.setType(BarCodeType.Planet);
// Set ShowText location on bottom
settings.setShowTextOnBottom(true);
// Set Border is visible
settings.hasBorder(true);
// Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
// Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode POST_NET Generation
## Generate POST_NET barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("202609900");
//Set the Symbology property
settings.setType(BarCodeType.Post_Net);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode PZN Generation
## Generate PZN barcode using Spire.Barcode for Java
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("123456");
//Set the Symbology property
settings.setType(BarCodeType.PZN);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode QR Code Generation
## Generate QR code using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("ABC 123456789");
//Set the Symbology property
settings.setType(BarCodeType.QR_Code);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire Barcode Royal Mail 4-State Generation
## Generate Royal Mail 4-State barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("2130VA80430");
//Set the Symbology property
settings.setType(BarCodeType.Royal_Mail_4_State);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode RSS-14 Generation
## Generate RSS-14 barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("0061414199999");
//Set the Symbology property
settings.setType(BarCodeType.RSS_14);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire Barcode RSS-14 Truncated Generation
## Generate RSS-14 Truncated barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("0061414199999");
//Set the Symbology property
settings.setType(BarCodeType.RSS_14_Truncated);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode RSS Expanded Generation
## Generate RSS Expanded barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("(01)90614141000015(3202)000150");
//Set the Symbology property
settings.setType(BarCodeType.RSS_Expanded);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire Barcode RSS Limited Generation
## Generate RSS Limited barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("0061414199999");
//Set the Symbology property
settings.setType(BarCodeType.RSS_Limited);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire Barcode SCC-14 Generation
## Generate SCC-14 barcode with specific settings
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("1061414100041");
//Set the Symbology property
settings.setType(BarCodeType.SCC_14);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode Singapore Post 4-State Generation
## Generate Singapore Post 4-State barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("529508");
//Set the Symbology property
settings.setType(BarCodeType.Singapore_Post_4_State);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire.Barcode SSCC-18 Generation
## Generate SSCC-18 barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("00614141123456789");
//Set the Symbology property
settings.setType(BarCodeType.SSCC_18);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Swiss Post Parcel Barcode Generation
## Generate a Swiss Post Parcel barcode using spire.barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("993413796700168509");
//Set the Symbology property
settings.setType(BarCodeType.Swiss_Post_Parcel);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# spire.barcode java UPCA generation
## generate UPCA barcode using spire.barcode
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("0987654321");
//Set the Symbology property
settings.setType(BarCodeType.UPCA);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Java UPCE Barcode Generation
## Generate UPCE barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("01234567890|991234-abcd");
//Set the Symbology property
settings.setType(BarCodeType.UPCE);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire Barcode USPS Generation
## Generate USPS barcode using Spire.Barcode library
```java
//Create the BarcodeSettings
BarcodeSettings settings = new BarcodeSettings();
//Set Data
settings.setData("34160265194042788110");
//Set the Symbology property
settings.setType(BarCodeType.USPS);
//Set ShowText location on bottom
settings.setShowTextOnBottom(true);
//Set Border is visible
settings.hasBorder(true);
//Create the BarCodeGenerator
BarCodeGenerator barCodeGenerator = new BarCodeGenerator(settings);
//Get image from the BarCodeGenerator
BufferedImage bufferedImage = barCodeGenerator.generateImage();
```

---

# Spire Barcode Scanner
## Scan barcode from image
```java
// Get code information by scanning the image
String[] s = BarcodeScanner.scan("CODABAR.png");
```

---

