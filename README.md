# AliceScript
![image](https://github.com/WSOFT-Project/alicescript/assets/34591675/64dac579-c535-471e-936f-9de552cc8f88)

AliceScriptの言語設計リポジトリへようこそ。このリポジトリは、AliceScript言語の新機能を議論、採用、仕様化する場です。

- AliceScriptの言語仕様は、今後順次specフォルダにアップロードする予定です。
- 新しい言語機能の提案や不備を見つけた場合は、プルリクエストではなくIssueを投稿してください。
- AliceScriptの実装である[Losetta](https://github.com/WSOFT-Project/Losetta)リポジトリもご覧ください。

> [!NOTE]
> Alice3.0までの新機能および不具合に関するIssueは、[Losetta]([https://github.com/WSOFT-Project/Losetta](https://github.com/WSOFT-Project/Losetta/issues))リポジトリにあります。
> 合わせてご覧ください。

### 新機能の提案
#### 0. Discussionへの投稿
新機能を思いついたら、まずはDiscussionで詳細について議論することをお勧めします。
また、過去に同じようなIssueが立っていないか確認してください。

#### 1. Issueの投稿
Issueテンプレートを使用して、言語機能の概要、構文、実装内容、利点と欠点をまとめて、Issueを投稿してください。

#### 2. プロトタイプの実装
多くの場合、新機能が提案され採用される前に、機能のプロトタイプを実装します。
この手順を踏むことで、実装面と使用面の両方の側面から言語機能の問題を発見しやすくなります。
プロトタイプはLosettaリポジトリで実装します。
状況によっては、提案者にLosettaリポジトリをフォークして実装することを依頼することもあります。

#### 3. 仕様と実装への反映
投稿された新機能が採用されたら、言語仕様とLosetta、docsリポジトリの該当する箇所に新機能を反映します。

### 不具合の報告
不具合を報告する前に、不具合の原因がプログラミング言語の仕様によるものであることを確認してください。
よくある不具合は、たいていの場合プログラミング言語の仕様ではなく実装に原因があります。
