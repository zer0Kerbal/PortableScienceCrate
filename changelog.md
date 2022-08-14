# Changelog  
  
| modName    | Portable Science Crate (PSC)                                      |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-4.0                                                         |
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
* rename parts to standardized names (e.g. drop-)
  * <WrapperTankLong> --> <drop-tank-sleeve> v2.0.0.0
  * <WrapperTankBracelet> --> <drop-tank-bracelet> v2.0.0.0
  * <WrapperTank> --> <drop-tank-wrapper> v2.0.0.0
  * <WrapperCap> --> <drop-tank-cap> v2.0.0.0
  * <WrapperTankWristband> --> <drop-tank-wristband> v2.0.0.0
  * Add
    * <ghostParts.cfg> v1.3.0.1
    * in order to prevent name changes from breaking compatibility
* closes #27 - Asset Updates

### Compatibility 1.0.99.0

* Add
  * <InterstellarFuelSwitch.cfg> v1.0.0.0
  * <TweakScale.cfg> v1.0.0.0

### Documentation

* Update
  * [Readme.md]
  * [.version]
    * remove [KSP_VERSION_MAX]

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
