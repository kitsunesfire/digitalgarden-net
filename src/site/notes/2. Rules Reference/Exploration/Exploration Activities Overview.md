---
database-plugin: basic
dg-publish: true
---

```yaml:dbfolder
name: new database
description: new description
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 0
    isHidden: false
    sortIndex: 1
    isSorted: true
    isSortedDesc: false
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  __tags__:
    key: __tags__
    id: __tags__
    input: metadata_tags
    label: File Tags
    accessorKey: __tags__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: false
    position: 0
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Description:
    input: text
    accessorKey: Description
    key: Description
    id: Description
    label: Description
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 226
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      wrap_content: true
  Campsite_Required?:
    input: select
    accessorKey: Campsite_Required?
    key: Campsite_Required?
    id: Campsite_Required?
    label: Campsite_Required?
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "No", value: "No", color: "hsl(0,0%,10%)"}
      - { label: "Yes", value: "Yes", color: "hsl(0,0%,67%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Settlement_Required?:
    input: select
    accessorKey: Settlement_Required?
    key: Settlement_Required?
    id: Settlement_Required?
    label: Settlement_Required?
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "No", value: "No", color: "hsl(0,0%,10%)"}
      - { label: "Yes", value: "Yes", color: "hsl(0,0%,67%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  NPC_Required?:
    input: select
    accessorKey: NPC_Required?
    key: NPC_Required?
    id: NPC_Required?
    label: NPC_Required?
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "No", value: "No", color: "hsl(0,0%,10%)"}
      - { label: "Yes", value: "Yes", color: "hsl(0,0%,67%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Skill_Training_Required?:
    input: select
    accessorKey: Skill_Training_Required?
    key: Skill_Training_Required?
    id: Skill_Training_Required?
    label: Skill_Training_Required?
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "None", value: "None", color: "hsl(0,0%,10%)"}
      - { label: "Arcana", value: "Arcana", color: "hsl(96, 95%, 90%)"}
      - { label: "Intimidation", value: "Intimidation", color: "hsl(281, 95%, 90%)"}
      - { label: "Survival", value: "Survival", color: "hsl(183, 95%, 90%)"}
      - { label: "Society", value: "Society", color: "hsl(317, 95%, 90%)"}
      - { label: "Diplomacy", value: "Diplomacy", color: "hsl(181, 95%, 90%)"}
      - { label: "Crafting", value: "Crafting", color: "hsl(111, 95%, 90%)"}
      - { label: "Varies", value: "Varies", color: "hsl(268, 95%, 90%)"}
      - { label: "Deception", value: "Deception", color: "hsl(358, 95%, 90%)"}
      - { label: "Nature", value: "Nature", color: "hsl(182, 95%, 90%)"}
      - { label: "Acrobatics", value: "Acrobatics", color: "hsl(82, 95%, 90%)"}
      - { label: "Medicine", value: "Medicine", color: "hsl(151, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Minimum_Recon_Points:
    input: text
    accessorKey: Minimum_Recon_Points
    key: Minimum_Recon_Points
    id: Minimum_Recon_Points
    label: Minimum_Recon_Points
    position: 100
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: false
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: true
  source_data: tag
  source_form_result: "#Exploration"
  source_destination_path: /
  row_templates_folder: /
  current_row_template: 
  pagination_size: 100
  font_size: 16
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```