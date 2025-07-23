# 재미로 보는 아기성별계산기

한국 전통 계산법으로 아기 성별을 예측하는 모바일 앱입니다.

## 특징

- 🍼 한국 전통 음력 계산법 적용
- 📱 Android 네이티브 앱 (Google Play Store 배포 준비)
- 🌙 음력-양력 자동 변환
- 📋 4단계 간편한 입력 과정
- ⚡ 오프라인 작동 (서버 불필요)

## 기능

1. **마지막 생리시작일 입력**
2. **수정일/출산예정일 추가 입력**
3. **부모님 생년월일 입력** (음력 자동 변환)
4. **전통 공식으로 성별 예측 결과**

## 기술 스택

- **Frontend**: React + TypeScript + Tailwind CSS
- **Mobile**: Capacitor (Android)
- **Build**: Vite + GitHub Actions
- **Calendar**: 한국 음력 계산 라이브러리

## 개발 및 빌드

### 로컬 개발
```bash
npm install
npm run dev

##Android 빌드
npm run build
npx cap sync android
npx cap open android

자동 빌드
GitHub Actions가 자동으로 APK를 빌드합니다.

배포
Google Play Store 배포 가이드는 DEPLOYMENT_GUIDE.md를 참고하세요.

주의사항
⚠️ 이 앱은 재미 목적으로 제작되었습니다.

의학적 근거가 없습니다
정확한 성별은 의료진의 초음파 검사로 확인하세요
"재미는 재미일 뿐.. 맹신은 금물!!"
라이선스
MIT License
Update README
