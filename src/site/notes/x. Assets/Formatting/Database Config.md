---
{"dg-publish":true,"permalink":"/x-assets/formatting/database-config/"}
---

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
    accessor: __file__
    position: 1
    isSorted: true
    isSortedDesc: false
    width: -9
    isHidden: false
    sortIndex: 1
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
      source_data: current_folder
      wrap_content: true
  Gender:
    input: select
    accessor: Gender
    key: Gender
    label: Gender
    position: 7
    skipPersist: false
    accessorKey: Gender
    width: 77
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Female", backgroundColor: "hsl(302,87%,21%)"}
      - { label: "Male", backgroundColor: "hsl(228,82%,29%)"}
      - { label: "N/A", backgroundColor: "hsl(146,88%,20%)"}
      - { label: "Other", backgroundColor: "hsl(55,97%,27%)"}
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
      source_data: current_folder
  Age:
    input: select
    accessor: Age
    key: Age
    label: Age
    position: 8
    skipPersist: false
    accessorKey: Age
    width: 126
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Adult", backgroundColor: "hsl(170,61%,24%)"}
      - { label: "Ancient", backgroundColor: "hsl(287,63%,25%)"}
      - { label: "Child", backgroundColor: "hsl(32,91%,25%)"}
      - { label: "Elderly", backgroundColor: "hsl(258,57%,28%)"}
      - { label: "Infant", backgroundColor: "hsl(6,70%,25%)"}
      - { label: "Mature Adult", backgroundColor: "hsl(214,56%,28%)"}
      - { label: "Teen", backgroundColor: "hsl(52,79%,26%)"}
      - { label: "Young Adult", backgroundColor: "hsl(86,53%,32%)"}
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
      source_data: current_folder
  NoteIcon:
    input: select
    accessor: NoteIcon
    key: NoteIcon
    label: NoteIcon
    position: 19
    skipPersist: false
    accessorKey: NoteIcon
    width: 150
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Character", backgroundColor: "hsl(220,2%,32%)"}
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
      source_data: current_folder
  Condition:
    input: select
    accessor: Condition
    key: Condition
    label: Condition
    position: 9
    skipPersist: false
    accessorKey: Condition
    width: 109
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Dead", backgroundColor: "hsl(280,23%,33%)"}
      - { label: "Dying", backgroundColor: "hsl(323,30%,45%)"}
      - { label: "Healthy", backgroundColor: "hsl(121,35%,38%)"}
      - { label: "Hurt", backgroundColor: "hsl(10,31%,46%)"}
      - { label: "Sick", backgroundColor: "hsl(73,33%,49%)"}
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
      source_data: current_folder
  Location:
    input: select
    accessor: Location
    key: Location
    label: Location
    position: 10
    skipPersist: false
    accessorKey: Location
    width: 158
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Seithran", backgroundColor: "hsl(181,96%,20%)"}
      - { label: "Johtaja", backgroundColor: "hsl(32,100%,23%)"}
      - { label: "Seiken", backgroundColor: "hsl(256,83%,30%)"}
      - { label: "United Altos Isles", backgroundColor: "hsl(197,38%,28%)"}
      - { label: "Unknown", backgroundColor: "hsl(225,9%,26%)"}
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
      source_data: current_folder
  Occupation:
    input: tags
    accessor: Occupation
    key: Occupation
    label: Occupation
    position: 16
    skipPersist: false
    accessorKey: Occupation
    width: 132
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Adventurer", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Alchemist", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Archeologist", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Barkeeper", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Blacksmith", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Courier", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Enchanter", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Farmer", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Guard", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Historian", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Libarian", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Mage", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Merchant", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Noble", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Priest", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Royal", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Servant", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Stablehand", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Steward", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Teacher", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Hunter", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Student", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Housekeeper", backgroundColor: "hsl(240,3%,23%)"}
      - { label: "Nanny", backgroundColor: "hsl(240,3%,23%)"}
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
      source_data: current_folder
  WhichParty:
    input: select
    accessor: WhichParty
    key: WhichParty
    label: WhichParty
    position: 18
    skipPersist: false
    accessorKey: WhichParty
    width: 138
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Core Party", backgroundColor: "hsl(0,100%,21%)"}
      - { label: "SideCharacter", backgroundColor: "hsl(44,81%,31%)"}
      - { label: "Paralogue", backgroundColor: "hsl(233,95%,26%)"}
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
      source_data: current_folder
  Type:
    input: tags
    accessor: Type
    key: Type
    label: Type
    position: 17
    skipPersist: false
    accessorKey: Type
    width: 66
    isHidden: false
    sortIndex: -1
    options:
      - { label: "NPC", backgroundColor: "hsl(175,17%,44%)"}
      - { label: "VIP", backgroundColor: "hsl(38,20%,51%)"}
      - { label: "PC", backgroundColor: "hsl(220,9%,32%)"}
      - { label: "SessionJournal", backgroundColor: "hsl(315, 95%, 90%)"}
      - { label: "City", backgroundColor: "hsl(4, 95%, 90%)"}
      - { label: "Ancestry", backgroundColor: "hsl(115, 95%, 90%)"}
      - { label: "Faction", backgroundColor: "hsl(317, 95%, 90%)"}
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
      source_data: current_folder
  Likes:
    input: text
    accessorKey: Likes
    key: Likes
    label: Likes
    position: 14
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
  Dislikes:
    input: text
    accessorKey: Dislikes
    key: Dislikes
    label: Dislikes
    position: 15
    skipPersist: false
    isHidden: false
    width: 103
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
  Art:
    input: text
    accessorKey: Art
    key: Art
    id: Art
    label: Art
    position: 2
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 177
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
  Party1Standing:
    input: select
    accessorKey: Party1Standing
    key: Party1Standing
    id: PartyStanding
    label: Party1Standing
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Friend", backgroundColor: "hsl(244,27%,35%)"}
      - { label: "Family", backgroundColor: "hsl(209,27%,31%)"}
      - { label: "Ally", backgroundColor: "hsl(91,24%,35%)"}
      - { label: "Enemy", backgroundColor: "hsl(4,68%,27%)"}
      - { label: "Unmet", backgroundColor: "hsl(22,10%,16%)"}
      - { label: "Acquaintance", backgroundColor: "hsl(10,53%,34%)"}
      - { label: "Lover", backgroundColor: "hsl(337,38%,36%)"}
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
  Ancestry:
    input: select
    accessor: Race
    key: Ancestry
    label: Ancestry
    position: 5
    skipPersist: false
    accessorKey: Ancestry
    width: 128
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Dwarf", backgroundColor: "hsl(0,77%,29%)"}
      - { label: "Elf", backgroundColor: "hsl(179,57%,35%)"}
      - { label: "Human", backgroundColor: "hsl(0,0%,35%)"}
      - { label: "Catfolk", backgroundColor: "hsl(24,22%,36%)"}
      - { label: "Dragonborn", backgroundColor: "hsl(41,47%,20%)"}
      - { label: "Vathi", backgroundColor: "hsl(258,64%,27%)"}
      - { label: "Grippli", backgroundColor: "hsl(132,68%,28%)"}
      - { label: "Kitsune", backgroundColor: "hsl(32,73%,28%)"}
      - { label: "Kobold", backgroundColor: "hsl(281,39%,27%)"}
      - { label: "Lizardfolk", backgroundColor: "hsl(96,63%,16%)"}
      - { label: "Nagaji", backgroundColor: "hsl(90,59%,31%)"}
      - { label: "Ratfolk", backgroundColor: "hsl(55,60%,33%)"}
      - { label: "Silufae", backgroundColor: "hsl(232,32%,33%)"}
      - { label: "Tengu", backgroundColor: "hsl(206,45%,24%)"}
      - { label: "Vishkanya", backgroundColor: "hsl(78,41%,22%)"}
      - { label: "Dragon", backgroundColor: "hsl(126,18%,11%)"}
      - { label: "Nephilim", backgroundColor: "hsl(182,37%,18%)"}
      - { label: "Malak", backgroundColor: "hsl(315,74%,21%)"}
      - { label: "Eldest", backgroundColor: "hsl(234,43%,13%)"}
      - { label: "Empyrean", backgroundColor: "hsl(290,40%,21%)"}
      - { label: "Seraph", backgroundColor: "hsl(44,38%,46%)"}
      - { label: "Beast", backgroundColor: "hsl(9,97%,14%)"}
      - { label: "Deva", backgroundColor: "hsl(157,71%,23%)"}
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
      source_data: current_folder
      wrap_content: true
  Heritage:
    input: select
    accessorKey: Heritage
    key: Heritage
    id: Heritage
    label: Heritage
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Half-Elf", backgroundColor: "hsl(173,55%,28%)"}
      - { label: "Half-Dwarf", backgroundColor: "hsl(12,86%,28%)"}
      - { label: "Devakim", backgroundColor: "hsl(157,82%,17%)"}
      - { label: "Seraphim", backgroundColor: "hsl(44,80%,29%)"}
      - { label: "Malakim", backgroundColor: "hsl(315,66%,32%)"}
      - { label: "Skilled", backgroundColor: "hsl(0,0%,26%)"}
      - { label: "Nephilim", backgroundColor: "hsl(19, 95%, 90%)"}
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
  Description:
    input: text
    accessorKey: Description
    key: Description
    id: Description
    label: Description
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 169
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
      content_vertical_alignment: align-middle
      content_alignment: text-align-center
  Faction:
    input: tags
    accessor: AssociatedGroup
    key: Faction
    label: Faction
    position: 12
    skipPersist: false
    accessorKey: Faction
    width: 207
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Argent Phoenix Company", backgroundColor: "hsl(0,98%,18%)"}
      - { label: "Drakengard", backgroundColor: "hsl(0,98%,18%)"}
      - { label: "Greyshield Battalion", backgroundColor: "hsl(0,98%,18%)"}
      - { label: "League of Explorers", backgroundColor: "hsl(0,98%,18%)"}
      - { label: "Royal Bird Watching Society", backgroundColor: "hsl(0,98%,18%)"}
      - { label: "Acquolina", backgroundColor: "hsl(32,97%,23%)"}
      - { label: "AltidiSassari", backgroundColor: "hsl(32,97%,23%)"}
      - { label: "Emberlight Forge Council", backgroundColor: "hsl(32,97%,23%)"}
      - { label: "Flint Mechanim", backgroundColor: "hsl(32,97%,23%)"}
      - { label: "Followers of the Broken Blade", backgroundColor: "hsl(32,97%,23%)"}
      - { label: "Holly & Ivy", backgroundColor: "hsl(32,97%,23%)"}
      - { label: "Horological Society", backgroundColor: "hsl(32,97%,23%)"}
      - { label: "Papermakers Guild", backgroundColor: "hsl(32,97%,23%)"}
      - { label: "Sisters of Stone", backgroundColor: "hsl(32,97%,23%)"}
      - { label: "Staffcrafters Guild", backgroundColor: "hsl(32,97%,23%)"}
      - { label: "Stone and Iron Builder's Collective", backgroundColor: "hsl(32,97%,23%)"}
      - { label: "The Stockwood Guild", backgroundColor: "hsl(32,97%,23%)"}
      - { label: "The Aria", backgroundColor: "hsl(32,97%,23%)"}
      - { label: "Camorra Family", backgroundColor: "hsl(52,91%,18%)"}
      - { label: "Cipher", backgroundColor: "hsl(52,91%,18%)"}
      - { label: "Evergreen", backgroundColor: "hsl(52,91%,18%)"}
      - { label: "Irae Nox", backgroundColor: "hsl(52,91%,18%)"}
      - { label: "Shiverblade Nigh", backgroundColor: "hsl(52,91%,18%)"}
      - { label: "The Web", backgroundColor: "hsl(52,91%,18%)"}
      - { label: "Vary Y Zagone", backgroundColor: "hsl(52,91%,18%)"}
      - { label: "Whisperwyn", backgroundColor: "hsl(52,91%,18%)"}
      - { label: "Carnation", backgroundColor: "hsl(99,83%,14%)"}
      - { label: "Chandelier", backgroundColor: "hsl(99,83%,14%)"}
      - { label: "Fiddlesticks", backgroundColor: "hsl(99,83%,14%)"}
      - { label: "Karyukai", backgroundColor: "hsl(99,83%,14%)"}
      - { label: "Krasotachary Ballet", backgroundColor: "hsl(99,83%,14%)"}
      - { label: "Princes of Heaven", backgroundColor: "hsl(99,83%,14%)"}
      - { label: "Shadowsingers", backgroundColor: "hsl(99,83%,14%)"}
      - { label: "Shimbara", backgroundColor: "hsl(99,83%,14%)"}
      - { label: "Sons of Fortune", backgroundColor: "hsl(99,83%,14%)"}
      - { label: "The Sovereign Court", backgroundColor: "hsl(99,83%,14%)"}
      - { label: "The Wandering Muse", backgroundColor: "hsl(99,83%,14%)"}
      - { label: "Brazen Lion Brewery", backgroundColor: "hsl(173,95%,17%)"}
      - { label: "Harvest Garden", backgroundColor: "hsl(173,95%,17%)"}
      - { label: "Odyssey Lounge", backgroundColor: "hsl(173,95%,17%)"}
      - { label: "Sweet Staves Vineyard & Winery", backgroundColor: "hsl(173,95%,17%)"}
      - { label: "The Inner Circle", backgroundColor: "hsl(173,95%,17%)"}
      - { label: "Curio City", backgroundColor: "hsl(198,98%,18%)"}
      - { label: "Golden Griffin", backgroundColor: "hsl(198,98%,18%)"}
      - { label: "Gourmet Gorget", backgroundColor: "hsl(198,98%,18%)"}
      - { label: "Greenhouse Guild", backgroundColor: "hsl(198,98%,18%)"}
      - { label: "House of Crows", backgroundColor: "hsl(198,98%,18%)"}
      - { label: "The Book Club", backgroundColor: "hsl(198,98%,18%)"}
      - { label: "The Honorable Society of the Brass Bell", backgroundColor: "hsl(198,98%,18%)"}
      - { label: "Xian'sApothecary", backgroundColor: "hsl(198,98%,18%)"}
      - { label: "Ash'bahri", backgroundColor: "hsl(230,98%,18%)"}
      - { label: "Battle Riders", backgroundColor: "hsl(230,98%,18%)"}
      - { label: "Brotherhood of Bastards", backgroundColor: "hsl(230,98%,18%)"}
      - { label: "Hexerei", backgroundColor: "hsl(230,98%,18%)"}
      - { label: "Immortals", backgroundColor: "hsl(230,98%,18%)"}
      - { label: "Jiaoyi", backgroundColor: "hsl(230,98%,18%)"}
      - { label: "Knights", backgroundColor: "hsl(230,98%,18%)"}
      - { label: "Riders of the Storm", backgroundColor: "hsl(230,98%,18%)"}
      - { label: "Swordlords", backgroundColor: "hsl(230,98%,18%)"}
      - { label: "Waste Walkers", backgroundColor: "hsl(230,98%,18%)"}
      - { label: "The Wild Hunt", backgroundColor: "hsl(230,98%,18%)"}
      - { label: "Divine Favor", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Order of Tamara", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Order of the Chosen", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Order of the Covenant Grace", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Order of the Exorcists", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Order of the Peacekeepers", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Order of the Sacred Spirit", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Order of the Scarab Sages", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Order of the Shepherds", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Order of the Silver Laurel", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Order of the Veiled Ones", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Order of the Whispering Way", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "The Divine Order", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Seekers", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Star-Touched", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Templars", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "The Imperial Registry", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Valkyrie", backgroundColor: "hsl(258,85%,23%)"}
      - { label: "Accademia Della Monda", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Alchimia Rossini", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Beul-Aithris", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Daneshmand", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Gakuen Kereska", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Greythorn Institute", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Kadrija Academy", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Karada Ugoki", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Labratorium Alkemi", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Les Ateliers", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Lorenzo Perosi Studios", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Nevitah Consotium", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Opatija Abbey", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Parola Castelli", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Puntos de Luz", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Sacrosanct Arcana", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Saint Sacrement de la Creation", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Sapienza", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Sckolas", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Skyhold", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Taribat Modares", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "The Archive", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Whatkaaetanga Kawenata", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Yin Shendian", backgroundColor: "hsl(276,89%,18%)"}
      - { label: "Alban Arthan", backgroundColor: "hsl(313,89%,18%)"}
      - { label: "Aristocracy", backgroundColor: "hsl(313,89%,18%)"}
      - { label: "Ars Arcanum", backgroundColor: "hsl(313,89%,18%)"}
      - { label: "Circle of Fayte", backgroundColor: "hsl(313,89%,18%)"}
      - { label: "Circle of Glass", backgroundColor: "hsl(313,89%,18%)"}
      - { label: "Fraiser", backgroundColor: "hsl(313,89%,18%)"}
      - { label: "MacKenzie", backgroundColor: "hsl(313,89%,18%)"}
      - { label: "Shesten", backgroundColor: "hsl(313,89%,18%)"}
      - { label: "Society of Heavenly and Earthly Idols", backgroundColor: "hsl(313,89%,18%)"}
      - { label: "The Exchange", backgroundColor: "hsl(313,89%,18%)"}
      - { label: "Wings of Glory", backgroundColor: "hsl(313,89%,18%)"}
      - { label: "Court of Mists and Fury", backgroundColor: "hsl(336,89%,18%)"}
      - { label: "Falkan Intercontinental Railway", backgroundColor: "hsl(336,89%,18%)"}
      - { label: "Hell or High Water Shipping Fleet", backgroundColor: "hsl(336,89%,18%)"}
      - { label: "Questions ,Information and Answers", backgroundColor: "hsl(336,89%,18%)"}
      - { label: "Safe Travels Club", backgroundColor: "hsl(336,89%,18%)"}
      - { label: "The Wayfarers", backgroundColor: "hsl(336,89%,18%)"}
      - { label: "Tree Stride Transportation Company", backgroundColor: "hsl(336,89%,18%)"}
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
      source_data: current_folder
      wrap_content: true
  Faith:
    input: tags
    accessor: AssociatedReligion
    key: Faith
    label: Faith
    position: 13
    skipPersist: false
    accessorKey: Faith
    width: 78
    isHidden: false
    sortIndex: -1
    options:
      - { label: "Ihtizaz", backgroundColor: "hsl(32,87%,21%)"}
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
      source_data: current_folder
  Home:
    input: select
    accessorKey: Home
    key: Home
    id: Home
    label: Home
    position: 11
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 164
    options:
      - { label: "Seithran", backgroundColor: "hsl(182,97%,15%)"}
      - { label: "Johtaja", backgroundColor: "hsl(32,100%,17%)"}
      - { label: "Seiken", backgroundColor: "hsl(256,82%,22%)"}
      - { label: "The Fade", backgroundColor: "hsl(127,13%,26%)"}
      - { label: "Vere", backgroundColor: "hsl(216,96%,21%)"}
      - { label: "Amina Dorei", backgroundColor: "hsl(135,100%,15%)"}
      - { label: "United Altos Isles", backgroundColor: "hsl(187,100%,22%)"}
      - { label: "Heartrest", backgroundColor: "hsl(30, 95%, 90%)"}
      - { label: "Falkor", backgroundColor: "hsl(29, 95%, 90%)"}
      - { label: "The United Altos Isles", backgroundColor: "hsl(149, 95%, 90%)"}
      - { label: "The Johtaja", backgroundColor: "hsl(89, 95%, 90%)"}
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
  enable_show_state: false
  group_folder_column: 
  remove_field_when_delete_column: true
  cell_size: normal
  sticky_first_column: true
  show_metadata_created: false
  show_metadata_modified: false
  source_data: current_folder
  source_form_result: 
  show_metadata_tasks: false
  frontmatter_quote_wrap: false
  row_templates_folder: /
  current_row_template: x. Assets/Templates/NPCTemplate.md
  pagination_size: 50
  source_destination_path: /
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: top
  date_format: yyyy-MM-dd
  datetime_format: "yyyy-MM-dd HH:mm:ss"
  font_size: 16
  metadata_date_format: "yyyy-MM-dd HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions: