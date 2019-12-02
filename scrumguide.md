**Scrum**（スクラム）とは、**Project**（プロジェクト）の現状を把握する為のフレームワークである。

ビズリーチ社におけるScrumの正しい理解を促進する目的で本ドキュメントを作成し、公開する。

文責：スクラム推進グループ（貝瀬、江端）

# 0.Background

## ProjectとProductの違い
* **Project**（プロジェクト）とは、定めた目的を実現する為の「活動」
* **Product**（プロダクト）とは、対象に対して提供しようとしている「仮説」

## Scrumを支える学問
組織論と集団心理学を基礎としている。**Project**は、組織的かつ集団で遂行する事が大半なので、この学問を引用している。

### 組織論
**Scrum**が具体的に参考にしてる組織論は複数あるが、主に「**Team-based organizations**」の思想が、**Scrum**には強く反映されている。**中央集権型モデル**と重要視しているコトが異なっている。

### 集団心理学
アメリカの心理学者であるGeorge Armitage Miller（ジョージ・A. ミラー）の研究を引用している。認知心理学の先駆者でもあり、**Scrum**は、認知心理学の誕生と評される「プランと行動の構造」に基づいている。George Armitage Millerは、短期記憶の容量が7±2であることを発見した事で有名。言語学、計算言語学、自然言語処理、オントロジーなどの分野でも著名である。

## Key
**Scrum**は、基礎となる学問から導き出した重要とする「3つの状態」を定義している。それは、**Transparence**（透明性）、**Inspect**（検証）、**Adapt**（適応）である。

### Transparenceという状態
正しい情報が、一箇所に集まっており、次の行動が誘発され続けている状態。

* 情報には、消費期限があり、この「正しい情報」とは、現時点での情報として正しいと評価した情報のこと
* 情報を確認できるだけでは、**Transparence**ではない
* 次の行動が誘発され続けなければならない

### Inspectという状態
定めた目的と現場との差分（ギャップ）を把握し続けている状態。

* **Project**で必要とする定めた目的と現場との差分が把握できるだけでは、**Inspect**ではない
* 定めた目的は、1つとは限らない。複数ある場合が多い
* 差分は、常に把握し続けなければならない

### Adaptという状態
定めた目的と現場との差分を埋める為に活動し続けている状態。

* 狙いもなく闇雲に活動しているのは、**Adapt**ではない
* 定めた目的と現場との差分を埋める為の「戦略」に基づいて、行動し続けなければならない

# 1.Role
**Scrum**では、**Role**（役割）を3つ定めている。

* **Product Owner**（プロダクトオーナー）
* **Scrum Master**（スクラムマスター）
* **Team**（チーム）

**Team**と**Scrum Team**（スクラムチーム）を明確に異なる集団であると定義している。

## Product Owner
**Product Owner**は、**Scrum Team**の「**ROI**（投資対効果）」を最大化する責任がある。	

基本、**Project**内の制約に基づいて、複雑性をコントロールするなどし、**ROI**を最大化する戦略立案と戦略に基づく**Team**支援を行う。Invester（投資家）とは異なる役割。

**ROI**最大化の戦略に基づき、**Product Backlog**（要件や技術的な負債であるUndoneなど）の優先順位を決める。**Product Owner**は、すべての要件を**Product Backlog**で管理する。**Product Backlog**にない要件を**Team**に依頼することはできない。**Stakeholder**からの依頼が発生した場合も、**Product Owner**は**Product Backlog**を通じて、**Team**へ依頼する。

**Product Owner**は Product Manager（プロダクトマネージャー）が担当することが多いが、上記の責任と役割を果たすことができれば職種に定めはない。

