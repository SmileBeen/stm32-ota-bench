# STM32 서명 OTA 시험대

현장 장비가 남긴 로그(B)를 연구소 시험대에서 재현·수정하고(A), 서명된 펌웨어로 원격 업데이트(C)하는 과정을 영상으로 따라 하는 프로젝트예요.

- 사이트: https://smilebeen.github.io/stm32-ota-bench/
- 영상: 유튜브 채널 링크
- 회차마다 시작·끝 코드는 태그로 받아요: `git checkout ep04-start`

## 폴더
| 폴더 | 내용 |
|---|---|
| `firmware/` | 노드(G474), 게이트웨이(H743), HIL(F746), 옛 장비(F103) 펌웨어 |
| `bootloader/` | 서명 검증 · A/B 슬롯 부트로더 |
| `tools/` | 로그 파서, 서명 도구, 서버 |
| `tests/` | 단위 시험, HIL 시험 |
| `docs/` | 사이트 원본 (MkDocs) |

## 라이선스
코드는 MIT, 문서(`docs/`)는 CC BY 4.0.
