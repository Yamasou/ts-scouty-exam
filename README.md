# Scouty Exam

以下の仕様で、戦士、魔法使い、武道家の
攻撃力 防御力 スキル のパラメータを取得できるようにしたいです。
問題文では少ないパターンの組み合わせになっていますが、将来的に装備やジョブの数が数百、数十になることを想定したクラス設計をしてください。

### キャラクター(Character):
**性別**
男の場合は攻撃力 +5
女の場合は防御力 +5 

**属性(Element)**
風(Wind):
  攻撃力 +5
  防御力 +10(武道家の場合はさらに攻撃力+20) 
水(Water):
  攻撃力 +10
  防御力 +5 (戦士の場合はさらに防御力+10)
雷(Thunder):
  攻撃力 +15
  防御力 +0 (魔法使いの場合はさらに防御力+5)

**ジョブ(Job)**
戦士(Fighter):
  スキル
    男の場合は「ギガスラッシュ」
    女の場合は「ビッグバン」
魔法使い(Magician):
  スキル
    男の場合は「ベギラマ」
    女の場合は「メラミ」
武道家(Martial) 
  スキル
    男の場合は「ブースト」
    女の場合は「カウンタ」 

**装備(Equipment)**
剣(Sword) 攻撃力 +30 防御力 +30(戦士の場合はさらに攻撃力+20)
杖(Stick) 攻撃力 +30 防御力 +10(魔法使いの場合はさらに攻撃力+20)
グローブ(Glove) 攻撃力 +20 防御力 +20(武道家の場合はさらに防御力+20)
