# 🍊 제주아꼼이네 자사몰 리뉴얼 — Claude Code 지시사항

## 👤 프로젝트 오너
- **대표자**: 전승범 (bum / 범)
- **회사**: 제주아꼼이네 농업회사법인(주)
- **현재 운영 자사몰**: https://akkome.com (카페24)
- **테스트 사이트**: https://akkome-test.onrender.com
- **GitHub**: https://github.com/bumiletter-bit/akkome-website (dev 브랜치)
- **최종 목표**: 스마트스토어 고객을 자사몰로 이전

---

## ⚠️ 절대 규칙

```
🚫 대표님이 지시한 내용 외에는 절대 수정하지 않는다
🚫 main 브랜치에 직접 push 하지 않는다
🚫 akkome.com 운영 서버에 직접 접근하지 않는다
🚫 스마트스토어 링크 사용 금지 (자사몰 링크만 사용)
🚫 결제/장바구니 외 카페24 링크 사용 금지
🚫 결제(장바구니/바로구매/회원가입/로그인) 제외 모든 링크는 반드시 우리가 만든 페이지로 연결
🚫 akkome.com 링크는 위 4가지(cart/buy/join/login) 외 절대 사용 금지
✅ 모든 작업은 dev 브랜치에서만 진행한다
✅ 작업 완료 후 반드시 git push origin dev
✅ 확신이 없으면 먼저 조언하고 실행은 나중에 한다
```

---

## 🎨 브랜드 가이드

| 항목 | 값 |
|------|------|
| 메인 컬러 | 노랑 #F5C800 (포인트/버튼/뱃지만) |
| 서브 컬러 | 네이비 #1B3A6B (로고/텍스트) |
| 배경 | 흰색 #FFFFFF (모던 심플) |
| 할인율 | 빨강 #FF3B30 |
| 무료배송 | 초록 #00A651 |
| 포인트 | 오렌지 #FF6B00 |
| 폰트 | Noto Serif KR + Noto Sans KR |
| 슬로건1 | "제주가 키우고, 아꼼이네가 고릅니다." |
| 슬로건2 | "달아야 팝니다. 안 달면 안 팝니다." |
| 참고 사이트 | 과일꾼(fruitggun.com), 온브릭스(onbrix.co.kr) |

---

## 🌿 브랜치 전략

```
main   → 운영 브랜치 (akkome.com 연결 예정 — 건드리지 않음)
dev    → 개발 브랜치 (모든 작업은 여기서 진행)
```

---

## 📁 전체 페이지 구조 (총 18개)

```
/ (index.html)                    ← 메인 홈페이지
/story.html                       ← 브랜드 스토리
/benefit.html                     ← 회원 혜택
/product/list.html                ← 전체상품 목록
/product/sale.html                ← 특가상품
/product/best.html                ← 베스트 상품
/product/experience.html          ← 감귤체험 예약
/product/hanrabong.html           ← 제주 한라봉
/product/cheonhyehyang.html       ← 제주 천혜향
/product/kkoma-hanrabong.html     ← 제주 꼬마한라봉
/product/gamgyul.html             ← 제주 비가림 감귤
/product/lemon.html               ← 제주 레몬
/product/surahyang.html           ← 제주 수라향
/product/karahyang.html           ← 제주 카라향
/product/blood-orange.html        ← 제주 블러드오렌지
/product/jagong.html              ← 제주 자몽
/product/hagyul.html              ← 제주 하귤
/product/taibek.html              ← 제주 타이벡 감귤
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
장바구니: https://akkome.com/order/cart.html  ← 카페24 유지
회원가입: https://akkome.com/member/join.html  ← 카페24 유지
로그인: https://akkome.com/member/login.html   ← 카페24 유지
쿠폰존: https://akkome.com/coupon/coupon_zone.html
고객후기: https://akkome.com/board/product/list.html?board_no=4
```

---

## 🎬 숏클립 영상 링크

```
영상1 (귤):
https://www.instagram.com/reel/DSHNXv8Eqsi/
→ 연결상품: /product/gamgyul.html

영상2 (체험장):
https://www.instagram.com/reel/DSCId6pEga9/
→ 연결상품: /product/experience.html

영상3 (천혜향):
https://www.instagram.com/reel/DRjUe2uEjb5/
→ 연결상품: /product/cheonhyehyang.html
```

---

## 📋 홈페이지 구조 (모바일 퍼스트)

```
롤링 공지 배너 (최상단)
헤더 (로고 + 알림 + 장바구니)
카테고리 탭바 (추천/특가/베스트/숏클립/스토리/혜택)
무료배송 배너
메인 배너 슬라이드 (스와이프)
당일발송 카운트다운
제철 아꼼이 추천 pick (🥇🥈🥉 가로 배열)
아꼼이네 상품 (2열 그리드 + 더보기)
숏클립 영상 (mp4 자동재생)
감귤체험 섹션
고객후기 섹션
푸터
하단 고정 네비 (홈/상품/체험/후기/장바구니)
```

---

## 🛍 상품 데이터 관리

```javascript
// index.html 상단 PRODUCTS 변수로 관리
// soldOut: true → 메인 진열에서 숨김
// soldOut: false → 정상 표시
// 품절 처리: soldOut 값만 변경 후 git push
```

---

## ✅ 완료된 작업 (2026-03-24)

- [x] GitHub 저장소 생성
- [x] Render 테스트 사이트 배포
- [x] 모바일 퍼스트 전면 리뉴얼
- [x] 모던 심플 흰색 톤 적용
- [x] 스와이프 배너
- [x] 제철 아꼼이 추천 pick
- [x] 상품 JS변수 관리 + 품절 자동숨김
- [x] 숏클립 인스타그램 릴스 연결
- [x] 하단 고정 네비게이션
- [x] 전체 18개 페이지 제작
- [x] 전체 링크 자사몰 연결
- [x] 롤링배너 + 카테고리탭바
- [x] 실제 상품 이미지 적용

## ⏳ 다음 작업

- [ ] 신규 페이지 완성도 보강 (story/benefit/experience/sale/best/list)
- [ ] 상세페이지 완성도 높이기 (이미지 슬라이드/추천상품)
- [ ] 모바일 최종 점검
- [ ] 카페24 FTP 업로드
- [ ] akkome.com 최종 반영
- [ ] 카페24 결제 디자인 통일
- [ ] (향후) 완전 독립 결제 시스템 구축

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
3. git branch 로 현재 브랜치 확인 (반드시 dev)
4. https://akkome-test.onrender.com 현재 상태 확인
5. 대표님께 현재 진행 상태 보고
6. 다음 작업 지시 대기
```

---

*마지막 업데이트: 2026-03-24*
*대표님 지시 없이는 이 파일 자체도 수정하지 않습니다.*
