# 통신클럽 랜딩페이지

인터넷 가입 유선 랜딩페이지 + 어드민 시스템

## 파일 구조

```
tongsin-club/
├── landing/
│   └── index.html      # 메인 랜딩 페이지
├── admin/
│   └── index.html      # 어드민 페이지
└── README.md
```

## 기능

### 랜딩 페이지
- 고정 카운트다운 배너 (매일 자정 기준)
- 슬라이딩 배너 (5개 문구, 3.5초 자동 전환)
- 접기/펼치기 가능한 신청 폼 (기본: 접힘)
- 연락처 3분할 입력 (010 드롭다운)
- SK/KT/LG 통신사 선택
- 약관 전체동의
- 실시간 접수 현황 테이블
- 카운트다운 타이머

### 어드민
- 대시보드 (접수 통계)
- 접수 현황 관리 + CSV 내보내기
- 슬라이딩 배너 문구 추가/수정/삭제
- 히어로 섹션 텍스트 수정
- 요금제 비교표 수정
- 후기 추가/수정/삭제
- 브랜드 정보 / 컬러 / 기능 ON/OFF 설정

## GitHub Pages 배포

1. GitHub 저장소 생성
2. 파일 업로드
3. Settings → Pages → Branch: main 설정
4. 랜딩: `https://{username}.github.io/tongsin-club/landing/`
5. 어드민: `https://{username}.github.io/tongsin-club/admin/`
