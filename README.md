# PythonPart SOM2_1Attribute

FOR ENGLISH VERSION SEE [BELOW](#SOMAttributes)!

Das PythonPart ermöglicht die Umsetzung der von der **DB InfraGO AG** gestellten Anforderungen an die Semantik, also die Alphanumerik der Objekte und Bauteile **SOM** (**S**emantic**O**bject**M**odel) in ALLPLAN. Damit lassen sich die meisten der hierfür erforderlichen Schritte mehr oder weniger automatisch ausführen:
- **Definition** der erforderlichen Attribute
- **Zuweisung** von Attributen and die relevanten Objekte
- **Erstellung** eines angepassten **Attributmapping** für den IFC Export

Ein zusätzlicher Filter erlaubt die Einschränkung des Attribute- und Objektumfangs auf das für die aktuelle **Leistungsphase** oder **UseCase** erforderliche Maß.

Basis für sämtliche Einzelschritte bilden die **Excel Dateien** **DB_InfraGO_AG_Fahrweg_SOM_2.1.1-A03.xlsx** und **DB-InfraGO-AG-Fahrweg-SOM-2-1-1_Projektanforderungen.xlsx**. Sie werden daher zusammen mit dem PythonPart zur Verfügung gestellt.

> ⚠️ACHTUNG\
Da sich der Status der Excel Dateien seit der Bereitstellung des PythonParts geändert haben kann, sollten diese immer über die offizielle Seite der **DB_InfraGO_AG** auf Aktualität überprüft werden.

## Installation

Das PythonPart **SOM2_1Attribute** lässt sich direkt über den PluginManager in ALLPLAN installieren. 

Alternativ kann die ***.allep** Datei von der zugehörigen [Release Website](https://github.com/AnkeNiedermaier/som-attributes-public/releases) direkt heruntergeladen werden. Bei ***.allep** Dateien handelt es sich um ein internes ALLPLAN Setup, das sich per Drag und Drop in das Programmfenster installieren lässt.

Voraussetzung zur Installation des PythonParts ist die ALLPLAN Version 2026.

## Installiertes PythonPart Script

Nach erfolgreicher Installation ist die Datei **SOM2_1Attribute.pyp** zusammen mit den Excel Dateien in der ALLPLAN Bibliothek zu finden:
`Std` → `Library` → `ALLPLAN GmbH` → `SOM2_1Attribute`

Das PythonParts wird neben der Bibliothek auch in einem neu angelegten Aufgabenbereich **SOM_Attributes** in der Aufgabe **Plug-in** in die ActionBar aufgenommen.


# SOMAttributes

The PythonPart enables the implementation of the requiremtes from **DB InfraGO AG** (German Railway Sytem) for the semantic, that means the alphanumeric, of objects and building components, the so called **SOM** (**S**emantic**O**bject**M**odel) in ALLPLAN. Most of the necessary steps can be executed more or less automatically:
- **define** the required attributes
- **assign** attributes to dedicated objects
- **create** an adapted **mapping table** for the IFC export

An additional filter allows the adoption of the attributes to the range needed for the current **project phase** or **UseCase**.

The **Excel files** **DB_InfraGO_AG_Fahrweg_SOM_2.1.1-A03.xlsx** and **DB-InfraGO-AG-Fahrweg-SOM-2-1-1_Projektanforderungen.xlsx** serve as Basis for the individual steps. Therefor they are also delivered with the PythonPart.

> ⚠️IMPORTANT\
As the status of the Excel file might have been changed since the PythonPart has been published or installed, it should always be checked for Updates on the official **DB_InfraGO_AG** site.

## Installation

The PythonPart **SOM2_1Attribute** can be installed directly from the PluginManager in ALLPLAN. 

Alternatively, the corresponding ***.allep** package can be downloaded from the [release page](https://github.com/AnkeNiedermaier/som-attributes-public/releases). ***.allep** files are ALLPLAN internal setups that can be installed via drag and drop into the program window.

At least the version 2026 is needed to install the PythonPart.

## Installed PythonPart Scripts

If the installation was successfull, the PythonPart **SOM2_1Attribute.pyp** can be found
in the ALLPLAN Library:
`Office` → `Library` → `ALLPLAN GmbH` → `SOM2_1Attribute`

Besides the library, the PythonPart can also be found in the ActionBar in a newly created task area **SOM_Attributes** inside the task **Plug-ins**.