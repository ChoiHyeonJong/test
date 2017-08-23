##튜토리얼 1. Git의 기본

---

###1.1 초기 설정

-	**.gitconfig**

```
   $git config --global user.name "<사용자명>"
   $git config --global user.email "<메일 주소>
   $git config --global color.ui auto
```

###1.2 새 저장소 만들기

-	로컬에 tutorial 저장소 등록
	-	tutorial 폴더 생성 후 폴더에서 **git init**

```
   $git init
```

###1.3 파일 커밋하기

-	tutorial 폴더에 새로운 파일 추가 후 임의 입력
-	작업트리와 인덱스 상태 확인 **git status**

```
   $git status
```

-	파일을 인덱스에 등록 (추적 대상 등록) **git add**

```
   $git add <file>
```

-	커밋 **git commit**

```
   $git commit
```

-	변경 이력 확인 **git log**

```
   $git log
```

-	변경 이력 GUI 확인 **gitk**

```
   $gitk
```
