# v1.0.13
- Patches the schema-field prototypes (DataModelSchemaField/SchemaField/TypeDataField) at module load so parent-less `getInitialValue` calls degrade to `{}`, fixing the SettingsApp crash on PF2e v8 + Item Piles v3.3.

# v1.0.12
- Fixes SettingsApp crash on PF2e v8 / Foundry v14 caused by parent-less `getInitialValue` calls in Item Piles' document template enumeration.

# v1.0.11
- Updates compatibility to Foundry VTT v14.

# v1.0.10
- Removes redundant Sheet Overrides, should stop warning from popping up when selecting item piles actors.

# v1.0.9
- (Haxxer) Updated sheet overrides to override all classes
- This should fix an issue in v13 where merchant sheet not overriding default loot sheet when actor from journal or sidebar.

# v1.0.8
- (Haxxer) Fixes v13 PF2e not rendering Item Piles sheets

# v1.0.7
- Sets up automated github release

# v1.0.2
- Removes previewing unidentified items which lacks a UI and will throw an error.

# v1.0.1
- First release