---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- 
hdr-changelog.md v1.0.0.0
Portable Science Crate (PSC)
created: 13 May 2022
updated:
CC BY-ND 4.0 by zer0Kerbal
--># Changelog  
  
| modName    | Portable Science Crate (PSC)                                      |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-4.0                                                      |
| author     | Enceos and zer0Kerbal                                             |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209350-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/PortableScienceCrate)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/PortableScienceCrate) |
| spacedock  | (https://spacedock.info/mod/3080)                                 |
| ckan       | PortableScienceCrate                                              |

## Version 1.0.99.0-adoption - `<Thank you Enceos>` edition

* 13 Aug 2022  
* Released for Kerbal Space Program [KSP 1.12.x]

### Summary 1.0.99.0

* Adoption by zer0Kerbal

### Parts 1.0.99.0

* Update
  * [psc-science-crate] v2.0.0.0
    * [tags] #autoLOC_500696 // science
    * [angularDrag] was 2 now 2
    * [crashTolerance] was 20 now 15
    * [breakingForce] was 20 now 250
    * [breakingTorque] was 20 now 250
    * [maxTemp] was 1200 now 2900
    * [ModuleScienceContainer]
      * [storageRange] was 1.3 now 2.3
  * Add
    * [heatConductivity] = 0.04
    * [thermalMassModifier] = 5.0
    * [emissiveConstant] = 0.95
    * [ModuleConductionMultiplier]
    * [DRAG_CUBE]
    * thumbnail

### Update License

* Updated License: CC BY-SA 4.0
  * was: CC BY 4.0
* closes #25 - Updated  License

### docs/

* Add
  * [`_config.yml`]
  * [Attribution.md] v1.0.7.1
  * [ManualInstallation.md] v1.1.8.0
  * [404.md] v1.0.3.2
  * [LegalMumboJumbo.md] v1.0.5.1
  * [Localizations.md] v1.1.7.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [Parts-Catalog.md] v1.1.4.1
  * [Why.md] v1.1.0.0
* closes #26 - docs/

### Add localized tags to parts

* Add
  * [DropTankWrapper.cfg] v1.0.0.0
    * adds localized tags to parts
* closes #28 - Add localized tags to parts

### Localization 1.0.99.0

* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* Update
  * [psc-science-crate]
    * [manufacurer], [title], [description] and [tags] are localized
    * [ModuleScienceContainer] actions are now localized
* updates #5 - Localization Master
* closes #6 - English <en-us.cfg>
* closes #19 - Part Localization

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* rename
  * <ScienceCrate.cfg> to <psc-science-crate.cfg> v2.0.0.0
  * parts to standardized names (e.g. psc-)
    * [name] Science_Crate to psc-science-crate
    * Add
      * <ghostParts.cfg> v1.3.0.1
      * in order to prevent name changes from breaking compatibility
* closes #27 - Asset Updates

### Compatibility 1.0.99.0

* Add
  * <KerbalInventorySystem.cfg> v1.0.0.0

### Documentation

* Update
  * [Readme.md] v1.6.9.4
  * [_releaseNotes.md] v1.3.2.1
  * [.version]

### Status 1.0.99.0

* Issues
  * closes #1 - Portable Science Crate (PSC) 1.0.99.0-adoption `<Thank you Enceos>`
  * closes #2 - 1.0.99.0 Verify Legal Mumbo Jumbo
  * closes #3 - 1.0.99.0 Update Documentation
  * closes #4 - 1.0.99.0 Update Social Media

---

## Version 1.0.0.0-release - `<Archive>` edition

* 20 Dec 2016
* Released for Kerbal Space Program 1.2.0
* Last release by Enceos

### Status 1.0.0.0

* Issues
  * closes #24 - Previous Archival Releases

---
