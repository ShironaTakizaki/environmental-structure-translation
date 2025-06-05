## 1. Definition（定義）

本構文ファイル群は、社会的理念・制度構想・知的作業手順などの抽象的知識構造を、再利用可能かつ機械可読な形で記述・展開することを目的として設計された構文的記述モデルである。

主構成ファイル `environmental_structure_translation.json` では、以下のような構造的二軸によって構文項目が切り出されている：

- 発動構造 / 制約構造（Activation / Constraint Structure）  
- 択一的操作 / 相対的操作（Selective / Relative Operation）

この構造化に基づき、以下の9項目を記述単位として定義している：

- **Why**（理念・動機）  
- **Trigger**（発動契機）  
- **Constraint**（制約条件）  
- **How**（手段）  
- **Degree**（強度・程度）  
- **Actor**（行為主体）  
- **Object**（対象）  
- **Reflexive**（反作用／構文的抽象）  
- **Effect**（理念の再提示／意図）

これらの構文要素は、問いの最小構造単位として組み合わされ、以下の4種の伝達構文群を構成している：

- 理解促進構文（読解支援構造）  
- マニュアル構文（実行誘導構造）  
- 政策構文（制度的記述構造）  
- 仕様記述構文（定義記述構造）

なお、本構文モデルにおいては、仕様記述構文にのみ例外的に `Definition`（定義）セクションが存在し、その全体記述構造の基礎を担っている。

構文記述の完全な構造定義については、冗長回避のため、直接 `environmental_structure_translation.json` を参照されたい。

## 📦内容物

| ファイル名 | 説明 |
|------------|------|
| `environmental_structure_translation.json` | 構文定義と記述構造本体 |
| `example_structure_for_comprehension.json` | 理解促進のための具体例構造群 |
| `LICENSE` | 本構文群の使用条件（CC BY-NC-SA 4.0） |

## 📖利用方法（概要）
- **非営利目的に限り、再配布・改変・使用が可能です。**
- 各構文ユニットは `Why`, `Constraint`, `Actor`, `Object`, `Trigger`, `Degree`, `Effect`, `Reflexive` 等のタグによって構造化されます。
- 理念を他者に伝える必要がある教育者、政策設計者、AIプロンプト設計者向けに最適化されています。

## 🛡ライセンス
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ja)  
著作者: 滝咲白菜（Shirona Takizaki）
商業利用は禁止されており、継承ライセンスの適用が義務づけられています。
