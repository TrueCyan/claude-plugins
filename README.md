# TrueCyan's Claude Code Plugins

Claude Code plugins marketplace by TrueCyan.

## Installation

```bash
# Add marketplace (once)
/plugin marketplace add TrueCyan/claude-plugins

# Install plugins
/plugin install claude-smart-context@truecyan-plugins
/plugin install smart-approve@truecyan-plugins
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

### smart-approve

Smart Bash command auto-approval - 읽기 전용 명령과 유저가 요청한 명령을 자동 수락.

- **Rule-Based**: `ls`, `git status` 등 명확한 읽기 명령 즉시 자동 수락
- **npm Scripts**: `package.json`의 scripts를 읽어 실제 명령어 분석
- **Static Analysis**: 스크립트 파일 내용을 분석하여 쓰기 작업 감지
- **LLM + User Intent**: 대화 기록에서 유저 의도를 파악하여, 유저가 요청한 명령은 자동 수락

[View Repository](https://github.com/TrueCyan/smart-approve)

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
