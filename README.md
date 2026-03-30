# 청하터널 전기안전관리 시스템

터널 전기설비의 안전한 관리를 위한 디지털 도구 모음입니다.

## 주요 도구

| 도구 | 설명 | 형식 |
|------|------|------|
| 일일점검일지 | 전기설비 일일점검 기록 (고압반/저압반/UPS/태양광/조명) | HTML |
| 월간 점검계획서 | 공휴일 기준 근무표 및 점검일정 자동 생성 | Excel |
| 공휴일 달력 | 대한민국 공휴일/대체공휴일 연간 달력 | HTML/Excel |
| SCADA 데이터 추출 | 화면 캡처 OCR → 점검일지 자동 입력 | 내장 기능 |

## 기술 스택

- **프론트엔드**: HTML5, CSS3, Vanilla JavaScript
- **엑셀 처리**: SheetJS (xlsx)
- **OCR**: OCR.space API + Canvas 이미지 전처리
- **파일 생성**: JSZip, FileSaver.js
- **데이터 저장**: LocalStorage

## 사용 방법

1. 이 저장소를 클론합니다
2. `index.html`을 브라우저에서 열면 포트폴리오 페이지가 표시됩니다
3. 각 도구의 HTML 파일을 브라우저에서 직접 열어 사용합니다

## GitHub Pages 배포

1. GitHub에서 새 저장소를 생성합니다 (예: `username.github.io`)
2. 이 폴더의 파일들을 저장소에 푸시합니다
3. Settings > Pages에서 Source를 `main` 브랜치로 설정합니다
4. `https://username.github.io`에서 확인합니다

## 파일 구조

```
github-pages/
├── index.html          # 메인 포트폴리오 페이지
├── README.md           # 프로젝트 설명
└── assets/
    └── images/         # 스크린샷 등 이미지 파일
```

## 라이선스

이 프로젝트는 개인 업무용으로 제작되었습니다.

---

Built with Claude AI
