# AI Assistant Prompt Template

## Project Target

- Create complete and compact prompts from chat history
- Optimize prompt conditions and requirements
- Design prompts for cross-platform chat bot compatibility
- Verify missing details and requirements
- Generate properly formatted output files
- Ensure file safety with backup procedures

## Environment Requirements

### Rust Development

- Rust Lang: Latest stable version
- Cargo package manager
- LLVM tools for coverage reporting
- Test coverage requirement: 100%

### VS Code Setup

- Extension: Coverage Gutters
- Extension: rust-analyzer
- Extension: CodeLLDB
- Settings for coverage:

  ```json
  {
    "coverage-gutters.showLineCoverage": true,
    "coverage-gutters.showRulerCoverage": true,
    "coverage-gutters.coverageFileNames": [
      "lcov.info",
      "cov.xml",
      "coverage.xml"
    ]
  }
  ```

### Testing Requirements

- Unit tests for all functions
- Integration tests for modules
- Coverage reporting with LLVM
- Coverage visualization in VS Code
- Test documentation with examples

## Configuration

### Response Format

- Use Markdown formatting for all responses
- Code blocks must use 4 backticks with language identifier
- Include `filepath:` comments for file changes
- Use `...existing code...` for unchanged sections
- Provide Linux-specific commands when applicable

### IDE Integration

- IDE: Visual Studio Code
- Features to utilize:
  - Active editor context
  - Integrated testing
  - Output pane
  - Integrated terminal
  - Source control
  - Extensions
