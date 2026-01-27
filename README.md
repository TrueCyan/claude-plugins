# TrueCyan's Claude Code Plugins

Claude Code plugins marketplace by TrueCyan.

## Installation

```bash
# Add marketplace (once)
/plugin marketplace add TrueCyan/claude-plugins

# Install plugins
/plugin install claude-smart-context@truecyan-plugins
```

## Available Plugins

### claude-smart-context

Smart context management for Claude Code.

- **Fast Compaction**: Uses `/clear` instead of slow LLM-based `/compact`
- **Progressive Summarization**: Continuously saves context to external files
- **Auto Context Switching**: Detects task changes and manages transitions
- **Archive Access**: Instantly load previous work context

[View Repository](https://github.com/TrueCyan/claude-smart-context)

## License

MIT
