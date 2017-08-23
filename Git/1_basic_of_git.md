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

###1.4 원격 저장소에 푸시하기

-	**push** : 로컬 저장소에서 원격 저장소로 파일을 업로드
	-	원격 저장소와 로컬 저장소가 동일한 상태가 된다.

###1.5 원격 저장소에 복제하기

-	**clone** : 원격 저장소를 복제
	-	변경 이력도 함께 복제되어 온다.

###1.6 원격 저장소에서 풀 해오기

-	**pull** : 원격 저장소에서 최신 변경 이력을 다운로드하여 내 로컬 저장소에 적용(update)
