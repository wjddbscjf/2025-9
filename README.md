# Open Source Software Design and Lab
## 9조
 - 정윤철
 - 권병혁
 - 박상현


🥈 2️⃣ “음악 추천 기반 감정 일기”
💡 핵심 개념:

사용자가 입력한 일기의 감정을 분석해서 음악을 추천하는 감성형 웹앱

감정 분석은 간단한 키워드 매칭 방식으로도 충분 (AI API 없어도 가능)

⚙️ 기술 구성:

Backend: Node.js + Express

Frontend: HTML/CSS + JS (or EJS)

API(Optional): YouTube Search API or Spotify API

🧩 구현 기능:

일기 작성 → 감정 분석 (“행복”, “슬픔”, “분노”, “설렘” 등)

감정에 맞는 음악 리스트 출력 (미리 준비된 DB or API)

감정별 컬러 테마 UI

🕒 예상 개발시간:

약 8~12시간 (2~3일)
→ API 없이 로컬 데이터 기반으로 하면 하루 만에도 완성 가능
