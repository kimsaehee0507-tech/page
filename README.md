# page# 📜 유언장 주작단 (Will Forger Team)

> "임종 직전 45초, 유언장 속 단어를 돌려막아 최선의 상속을 완수하라!"

<div align="center">

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=github&logoColor=white)](https://pages.github.com/)

</div>

---

## 📂 파일 구조 (Files)

* **`index.html`**: 게임 실행 및 인터페이스, 타이틀/플레이/상점/정산 화면의 느와르 스타일 UI 구조
* **`style.css`**: 다크 느와르 톤, 낡은 종이 텍스처, 심박수 모니터 애니메이션, 반응형 디자인 스타일
* **`app.js` (또는 스크립트)**: 45초 타임어택 타이머, 단어 스왑 & 태그 검증 로직, BPM 실시간 상승, 불법 장비 상점 및 `localStorage` 자동 저장 시스템

---

## 🕵️ 프로젝트 개요

* **장르**: 텍스트 스왑 퍼즐 & 실시간 스릴러 타임어택
* **컨셉**: 뒷골목 전설의 '유언장 조작단' 에이스가 되어, 임종 직전의 병실에서 감시망을 피해 거액의 상속을 위조하는 블랙 코미디 스릴러 퍼즐
* **핵심 레퍼런스**: *Papers, Please* (서류 검토 및 제한시간 압박) / *Orwell* (텍스트 스토리 및 정보 변조)
* **개발자**: 2024681007 김세희

---

## 🕹️ 핵심 플레이 루프

1. **의뢰 수락 & 유언장 확인**: 병실 진입과 동시에 45초 제한 시간 작동.
2. **단어 카드 스왑**: 유언장 문장 속 타겟 단어치([큰아들] 등)를 빼내어 내 덱으로 가져옴.
3. **조건 재배치 & 돌려막기**: 손에 든 의뢰인 카드([첫째 손자(의뢰인)])를 빈자리에 넣고, 기존 단어는 다른 문장에 짬처리.
4. **태그 기반 검증**: 「~에게 양도한다」 ➔ `[인물]/[기관]` 태그 필수 (동물 태그 등 입력 시 무효 처리).
5. **위기 대응**: 복도 발소리(친척·간호사) 접근 시 경고 및 BPM 급상승.
6. **탈출 및 정산**: S~F 등급 평가 보고서 도장, 수수료 블랙 머니 획득 후 아지트 장비 업그레이드.

---

## 🛠️ 고도화된 기능 및 시스템

* **실시간 심박수 (BPM) 시스템**: 빠른 연속 조작이나 위기 발생 시 BPM 상승, 한계 초과 시 화면 흔들림 및 조작 난이도 증가.
* **침입 방해 대응**: 친척 및 간호사의 복도 발소리 알림 (발각 시 현장 체포 및 F등급 처리).
* **지하 밀실 아지트 & 불법 장비**:
  * 🔇 **소음 방지 스티커**: 발소리 침입 타이밍 지연 (30,000 KRW)
  * 💮 **만능 위조 도장**: 태그 규칙 오류 1회 무효화 (150,000 KRW)
  * 💉 **신경 안정제**: 미션 시작 시 BPM 억제 및 화면 안정화 (80,000 KRW)
* **데이터 지속성 (`localStorage`)**: 자금 및 불법 장비 구매 내역의 영구 브라우저 저장 지원.
* **평가 등급 보고서**: 정확도와 완료 시간에 따른 S / A ~ B / F 등급 도장 스탬프 연출.

---

## 🎯 평가 등급 기준

| 평가 등급 | 조건 및 정확도 | 보상 및 결과 |
| :---: | :--- | :--- |
| **S급** | 시간 내 오차율 0%, 완벽한 위조 조건 달성 | 거액의 보너스 수수료 + 암흑가 명성 대폭 상승 |
| **A ~ B급** | 조건은 맞췄으나 시간이 촉박하거나 턱걸이 달성 | 기본 수수료 정산 |
| **F급** | 45초 초과, 태그 규칙 위반, 또는 친척에게 발각 | 현장 체포, 미션 실패 및 자금 차압 |

---

> **AI응용게임기획및프로그래밍** 프로젝트  
> Designed & Developed by **2024681007 김세희**
