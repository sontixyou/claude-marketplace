# claude-marketplace

Claude Code plugins marketplace.

## Install

```bash
claude plugin marketplace add <path-to-this-repo>
```

## Structure

```
claude-marketplace/
├── .claude-plugin/
│   └── marketplace.json
├── plugins/
│   └── .gitkeep
└── README.md
```

## Adding plugins

`plugins/` ディレクトリにプラグインを追加し、`marketplace.json` の `plugins` 配列に登録してください。
