# Electronic-Interchange-Github-Resources
List of EDI Github Resources. PRs Welcome!

## Syntax Highlighters

- [amandagrice/sublime-x12-highlighting](https://github.com/amandagrice/sublime-x12-highlighting) - Adds syntax highlighting to Sublime for x12 files. Made especially for the healthcare EDI space. (837s, etc.)
- [michaelachrisco/sublime-834-syntax](https://github.com/michaelachrisco/sublime-834-syntax) - Sublime syntax highlighter for the EDI x12 834 file.
- [Notepad++](https://gist.github.com/bhattisatish/6b5f5c90443a64cef192) - A user-defined language file for highlighting EDI X12.
- [Silvenga/vscode-edi-x12-support](https://github.com/Silvenga/vscode-edi-x12-support) - A Visual Studio Code extension aimed at providing basic support for the EDI format.
- [vim-scripts/x12-syntax](https://github.com/vim-scripts/x12-syntax) - A simple syntax highlighter for EDI X12 files. Currently only Healthcare 270/271s are tested.

## Standalone editors
- [RKDN/x12Tool](https://github.com/RKDN/x12Tool) - A tool for reading and modifying x12/EDI files.

## Libraries

### Java
- [BerryWorksSoftware/edi-json](https://github.com/BerryWorksSoftware/edi-json) - Serializing EDI as JSON
- [moqui/mantle-edi](https://github.com/moqui/mantle-edi) - Mantle EDI Integrations
- [mrcsparker/nifi-edireader-bundle](https://github.com/mrcsparker/nifi-edireader-bundle) - Apache NIFI processor that converts EDI ASC X12 and EDIFACT documents into XML
- [imsweb/x12-parser](https://github.com/imsweb/x12-parser) - A Java parser for ANSI ASC X12 documents.
- [xiaoerge/X12Healthcare](https://github.com/xiaoerge/X12Healthcare) - ANSI ASC X12 implementation for healthcare
### C#/DotNet
- [olmelabs/EdiEngine](https://github.com/olmelabs/EdiEngine) - Simple .NET EDI Reader, Writer and Validator. Read, Write and Validate X12 EDI files with simple EDI Parser written on C#. 
- [indice-co/EDI.Net](https://github.com/indice-co/EDI.Net) - EDI Serializer/Deserializer. Supports EDIFact, X12 and TRADACOMS formats
- [Silvenga/EdiWeave](https://github.com/Silvenga/EdiWeave) - Open Source Hard-Fork of EdiFabric
- [MassTransit/Machete](https://github.com/MassTransit/Machete) - Cut through the Crap, with Machete, a text parser, object mapper, and query engine.
### Python
- [glitchassassin/python-edi](https://github.com/glitchassassin/python-edi) - EDI message generator in Python. Creates & validates messages according to specific formats
- [git-albertomarin/badX12](https://github.com/git-albertomarin/badX12) - A Python Library for parsing ANSI ASC X12 files.
## Swift
- [kuyawa/EdiMapper](https://github.com/kuyawa/EdiMapper) - Convert EDI Documents to XML
### PHP
- [php-edifact/edifact](https://github.com/php-edifact/edifact) - (PHP) Tools to process EDI messages in UN/EDIFACT format
- [php-edifact/edifact-generator](https://github.com/php-edifact/edifact-generator) - Library to create UN/EDIFACT messages
- [php-edifact/edifact-mapping](https://github.com/php-edifact/edifact-mapping) - UN/EDIFACT mappings in XML, with a PHP provider
### Javascript
- [dlumpp/x12-patient-faker](https://github.com/dlumpp/x12-patient-faker) - Generates test patient data in HIPAA X12 format
- [tdecaluwe/node-edifact](https://github.com/tdecaluwe/node-edifact) - (Javascript) Javascript stream parser for UN/EDIFACT documents.
- [parcelLab/edi-iftmin](https://github.com/parcelLab/edi-iftmin) - Parsing EDI IFTMIN and IFTSTA messages properly. Yes, EDI. You're welcome.
### Ruby
- [ConsultingMD/ediot](https://github.com/ConsultingMD/ediot) - (Ruby) Electronic Data Interexchange Open Transformer (transforms EDI-834 into CSV)
- [irobayna/stupidedi](https://github.com/irobayna/stupidedi) - Ruby API for parsing and generating ASC X12 EDI transactions.

## CLI utilities
- [azoner/pyx12](https://github.com/azoner/pyx12) - (Python) HIPAA X12 document validator and converter
- [notpeter/edicat](https://github.com/notpeter/edicat) - Print and concatenate X12 and Edifact EDI

## Systems or Paid Services
- [abhishek-ram/pyas2](https://github.com/abhishek-ram/pyas2) - A pythonic AS2 client and server
- [bots-edi/bots](https://github.com/bots-edi/bots) - Bots EDI Translator
- [Campbellony/X12SqlServer](https://github.com/campbellony/x12sqlserver) - Simple X12 data model with TSQL parsing procedures
- [EdiFabric/Sdk](https://github.com/EdiFabric/Sdk) - Dynamically read, manipulate and write EDI files. From EDIFabric.
- [EDI Editor](https://www.tallan.com/products/t-connect-edi-management/x12-studio-tool-box/) - X12 EDI editor
- [MicrosoftDocs/biztalk-docs](https://github.com/MicrosoftDocs/biztalk-docs) - Microsoft Biztalk documentation
- [Mulesoft](https://github.com/mulesoft) - Collection of Mulesoft Repositories.
- [T-Connect](https://www.tallan.com/products/t-connect-edi-management/t-connect-edi-management-suite/) - T-Connect is a HIPAA-focused EDI management platform designed to accelerate claim and payment processing, improve first-pass adjudication rates and provide end-to-end visibility into the lifecycle of your data.
- [BerryWorksSoftware/edireader](https://github.com/BerryWorksSoftware/edireader) - EDIReader is a Java package for parsing business documents structured according to EDI standards. It supports the SAX and JAXP interfaces defined for XML, making it suitable for use in any XML-based system that allows the configuration of a custom SAX parser.

## Examples
- [Edipique/EDI-X12](https://github.com/dipique/EDI-X12) - Rough process for generating EDI X12 834 and 837 files from a CSV file. Structured in a way that allows easy transition to other data sources.
- [PHP Implementations of Transactions](https://github.com/stephenmccready/X12) - PHP examples of writing EDI from scratch.
- [Sdk](https://github.com/EdiFabric/Sdk/blob/master/EdiFabric.Sdk.Demo/Program.cs) - C# Demo using EdiFabric. 
- [walkswithme/EDI-X12-ANSI-270](https://github.com/walkswithme/EDI-X12-ANSI-270) - PHP Library for creating EDI X12 ANSI 270 File 5010 Version
