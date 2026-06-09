# 경상국립대학교 홈페이지 샘플

GitHub Pages 배포를 염두에 둔 HTML/CSS/JS 기반 정적 홈페이지 샘플입니다.

## 구성

```text
.
├── index.html
├── assets/
│   ├── style.css
│   └── script.js
└── README.md
```

## 디자인 반영 사항

- 딥 네이비, 에너지 블루, 화이트 중심의 국립대학형 톤앤매너
- 반응형 헤더와 모바일 메뉴
- 메인 히어로 비주얼, 플로팅 칩, 글래스모피즘 카드
- 대학소개, 브랜드 아이덴티티, 학문 분야, 연구·산학, 캠퍼스, 입학, 뉴스 섹션
- 스크롤 등장 애니메이션 및 접근성용 `prefers-reduced-motion` 대응

## GitHub Pages 배포 방법

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더의 파일을 저장소 루트에 업로드합니다.
3. 저장소의 `Settings` → `Pages`로 이동합니다.
4. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
5. Branch를 `main`, 폴더를 `/root`로 설정하고 저장합니다.
6. 잠시 후 `https://계정명.github.io/저장소명/` 주소로 접속합니다.

## 주의사항

공식 로고, 실제 캠퍼스 사진, 최신 공지·입학 정보는 포함하지 않았습니다. 실제 배포 전 경상국립대학교 공식 CI/BI 사용 규정과 최신 콘텐츠를 확인해 교체하세요.
