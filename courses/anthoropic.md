## Claude 101

- Constitutional AI：有害なトピックや違法なことの手助けをしないように設計されているAI
- `Claude and Slack`や`Claude for Excel`といったアプリに統合されたClaudeもある
- 4D Framework for AI Fluency：AIと効果的にやりとりするためのフレームワーク
  - Delegation：どのタスクを人間がやり、どのタスクをAIにやらせるか
  - Description：AIと効果的にコミュニケーションする
  - Discernment：AIのアウトプットを評価する
  - Diligence：責任もって倫理的にAIを使う
- タスクに対してどの程度Claudeが有効に働くかをテストするために評価が必要
  - 評価の方法
    1. 5～10の実際の例を用意する（自分が書いたメールなど）
    1. テストプロンプトを作成する
    1. 用意した例とAIのアウトプットを比較する
    1. 比較結果をもとにプロンプトを調整する
- Projects
  - 専用のメモリやチャット履歴、ナレッジベースなどを持つ専用のワークスペース
  - 単なる質問-回答ではなく、継続的に同じ文脈で何かしたり、チームと協力したりするのに最適
  - 大量のコンテンツをアップロードしてコンテキストにおさまらない場合、自動的にRAGモードになる
  - プロジェクトをシェアする場合、view、edit、ownerの権限が設定できる
- Artifacts
  - Claude上のスタンドアロンでインタラクティブなアウトプット
  - ドキュメント、コードスニペット、HTMLページなどがある
  - チャットで指示するだけでClaudeが自動的に判断してArtifactsを作成する
- Skills
  - instructionやスクリプトなどが入ったフォルダで、Claudeが特定のタスクのパフォーマンスを向上させるために使う
  - Anthropic管理のスキルとカスタムスキルがある
  - 外部からSkillをダウンロードした場合、内容をレビューしないとセキュリティリスクがある
- Connectors
  - Claudeが色々なツールやデータを使えるようにする
  - MCPはConnectorsを標準化する
  - WebツールにアクセスできるWeb Connectorsとローカルファイルやアプリにアクセスできるdesktop extensionsがある
- Enterprise Search
  - 企業全体のプロジェクトのようなもの
- Research Mode
  - Agenticなリサーチをする
  - 複数のソースを調査し包括的なレポートを作成する
  - リサーチの複雑度によって5～45分かかる
