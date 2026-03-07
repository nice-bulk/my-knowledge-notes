# 最強の個人開発環境（バイブコーディング仕様）

「直感（Vibe）」を即座に形にするための、AIネイティブな開発スタック。
ツール間の摩擦を極限まで減らし、思考の速度でデプロイまで繋げる構成。

## 1. Frontend Stack (Speed & DX)
- **Framework**: React + TypeScript
- **Build Tool**: **Vite**
  - **選定理由**: 爆速ビルドとHMR（Hot Module Replacement）により、コードの変更を瞬時にブラウザへ反映。試行錯誤のサイクルを最速化する。

## 2. Editor & IDE (AI Native)
- **Primary Editor**: **Claude Desktop**
  - **選定理由**: 高度な推論能力を持つClaudeをメイン環境とし、チャットベースでのUI構築・ロジック生成を主軸に置く。

## 3. Context Management (AI Recognition)
- **Tool**: **Serena MCP (Model Context Protocol)**
  - **役割**: プロジェクト全体の構造、依存関係、コードベースをAIに完全理解させる。
  - **メリット**: 「あのファイルのあの関数」といった曖昧な指示を排除し、プロジェクトのコンテキストを維持したまま精度の高いコード生成を実現。

---

## 💡 バイブコーディング（Vibe Coding）の実践指針

AIとの対話を通じて「ノリ」と「直感」で形にする開発スタイルにおいて、以下の3点を重視しています。

1. **Context First**: MCPを活用し、AIがプロジェクトの「今」を常に把握している状態を作る。
2. **Immediate Feedback**: Viteによる高速フィードバックループを回し、視覚的な変化を即座に確認する。
3. **TypeScript by Default**: AIが生成するコードの型安全性を担保し、ランタイムエラーを未然に防ぐ。

> 「技術は、作りたいものを最速で形にするための魔法であるべきだ。」