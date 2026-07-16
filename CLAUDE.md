# CLAUDE.md — david-warriors3d(大衛的勇士們 3D,撒母耳記下 23 章)

> 2026-07-16,arena-duel-kit 首個聖經皮:fork warrior3d,引擎零改動。
> GitHub summer09201017-cloud/david-warriors3d;Netlify hfpc-david-warriors3d(聖經皮 hfpc- 前綴)。

## 皮層(引擎見 arena-duel-kit / warrior3d CLAUDE.md)

- 勇士四選一 CHARACTERS(各配成名武器,選了自動帶起手武器):以利亞撒(劍,撒下23:9-10)/
  沙瑪(大刀,23:11-12)/比拿雅(長槍,23:20-21)/亞比篩(長矛,23:18);對手固定=非利士勇士
  (makePhilistine:青銅冠盔+紅纓羽冠)。戰袍選單已移除(勇士自帶配色)。
- 場景=沙瑪死守的紅豆田:田色地面+棋盤式紅豆叢地紋(平貼不擋路)。
- 甩石索=原 greenballs 換皮(石色、無螢光),機制不變(兩顆連投+暈眩)。
- 模式:對決 100/三百人之戰 300(亞比篩典故,roundCap 300)/練習場。
- 經文(全部 cuv 查驗):勝利 overlay+曉臻誦讀「那日耶和華使以色列人大獲全勝。」(撒下 23:10);
  各勇士 verse 存 CHARACTERS;敗方文案用以利亞撒「手黏刀把」溫柔鼓勵。
- 神學語氣:得勝歸耶和華,不頌暴力;溫柔 KO 無流血不變。

## 驗證

npm run build && npx vite preview → node scripts/verify-david.mjs http://localhost:PORT <outDir>
(hook window.__davidwarriors3d;八項驗證同 arena-duel-kit §7)

## 同步

大廳 hfpc-bible-games 聖經3D 卡+portfolio(bible3d)+gamefleet 聖經3D 分類+sites.json 快遞。
