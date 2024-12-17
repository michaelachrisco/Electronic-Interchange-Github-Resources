# Electronic-Interchange-Github-Resources
List of EDI Github Resources. Pull Requests are Welcome!

https://michaelachrisco.github.io/Electronic-Interchange-Github-Resources/

## Libraries

### Java
- [apifocal/x12-parser](https://github.com/apifocal/x12-parser) - Java library for parsing and creating ASC X12 EDI transactions
- [ballerina-platform/edi-tools](https://github.com/ballerina-platform/edi-tools) - This library provides the functionality required to process EDI files and implement EDI integrations.
- [BerryWorksSoftware/edi-json](https://github.com/BerryWorksSoftware/edi-json) - Serializing EDI as JSON
- [moqui/mantle-edi](https://github.com/moqui/mantle-edi) - Mantle EDI Integrations
- [mrcsparker/nifi-edireader-bundle](https://github.com/mrcsparker/nifi-edireader-bundle) - Apache NIFI processor that converts EDI ASC X12 and EDIFACT documents into XML
- [imsweb/x12-parser](https://github.com/imsweb/x12-parser) - A Java parser for ANSI ASC X12 documents.
- [smooks/smooks](https://github.com/smooks/smooks) - An extensible Java framework for building XML and non-XML (CSV, EDI, Java, etc...) streaming applications 
- [walmartlabs/gozer](https://github.com/walmartlabs/gozer) - The EDI X12 Standard provides a uniform way for companies to exchange information across different sectors.
- [xlate/staedi](https://github.com/xlate/staedi) - General X12/EDIFACT stream reader and writer with support for validation of standards with optional schema customizations (i.e. implementation guides)

### C#/DotNet
- [olmelabs/EdiEngine](https://github.com/olmelabs/EdiEngine) - Simple .NET EDI Reader, Writer and Validator. Read, Write and Validate X12 EDI files with simple EDI Parser written on C#. 
- [indice-co/EDI.Net](https://github.com/indice-co/EDI.Net) - EDI Serializer/Deserializer. Supports EDIFact, X12 and TRADACOMS formats
- [Silvenga/EdiWeave](https://github.com/Silvenga/EdiWeave) - Open Source Hard-Fork of EdiFabric
- [MassTransit/Machete](https://github.com/MassTransit/Machete) - Cut through the Crap, with Machete, a text parser, object mapper, and query engine.
### Python
- [glitchassassin/python-edi](https://github.com/glitchassassin/python-edi) - EDI message generator in Python. Creates & validates messages according to specific formats
- [nerdocs/pydifact](https://github.com/nerdocs/pydifact) - A python library for parsing EDIFACT messages
- [git-albertomarin/badX12](https://github.com/git-albertomarin/badX12) - A Python Library for parsing ANSI ASC X12 files.
- [greasysock/CahasEDI-Core](https://github.com/greasysock/CahasEDI-Core) - Server/Client to AS2 messaging server for managing EDI partnerships and interpreting messages. 
- [keironstoddart/edi-835-parser](https://github.com/keironstoddart/edi-835-parser) - A simple EDI 835 file format parser.
- [slott56/TigerShark](https://github.com/slott56/TigerShark) - X12 Message Processing.
### Swift
- [kuyawa/EdiMapper](https://github.com/kuyawa/EdiMapper) - Convert EDI Documents to XML
### PHP
- [php-edifact/edifact](https://github.com/php-edifact/edifact) - (PHP) Tools to process EDI messages in UN/EDIFACT format
- [php-edifact/edifact-generator](https://github.com/php-edifact/edifact-generator) - Library to create UN/EDIFACT messages
- [php-edifact/edifact-mapping](https://github.com/php-edifact/edifact-mapping) - UN/EDIFACT mappings in XML, with a PHP provider
### Javascript
- [dlumpp/x12-patient-faker](https://github.com/dlumpp/x12-patient-faker) - Generates test patient data in HIPAA X12 format
- [tdecaluwe/node-edifact](https://github.com/tdecaluwe/node-edifact) - (Javascript) Javascript stream parser for UN/EDIFACT documents.
- [parcelLab/edi-iftmin](https://github.com/parcelLab/edi-iftmin) - Parsing EDI IFTMIN and IFTSTA messages properly. Yes, EDI. You're welcome.
- [tastypackets/x12-parser](https://github.com/tastypackets/x12-parser) - X12 parser implemented using the NodeJS Transform API. Tested with over 1M 835 records, but is designed to work with all modern X12 records.
- [aaronhuggins/node-x12](https://github.com/aaronhuggins/node-x12) - ASC X12 parser, generator, query engine, and mapper; now with support for streams.
### Ruby
- [ConsultingMD/ediot](https://github.com/ConsultingMD/ediot) - (Ruby) Electronic Data Interexchange Open Transformer (transforms EDI-834 into CSV)
- [irobayna/stupidedi](https://github.com/irobayna/stupidedi) - Ruby API for parsing and generating ASC X12 EDI transactions.
- [greasysock/CahasEDI-Dashboard](https://github.com/greasysock/CahasEDI-Dashboard) - User interface for CahasEDI-Core built on rails.
- [tcd/eddy](https://github.com/tcd/eddy) - 🧨 EDI toolkit (WIP)
### Rust
- [sezna/edi](https://github.com/sezna/edi) - Rust crate for parsing X12 EDI and acting on it. Supports serialization to a variety of formats including JSON.

### Golang
- [jf-tech/omniparser](https://github.com/jf-tech/omniparser) - omniparser is a native Golang ETL parser that ingests input data of various
formats (CSV, txt, fixed length/width, XML, EDI/X12/EDIFACT, JSON, and custom formats) in streaming fashion and transforms data into desired
JSON output based on a schema written in JSON. See [EDI](https://github.com/jf-tech/omniparser/blob/master/doc/edi_in_depth.md) and
[EDI readers](https://github.com/jf-tech/omniparser/blob/master/doc/programmability.md#full-edi-reader) for more usage details.
- [moov-io/x12](https://github.com/moov-io/x12) - ASC X12 standards reader/writer 

## CLI utilities
- [azoner/pyx12](https://github.com/azoner/pyx12) - (Python) HIPAA X12 document validator and converter
- [lanceengland/EdiTools](https://github.com/lanceengland/EdiTools) - EdiTools is a repository of PowerShell scripts for parsing EDI X12 files.
- [notpeter/edicat](https://github.com/notpeter/edicat) - Print and concatenate X12 and Edifact EDI
- [clarkema/x12pp](https://github.com/clarkema/x12pp) - Fast cross-platform X12 pretty-printer in Rust


## Systems or Paid Services
- [abhishek-ram/pyas2](https://github.com/abhishek-ram/pyas2) - A pythonic AS2 client and server
- [bots-edi/bots](https://github.com/bots-edi) - Bots EDI Translator
- [Campbellony/X12SqlServer](https://github.com/campbellony/x12sqlserver) - Simple X12 data model with TSQL parsing procedures
- [EdiFabric/X12-Examples](https://github.com/EdiFabric/X12-Examples) - X12 and HIPAA Examples for EdiFabric EDI Tools
- [EdiFabric/EDIFACT-Examples](https://github.com/EdiFabric/EDIFACT-Examples) -  EDIFACT and EANCOM Examples for EdiFabric EDI Tools
- [EDIJunction](https://edi-junction.com) - EDIFACT & X12 json conversion API.
- [MicrosoftDocs/biztalk-docs](https://github.com/MicrosoftDocs/biztalk-docs) - Microsoft Biztalk documentation
- [Mulesoft](https://github.com/mulesoft) - Collection of Mulesoft Repositories.
- [BerryWorksSoftware/edireader](https://github.com/BerryWorksSoftware/edireader) - EDIReader is a Java package for parsing business documents structured according to EDI standards. It supports the SAX and JAXP interfaces defined for XML, making it suitable for use in any XML-based system that allows the configuration of a custom SAX parser.
- [EDIdEv](https://www.edidev.com) - The EDIdEv Framework EDI (FREDI) solution is comprised of an EDI tool and a customizable EDI application. 
- [Odoo](https://github.com/odoo/odoo) - Odoo. Open Source Apps To Grow Your Business. 
- [nextgenhealthcare](https://github.com/nextgenhealthcare/connect) - The swiss army knife of healthcare integration. 
- [OCA/edi](https://github.com/OCA/edi) - EDI Modules for Ooda
- [Javonet/RDPCrystal](https://github.com/Javonet/RDPCrystal) - Java based EDI platform with example EDI solutions.
- [EDI Platform](https://www.stedi.com/edi-platform) - Simplify your EDI. Onboard partners fast. Integrate once.
- [smooks/smooks-edi-cartridge](https://github.com/smooks/smooks-edi-cartridge) - Smooks EDI & EDIFACT cartridges for reading as well as writing EDI.

## Examples
- [Edipique/EDI-X12](https://github.com/dipique/EDI-X12) - Rough process for generating EDI X12 834 and 837 files from a CSV file. Structured in a way that allows easy transition to other data sources.
- [PHP Implementations of Transactions](https://github.com/stephenmccready/X12) - PHP examples of writing EDI from scratch.
- [walkswithme/EDI-X12-ANSI-270](https://github.com/walkswithme/EDI-X12-ANSI-270) - PHP Library for creating EDI X12 ANSI 270 File 5010 Version
- [EdiFabric/EDI-Translator-Demo](https://github.com/EdiFabric/EDI-Translator-Demo) - EDI Translator for EDIFACT D.96A, X12 004010 and HIPAA 5010
- [EDI Bootstrap (Stedi)](https://github.com/Stedi-Demos/bootstrap) - open-source, end-to-end system to generate and parse X12 EDI from a JSON

## Public EDI References
- [X12 Reference](https://www.stedi.com/edi/x12) - Free online viewer for all releases of X12 specifications.
- [EDI Guide Catalog](https://www.stedi.com/edi/catalog) - An open directory of the most-requested Stedi Guides, interactive EDI specifications that let you instantly validate EDI documents.
- [EDIFACT Reference](https://www.stedi.com/edi/edifact) - Free online viewer for all releases of EDIFACT specifications.

## Syntax Highlighters
- [josesanchezcapo/sublime-x12-highlighting](https://github.com/josesanchezcapo/sublime-x12-highlighting) - Adds syntax highlighting to Sublime for x12 files. Made especially for the healthcare EDI space. (837s, etc.)
- [michaelachrisco/sublime-834-syntax](https://github.com/michaelachrisco/sublime-834-syntax) - Sublime syntax highlighter for the EDI x12 834 file.
- [clarkema/x12-mode](https://github.com/clarkema/x12-mode) - An Emacs major mode for X12 EDI files
- [Notepad++](https://gist.github.com/bhattisatish/6b5f5c90443a64cef192) - A user-defined language file for highlighting EDI X12.
- [Silvenga/vscode-edi-x12-support](https://github.com/Silvenga/vscode-edi-x12-support) - A Visual Studio Code extension aimed at providing basic support for the EDI format.
- [vim-scripts/x12-syntax](https://github.com/vim-scripts/x12-syntax) - A simple syntax highlighter for EDI X12 files. Currently only Healthcare 270/271s are tested.
- [DAXaholic/vscode-edifact](https://github.com/DAXaholic/vscode-edifact) - Visual Studio Code extension providing basic language support for EDIFACT files.
- [hellooops/Edi Support](https://github.com/hellooops/vscode-edi-support) - Visual Studio Code extension providing language support for X12/HIPAA and EDIFACT

## Free Online EDI editors
- [EDI Inspector](https://www.stedi.com/edi/inspector) - A tool for inspecting EDI files and getting a free JSON conversion.
## Standalone editors
- [RKDN/x12Tool](https://github.com/RKDN/x12Tool) - A tool for reading and modifying x12/EDI files.
