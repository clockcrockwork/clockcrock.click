## Summary
This is a release PR.

For more information on the release instructions, please see:
https://github.com/misskey-dev/misskey/blob/develop/CONTRIBUTING.md#release

## For reviewers
- CHANGELOGに抜け漏れは無いか
- バージョンの上げ方は適切か
- 他にこのリリースに含めなければならない変更は無いか
- 全体的な変更内容を俯瞰し問題は無いか
- レビューされていないコミットがある場合は、それが問題ないか
- 最終的な動作確認を行い問題は無いか

などを確認し、リリースする準備が整っていると思われる場合は approve してください。

## Checklist
- [ ] package.jsonのバージョンが正しく更新されている
- [ ] CHANGELOGが過不足無く更新されている
- [ ] CIが全て通っている

## 受け入れ条件と次の状態

<!-- 作業を追加する前に、検証可能な受け入れ条件を決める。既存の「完了条件」「証拠表」があれば参照し、二重に管理しない。 -->
- 対象: head SHA / base branch + SHA / 検証した merge SHA または tree（該当時）:
- 受け入れ条件と対応する証拠: <!-- 既存の条件・証拠表への参照、または下表 -->

| 受け入れ条件 | 証拠・対象SHA・実行環境 | 判定 |
| --- | --- | --- |
|  |  | UNVERIFIED |

<!-- PASS / FAIL / UNVERIFIED / NOT_REQUIRED（根拠必須）。CIの skipped・cancelled・NOT_REQUIRED・未実行・旧head成功を実テストのPASSにしない。 -->
- 独立レビュー: <!-- 対象head/base、記録、未解決指摘。既存レビューの有効範囲を確認し、GitHubの正式APPROVEDとは区別する。 -->
- 現在の状態と残る具体的な作業: <!-- 作業、担当、待つ理由。人間判断なら確認対象・判断内容・判断後の操作を示す。 -->
- 条件を満たした後の状態: <!-- Ready for review / 人間の判断待ち / マージ候補 / 承認済みの親へマージ / supersededとしてClose 等 -->
- 統合・公開の権限と影響: <!-- マージ先、適用する承認、デプロイ・公開の有無。候補であることは実行権限ではない。 -->

<!-- 有効な証拠を引き継ぎ、head/baseが動いた場合は差分と統合影響に対応する確認を行う。実装が完成し、リポジトリのReady条件と明示的なDraft維持指示を確認したうえで、人間が確認できる段階なら残る確認・判断を明示してReadyへ進める。既存の必須チェック・独立レビュー・保護設定・公開権限は維持する。 -->
