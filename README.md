---
layout: default
title: "Vibe Writing実践ガイド"
description: "大学教職員向け生成AI利活用ハンドブックの作成を通じて、Vibe Writingの手法を学ぶ実践的なガイド"
---

# Vibe Writing 実践ガイド - 目次

大学教職員向け生成AI利活用ハンドブックの作成を通じて、Vibe Writingの手法を学ぶ実践的なガイドです。

🌐 **[GitHub Pagesで見る](https://nahisaho.github.io/Getting_Started_with_Vibe_Writing/)** | 📚 **[ガイド一覧](docs/)** | 🚀 **[すぐに始める](#-はじめ方)**

## 📚 ガイド文書

### 1. [Vibe Writingとは](docs/guides/what-is-vibe-writing.md)
Vibe Writingの概念と基本理念を理解し、VIBEの4要素（Value、Intent、Balance、Engagement）について学びます。

### 2. [事前準備](docs/guides/preparation.md)
Vibe Writingを実践するために必要な環境構築について説明します。
- GitHubリポジトリの作成
- 生成AIサービスの準備（Microsoft Copilot、ChatGPT、Claude、Google Gemini）
- WSLとClaude Codeのセットアップ
- VS CodeとGitHub Copilotの設定

### 3. [VIBEに基づくドキュメント戦略設計](docs/guides/vibe-strategy-design.md)
VIBEの4要素を活用した分析により、5編構成の詳細目次を作成するプロセスを説明します。
- Value（価値）の定義とプロンプト
- Intent（意図）の明確化とプロンプト
- Balance（バランス）の設計とプロンプト
- Engagement（エンゲージメント）の仕組みとプロンプト

### 4. [目次から文書へ：Claude codeによる効率的な文書作成手順](docs/guides/document-creation-process.md)
前章で作成した目次を基に、実際の文書制作に必要な情報を洗い出し、Claude codeの支援を受けながら効率的に文書を作成する手順を説明します。
- 制作情報の体系的洗い出し
- Claude code支援による情報生成
- 編別制作仕様の設計
- 統合管理システムの構築

### 5. [実際の文書制作への移行：段階的制作による品質確保](docs/guides/content-creation-execution.md)
制作情報を活用して実際の文書制作を開始する手順を説明します。一度に全体を依頼せず、章・節・項ごとに段階的に制作する重要性と、mermaid.jsを活用した視覚的コンテンツ作成を解説します。
- 段階的制作の必要性と利点
- mermaid.js活用による図表統合
- 章・節・項レベルでの制作プロセス
- 品質管理と継続的改善

### 6. [ワークスペースの設定と分析データの管理](docs/guides/workspace-setup.md)
分析結果や下書きを管理するためのディレクトリ構造とGitHub設定について説明します。
- 推奨ディレクトリ構成
- .gitignoreの設定
- セキュリティとベストプラクティス

### 7. [Vibe Writingハンドブックを活用したプレゼンテーション資料作成ガイド](docs/guides/presentation-creation-guide.md)
Vibe Writingで作成したハンドブックを基に、効果的なプレゼンテーション資料を作成する手法について説明します。
- ハンドブックとの一貫性を保った統合的なコンテンツ
- 多様なフレームワーク（Marp、Reveal.js、Swiper.js等）の活用
- インタラクティブで視覚的に魅力的な資料制作

### 8. [総括と成果](docs/guides/summary.md)
Vibe Writing実践ガイド全体の成果をまとめ、今後の発展方向を示します。
- 習得した知識体系と制作システム
- 実現された効果と価値
- 継続的成長への道筋

## 🎯 学習の流れ

```mermaid
graph LR
    A[Vibe Writingとは] --> B[事前準備]
    B --> C[戦略設計・目次作成]
    C --> D[文書作成手順]
    D --> E[段階的制作実行]
    E --> F[ワークスペース設定]
    F --> G[プレゼン制作]
    G --> H[総括・応用展開]
```

## 📖 本書の特徴

- **実践的アプローチ**: 実際のハンドブック作成を題材に学習
- **段階的学習**: 基礎から応用まで順を追って習得
- **プロンプト例付き**: すぐに使える具体的なプロンプトを多数収録
- **セキュリティ重視**: 機密情報の適切な管理方法も解説

## 🚀 はじめ方

1. まず「[Vibe Writingとは](docs/guides/what-is-vibe-writing.md)」を読んで基本概念を理解
2. 「[事前準備](docs/guides/preparation.md)」で必要な環境を整備
3. 「[VIBEに基づくドキュメント戦略設計](docs/guides/vibe-strategy-design.md)」で目次作成手法を学習
4. 「[目次から文書へ：Claude codeによる効率的な文書作成手順](docs/guides/document-creation-process.md)」で制作プロセスを理解
5. 「[実際の文書制作への移行：段階的制作による品質確保](docs/guides/content-creation-execution.md)」で段階的制作手法を習得
6. 「[ワークスペースの設定](docs/guides/workspace-setup.md)」で作業環境を構築
7. 「[プレゼンテーション資料作成ガイド](docs/guides/presentation-creation-guide.md)」でハンドブックの応用展開を学習
8. 「[総括と成果](docs/guides/summary.md)」で全体を振り返り、今後の展開を計画
9. 実際にハンドブック作成を開始

## 📝 対象読者

- 大学や教育機関でドキュメント作成に携わる方
- 生成AIを活用した効率的な文書作成を学びたい方
- Vibe Writingの手法を実践的に習得したい方
- チームでのドキュメント作成を改善したい方

## 🤝 貢献について

本ガイドへの改善提案やフィードバックは歓迎します。GitHubのIssueやPull Requestでお寄せください。

## 📄 ライセンス

本ドキュメントは[Creative Commons Attribution 4.0 International License (CC BY 4.0)](../LICENSE)の下で公開されています。

[![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

---

*本ガイドは、大学教職員向けの生成AI利活用ハンドブックを実際に作成していく過程を通じて、Vibe Writingの実践的な手法を学んでいただくことを目的としています。*