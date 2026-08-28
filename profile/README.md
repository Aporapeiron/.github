# Aporapeiron

**関係力学言語（RDL: Relational Dynamics Language）** の基底、検証モジュール、および社会・人間・諸芸術への応用生態系を管理するオーガニゼーションです。

> **関係力学言語とは、関係を見て、記述して、操作するための言葉である。**
> 
> それは、世界を一つに決めつけるための主義ではない。
> また、世界を一つの説明原理で閉じるための理論でもない。
> 決めつけられない世界を、それでも丁寧に見て、言葉にし、必要なら扱い直すための言葉である。

---

## 🪐 RDL Ecosystem Architecture

RDL のリポジトリ群は、自己代謝するひとつのシステムとして、**基底層（T0/T1）**から**応用層（T3）**へと階層化・分割されています。

```mermaid
graph TD
    subgraph T0: Entrance
        Intro[<b>RDL_Introduction</b><br>初心者向けチュートリアル・案内所]
    end

    subgraph T1: Core
        C[<b>RDL_Core</b><br>基底仮設・最低動作仕様・基本代謝] 
    end

    subgraph T2: Modules
        F[<b>RDL_Functions</b><br>外部理論の翻訳エンジン・汎用計算モジュール]
        M[<b>RDL_Durability_Modules</b><br>耐久検査・証明書発行機関]
        G[<b>RDL_General_Modules</b><br>小規模・遊撃的な便利ツールボックス]
    end

    subgraph T3: Applications
        H[<b>RDL_Human</b><br>人間動態・社会・既存学問マッピング]
        Music[<b>RDL_Music_Theory</b><br>音楽理論の力学的解剖]
    end

    C ==>|代謝公理の提供| F
    F ==>|翻訳された部品群| M & H & Music
    M ==>|耐久証明付きの構造| H & Music
    H -.->|破断・実験結果の還元| M
    Music -.->|特殊条件下での力学実証| M
```

---

## 📂 Repositories

### 1. [RDL_Introduction](https://github.com/Aporapeiron/RDL_Introduction) (Entrance)
★ はじめての方はこちら！ RDLの難解な数式や定義を一旦脇に置き、平易な言葉と日常的な比喩で世界観を解説した初心者向けチュートリアル・案内所です。

### 2. [RDL_Core](https://github.com/Aporapeiron/RDL_Core) (T1)
RDLのすべての土台。基底仮設（B, ξ）、基本代謝プロセス（SILN）、共通語彙を厳密に保持するコア。

### 3. [RDL_Functions](https://github.com/Aporapeiron/RDL_Functions) (T2)
既存の数学、物理学、AI技術（Neural Network等）を RDL の力学へ持ち込み、どこでも使える「関数（部品）」としてストック・提供する純粋な翻訳エンジンおよび汎用モジュール庫。

### 4. [RDL_Durability_Modules](https://github.com/Aporapeiron/RDL_Durability_Modules) (T2)
対象を極限状態に置いて耐久限界を測るテスト機関。RDL自体の「耐久検査（破断アタック）」の手法を隔離し、どこまで耐えたかの証明書を発行する。

### 5. [RDL_General_Modules](https://github.com/Aporapeiron/RDL_General_Modules) (T2)
小規模だが便利そうな補助モジュールや、日々の分析でパッと使える思考のショートカット（テンプレート等）を気軽に配置・ストックしておくための遊撃的なツールボックス。

### 6. [RDL_Human](https://github.com/Aporapeiron/RDL_Human) (T3)
人間という特定の対象における「固有仮説」の実験場。4層時間スケール、SFO流向、笑いと快の放熱力学、道具結合のほか、心理学や経済学など**人類の「既知学問」をRDLの力学軸へ翻訳・マッピングしたツリー**を展開。

### 7. [RDL_Music_Theory](https://github.com/Aporapeiron/RDL_Music_Theory) (T3)
音楽を「純粋な関係構造の推移」と「熱（H）の蓄積とカタルシス的放熱」の力学として再解剖する応用群。音の引力、和音の境界、リズムの同期をRDLで記述する。

---

## 🏛️ Why "Aporapeiron" ?

Aporia（有限閉包による行き詰まり）＋ Apeiron（非終端の無際限性）。
どんな理論・解釈（$M_B$）も、必ず未回収の余白（$\xi$）を残す。だからこそ RDL は絶対の真理として教条化することなく、常に破断点を見つめ、自らを壊しながら更新し続ける（`[SELF]`）。
この終わりのない「自己維持と自己解体」の代謝プロセスを体現する名前として、本組織は命名されています。
