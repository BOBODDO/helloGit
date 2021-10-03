# 풀스택 28 Git 실무 - Git Flow 개념 및 실제 사례

## Git Flow Concepts

1. master : 최종 릴리즈. 종종 긴급 패치가 필요할 때에는 master에서 hotfix 브랜치가 분기되기도 한다.
2. develop : 개발중인 버전
3. feature : 특정 기능을 개발할 때, 기능 개발 완료 후에는 develop 브랜치로 merge 한다.
4. release : 배포를 할 때
5. hotfix : 긴급 버그를 수정할 때
6. support : Git flow cli에서 만들어지는 Flow (거의 쓰지 않음)

## Git Flow를 사용하는 방법
1. Git Extension
> VS Code에 Extension을 설치해서 사용하는 방법

2. 터미널에서 명령어를 사용하는 방법
> 강사님께서 사용하시는 방식.. MAC에 brew를 설치하고 복잡한듯??

### Git Flow를 터미널에서 사용
1. git flow init
2. git branch -a

