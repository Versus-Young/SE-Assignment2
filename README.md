# SE-Assignment2
## https://github.com/Versus-Young/SE-Assignment2.git

### init
먼저 제일 처음 git init 명령어를 사용하면 새로운 Git repository가 만들어진다. 
![init 실행 화면](https://github.com/Versus-Young/SE-Assignment2/blob/36c84ab2bf7a805f3fdf96a1a1f110e0059471bb/init%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B4.PNG)

### status, add
init 명령어를 사용해 만든 repository에서 새로운 파일을 추가한 후, git status 명령어를 사용하면 이런 화면이 나온다. 새로운 파일은 추적되지 않은 파일이라고 나타내어진다. 그 다음 git add <파일명> 명령어를 사용하면 새로운 파일이 커밋된다.
![status, add 실행 화면](https://github.com/Versus-Young/SE-Assignment2/blob/2ad2fea4984b05d97fb3c3bdb4a7171499ae52bc/status,%20add%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B4.PNG)

### config
git config 명령어를 사용해 지금 이 작업을 누가 진행하는지를 알려줄 수 있다. user.name과 user.email 즉, 이름과 이메일을 입력하면 된다.  (--global이란 옵션을 사용해 모두가 알 수 있게 한다.)
![config 실행화면](https://github.com/Versus-Young/SE-Assignment2/blob/2cb8078f225b945eb917a5d6ab339e255c0eb0d4/config%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B4.PNG)

### commit
git commit 명령어를 실행하면 현재 버전에 대한 정보를 조회, 입력할 수 있다.
![commit 실행화면](https://github.com/Versus-Young/SE-Assignment2/blob/efbabd9930f7014d583c21bb59336d85b2391906/commit%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B41.PNG)

이 화면은 commit 명령어를 입력했을 시에 나타난다.
![commit 실행화면2](https://github.com/Versus-Young/SE-Assignment2/blob/efbabd9930f7014d583c21bb59336d85b2391906/commit%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B42.PNG)

그리고 내용을 입력한 후 돌아오면 이런 화면이 나온다.
![commit 실행화면3](https://github.com/Versus-Young/SE-Assignment2/blob/86dc16f93b96c7216ec99bca545cc67d4e0f873e/commit%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B43.PNG)

### log
git log 명령어를 실행하면 현재 버전에 대한 간략한 정보를 볼 수 있다.
![log 실행화면](https://user-images.githubusercontent.com/81523488/117293251-1e3f3980-aeac-11eb-810a-27974f0ab29c.png)

### reset
git reset 명령어를 사용하면 과거 버전으로 돌아갈 수 있다. 이때 옵션에 따라 상태가 달라지는데 --hard 옵션을 사용하면 돌아가고 싶은 버전 이후의 모든 것이 reset된다. 이 화면은 버전 2를 삭제하고 버전 1으로 돌아가는 과정이다. (중간의 git reset과 아무것도 치지 않은 것은 이 과정과 관계가 없다.)

![reset 실행화면](https://github.com/Versus-Young/SE-Assignment2/blob/f93fbe6fed6ea249b9968f423f8e7efbf88024f5/reset%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B4.PNG)

### branch
git branch 명령어를 실행하면 현재 사용중인 branch가 무엇인지 알려준다.
![branch 실행화면](https://github.com/Versus-Young/SE-Assignment2/blob/b029eb137da06f32bd1245d704c44fc4332fb908/branch%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B4.PNG)

새로운 branch를 만들고 싶으면 git branch <branch 이름> 명령어를 사용하면 된다.
![branch 실행화면2](https://github.com/Versus-Young/SE-Assignment2/blob/77aa0496d4c9c8cc02c08f4404185dd2c4905ca3/branch%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B42.PNG)

#### checkout
그리고 다른 branch로 이동하고 싶을 때에는 git checkout 명령어를 사용하면 된다.
![checkout 실행화면](https://github.com/Versus-Young/SE-Assignment2/blob/b75e238b2cdef98f9d33c851915efc31247af37b/checkout%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B4.PNG)

### merge
branch를 병합하고 싶으면 git merge 명령어를 사용하면 된다. exp branch를 master branch에 병합하고 싶으면 git merge <branch 이름> 명령어를 사용하면 되는데 이때 꼭 master branch로 checkout 해야한다.
![merge 실행화면1](https://github.com/Versus-Young/SE-Assignment2/blob/feecd4fa98bf7b47db975aeae5417ea82daf949a/merge%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B41.PNG)

merge를 실행한 결과, 이러한 상태가 된다.
![merge 실행화면2](https://github.com/Versus-Young/SE-Assignment2/blob/38f3f9f6e343fe624907bb5b1b15af94d30f96c9/merge%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B42.PNG)

### clone
git clone 명령어를 사용하면 repository를 복사할 수 있다.
예를 들어 github에 있는 git이란 repository를 복사하려면 이렇게 주소를 복사한 후,
![clone 실행화면1](https://github.com/Versus-Young/SE-Assignment2/blob/541af5c2ec4055a5d1ab7244888d680184804499/clone%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B4.PNG)

git clone <주소> <복사할 directory> 명령어를 사용해주면 복사가 완료된다.
![clone 실행화면2](https://github.com/Versus-Young/SE-Assignment2/blob/541af5c2ec4055a5d1ab7244888d680184804499/clone%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B42.PNG)

### remote
원격 저장소(여기선 github)를 현재 local 저장소에 추가하려면 git remote 명령어를 사용하면 됩니다.
git remote add (별명) <원격 저장소 주소> 이런 식으로 사용해주는 것이 일반적입니다.
![remote 실행화면](https://github.com/Versus-Young/SE-Assignment2/blob/03acedf1b23a59989460eec46e042402fc27054c/remote%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B4.PNG)

### push
로컬 저장소에서 작업한 파일을 원격 저장소에 올리고 싶을 때에 git push 명령어를 사용한다.
git push -u <원격저장소> <로컬저장소> 의 형태로 사용하면 된다. (-u는 다음에도 push를 할 때에 같은 원격 저장소에 저장한다는 뜻이다.)
![push 실행화면1](https://github.com/Versus-Young/SE-Assignment2/blob/5d32921ea3d269decc2367719c54b55b88df12bd/push%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B41.PNG)

명령어를 실행하면 github에 로그인을 해야하고 그 후 다시 돌아오면 이런 상태가 된다.
![push 실행화면2](https://github.com/Versus-Young/SE-Assignment2/blob/5d32921ea3d269decc2367719c54b55b88df12bd/push%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B42.PNG)

### pull
이번엔 원격 저장소에 있는 파일을 로컬 저장소에 불러오고 싶을 때, git pull 명령어를 사용하면 된다.
이 화면은 origin이라는 원격 저장소에서 master라는 로컬 저장소에 파일을 불러오는 화면이다. (아직 바뀐 내용이 없기 때문에 이런 화면이 뜬다.)
![pull 실행화면](https://github.com/Versus-Young/SE-Assignment2/blob/977232138db69e4885ac35ac38c1d0da2f1e40d2/pull%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B4.PNG)

### tag
git tag 명령어를 사용하면 tag를 만들 수 있다. 가장 최신의 커밋에 태그를 만들고 싶으면 git tag <버전> <branch 이름> 이런 식으로 작성하면 된다.

![tag 실행화면](https://github.com/Versus-Young/SE-Assignment2/blob/2262f5a3e61da61ee01514f0c3d6a2957ce0f2fc/tag%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B4.PNG)

그 후, 태그를 원격 저장소에 추가하고 싶으면 git push --tags 명령어를 사용하면 된다.
![tag 실행화면2](https://github.com/Versus-Young/SE-Assignment2/blob/902a90ab42f396f4e8d9ddc419615ad86572b071/tag%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B42.PNG)

### rebase
만약 새로운 branch를 만들고 그 branch를 병합하고 싶을 때에 merge와는 조금 다른 방식으로 작동하는 것이 rebase이다.
예를 들어 new라는 branch를 만들고 최신 base를 master로 변경하고 싶을 때에 new branch로 checkout한 후, git rebase master 명령어를 입력하면 다음과 같은 상태가 된다.

![rebase 실행화면](https://github.com/Versus-Young/SE-Assignment2/blob/b91013429b945f842cecfb833e96cea24027f5cd/rebase%20%EC%8B%A4%ED%96%89%ED%99%94%EB%A9%B4.PNG)

<table>
  <thead>
    <tr>
      <th>init</th>
      <th>status</th>
      <th>add</th>
      <th>config</th>
      <th>commit</th>
      <th>log</th>
      <th>reset</th>
      <th>branch</th>
      <th>checkout</th>
      <th>merge</th>
      <th>clone</th>
      <th>remote</th>
      <th>push</th>
      <th>pull</th>
      <th>tag</th>
      <th>rebase</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>O</td>
      <td>O</td>
      <td>O</td>
      <td>O</td>
      <td>O</td>
      <td>O</td>
      <td>O</td>
      <td>O</td>
      <td>O</td>
      <td>O</td>
      <td>O</td>
      <td>O</td>
      <td>O</td>
      <td>O</td>
      <td>O</td>
      <td>O</td>
    </tr>
  </tbody>
</table>

[init 설명으로 이동](#init)

[status 설명으로 이동](#status-add)

[add 설명으로 이동](#status-add)

[config 설명으로 이동](#config)

[commit 설명으로 이동](#commit)

[log 설명으로 이동](#log)

[reset 설명으로 이동](#reset)

[branch 설명으로 이동](#branch)

[checkout 설명으로 이동](#checkout)

[merge 설명으로 이동](#merge)

[clone 설명으로 이동](#clone)

[remote 설명으로 이동](#remote)

[push 설명으로 이동](#push)

[pull 설명으로 이동](#pull)

[tag 설명으로 이동](#tag)

[rebase 설명으로 이동](#rebase)
