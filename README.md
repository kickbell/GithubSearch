# GithubSearch

## 프로젝트 구성 
- ReactorKit + RxSwift + Coordinator  

## 기술사항 
- 다크모드 대응
- 각 레이블/버튼 다이나믹 폰트 대응 
- 네트워킹 부분 추상화(OCP)하여 새로운 API가 필요할 때는 추상화 된 부분은 수정하지 않고 새로 생성해서 사용
- 일부 Unit 테스트 추가
- 에러 핸들링, 검색결과 없음 대응 
- 정렬 선택시 SearchOptionable 프로토콜을 통해 1개로 재사용 

## 사용한 기술 스택 및 라이브러리
- iOS 14, Swift, RxSwift, ReactorKit
