# .claude Folder

## Overview

This directory contains standardized templates for creating .claude folders throughout the AGENTIC_INFRASTRUCTURE. These templates ensure consistency, proper context inheritance, and comprehensive documentation for all AI agents working within the system.

## Template Types

### Basic Template (`basic/`)
**Use for**: General directories, simple components, basic organizational structures

**Files included**:
- `CLAUDE.md` - Main context and documentation file
- `settings.json` - Component configuration and metadata
- `navigation.md` - Hierarchical relationships and navigation paths

### Component Template (`component/`)
**Use for**: Functional components with specific capabilities, tools, or services

**Files included**:
- All basic template files plus:
- `capabilities.md` - Detailed capability documentation
- `integration.md` - Integration patterns and examples

### System Template (`system/`)
**Use for**: Major system-level components, cognitive cores, infrastructure layers

**Files included**:
- All component template files plus:
- `architecture.md` - Detailed architectural documentation
- `security.md` - Security model and compliance requirements
- `evolution.md` - Development roadmap and evolution tracking

## Quick Deployment Guide

### Method 1: Manual Template Application

1. **Choose appropriate template type**:
   ```bash
   # For basic directories
   cp -r C:\AGENTIC_INFRASTRUCTURE\.claude\templates\basic\ [target_directory]\.claude\
   
   # For functional components  
   cp -r C:\AGENTIC_INFRASTRUCTURE\.claude\templates\component\ [target_directory]\.claude\
   
   # For system-level components
   cp -r C:\AGENTIC_INFRASTRUCTURE\.claude\templates\system\ [target_directory]\.claude\
   ```

2. **Customize the template**:
   - Replace all `[PLACEHOLDER]` values with actual information
   - Update hierarchy paths and relationships
   - Add specific functionality documentation
   - Set current status and metrics

3. **Verify context inheritance**:
   - Ensure parent .claude folders exist and are referenced correctly
   - Check that hierarchical relationships are accurate
   - Validate navigation paths

### Method 2: Using Claude Code Commands

Use the custom slash commands in the `commands/` directory:

```bash
# In Claude Code session
/project:create-claude-folder basic
/project:create-claude-folder component  
/project:create-claude-folder system
```

## Template Placeholders

### Common Placeholders
- `[DIRECTORY_NAME]` - Name of the current directory
- `[FULL_PATH]` - Complete path from AGENTIC_INFRASTRUCTURE root
- `[PARENT_COMPONENT]` - Name of parent component/system
- `[CURRENT_LEVEL]` - Description of current hierarchy level
- `[STATUS]` - Current operational status
- `[DATE]` - Current date (YYYY-MM-DD format)

### Hierarchy Placeholders
- `[PARENT_LEVEL]` - Parent hierarchy level name
- `[PARENT_DESCRIPTION]` - Parent level description
- `[CURRENT_DESCRIPTION]` - Current level description

### Component Placeholders
- `[COMPONENT_NAME]` - Technical component name
- `[COMPONENT_TYPE]` - Type category of component
- `[PRIMARY_ROLE_DESCRIPTION]` - Main role within the system
- `[SCOPE_DESCRIPTION]` - Scope of influence/operation

## Customization Guidelines

### Required Customizations
1. **All placeholders must be replaced** - Do not leave any `[PLACEHOLDER]` text
2. **Hierarchy paths must be accurate** - Verify all parent/child relationships
3. **Status must reflect reality** - Use accurate operational status indicators
4. **Metrics must be current** - Include actual operational metrics where applicable

### Optional Customizations
1. **Add component-specific sections** - Extend templates for unique requirements
2. **Include additional files** - Add specialized documentation as needed
3. **Enhance navigation** - Add project-specific navigation shortcuts
4. **Expand integration details** - Document specific integration patterns

## Standards Compliance

### Required Files
Every .claude folder MUST contain:
- `CLAUDE.md` - Primary context file (stored in .claude folder, not root directory)
- `settings.json` - Component metadata and configuration

### Recommended Files
- `navigation.md` - For components with complex relationships
- Additional specialized files based on component type

### File Naming Conventions
- Use lowercase with hyphens for multi-word files: `integration-guide.md`
- Keep file names descriptive and specific
- Maintain consistency across similar components

## Context Inheritance Chain

Every .claude folder participates in the context inheritance chain:

```
AGENTIC_INFRASTRUCTURE/.claude/          [Root Context]
├── Universal agent rules                 
├── Multi-dimensional framework          
├── Security standards                   
└── Development protocols                

DIGITAL_CORE/.claude/                    [Layer Context]  
├── Computational substrate principles   
├── Agent-centric design patterns       
├── Scalability requirements            
└── Integration standards               

CENTRAL_INTELLIGENCE/.claude/            [System Context]
├── Cognitive coordination              
├── Multi-agent management              
├── Tool access patterns               
└── Knowledge preservation             

COMPONENT/.claude/                       [Component Context]
├── Specific functionality             
├── Local configuration               
├── Integration details               
└── Operational metrics               
```

## Quality Assurance

### Validation Checklist
- [ ] All placeholders replaced with actual values
- [ ] Hierarchy relationships are accurate and current
- [ ] Status indicators reflect actual operational state
- [ ] Navigation paths are tested and functional
- [ ] Parent .claude folders exist and are referenced
- [ ] Integration points are documented and verified
- [ ] Metrics are current and meaningful

### Maintenance Requirements
- Update templates when system architecture changes
- Refresh metrics and status indicators regularly
- Verify navigation paths remain accurate
- Ensure new components follow established patterns
- Review and update customization guidelines

## Integration with Development Workflow

### For New Directory Creation
1. **Always create .claude folder** when creating new directories
2. **Choose appropriate template** based on directory purpose
3. **Customize immediately** - don't leave placeholder text
4. **Verify context chain** - ensure proper inheritance
5. **Test navigation paths** - confirm all links work

### For AI Agents
- **Read .claude/CLAUDE.md first** when entering any directory
- **Follow context inheritance** - understand the full hierarchy
- **Update documentation** when making changes
- **Maintain template standards** when creating new folders
- **Use navigation.md** for understanding relationships

This template system ensures that every component of the AGENTIC_INFRASTRUCTURE maintains comprehensive context documentation, enabling effective AI agent operation and seamless human-AI collaboration.