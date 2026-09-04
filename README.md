# VirgoScript — 배포 창고

VirgoScript 시리즈의 **설치 상자(.rbz)와 판 번호 쪽지**가 사는 자리입니다.
소스 코드는 여기에 없습니다.

## 무엇이 있나

| 파일 | 하는 일 |
|---|---|
| `versions.json` | 지금 최신이 몇 판이고 상자가 어디 있는지 적은 쪽지 |
| Releases | 각 판의 설치 상자(.rbz) |

깔려 있는 VirgoScript 가 스케치업을 켤 때 하루에 한 번 이 쪽지를 읽어,
새 판이 있으면 알려 주고 한 번 눌러 받을 수 있게 합니다.

## 드는 종 (일곱)

Dimtrix · Isolate · Mirrota · Piemenu · Rectolution · Viewpie · Vstretch

## 새 판을 낼 때

1. 각 종 1차 로더의 `VERSION` 을 올린다
2. 상자를 굽고 이 창고의 **Releases** 에 올린다 (태그 `v<판번호>`)
3. `versions.json` 의 `version` 과 `url` 을 그 판으로 고친다

⚠️ 로더의 `VERSION` 과 쪽지의 `version` 이 어긋나면 알림이 영영 안 뜨거나 늘 뜹니다.

## 만든 이

deadforest — VirgoScript, 2026
