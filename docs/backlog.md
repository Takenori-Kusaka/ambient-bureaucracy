# 制作バックログ（新官僚主義のドッグフーディング）

> 本書は「お役所仕事の構造にAIを刺す」ことを主張する。**その制作プロセス自体をバックログ化**して実演する。
> 起票 → 優先度付け → 上から処理。状態：`todo` / `doing` / `done`。**優先度は"背骨先行"**（thesis→ch4→ch5を上に）。

## 章 × 必要エビデンス

| 優先 | ID | 項目 | 種別 | 支える章 | 状態 |
|---|---|---|---|---|---|
| P0 | T-01 | 一文テーゼの確定（新官僚主義→環境知能の橋を含む） | thesis | 全体 | doing |
| P0 | T-02 | 逆説の"核の一文"を磨いて格納 | thesis | 4,5 | done（`thesis.md`） |
| P0 | R-01 | 読者ペルソナの固定 | reader | 全体 | done（`reader.md`） |
| P1 | E-01 | Amodei "Machines of Loving Grace" 採取（環境知能・未来） | evidence | 5,7 | **done**（`evidence/amodei-machines-of-loving-grace.md`） |
| P1 | E-06 | 第5章「環境知能」を一次で支える**別ソース**探索（Amodeiは逆だった／アンビエントcomputing提唱者・他リーダー） | evidence | 5 | todo（E-01の宿題） |
| P1 | E-02 | Jensen Huang 基調講演から採取（AIの地形） | evidence | 3,5 | todo |
| P1 | E-03 | Sam Altman 公式発信から採取（自動化・エージェント） | evidence | 3,7 | todo |
| P1 | E-04 | GPT系論文著者の一次発信 | evidence | 3,4 | todo |
| P1 | E-05 | Graeber ブルシットジョブ原著 | evidence | 2 | todo |
| P2 | C-04 | 第4章（新官僚主義）ドラフト：パンチ→証拠 | chapter | 4 | todo |
| P2 | C-05 | 第5章（環境知能）ドラフト：手袋の逆説→動線を変えない実装 | chapter | 5 | todo |
| P3 | C-02 | 第2章（DXの帰結／認知負荷）ドラフト | chapter | 2 | todo |
| P3 | C-07 | 第7章（未来像）ドラフト | chapter | 7 | todo |
| P4 | C-06 | 第6章（上司バックログ）＝実務が進むたび追記 | chapter | 6 | todo（継続） |

## 処理ルール

1. **上から1つだけ着手**（同時多発しない＝認知負荷を増やさない）。
2. エビデンス（E-**）は**章ドラフト（C-**）より前**に処理。一次に届かない主張は本文で断定しない。
3. 章ドラフトは**先に道場で声に出して翻訳 → 崩れを直してから書く**。
4. 完了の定義：`docs/reader.md` のペルソナ「T」が半歩うなずくか。
