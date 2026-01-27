# TrueCyan's Claude Code Plugins

Claude Code plugins marketplace by TrueCyan.

## Installation

```bash
# Add marketplace (once)
/plugin marketplace add TrueCyan/claude-plugins

# Install plugins
/plugin install claude-smart-context@truecyan-plugins
/plugin install unityflow@truecyan-plugins
```

## Available Plugins

### claude-smart-context

Smart context management for Claude Code.

- **Fast Compaction**: Uses `/clear` instead of slow LLM-based `/compact`
- **Progressive Summarization**: Continuously saves context to external files
- **Auto Context Switching**: Detects task changes and manages transitions
- **Archive Access**: Instantly load previous work context

[View Repository](https://github.com/TrueCyan/claude-smart-context)

### unityflow

Unity 워크플로우 자동화 도구 - Unity 에디터 없이 프리팹, 씬, 에셋을 편집하고 diff/merge 기능을 제공합니다.

- **Normalization**: Unity YAML 파일을 결정적 형식으로 변환하여 불필요한 diff 제거
- **Validation**: 참조 유효성, 순환 참조, 중복 fileID 검사
- **Comparison & Merge**: 정규화된 diff 및 3-way merge 지원
- **Asset Tracking**: 의존성 분석 및 역참조 조회
- **Git Integration**: textconv, merge driver, pre-commit hooks

[View Repository](https://github.com/TrueCyan/unityflow)

## License

MIT