参考：[Product ManagerのJob Description（職務記述書）](https://hrmos.co/pages/hrmos/jobs/160006110100)

## Team
**Team**は、**Scrum Team** の「生産性」を最大化する責任がある。**Development Team**（開発チーム）と表現される事が多い。

**Team**は、サービスや**Product**を開発する「生産性」を向上し続けなければならない。単にサービスや**Product**を開発するだけの役割ではない。

**Team**は、開発すべき要件を必ず**Product Backlog**から取得する。**Product Backlog**にない要件を開発してはいけない。**Stakeholder**からの依頼が発生した場合も、**Team**は**Product Owner**にエスカレーションし、**Product Backlog**を通じて、開発の要件と優先順位を理解する。
 
**Team**には、上記の責任と役割を果たすために必要なすべての職種が含まれるが、エンジニアやデザイナーが含まれることが多い。

## Scrum Master
**Scrum Master**は、**Scrum Team**の環境や活動を改善し「目的実現の確率」を最大化する責任がある。

基本、**Project**を通じて、**Impediment**（活動における妨害や障害、課題など）を発見し、組織や環境、活動スタイルやツール等を改善し、目的実現の確率を最大化する戦略立案と戦略に基づく**Team**支援を行う。Project Manager（プロジェクトマネージャー）とは異なる役割。

改善戦略に基づき、**Impediment**の優先順位を決める。

参考：[Scrum MasterのJob Description](https://hrmos.co/pages/hrmos/jobs/160000010200)

## Scrum Team
**Scrum Team**とは、**Product Owner**、**Scrum Master**、**Team**の3つの役割で構成されている集団のこと。

* **Team**と異なり人数制限はない
* 他の役割は全て**Stakeholder**（利害関係者）と位置付けて捉えて、**Scrum Team**は協業する

# 2.Ceremony
**Ceremony**とは、**Scrum**を実践する中で **Scrum Team**が行う5つの打合せのこと。Scrum Event（スクラムイベント）や Scrum Meeting（スクラムミーティング）と表現されるようになりつつある。

* **Sprint Planning**（スプリントプランニング）
* **Daily Scrum**（デイリースクラム）
* **Product Backlog Refinement**（プロダクトバックログリファインメント）
* **Sprint Review**（スプリントレビュー）
* **Sprint Retrospective**（スプリントレトロスペクティブ）

上記以外に、PO会議などで実施する、事業部内の重要な意思決定やチーム横断の優先順位調整もあるが、これらはオプションである。

## Sprint Planning
**Scrum Team**が、**Sprint**（短期間）の計画または再計画を行う**Ceremony**。

* **Product Backlog**の**Product Backlog Item**（プロダクトバックログアイテム）のうち優先順位の高いものから実現に必要な設計を行い、必要な**Sprint Backlog Item**（スプリントバックログアイテム）を洗い出す
* そのSprintで、「期待する**Velocity**（ベロシティ）」を確定する

### Sprint Planningの基本ルール
* **Product Backlog Refinement**で、**Product Backlog**の優先順位が高い**Product Backlog Item**を、**Sprint Planning**可能な状態にしておく
	* **Product Backlog Refinement**と**Sprint Planning**までの間に追加された**Product Backlog Item**は、例外として対応する
* **Sprint Backlog Item**は、「**30分**単位」で管理する
	* 30分単位で管理できなければ、Sprint中に、Team で助けあえない可能性を高め、Sprintが未達になる等、計画がブレるリスクが高まるので避けるべき
	* **Sprint Backlog Item**を細分化し、30分枠の箱に**Sprint Backlog Item**を入れるイメージを持つと実現し易い
* 1週間の**Sprint**の場合、実施時間は「**4時間**」
	* 4時間以内に終了することが望ましいが、最初は、時間を延長してでも徹底的に実施すべきである（時間より内容を優先する）
	* **Product Backlog Refinement**で、**Product Backlog**を**Sprint Planning**可能な状態にしておかないと、**Sprint Planning**の実施時間が長くなる


## Daily Scrum
2つの目的がある**Ceremony**。

* **Sprint Planning**で計画した通りに推進しているのかを確認し、**Impediment**の有無を把握する
* 前回の**Sprint Retrospective**で**Commitment**（コミットメント）した改善アクションを実施しているのか、効果が出ているのかを確認する

### Daily Scrumの基本ルール

* 基本的な質問のテンプレートは、以下の3つの質問
	* 前回の**Daily Scrum**から、今回の**Daily Scrum**まで何を行いましたか？
	* 今回の**Daily Scrum**まで何を実施する予定ですか？
	* 困っている事や課題、**Impediment**はありませんか？
* 質問に回答しながら、**Sprint Backlog Item**のステータスを更新する
	* **Team**の成熟度に合わせて、質問内容を変更したり、質問を追加しても良い
* **Sprint**の長さを問わず、実施時間は「**15分**」
	* 必ず15以内に終了する（内容より時間を優先する）

## Product Backlog Refinement
**Scrum Team**が、当該**Sprint**より先の中長期の計画または再計画を行う**Ceremony**。

### Product Backlog Refinementの基本ルール
* 少なくとも、2~3**Sprint**先の**Product Backlog Item**の追加や修正、見積り、**Product Backlog**の優先順位を更新する
	* 可能なら、2~3**Sprint**よりも先まで、**Product Backlog Item**の追加や修正、見積り、**Product Backlog**の優先順位まで更新できると更に良い
* **Product Backlog Item**の見積りは、「**プランニングポーカー**」を使って、相対見積りで見積る
* **Product Backlog Item**の見積る対象は「**複雑度**」である。決して、作業時間ではない
* 1週間の**Sprint**の場合、実施時間は、「**1時間**」
	* 遅くとも2時間以内に終了する（内容より時間を優先する）

## Sprint Review
2つの目的がある Ceremony。
 
* **Scrum Team**が、**Sprint Planning**で計画した内容が、「**Product**で実現」できているのかを確認し、**Velocity**の「実績」を算出する
* **Scrum Team**が、現状の実Productを使いながら、より良くする為のアイデアを出したり、議論する

### Sprint Reviewの基本ルール

* **Product**は、**Acceptance Criteria**（受入基準）と **Done**（技術品質）を満たしていないければ、**Accepted**（完了）とはならない
* **Product Backlog Item**のステータスは、**Accepted**か**Not Accepted**しかない
	* **Accepted**となった**Product Backlog Item**は、ステータスが Acceptedとなる
	* **Not Accepted**となった**Product Backlog Item**は、ステータスを更新せず、次の**Sprint**以降で予定している**Product Backlog Item**と合わせて優先順位を再検討する
* 1週間の**Sprint**の場合、実施時間は、「**30分**」
	* 遅くとも1時間以内に終了する（内容より時間を優先する）

## Sprint Retrospective
**Team**が、生産性を向上する目的のために、次の**Sprint**で「実施する具体的な改善アクションを Commitment（コミットメント）」する**Ceremony**。

### Sprint Retrospectiveの基本ルール

* **Sprint**での事象を分析して、改善課題を特定する
	* 思い込みから改善課題を設定してはならない
	* 前までの**Sprint**で**Commitment**した改善アクションの効果も分析しなければならない
* **Commitment**した改善アクションは、**Sprint**単位で積み上げ、増やし続ける
* 1週間の**Sprint**の場合、実施時間は、「**30分**」
	* 遅くとも1時間以内に終了する（内容より時間を優先する）

# 3.Artefact
**Artefact**（アーティファクト）とは、**Scrum**を実践する中で**Scrum Team**が作成、管理する、5つの作成物。

* **Product Backlog**（プロダクトバックログ）
* **Sprint Backlog**（スプリントバックログ）
* **Impediment List**（妨害リスト）
* **Done** / **Definition of Done**（Doneの定義）
* **Potentially Shippable Product Increment**（出荷可能なプロダクト単位）

上記以外に、Market（マーケット）を定義したり、Marketの課題を管理する作成物として、Lean CanvasやIssue Map 等があるが、これらはオプションである。

## Product Backlog
5つの目的がある**Artefact**。

* **Scrum Team**が、取り扱う**Product Backlog Item**（要件）の一覧
	* **Scrum Team**内で、**Product Backlog Item**を軸に、不明点を確認や特定する
* **Product Owner**が、**ROI**を最大化する為の「戦略」を明らかにする
	* その為に、**Product Backlog Item**の優先順位を明らかにする
* **Product Owner**が、**ROI**を最大化する為に、**Acceptance Criteria**（受け入れ基準）を明確にする
	* その為に、1つ1つの**Product Backlog Item**のスコープをコントロールする
* **Team**が、**Product**で実現する「期待」、実現できた「実績」を管理する
	* その為に、**Velocity**を把握する
* Scrum Team が、Team のVelocityに基づいて、中長期の計画の見通しを確認し、再計画した内容を管理する

不具合やバグについても必ず**Product Backlog**で一元管理し、優先順位に基づいて開発する。

### Product Backlogの基本ルール
* **Product Backlog Item**の見積る対象は、要件の「複雑度」である
	* 理由は、確率高く実現できるか否かを把握したいため
* **Product Backlog Item**1つあたりの見積りは、最大「**5**」までに抑える
	* 5を超えるサイズは必ず分割する
	* 3以内でコントロールできるようになるのが望ましい
* 管理するツールは、Atlassian社の「JIRA」とする

## Sprint Backlog
5つの目的がある**Artefact**。

* **Team**が、**Sprint**で実行する戦略を明らかにする
* **Team**が、**Sprint**で実行するタスク（作業）を明らかにする
	* 実行するタスクは、Scrum Teamが合意した**Product Backlog Item**のみ
* **Team**が、**Sprint**におけるタスクのステータスを管理する
	* タスクの状態「実行前、実行中、完了」を明らかにする
* **Sprint**において、**Team**が計画通り実行できているのか、協力しているのか、問題を放置していないのかを明らかにする
* **Done/Undone**を明らかにする

### Sprint Backlogの基本ルール

* 管理するツールは、アナログツールの「ホワイトボードや模造紙」と「付箋」とする

## Impediment List
3つの目的がある**Artefact**。

* **Project**における、**Impediment**（活動における妨害や障害、課題など）を明らかにする
	* 本ガイドラインから逸脱したルールで運営されている**Scrum**なども**Impediment**として取り扱わなければならない
* **Scrum Master**が、**Scrum Team**の目的実現の確率を最大化する為の「戦略」を明らかにする
	* その為に、「取り扱う**Impediment**の優先順位」を明らかにする
* **Scrum Team**が、**Project**の改善実績、改善中、未着手課題を明らかにする

### Impediment Listの基本ルール

* 管理するツールは、Atlassian社の「JIRA」とする。

## Done(Definition of Done)
2つの目的がある**Artefact**。

* **Scrum Team**として、**Product**をリリースする為に、すべき事を管理する
* **Done/Undone**を区別して管理し、**Product**におけるリスク、**Project**における「サービス提供社としてのリスク」を明らかにする
	
### Done/Undone

* **Done** とは、**Product**をリリースする為に、すべき事が出来ている**Product**の状態のこと
	* **Done**は、開発手順が「Definition of Done」を最初に構築・実現し、それから要件を開発する
* **Undone**とは、**Product**をリリースする為に、すべき事が出来ていない **Product**の状態のこと
	* **Undone**は、開発手順が「要件」を最初に構築・実現し、それから Definition of Done を実現する
 
Done/Undoneの区別は、作業の順番で決まる。

## Potentially Shippable Product Increment
**Team**が、どの要件でも**Product**をリリースできるよう、要件を開発できるか否かを判断する目的の**Artefact**。

この実現力が高い**Team**が、**Technical debt（技術的な負債）**が少ない Productを開発、維持できる。世界中の**Team**が実現できるよう切磋琢磨して、創意工夫しながら技術力を高めている。

世界中で実現できている**Team**はないが、2019年3月末時点では、netflix のチームが、Chaos Engineering（カオスエンジニアリング）に取組むなど、実現に最も近いと評価されている。

# 4.Sprint
**Sprint**（スプリント）とは短期間のこと。期間を定めるのには6つの目的がある。

* **Scrum Team**として、計画をする期間（短期間）を明らかにする
* **Team**として、短期間の戦略が立案できるようにする
	* **Velocity**（短期の実績）から、戦略を継続的に改善できる
* **Product Owner**として、中長期の戦略が立案できるようにする
	* **Velocity**から、戦略を継続的に改善できる
* **Scrum Master**として、**Project**の状況把握と改善戦略が立案できるようにする
	* **Velocity**などから、中長期の戦略を継続的に改善できる
* **Scrum Team**として、活動を調整し易くする
	* 対象となる期間が一定となるため
* **Scrum Team**の活動サイクルを明らかにする
	* **Stakeholder**とも調整し易くなる

## Sprintの基本ルール

* **Sprint**は、「**1週間**」とする
* 祝日がある場合は、稼働日数を減らして計画、実行する

# 5.Scrum Checklist

ビズリーチ社におけるScrumの導入・活用状況を可視化するためのチェックリスト。主にスクラム推進グループのチェッカーが、スクラムマスターやメンターに課題を共有する目的で利用する。

項目の難易度に応じて5段階（+Option）にレベル分けをしているので、レベルNの項目に全てチェックがついたらレベルN+1に進む、といった活用方法が望ましい。

* レベル1:Scrumを最低限導入している
* レベル2:ScrumのArtefactを効率的に運用している
* レベル3:ScrumのCeremonyを効率的に運用している
* レベル4:Scrumを中長期的な目標達成のために活用している
* レベル5:Scrumをビジネスと組織のさらなる成長のために活用している
* Option:Scrumに関する最新のプラクティスを活用している

## 利用方法

1. [Scrum ChecklistーMaster](https://docs.google.com/spreadsheets/d/1q0dAqOu-WHVAa2XRDu7dLLQy3pjvyVGuNAb-vb4F9nQ/edit#gid=1603532095)をコピーする
1. チェックする日付の列を作り、その時点でできている項目にチェックを入れる
1. チェックがつかない項目を参考に、**Scrum Master**の目標設定などに活用する
1. 次回チェックする日付を決める
1. 2に戻る
