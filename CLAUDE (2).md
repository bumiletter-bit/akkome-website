# 🍊 제주아꼼이네 자사몰 리뉴얼 — Claude Code 지시사항

## 👤 프로젝트 오너
- **대표자**: 전승범 (bum)
- **회사**: 제주아꼼이네 농업회사법인(주)
- **현재 운영 자사몰**: https://akkome.com (카페24 — 건드리지 않음)
- **테스트 사이트**: https://akkome-test.onrender.com
- **GitHub**: https://github.com/bumiletter-bit/akkome-website
- **최종 목표**: 스마트스토어 고객을 자사몰로 이전

---

## ⚠️ 절대 규칙

```
🚫 대표님이 지시한 내용 외에는 절대 수정하지 않는다
🚫 main 브랜치에 직접 push 하지 않는다
🚫 akkome.com 운영 서버에 직접 접근하지 않는다
🚫 스마트스토어 링크 사용 금지 (자사몰 링크만 사용)
✅ 모든 작업은 dev 브랜치에서만 진행한다
✅ 작업 완료 후 반드시 git push origin dev
✅ 확신이 없으면 먼저 조언하고 실행은 나중에 한다
```

---

## 🎨 브랜드 가이드

| 항목 | 값 |
|------|------|
| 메인 컬러 | 노랑 #F5C800 (70%) |
| 서브 컬러 | 네이비 #1B3A6B (30%) |
| 포인트 | 오렌지 #FF6B00 |
| 폰트 | Noto Serif KR + Noto Sans KR |
| 슬로건 | "제주가 키우고, 아꼼이네가 고릅니다." |
| 슬로건2 | "달아야 팝니다. 안 달면 안 팝니다." |
| 참고 사이트 | 과일꾼(fruitggun.com), 온브릭스(onbrix.co.kr) |

---

## 🌿 브랜치 전략

```
main   → 운영 브랜치 (akkome.com 연결 예정 — 건드리지 않음)
dev    → 개발 브랜치 (모든 작업은 여기서 진행)
```

---

## 🔗 자사몰 akkome.com 상품 링크

```
메인 홈: https://akkome.com
전체상품: https://akkome.com/product/list.html?cate_no=42
꼬마 한라봉: https://akkome.com/product/제주-꼬마한라봉/37/
제주 한라봉: https://akkome.com/product/제주-한라봉/29/
천혜향: https://akkome.com/product/제주-천혜향/32/
비가림 감귤: https://akkome.com/product/제주-비가림-감귤/33/
레몬: https://akkome.com/product/제주-레몬/24/
수라향: https://akkome.com/product/제주-수라향/35/
카라향: https://akkome.com/product/제주-카라향/39/
블러드오렌지: https://akkome.com/product/제주-블러드오렌지/38/
하귤: https://akkome.com/product/제주-하귤/54/
자몽: https://akkome.com/product/제주-자몽/83/
감귤체험: https://akkome.com/product/제주-감귤-체험-농장/47/
장바구니: https://akkome.com/order/cart.html
회원가입: https://akkome.com/member/join.html
로그인: https://akkome.com/member/login.html
고객후기: https://akkome.com/board/product/list.html?board_no=4
```

---

## 🎬 숏클립 영상 링크

```
영상1 (귤):
https://view.shoppinglive.naver.com/shortclips/10188248?fm=store&offFeature=contentLayer&sn=ltlsc&swipe=%7B%22sortType%22%3A%22LATEST%22%2C%22pagerType%22%3A%22ALL%22%2C%22channelId%22%3A55401%2C%22referrerType%22%3A%22STORE%22%2C%22referrerKey%22%3A%2255401%22%7D&tr=ltlsc
→ 연결상품: https://akkome.com/product/제주-비가림-감귤/33/

영상2 (천혜향):
https://view.shoppinglive.naver.com/replays/1851698?fm=store&offFeature=contentLayer&sn=ltlsc&swipe=%7B%22sortType%22%3A%22LATEST%22%2C%22pagerType%22%3A%22ALL%22%2C%22channelId%22%3A55401%2C%22referrerType%22%3A%22STORE%22%2C%22referrerKey%22%3A%2255401%22%7D&tr=lim
→ 연결상품: https://akkome.com/product/제주-천혜향/32/
```

---

## 📋 홈페이지 구조 (모바일 퍼스트)

```
1. 헤더 (고정) — 로고 + 검색 + 장바구니
2. 메인 배너 — 스와이프 슬라이드 (클릭시 상품 이동)
3. 당일발송 카운트다운 타이머 (오전 8시 마감)
4. 사장님 추천 랭킹 — 🥇🥈🥉 (JS 변수로 관리)
5. 상품 진열 — 2열 그리드 (과일꾼 스타일)
6. 숏클립 영상 — 네이버 쇼핑라이브 연결
7. 감귤체험 섹션
8. 고객 후기 섹션
9. 푸터 (간소화)
10. 하단 고정 네비 — 홈/상품/체험/후기/장바구니
```

---

## ✅ 완료된 작업 (2026-03-23)

- [x] GitHub 저장소 생성 (bumiletter-bit/akkome-website)
- [x] Render 테스트 사이트 배포
- [x] 모바일 퍼스트 전면 리뉴얼
- [x] 노랑 70% / 네이비 30% 컬러 적용
- [x] 스와이프 배너 (마우스+터치)
- [x] 사장님 추천 랭킹 (🥇🥈🥉)
- [x] 상품 진열 2열 그리드
- [x] 숏클립 네이버 쇼핑라이브 연결
- [x] 하단 고정 네비게이션 (아이콘+텍스트)
- [x] 전체 링크 자사몰 akkome.com으로 교체
- [x] 푸터 간소화
- [x] 배너 클릭 수정 + 텍스트 제거

## ⏳ 다음 작업

- [ ] 실제 상품 이미지 교체 (images 폴더)
- [ ] 관리자 페이지 구축 (당도/상품/이미지 관리)
- [ ] 카페24 FTP 연동 또는 디자인 편집 적용
- [ ] akkome.com 도메인 최종 반영
- [ ] 앱(Android+iOS) 제작

---

## 🚀 작업 후 자동 Git + Render 배포

```bash
git add .
git commit -m "✏️ [작업내용 한줄 요약]"
git push origin dev
```

---

## 🔄 세션 재시작 시 확인사항

```
1. 이 CLAUDE.md 파일 먼저 읽기
2. git log --oneline -5 로 최근 작업 확인
3. git branch 로 현재 브랜치 확인 (반드시 dev 여야 함)
4. https://akkome-test.onrender.com 현재 상태 확인
5. 대표님께 현재 진행 상태 보고
6. 다음 작업 지시 대기
```

---

*마지막 업데이트: 2026-03-23*
*대표님 지시 없이는 이 파일 자체도 수정하지 않습니다.*
