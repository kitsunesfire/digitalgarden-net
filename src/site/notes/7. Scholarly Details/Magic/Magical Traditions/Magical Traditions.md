---
{"dg-publish":true,"permalink":"/7-scholarly-details/magic/magical-traditions/magical-traditions/","noteIcon":""}
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
    isSorted: true
    isSortedDesc: false
    sortIndex: 2
    position: 1
    isHidden: false
    width: 118
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Description:
    input: text
    accessorKey: Description
    key: Description
    id: Description
    label: Description
    position: 2
    width: 139
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
      persist_formula: false
      wrap_content: true
  Pf2e_Equivalent:
    input: tags
    accessorKey: Pf2e_Equivalent
    key: Pf2e_Equivalent
    id: Pf2e_Equivalent
    label: Pf2e Equivalent
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 105
    options:
      - { label: "Primal", value: "Primal", color: "hsl(150, 95%, 90%)"}
      - { label: "Divine", value: "Divine", color: "hsl(219, 95%, 90%)"}
      - { label: "Occult", value: "Occult", color: "hsl(207, 95%, 90%)"}
      - { label: "Arcane", value: "Arcane", color: "hsl(30, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Essences:
    input: tags
    accessorKey: Essences
    key: Essences
    id: Essences
    label: Essences
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 88
    options:
      - { label: "Matter", value: "Matter", color: "hsl(138, 95%, 90%)"}
      - { label: "Life", value: "Life", color: "hsl(40, 95%, 90%)"}
      - { label: "Spirit", value: "Spirit", color: "hsl(242, 95%, 90%)"}
      - { label: "Mind", value: "Mind", color: "hsl(345, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
  Signature_Caster(s):
    input: text
    accessorKey: Signature_Caster(s)
    key: Signature_Caster(s)
    id: Signature_Caster(s)
    label: Signature Caster(s)
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 117
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      persist_formula: false
      wrap_content: true
  newColumn6:
    input: text
    accessorKey: newColumn6
    key: newColumn6
    id: newColumn6
    label: Image
    position: 1
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
      persist_formula: false
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
  source_data: current_folder
  source_form_result: 
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
  show_metadata_tags: false
filters:
  enabled: false
  conditions:
```