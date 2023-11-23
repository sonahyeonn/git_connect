# git_connect

# git 설치 -> 기본값으로 그대로 설치했음

# 시작버튼에서 Git Bash 열기(실행)

```
git config --global user.name "ahyeon"
```

# gitHub 가입시 입력한 이메일과 동일해야 한다
```
git config --global user.email "koinohibi@gmail.com"
```
# 정보 확인하기
```
git config --list
```
![image](https://github.com/sonahyeonn/git_connect/assets/147791395/d02ebbd6-ba14-4832-aeeb-9494d1775f44)

위의 내용은 컴퓨터에 한번만 설치하면 됨
---------------------------------------
---------------------------------------

# gitHub에 코드 업로드 하기


1. 초기화

   ```
   git init
   ```
# .git이라는 폴더가 생성된다

2. 파일 올리기

   ```
   git add .
   ```

3. 히스토리 만들기

   ```
   git commit -m "내가 적고싶은 메시지"
   ```
# 메시지에는 한글이 가능함
# -메세지의 준말

4. gitHub repository랑 내 로컬 프로젝트랑 연결 (깃업에 프로젝트를 올릴 repository를 먼저 만들어야 한다)
# 아래 주소는 깃업에서 만든 repository에서 복사해서 가져와야 한다(repository를 만들때 read.me 선택하지 말기)

   ```
   git remote add origin https://github.com/sonahyeonn/webstandard.git
   ```

5. 잘 연결 되었는지 확인 (필수아님)

   ```
   git remote -v
   ```

6. Github에 자료 올리기

   ```
   git push origin master
   ```
   
# 여기까지 하면 Github의 repository에 자료가 올라가 있다

----------------------------------

# GitHub에 계속 업데이트 하는 법 💕💕💕💕💕

1. 추가할 파일 더하기

```
git add .
```

2. 히스토리 만들기

```
git commit -m "두번째 수정 2023/11/23"
```

3. GitHub에 올리기

```
git push origin master
```

📌📌📌📌📌 올릴때 오류가 발생한다면

# 1. 다시 github의 내용을 끌어와야 한다

```
git pull origin master
```

# 2. 히스토리 만들기

```
git commit -m "메세지"
```

# 3. github에 올리기

```
git push origin master
```
