# [DIRECTORY_NAME] - Navigation & Relationships

## Hierarchical Position

```
AGENTIC_INFRASTRUCTURE/
├── .claude/                            [🏠 Root Context]
├── [LEVEL_1]/
│   ├── .claude/                        [⚡ Level 1 Context] 
│   ├── [LEVEL_2]/
│   │   ├── .claude/                    [🧠 Level 2 Context]
│   │   └── [CURRENT_DIRECTORY]/        [📍 YOU ARE HERE]
│   │       └── .claude/                [📋 Current Context]
│   └── [OTHER_COMPONENTS]/             [🔧 Related Components]
└── [OTHER_REALMS]/                     [🌐 Other Realms]
```

## Direct Relationships

### Parent Components
- **[PARENT_COMPONENT]** [🎯] - [Description]
  - Status: [STATUS]
  - Relationship: [How this component relates to parent]
  - Integration: [How they work together]

### Sibling Components
- **[SIBLING_1]** [🔧] - [Description]  
  - Relationship: [How they relate]
  - Integration: [How they work together]

- **[SIBLING_2]** [📋] - [Description]
  - Relationship: [How they relate]
  - Integration: [How they work together]

### Child Components
- **[CHILD_1]/** - [Description]
- **[CHILD_2]/** - [Description]
- **[CHILD_3]/** - [Description]

## Functional Relationships

### Tools/Services Provided To
- **[CONSUMER_1]** - [What is provided]
- **[CONSUMER_2]** - [What is provided]
- **[CONSUMER_3]** - [What is provided]

### Dependencies
- **[DEPENDENCY_1]** - [What is consumed and where it's located]
- **[DEPENDENCY_2]** - [What is consumed and where it's located]

## Navigation Paths

### From [CURRENT_DIRECTORY] To...

#### Upward (Context Inheritance)
```bash
# View parent context
cd ../
cat .claude/CLAUDE.md

# View higher level context  
cd ../../
cat .claude/CLAUDE.md

# View root infrastructure context
cd ../../../
cat .claude/CLAUDE.md
```

#### Lateral (Sibling Systems)
```bash
# Access sibling component 1
cd ../[SIBLING_1]/
cat .claude/CLAUDE.md

# Access sibling component 2
cd ../[SIBLING_2]/
cat .claude/CLAUDE.md
```

#### Downward (Child Components)
```bash
# View child component 1
cd [CHILD_1]/
cat .claude/CLAUDE.md

# View child component 2
cd [CHILD_2]/
cat .claude/CLAUDE.md
```

## Status Indicators

### Current Status: [🟢 OPERATIONAL / 🟡 IN_DEVELOPMENT / 🔴 PLANNED]
- [Status detail 1]
- [Status detail 2]
- [Status detail 3]

### Component Statuses
- **[COMPONENT_1]** 🟢 Operational
- **[COMPONENT_2]** 🟡 In Development
- **[COMPONENT_3]** 🔴 Planned

## Quick Access Commands

### [CATEGORY_1] Operations
```bash
# [Command 1 description]
[command_1]

# [Command 2 description]
[command_2]
```

### [CATEGORY_2] Operations  
```bash
# [Command 3 description]
[command_3]

# [Command 4 description]
[command_4]
```

## Integration Points

### With [INTEGRATION_CATEGORY_1]
- [Integration point 1]
- [Integration point 2]

### With [INTEGRATION_CATEGORY_2]
- [Integration point 3]
- [Integration point 4]

## Evolution Timeline

**Phase 1** ✅ [Completed phase description]
**Phase 2** ✅ [Completed phase description]  
**Phase 3** 🔄 [Current phase description]
**Phase 4** 📋 [Planned phase description]

This navigation structure enables seamless traversal between all related components while maintaining clear context about [CURRENT_DIRECTORY]'s role as the **[PRIMARY_ROLE_DESCRIPTION]** for the [SCOPE_DESCRIPTION].