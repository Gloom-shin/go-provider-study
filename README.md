# Go Provider 14일 스터디

Java/Spring 개발자가 Go로 작성된 Terraform provider를 읽고 고칠 수 있게 되는 것을 목표로 한 인터랙티브 커리큘럼이에요. 2주 / 14일 구성이에요.

## 빠른 시작

`index.html` 파일을 더블클릭하면 바로 열려요. 별도 서버가 필요 없는 단일 HTML 파일이에요.

Week 1 실습은 [Go Playground](https://go.dev/play/)만 있으면 돼요. Week 2 마지막 날(Day 14)만 Go와 Terraform을 설치해요.

## 무엇이 들어있나요

- Week 1: Java 개발자를 위한 Go 기초 (설치, 변수와 zero value, 에러 처리, slice·map, struct와 포인터, 인터페이스, 테스트)
- Week 2: Terraform provider 읽고 고치기 (provider 구조, Schema, CRUD와 plan/state, Read와 drift, Arista eAPI 연동, 로컬 빌드와 버그 재현)

각 Day는 다음 6섹션으로 구성돼요:

1. 오늘의 목표
2. 핵심 개념 (Java 비교 활용)
3. 실습 코드
4. 자주 헷갈리는 것
5. 퀴즈 (객관식 + 단답형, 즉시 채점)
6. 진도 체크

## 기능

- 진도 자동 저장(LocalStorage)
- 다크모드 토글
- 키보드 단축키 (←/→ 이동, Ctrl/⌘+K 검색)
- 모바일 반응형
- 사이드바 네비게이션

## GitHub Pages로 배포하기

GitHub에서 빈 저장소 `go-provider-study`를 만든 뒤, 이 폴더에서 실행해요.

```bash
git init -b main
git add index.html README.md
git commit -m "Go Provider 14일 스터디"
git remote add origin https://github.com/<유저>/go-provider-study.git
git push -u origin main
```

저장소 Settings → Pages → Source를 `main` 브랜치 `/(root)`로 지정하면 `https://<유저>.github.io/go-provider-study/` 에서 접속할 수 있어요.

## 학습 팁

- Day 1부터 순서대로 가는 걸 추천해요. Week 1의 zero value, 포인터, 타입 단언이 Week 2 버그 설명에 그대로 다시 나와요.
- Day 7과 Day 14 미니 프로젝트는 꼭 직접 돌려 보세요. 버그를 한 번 재현해 보면 같은 버그를 실제 코드에서 바로 알아봐요.
- provider 코드를 읽다 막히면 Day 14의 체크리스트로 돌아오세요.
