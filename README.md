# ReactJS_마스터클래스 Assignment3 프로젝트

## 개요
ReactJS 마스터클래스 코드챌린지!!

## 사용 기술
- React
- Styled-components
- React Router (페이지 전환)

## 주요 기능
- **다크모드**: 누르면 다크모드가 적용되는 토글 버튼을 만들어주세요.
- **홈버튼**: /:coinId에서 홈으로 돌아갈 수 있는 버튼을 만들어주세요.
- **price탭 활성화**: 강의에서 구현하지 않은 Coin의 /:coinId/price탭을 구현해주세요.
- **차트 형식 변경**: /:coinId/chart탭의 차트 형식을 CandleStick 형식으로 변경해주세요.

## 기술 포인트
- React Router로 다중 페이지처럼 보이도록 구성된 SPA 구조.

## 어려웠던 점 및 해결 방법
- **Routes 문제**: Route와 Routes의 관계가 계속 오류가 떠서 Coin.tsx에서 어려움을 느꼈으나 링크 후 대괄호로 묶어주니 오류 해결
- **API 문제**: 영상에서는 API가 유료서비스가 되어서 무료 서비스로 바꾸는 과정에서 어려움을 느꼈으나 링크 뒤 **coinID**만 가져옴으로써 해결