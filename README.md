# Ha Young (하영)

Chungnam National University, Computer Science

---

## Projects

### 🧠 FocusFlow
AI-powered, on-device focus management for macOS
크롬 탭 30개를 열어두는 사람들(필자와같은)을 위한 도구. 탭을 무작정 닫는 게 아니라, 
지금 뭘 해야 하는지 알려주는 온디바이스 AI 비서.

Chrome Extension이 행동을 추적하고, 로컬 AI(Ollama)가 패턴을 분석해서, 
macOS 메뉴바에 '지금 하던 거 안하고 딴짓중' 같은 식으로 기록, 
다른 페이지로 넘어가버린 경우 원래 했어야 할 다음 할 일을 추론해 알려줍니다. 
모든 데이터는 기기 밖으로 나가지 않습니다.

`Chrome Extension` `Electron` `Ollama` `SQLite` `On-device AI`

---

### 🎬 Running-Snap
### 🏃 [Running-Snap · Video Editor](https://github.com/Running-Snap/running-snap)

러닝 영상을 입력받아 **Qwen VL 시각 분석 → MediaPipe 골격 추적 → 베스트컷 자동 선정**까지 전 과정을 자동화하는 멀티모달 AI 파이프라인을 개발했습니다.
PIL 기반 9:16 포스터 합성, MoviePy 기반 슬로우모션·줌 인증영상, 피드백 관절 하이라이팅이 포함된 자세분석 영상을 단일 파이프라인에서 동시 생성합니다.
현재 Wan2.2 Image-to-Video 모델과 ffmpeg 자막 자동 삽입을 통합하여 AI 생성 영상 파이프라인으로 확장 중입니다.

`Python` `MediaPipe` `Qwen VL` `MoviePy` `PIL` `FastAPI` `Wan2.2`
---

### 📊 Macro Trading Tracker

### 📈 **[Quant Chart Master](https://github.com/imHay0ung/Quant-Chart-Master)**

티커와 날짜만 넣으면 **기술적 분석 한 페이지 리포트**를 자동 생성합니다.

- ✅ **2000년 이후 역사적 백분위수** — RSI, CMF, 200MA 이격 등 모든 지표의 과거 분포와 비교
- ✅ **멀티 타임프레임 상호작용** — 주봉의 과열 vs 일봉의 강세 같은 충돌/정렬 자동 감지
- ✅ **갭 시각화** — 주말/뉴스로 인한 갭을 차트에 색상 박스로 표시
- ✅ **인터랙티브 Plotly 차트** — 4단 구성 (캔들/이평선/볼린저 + 거래량 + RSI + MACD)
- ✅ **가격성 매크로** — yfinance로 금리·VIX·달러·유가를 자동 수집

  **왜 만들었나:**
시장의 early warning signal을 놓치지 않기 위해. 특히 시장 사이클 후반부의:
- RSI 베어리시 다이버전스 (가격 신고가 vs RSI 낮아짐)
- 200일선 극단 이격 (회귀 압력)
- 갭의 패턴 (뉴스 반응)

위와 같은 내용들을 원래는 여러 페이지를 돌며 트래킹 하지만, 한 곳에서 손쉽게 볼 수 있도록 제작.

**투자 자문이 아닙니다.** 모든 투자는 본인 책임입니다.
---

## Tech Stack
- Languages: Python, TypeScript, C#
- Tools & Frameworks: 
- Interests: HCI, VRMR, Quantitative Analysis, On-Device AI

---

## Contact
- Email: hykhyung7777@gmail.com
