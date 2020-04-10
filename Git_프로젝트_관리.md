# Git 프로젝트 관리

## 1. .gitignore

> git으로 관리하지 않고 싶은 파일 목록은 `.gitignore` 에 정의한다.

```bash
$ vi .gitignore
```

에 들어가서

1. `i`누른 후 [gitignore.io](https://www.gitignore.io/)에서 복사한 것을 붙여넣는다
2. `esc` -> `:`->`wq`로 vi 에서 나온다



```
*.xlsx          # 특정 확장자
secret.txt      # 특정 파일
tests/          # 특정 폴더
```

- 주의 : 확장자 없음
- 만약, 어떠한 파일을 일반적으로 등록하는지 모른다면 [gitignore.io](https://www.gitignore.io/)을 참고하자.
  - 예) `ipynb_checkpoints/`

## 2. 파일 크기 문제 

### 1. Git-lfs

> 용량이 큰 파일을 관리하기 위해서는 `git-lfs` 설정이 필요하다.

- https://git-lfs.github.com/ 참고 할 것.
- 주의 : 해당 파일이 이미 커밋되면 다른 작업을 거쳐야함.

### 2. github student pack

- https://education.github.com/pack

- 학교 메일로 가입 가능