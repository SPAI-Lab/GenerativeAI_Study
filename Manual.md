## 스터디에 필요한 Github 사용법!

> 먼저, 깃허브 개인 계정이 있어야 함!

## 1. Organization Repository인 SPAI-Lab/GenerativeAI_Study을 fork 한다.

![fork](https://github.com/SPAI-Lab/GenerativeAI_Study/assets/59556524/4e9b433e-04ff-499f-ab3a-c6dfb322e99b)

- fork 하게 되면 개인 계정 repository에 추가됩니다.

## 2. 개인 계정의 GenerativeAI_Study Repository에 접근해서 url을 복사한다.

> **your profile -> Repository -> GenerativeAI_Study**

![개인 repository url 복사](https://github.com/SPAI-Lab/GenerativeAI_Study/assets/59556524/206211bf-5b91-4527-8ea6-e251b6bc74b1)

- `https://github.com/{username}/GenerativeAI_Study.git` username에는 본인 ID가 있어야 합니다.

## 3. git clone

- 본인 컴퓨터에서 해당 스터디 폴더를 저장하고자 하는 곳에 git clone을 한다.
- 그럼 내부에 GeneraltiveAI_Study 폴더가 생긴다.
- `cd GeneraltiveAI_Study`를 통해 해당 폴더에 접근한다.

![git clone](https://github.com/SPAI-Lab/GenerativeAI_Study/assets/59556524/79f6968c-5294-4d85-aeec-988bc97d8bd9)

## 4. 브랜치 생성과 체크아웃

- 브랜치 생성과 체크아웃을 동시에 하는 명령어 `git checkout -b YujinJI`
  - `YujinJI`라는 브랜치 생성되면서 `YujinJI` 브랜치로 이동함

![브랜치 생성](https://github.com/SPAI-Lab/GenerativeAI_Study/assets/59556524/8f6c8386-3fda-45a2-ae0f-d8a756c69304)

## 5. 본인 코드 작성

> ⚠️ `{username}` 브랜치에서 작성해야 함! 작성자는 `YujinJI` 브랜치에서 작성

### week1에 대해 코드를 작성하고자 한다면 `week1/지유진/filename.ipynb`에 작성

> 암묵적으로 폴더 이름은 본인 이름으로 합시다. 🤝

![vscode](https://github.com/SPAI-Lab/GenerativeAI_Study/assets/59556524/e19ff1c6-cab0-45ed-a5a0-3e630b4eafc4)

에디터는 본인이 사용하는것으로, 작성자는 vscode 사용했음. 또는 에디터를 사용하지 않아도 됨.

> colab을 사용하는 경우, 드라이브에서 해당 파일 다운로드 후 `C://.../GeneraltiveAI_Study/week1/지유진/{여기!}` 넣어도 됩니다.

## 6. 개인 Repository에 파일 업로드 (Feat. 명령어)

![파일 업로드](https://github.com/SPAI-Lab/GenerativeAI_Study/assets/59556524/72a92b27-d292-4e62-ac57-4bbf89f32d63)

### 1. git add .

- 변경된 내용을 git에 add
- `git add .` 에서 `.`은 변경된 모든 파일을 뜻함.
  > 특정 파일만 add 하고 싶다면 `git add week1/지유진/mlp.ipynb`와 같이 사용가능

### 2. git commit -m "커밋내용"

- 어떤게 변경되었는지 작성하면 됩니다.

### 3. git push origin {브랜치이름}

- {브랜치이름}브랜치의 원격저장소에 추가된 내용을 push 합니다.

### 이후 개인 Repository에 {브랜치이름}브랜치를 살펴보면 추가한 내용이 보임

## 7. Pull request 보내기

![pull request](https://github.com/SPAI-Lab/GenerativeAI_Study/assets/59556524/c70026dd-3d7f-4ad1-8a90-a9d20fd33706)

- 내가 추가한 내용을 Organization Repository인 SPAI-Lab/GenerativeAI_Study에 합쳐달란 뜻

![pull request 내용](https://github.com/SPAI-Lab/GenerativeAI_Study/assets/59556524/926e224f-9420-41cc-8789-1f2618b4f835)

- 위 사진은 YujinJI/GenerativeAI_Study의 YujinJI 브랜치를 SPAI-Lab/GenerativeAI_Study의 main 브랜치에 합쳐달라는 뜻!! **아주 중요 ⭐️**

모든 과정이 끝나면, 랩장이 pull request 변경사항 확인하고 main에 merge(병합)할 수 있습니당. 본인이 마음대로 merge 해버리기 금지

## 끝이 아님 ..^^ 😱

만약, 스터디원들이 Organization Repository인 SPAI-Lab/GenerativeAI_Study에 Pull request를 올렸고, 랩장이 승인을 했다? 그럼 여기에 변경 사항이 생기게 됩니다.

하지만 개인 Repository인 GenerativeAI_Study에는 변경 사항이 자동으로 업데이트 되지 않는다는 점,

이때는, 먼저 **개인** Repository GenerativeAI_Study에 접속 후 **main** 브랜치에서 Sync fork -> Update branch를 클릭합니다.

![update branch](https://github.com/SPAI-Lab/GenerativeAI_Study/assets/59556524/bb38c8dd-f9a1-4596-a55f-0d0a8d135016)

> 변경사항이 있을때만 해당 버튼 활성화됨. Update branch를 클릭하게되면 Organization Repository인 GenerativeAI_Study의 변경사항을 업데이트해줌.

### 굳이 이 작업을 하는 이유❓

```
만약 누군가가 내 Repository를 구경한다고 칩시다.

GenerativeAI_Study 레포가 보이네?? 구경해야겠다!

뭐야 아무것도 없네??

를 방지하기 위해서 틈틈히 업데이트 해주자구요.
```

### 그렇다고 내 컴퓨터 폴더가 자동으로 업데이트 되지 않음 ..^^ 😵

> 내 컴퓨터 파일에서 모든 사람의 폴더를 갖고싶은 경우 해당되는 내용으로 굳이..! 안해도 되는 작업

일단, 터미널에서 개인 계정의 GenerativeAI_Study Repository에 접근 후, **main** 브랜치로 접속

![git checkout main](https://github.com/SPAI-Lab/GenerativeAI_Study/assets/59556524/e5bf400a-e415-4c73-b9d3-f981cdc6003b)

![git pull origin main](https://github.com/SPAI-Lab/GenerativeAI_Study/assets/59556524/3ce8a3a7-b7da-491c-a2c3-270379bd1345)

`git pull origin main` 명령어를 통해 원격 저장소에 있는 main 브랜치를 땡겨오겠다는 뜻, 변경사항이 있다면 위 사진과 같이 동작합니다.

## 아마두 최종

- 깃허브 사용할 때 작성자처럼 터미널에 명령어 하나하나 치는 사람 별로 없을겁니다.. 좋은 툴 있으면 찾아 쓰시는 것을 추천! [10가지의 git GUI tool 추천](https://hosuappa.tistory.com/16)
- git을 처음 접하시는 분이라면 이 모든 내용이 다 외계어로 들릴 것..! 검색해보면서 차근차근 알아가는 게 좋습니다. 또는 쓰다보면 익숙해짐
- push를 잘못했다???!?!??! 놀란 마음 진정하시고 구글링 할 것

### Organization Repository, 개인 Repository 그게 몬데..

| 명칭                    | 설명                                                                                                  |
| ----------------------- | ----------------------------------------------------------------------------------------------------- |
| Organization Repository | 팀원들이 하나의 조직에 포함되어 있는 것으로, Organization - SPAI-Lab, Repository - GenerativeAI_Study |
| 개인 Repository         | 개인 계정의 Repository로, 개인 - YujinJI, Repository - GenerativeAI_Study                             |
