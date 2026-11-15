# 룸피니공원 · 러닝하고 불멍/물멍하기 (Lumpini Healing World)

방콕 룸피니공원을 OpenStreetMap 실제 지도로 옮긴 3D 웹 힐링 월드입니다. (three.js r160, 설치·빌드 없음 — 정적 파일만)

| 파일 | 내용 |
|---|---|
| `index.html` | 첫 화면 — 버전 고르기 |
| `character.html` | 캐릭터 버전 (귀여운 캐릭터, 가벼움) |
| `people.html` | 사람 버전 (실사 사람 모델, 실제 사진·풍경 영상) |
| `music/` | 멍때리기 음악 6곡 + 완주 축하곡 |
| `models/` | 사람 3D 모델·동작 (base64 JSON) |
| `photos/`, `shots/`, `videos/`, `tex/` | 사진·첫 화면·풍경 영상·바닥 텍스처 |

## 배포
- 빌드 명령 없음, 출력 폴더 = 저장소 맨 위(root).
- Vercel: GitHub 저장소 Import → Framework Preset `Other` → Deploy.
- `vercel.json`: 음악·모델·사진을 30일 캐시해 다시 방문할 때 데이터 사용을 줄입니다.

## 출처·라이선스
- 사람 모델: Microsoft Rocketbox (MIT), Ready Player Me 견본 "brunette" (CC BY-NC 4.0 — 비상업)
- 동작: three.js 예제 모델(Soldier, Xbot, Michelle)
- 텍스처: Poly Haven (CC0) · 지도: © OpenStreetMap contributors (ODbL)
- 음악: Google Gemini, Higgsfield(ElevenLabs Music)로 제작 · 사진: 제작자 직접 촬영
