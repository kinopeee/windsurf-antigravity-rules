<<<<<<< HEAD
# .windsurfrules 'v5'
=======
# Windsurf / Antigravity Rules "v5"
>>>>>>> a498101 (refactor: .cursor/ を .agent/ と .windsurf/ に移行)

This repository contains custom instruction files (`.windsurfrules`) for Windsurf. 
It's an optimized adaptation of [cursorrules](https://github.com/kinopeee/cursorrules) for Windsurf Cascade.

## Structure

<<<<<<< HEAD
The configuration contains specifications for tech stacks, API version management, and project structures. Two versions are available:
- v1: A streamlined version with predefined settings
- v5: A fully configurable version with extensive customization options

Note: Testing has been conducted in specific environments and timeframes. Results may vary across different use cases and environments. Consider these `.windsurfrules` as templates for your specific project requirements.
=======
## 🌏 About This Repository / このリポジトリについて

This repository provides custom instructions optimized for **Windsurf** and **Antigravity**.  
It is a port of [cursorrules](https://github.com/kinopeee/cursorrules) adapted for Windsurf Cascade and Antigravity.

このリポジトリは、**Windsurf** および **Antigravity** 用に最適化されたカスタムインストラクションを提供します。  
別リポジトリで公開している [cursorrules](https://github.com/kinopeee/cursorrules) を Windsurf Cascade および Antigravity に移植したものです。

### 📂 Related Repositories / 関連リポジトリ

| Editor | Repository |
|--------|------------|
| **Cursor** | [kinopeee/cursorrules](https://github.com/kinopeee/cursorrules) |
| **Windsurf / Antigravity** | This repository / このリポジトリ |
>>>>>>> a498101 (refactor: .cursor/ を .agent/ と .windsurf/ に移行)

## Changelog

For the latest updates and feature additions, see the [Changelog](CHANGELOG.en.md).

## Usage

1. Place the `.windsurfrules` file in your project's root directory
   - Alternatively, paste the contents via [Windsurf - Settings] > [Set Workspace AI Rules] > [Edit Rules]
   - For full configuration control: [v5-en/.windsurfrules](v5-en/.windsurfrules)
   - For standard implementation: [v1-en/.windsurfrules](v1-en/.windsurfrules)

<<<<<<< HEAD
2. Customize the technical specifications in v5:
   - Select the relevant part and press Cmd+i (or Ctrl+i) to open and edit.
   - Without reference files, update rules using language/framework-specific best practices
   - Update specifications as your project evolves

3. Custom instructions are most effective when combined with task-specific prompts and contextual reference materials.

## Important Notes

- Effectiveness decreases if content conflicts with the Global AI Rules. Review the Global AI Rules thoroughly.

## License

Released under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

This repository does not provide support services. For Windsurf Cascade updates, follow us on X:
[X (Twitter)](https://x.com/kinopee_ai)
=======
### For Windsurf Users

```bash
# Clone the repository / リポジトリをクローン
git clone https://github.com/kinopeee/windsurf-antigravity-rules.git

# Copy to your project / プロジェクトにコピー
cp -r windsurf-antigravity-rules/ja/.windsurf ~/your-project/   # 日本語
cp -r windsurf-antigravity-rules/en/.windsurf ~/your-project/   # English
```

### For Antigravity Users

```bash
# Clone the repository / リポジトリをクローン
git clone https://github.com/kinopeee/windsurf-antigravity-rules.git

# Copy to your project / プロジェクトにコピー
cp -r windsurf-antigravity-rules/ja/.agent ~/your-project/   # 日本語
cp -r windsurf-antigravity-rules/en/.agent ~/your-project/   # English
```

See [ja/README.md](ja/README.md) or [en/README.md](en/README.md) for details.

---

## 📋 What's Included / 含まれるもの

All rule files and workflow commands are available in both Japanese and English.  
すべてのルールファイルとワークフローコマンドに日本語版と英語版があります。

### ✅ Rule Files / ルールファイル

| File | Description |
|------|-------------|
| **v5.md** | Core coding support rules / コーディング支援ルール |
| **commit-message-format.md** | Commit message conventions / コミットメッセージ規約 |
| **pr-message-format.md** | PR message conventions / PRメッセージ規約 |
| **test-strategy.md** | Test strategy rules / テスト戦略ルール |
| **prompt-injection-guard.md** | Injection defense / インジェクション防御 |

### ⚙️ Workflow Commands / ワークフロー

| File | Description |
|------|-------------|
| **commit-only.md** | Commit only / コミットのみ |
| **commit-push.md** | Commit & push / コミット＆プッシュ |
| **commit-push-pr.md** | Commit, push & PR / コミット＆プッシュ＆PR |

> **📍 File Locations / ファイル配置**
>
> | Editor | Rules | Workflows |
> |--------|-------|-----------|
> | **Windsurf** | `.windsurf/rules/` | `.windsurf/workflows/` |
> | **Antigravity** | `.agent/rules/` | `.agent/workflows/` |
>
> For details, see [ja/README.md](ja/README.md) or [en/README.md](en/README.md).

---

## 🎯 Key Features / 主な特徴

### 🇯🇵 日本語

- **GPT-5.1 & Opus 4.5 最適化**: 適応的推論を活かした効率的なタスク実行
- **3段階タスク分類**: 軽量・標準・重要タスクに応じた最適なプロセス
- **並列実行**: 独立したタスクを並列処理して処理速度を向上
- **安全なツール利用**: ファイル読み取り・編集・コマンド実行の明確なポリシー
- **包括的なガードレール**: コミット規約、PR規約、テスト戦略、セキュリティ防御

### 🇬🇧 English

- **GPT-5.1 & Opus 4.5 Optimized**: Efficient task execution leveraging adaptive reasoning
- **3-Tier Task Classification**: Optimal processes for lightweight/standard/critical tasks
- **Parallel Execution**: Improved throughput by parallelizing independent tasks
- **Safe Tool Usage**: Clear policies for file reading, editing, and command execution
- **Comprehensive Guardrails**: Commit conventions, PR conventions, test strategy, security defense

---

## 📖 Documentation / ドキュメント

### 🇯🇵 日本語

- [使い方ガイド](ja/README.md)
- [変更履歴](ja/CHANGELOG.md)
- [ルールとワークフロー](ja/doc/rules-and-workflows.md)
- [プロンプトインジェクション防御](ja/doc/prompt-injection-guard.md)

### 🇬🇧 English

- [Usage Guide](en/README.md)
- [Changelog](en/CHANGELOG.md)
- [Rules and Workflows](en/doc/rules-and-workflows.md)
- [Prompt Injection Guard](en/doc/prompt-injection-guard.md)

---

## 📄 License / ライセンス

MIT License - See [LICENSE](LICENSE) for details.  
MITライセンス - 詳細は [LICENSE](LICENSE) を参照してください。

---

## 💬 Support / サポート

### 🇯🇵 日本語

このリポジトリに公式サポートはありませんが、フィードバックは歓迎します。  
AI関連情報を X (Twitter) で発信しています: [@kinopee_ai](https://x.com/kinopee_ai)

### 🇬🇧 English

There is no official support for this repository, but feedback is welcome.  
Follow on X (Twitter) for AI-related updates: [@kinopee_ai](https://x.com/kinopee_ai)

---

## Made with ❤️ for Windsurf & Antigravity users worldwide
>>>>>>> a498101 (refactor: .cursor/ を .agent/ と .windsurf/ に移行)
