# Git 사용팁
* local에서 feature/new라는 새로운 branch 만들기

  ```
  > git branch feature/new
  ```
  
* local에서 feature/new라는 새로운 branch를 만들면서 이동하기

  ```
  > git checkout -b feature/new
  ```
  
* local에 있는 branch 목록 보기

  ```
  > git branch -l
  ```
* remote에 있는 branch 목록 보기

  ```
  > git branch -r
  ```
  
* local, remote에 있는 모든 branch 목록 보기

  ```
  > git branch -a
  ```
  
* local에서 이전 remote branch 목록 최신화 하기

  ```
  > git fetch -p
  ```
  
* local에서 feature/new라는 branch를 feature/main이라는 branch로 이름 변경하기

  ```
  > git branch -m feature/new feature/main  
  ```
  
* local에서 만든 feature/new라는 branch 삭제
  ```
  > git branch -d feature/new
  ```

* remote에 있던 feature/new라는 branch 삭제
  ```
  > git push --delete origin feature/new
  ```
  or

  ```
  > git push origin :feature/new
  ```
