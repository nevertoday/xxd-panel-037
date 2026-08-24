<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 037 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 037

### 여행을 하나의 유금 에나멜 배지로

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-E7483E?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-1A7A8C?style=flat-square)](#)

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <strong>한국어</strong> · <a href="README.ar.md">العربية</a>

</div>

<div>

> 배지 하나 · 원본 에나멜 색 · 백색 금속 테두리 · 유금 디테일 · 짧은 실물 그림자

결정적인 윤곽과 국소 특징을 하나의 실제 여행 배지로 압축합니다. 원본 기반 에나멜 칸, 금속 구획선, 흰 금속 테두리, 절제된 유금, 둥근 두께와 짧은 실물 그림자가 하나로 작동합니다.

## 이 Skill이 필요한 이유

이 스타일은 원본에 의존하며 내용을 바꿔 끼우는 장식 프리셋이 아닙니다. 다음 변환 인과를 따릅니다:

```text
lock identity and silhouette → preserve the decisive contour and local features → simplify into meaningful enamel cells → build real metal dividers and white-metal rim → add restrained gilded accents, thickness, bevel, and short contact shadow → integrate native title into the badge body
```

무관한 사진으로 바꿔도 식별, 구성, 배치, 재료, 색, 여백과 문구가 실질적으로 달라지지 않는다면 이 Panel의 결과가 아닙니다.

## 시각적 원칙

- **원본 결속:** 여행을 하나의 유금 에나멜 배지로
- **스타일 DNA:** 배지 하나 · 원본 에나멜 색 · 백색 금속 테두리 · 유금 디테일 · 짧은 실물 그림자
- **식별성:** 원본 고유 단서를 세 가지 이상 보존하며 무관한 사진이라면 구성도 실질적으로 달라져야 합니다.
- **구도:** 하나의 주체 또는 분리할 수 없는 관계, 원본에 근거한 배치와 능동적 여백을 지킵니다.
- **재료와 색:** 고정 템플릿이 아니라 사진에서 도출하고 프로젝트별 생성 규격을 적용합니다.

미적 제약과 금지 항목은 [원본 프롬프트](references/037-source.md)에만 있으며 Skill과 런타임 어댑터는 이번 출력 변수만 처리합니다. [Skill](SKILL.md) · [영문 런타임 어댑터](references/xxd-panel-037-prompt.en.md)

## 예시 · X에서

> [샤오샤오둥（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2090799598336168140) · 2026-08-21<br>
> GPT2 x 鎏金珐琅 x 冰箱贴 x 美学提示词 x VOL.037

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090799598336168140"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 037 예시 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090799598336168140"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 037 예시 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090799598336168140"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 037 예시 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090799598336168140"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 037 예시 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090799598336168140">원문 게시물과 전체 프롬프트 보기 →</a></p>

이 예시는 037의 미학적 의도를 보여 줄 뿐이며, 예시의 주제, 구성, 색상, 문구, 이전 캔버스 비율은 생성 참고나 현재 기본값이 되지 않습니다.

## 원본 프롬프트가 유일한 미적 기준입니다

`references/037-source.md`는 이 프로젝트의 유일한 창작·미적 기준입니다. Skill은 원문을 요약하거나 확장하지 않으며 공통 색상 계획, 미적 동기, 제목, 마이크로카피를 추가하지 않습니다. 색, 재료, 구성, 여백, 문구, 타이포그래피는 GPT Image 2가 원본 프롬프트의 규칙대로 수행합니다.

모드와 크기가 덮어쓰는 것은 기존 3:4 상하 컨테이너뿐입니다. 좌우 모드에서는 ‘위 사진／아래 디자인’을 왼쪽／오른쪽으로 대응시키고, 디자인 단독 및 배경화면 모드에서는 아래쪽 디자인 언어를 전체 캔버스로 확장합니다. 나머지 원본 지시는 모두 유지됩니다.

## 조합 가능한 네 가지 출력

`top-bottom`, `left-right`, `design-only`, `wallpaper-pack`을 하나 이상 선택할 수 있습니다. 쌍 구성은 기본적으로 완성 캔버스 한 장으로 직접 생성하며, 결정론적 합성은 재시도 실패, 원본 사진의 픽셀 완전 보존, 무손실 크기 보정이 필요할 때만 사용합니다.

상하／좌우 균형은 시각적 구성 목표이며 경계선, 중앙 비율, 픽셀 좌표를 측정하지 않습니다. 약간의 오프셋은 실패가 아니며 사용자가 픽셀 단위의 정확한 분할을 명시한 경우에만 결정론적 합성을 사용합니다.

일반 크기도 복수 선택할 수 있습니다: 자동 맞춤, 원본 비율, 1:1, 3:4, 4:3, 4:5, 5:4, 2:3, 3:2, 9:16, 16:9, 21:9, 5:7, 7:5, 사용자 비율／정확한 픽셀. 암묵적 기본 크기는 없습니다. 서로 다른 비율은 동일한 원본 프롬프트에서 각각 다시 구성합니다.

배경화면 세트는 연속형 또는 독립형입니다. 연속형은 먼저 기준 이미지 한 장을 만들고, 나머지는 원본 사진＋기준 이미지를 함께 참고해 각 기기에 맞게 재구성합니다. 한 이미지를 네 크기로 기계적으로 자르지 않습니다.

## 텍스트 모드

생성 전에 다음 중 하나를 정합니다.

1. **원본 프롬프트에 따라 모델이 텍스트 생성**: 사용자는 언어 또는 지역만 지정하고, 내용·분량·톤·타이포그래피는 GPT Image 2가 원문 규칙대로 생성합니다.
2. **내 정확한 문구 사용**: 한 글자도 바꾸지 않고 전달하며 재작성, 번역, 제목 추가를 하지 않습니다. 배치는 원문을 따릅니다.
3. **텍스트 없음**: 모든 텍스트와 가짜 문자를 금지합니다.

외부 Skill은 제목이나 마이크로카피를 미리 쓰지 않습니다. 출력 언어는 인터페이스 언어와 별도로 확인하며 인물, 장면, 파일명에서 추정하지 않습니다.

## 완성 캔버스 우선과 래스터 경계

이미지 모델이 완성 화면 전체의 미학적 재구성을 담당하며 이중 패널도 완성 캔버스 한 장의 직접 생성을 기본으로 합니다. `scripts/compose_panel.py`는 조건부 복구, 무손실 픽셀 조정, 읽기 전용 검수에만 사용하고 매번 사전 계획하거나 미학적 성공을 판단하지 않습니다.

모든 결과물은 PNG 래스터이며 호출마다 `~/Desktop/xxd/`에 새 작업을 만듭니다. 설정된 이미지 경로는 비식별 상태만 반환하며 제공자, 엔드포인트, 인증 정보, 헤더, 프롬프트, 응답, 계정 정보를 공개하지 않습니다. SVG, HTML, Canvas, 도표와 프로그램 그림은 최종 작품을 대신할 수 없습니다.

## 호스트 기능에 맞춘 질문과 인라인 매개변수

같은 Skill이 호스트가 실제로 제공하는 상호작용 기능에 맞춰 동작하며 장식 기호를 클릭 가능한 UI처럼 보이게 하지 않습니다.

- **Claude Code에 `AskUserQuestion + multiSelect: true`가 있으면**: 모드와 크기는 실제 체크박스, 텍스트 방식과 배경화면 관계는 단일 선택을 사용합니다. 일반 크기는 정사각형·세로·가로 그룹으로 나누고 선택을 누적하며 사용자 크기는 자유 입력합니다.
- **Codex에 `request_user_input`만 있으면**: 텍스트 방식과 배경화면 관계처럼 상호 배타적인 항목에만 사용합니다. 모드와 크기를 단일 선택처럼 꾸미지 않고 조합 입력으로 받습니다.
- **상호작용 도구가 없으면**: 첫 번째 질문에서 모드, 두 번째 질문에서 크기＋텍스트 방식을 입력합니다. 가짜 `- [ ]`를 표시하지 않고 폼만을 위해 Plan mode 전환을 요구하지 않습니다.

두 번째 질문은 처음에 스마트 추천／원본 비율／일반 비율／사용자 지정만 보여 줍니다. 일반 비율을 선택할 때만 정사각형 `1:1`, 세로 `3:4, 4:5, 2:3, 9:16, 5:7`, 가로 `4:3, 5:4, 3:2, 16:9, 21:9, 7:5`를 펼칩니다. 여러 비율과 정확한 픽셀을 함께 지정할 수 있습니다.

모든 설정은 인라인으로도 전달할 수 있습니다.

```text
/xxd-panel-037 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text prompt --locale ja-JP
```

`--mode`, 반복 가능한 `--size`, `--text prompt|exact|none`, `--locale`, `--copy`, `--wallpaper linked|independent`, `--wallpaper-size`, `--out`을 지원합니다. 값이 모두 있으면 질문을 건너뛰고, 일부만 있으면 누락된 항목만 묻습니다.

## 이미지 모델 우선순위

GPT Image 2를 기본 최우선 모델로 사용합니다. 고충실도 원본 참조, 생성 전 완성 캔버스 확인, 이중 패널의 완성 화면 일괄 생성, 조건이 충족될 때만 사용하는 스크립트 합성이라는 기존 흐름은 그대로 유지합니다.

현재 도구 또는 설정된 경로에서 실제로 사용할 수 있고 원본 충실도, 완성 화면비, 대상 언어의 문자, 연결형 배경화면의 다중 참조 요구를 충족할 때는 Seedance 5.0 Pro, Nano Banana Pro(Gemini Image Pro), Nano Banana 2(Gemini Image Flash) 또는 다른 호환 비트맵 모델도 사용할 수 있습니다. 대체 모델은 생성 경로만 바꾸며 모드, 캔버스, 문구, 언어, 배경화면 관계와 완성 캔버스 우선 전략을 바꾸지 않습니다.

적합한 경로가 없으면 이미지 생성 도구를 활성화하거나 API Key를 제공하도록 사용자에게 요청합니다. 사용자가 제공한 인증 정보는 현재 작업에 사용할 수 있지만 답변이나 로그에 다시 표시·기록·노출하지 않습니다. 사용자가 명시적으로 요청하지 않는 한 장기 저장하거나 제공자, 계정, 결제 또는 전역 경로 설정을 변경하지 않습니다.

## 시작하기

```bash
git clone https://github.com/nevertoday/xxd-panel-037.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-037" ~/.codex/skills/xxd-panel-037
```

Claude Code 사용자는 같은 폴더를 다음 위치에 연결할 수 있습니다: `~/.claude/skills/xxd-panel-037`. 설치 후 에이전트 세션을 다시 시작하세요.

```text
$xxd-panel-037
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

전체 사양: [Skill 워크플로](SKILL.md) · [원본 스타일 자료](references/037-source.md) · [영문 런타임 어댑터](references/xxd-panel-037-prompt.en.md) · [중문 런타임 어댑터](references/xxd-panel-037-prompt.zh-CN.md)

## XXD 소개

XXD는 Xiaoxiaodong 브랜드 이름의 약자입니다. 제작 및 유지관리: [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## 지원과 멤버십

### 심층 상담 · 시간당 CNY 299

Skills 사용과 워크플로에 관한 일대일 심층 상담입니다. WeChat으로 Xiaoxiaodong에게 문의하세요. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills 사용자 교류 그룹 · CNY 99

한 번의 결제로 Skills 사용자 교류 그룹에 참여합니다. 시간제 일대일 상담은 별도입니다.

### Knowledge Planet＋회원 프롬프트 라이브러리 · 연 CNY 699

Knowledge Planet과 회원 프롬프트 라이브러리는 하나의 연간 멤버십입니다. 어느 한쪽에서 가입한 뒤 WeChat으로 연락하면 다른 쪽도 열립니다.

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>결정적인 윤곽이 광택 속에 남을 때 여행은 수집할 수 있는 기억이 됩니다.</strong></div>

---

<div align="center">

## ☕ 오픈 소스 프로젝트 후원

중국어판 이외에는 Buy Me a Coffee를 이용할 수 있습니다. 후원은 선택 사항이며 오픈 소스 접근 권한을 바꾸지 않습니다.


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
