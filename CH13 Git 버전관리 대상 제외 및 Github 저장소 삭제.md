
# CH14. Git 버전관리 대상 제외 및 Github 저장소 삭제

<br>
<br>

## 1. .gitignore 파일에 GIt 버전관리 제외 설정하기

<br>

```
toouh .gitignore
```

<br>

![](Files/image%2081.png)  

<br>

- 관리대상에서 제외된 파일은 목록에서도 아래처럼 제외됩니다.

<br>

```
git status
```

<br>

![](Files/image%2082.png)  

<br>  

- 스테이지에 추가하기  

```
git add .
git status
```

<br>

![](Files/image%2083.png)  

<br>  

- 커밋 메세지 작성하기   

```
git commit -m "프로젝트 생성"
git log
```

<br>

![](Files/image%2084.png)  

<br>
  

- 원격저장소에 업로드 하기 -  원격저장소를 새로 만든 다음 진행해 주세요!
  
```
git remote add origin https://github.com/labri70/vscode-project1.git
git branch -M main
git push origin main
```

<br>

![](Files/image%2085.png)  

<br>
<br>  

## 2. Github 저장소 필요없는 원격저장소 삭제하기

<br>

- Step1  -  상단에  \[ Settings \]  메뉴를 클릭해서 이동합니다.

  

![](Files/image%2086.png)  

<br>  

- Step2  -  하단에  \[ Danger Zone \] 으로 이동 후  \[ Danger Zone \] 에서  Delete this reposiory 클릭합니다.  

![](Files/image%2087.png)  

<br>

![](Files/image%2088.png)  

<br>

![](Files/image%2089.png)  

<br>

  

- 아래처럼 원격저장소 이름을 똑같이  작성 후  \[ Delete this reposiory \]  클릭하면 삭제됩니다!  

![](Files/image%2090.png)  

