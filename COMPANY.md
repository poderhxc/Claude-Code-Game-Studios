# Claude Code Game Studios

**Game Development Studio for AI-Assisted Development**

Turn a single Claude Code session into a full game development studio with 49 specialized agents, 72 skills, and coordinated workflows.

## Company Info

- **Name**: Claude Code Game Studios
- **Description**: A complete game studio organizational structure managed through coordinated AI agents
- **Prefix**: CCGS

## Studio Structure

This company package provides a complete organizational hierarchy for game development:

### Tier 1 — Leadership (Opus)
- **creative-director**: High-level vision and creative decisions
- **technical-director**: Technical architecture and tech stack
- **producer**: Production management and coordination

### Tier 2 — Department Leads (Sonnet)
- **game-designer**: Game mechanics and systems
- **lead-programmer**: Code architecture and review
- **art-director**: Visual direction and art bible
- **audio-director**: Audio implementation strategy
- **narrative-director**: Story and world-building
- **qa-lead**: Test strategy and quality assurance
- **release-manager**: Build and release pipeline
- **localization-lead**: Internationalization

### Tier 3 — Specialists (Sonnet/Haiku)
- **Designers**: systems-designer, level-designer, economy-designer
- **Programmers**: gameplay-programmer, engine-programmer, ai-programmer, network-programmer, tools-programmer, ui-programmer
- **Creative**: technical-artist, sound-designer, writer, world-builder, ux-designer
- **Support**: prototyper, performance-analyst, devops-engineer, analytics-engineer, security-engineer, qa-tester, accessibility-specialist, live-ops-designer, community-manager

### Engine Specialists
Choose the set matching your game engine:
- **Godot 4**: godot-specialist, godot-gdscript-specialist, godot-shader-specialist, godot-gdextension-specialist
- **Unity**: unity-specialist, unity-dots-specialist, unity-shader-specialist, unity-addressables-specialist, unity-ui-specialist
- **Unreal Engine 5**: unreal-specialist, ue-gas-specialist, ue-blueprint-specialist, ue-replication-specialist, ue-umg-specialist

## Repository Structure

```
/
├── CLAUDE.md                 # Master configuration
├── COMPANY.md                # Company definition (this file)
├── .claude/                  # Agent definitions, skills, hooks, rules
│   ├── agents/               # 49 agent definitions
│   ├── skills/               # 72 slash commands
│   ├── hooks/                # 12 automated hooks
│   ├── rules/                # 11 coding standards
│   └── docs/                 # Documentation and templates
├── src/                      # Game source code
├── assets/                   # Game assets
├── design/                   # Game design documents
├── docs/                     # Technical documentation
├── tests/                    # Test suites
├── tools/                    # Build and pipeline tools
├── prototypes/               # Throwaway prototypes
└── production/               # Production management
```

## Getting Started

1. **Configure your engine**: Run `/setup-engine` to configure for Godot, Unity, or Unreal
2. **Start onboarding**: Run `/start` to begin the guided onboarding flow
3. **Review agent roster**: See `.claude/docs/agent-roster.md` for all agents
4. **Check coordination map**: See `.claude/docs/agent-coordination-map.md` for workflows

## Resources

- **Agent Roster**: `.claude/docs/agent-roster.md`
- **Coordination Map**: `.claude/docs/agent-coordination-map.md`
- **Directory Structure**: `.claude/docs/directory-structure.md`
- **Coding Standards**: `.claude/docs/coding-standards.md`
- **Quick Start**: `.claude/docs/quick-start.md`

## License

MIT License - see LICENSE file

## Support

- **GitHub**: https://github.com/Donchitos/Claude-Code-Game-Studios
- **Issues**: https://github.com/Donchitos/Claude-Code-Game-Studios/issues
