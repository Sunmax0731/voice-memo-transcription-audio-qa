# 音声メモ・文字起こし・音声検品スイート

voice-memo-transcription-audio-qa は 音声メモを議事録、字幕、動画素材へ変換する制作者 向けの closed alpha プロダクトです。音声メモ、文字起こし、話者、音量/ノイズ確認をまとめてレビューする。

## Source

- PICKUP Rank: 47
- Domain / Idea No: WindowsApp / 6
- Repository: voice-memo-transcription-audio-qa
- 主な公開先: GitHub Release / BOOTH
- created_idea: `D:/AI/WindowsApp/created_idea_006_voice-memo-transcription-audio-qa`
- 同梱ZIP: `D:/AI/WindowsApp/created_idea_006_voice-memo-transcription-audio-qa/idea_006_voice-memo-transcription-audio-qa.zip`
- 開始時 README: 存在しない


## Alpha Scope

- 代表シナリオ4件の自動検証
- 必須項目不足、警告、混在バッチの分類
- ui/ のホスト連携シェル
- QCDS、security/privacy、traceability、release checklist、manual test docs
- docs ZIP: `dist/voice-memo-transcription-audio-qa-docs.zip`

## Commands

```powershell
npm test
node src/cli/index.js samples/representative-suite.json
npm run build:docs
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` にあります。

