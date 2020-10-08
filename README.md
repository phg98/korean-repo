## 한국어로 된 깃헙 저장소를 관리하시나요? 
## 한국어 깃헙 저장소에는 'korean'이라는 토픽을 붙여주세요!🇰🇷

### 현재까지 캠페인 참여 저장소의 갯수는
<h2 id='counter1'>잠시 기다리세요...</h2>
<script>
  async function getKoreanRepos() {
    let searchString = `https://api.github.com/search/repositories?q=topic:korean`

    let res = await fetch(searchString)
    let data = await res.json()
    let total = data.total_count
    var elem = document.getElementById('counter1');
    elem.textContent = total - 427;
}
getKoreanRepos()
</script>
### 입니다! 참여하여 카운트를 올려주세요!!
---
**한글날**을 맞아 작은 캠페인을 해보려고 합니다.

초보자들이 기여하려고 할 때 큰 두려움 중에 하나가 영어입니다.
영어로 된 저장소들 보기만 해도 무섭지 않으신가요? :scream:

그래서 마음편한 한국어 저장소(_저장소 설명, 이슈 관리등이 한국어로 되어있고 한국어 질문답변이 가능한 저장소_)를 찾기 위해 깃헙 검색에서 토픽으로 검색해 보면 

![topic_korean](https://user-images.githubusercontent.com/12092302/95450487-54155180-09a1-11eb-86d2-3786035d9626.png)

* topic:korean : 427개
* topic:korea  : 114개
* topic:hangul :  83개

으로 총 **624개**의 저장소가 있습니다. (10월 8일 기준)

반면 사용자 검색을 해보면 거주지가 korea인 사람은 훨씬 많습니다.

* location:korea : 33,660명

**33,660명**입니다. (10월 8일 기준) 

즉 **한국어 저장소중에 관련된 토픽으로 검색이 안되는 저장소가 꽤 많이 있다**고 추정됩니다.🕵️‍♂️

그래서, 검색이 안되는 수많은 한국어 저장소가 있을것 같으니 이 저장소들에 한국어 저장소임을 나타내는 토픽을 붙여주시면 검색이 용이할것 같습니다.

마침 이제 한글날이니 의미도 있겠구요.!🇰🇷

그래서 **한국어 저장소 관리자 분들께** 한국어로 관리되는 저장소에는 **'korean'이라는 토픽을 붙여주세요**라는 요청을 드립니다. :pray:



### 왜 이런 일을 하나요? :raising_hand:

이 캠페인은 어떠한 단체, 회사와도 관계가 없고 제가 개인적으로 하고 싶어서 하는 캠페인입니다. 

큰 이유는 없습니다. 제가 찾기 힘드니, 다른 분들도 힘들 것이라 생각했습니다.


### '내 저장소는 별거 없어서...'라고 생각하신다면 :heart:

물론 굳이 토픽을 안 붙이셔도 괜찮습니다. 하지만 작은 저장소가 초보자들에게는 오히려 더 도움 되지 않을까요?


### 설정후에 카운터를 확인하세요! :rocket:

topic이 korean인 저장소의 갯수는
10월 8일 기준 **427개** 였습니다.
현재는
<h2 id='counter'>잠시 기다리세요...</h2>
<script>
  async function getKoreanRepos() {
    let searchString = `https://api.github.com/search/repositories?q=topic:korean`

    let res = await fetch(searchString)
    let data = await res.json()
    let total = data.total_count
    var elem = document.getElementById('counter');
    elem.textContent = total;
}
getKoreanRepos()
</script>
개 입니다.
저장소에 토픽을 설정하시고 카운터가 늘어났는지 확인해 보세요!


## 저장소 토픽 설정 방법

### 1. 저장소 About의 톱니바퀴 설정 버튼을 클릭

![about](https://user-images.githubusercontent.com/12092302/95475144-e2e59680-09c0-11eb-9ab2-840718b9e954.png)


### 2. topics에 korean 입력후 저장

![topic](https://user-images.githubusercontent.com/12092302/95475160-e5e08700-09c0-11eb-9f1d-f6caa99eb967.png)

---

### 캠페인에 참여하면 어떤 이익이 있나요?

제가 특별히 드릴 것은 없고... 아래에 저장소를 링크해 주시면 이 페이지를 본 사람들이 많이 찾아주시지 않을까요...

그리고 10월 말쯤에 결과를 정리해서 업뎃하겠습니다.

## 캠페인에 참여하는 저장소 링크

* [한국어 저장소 찾아주기 캠페인 페이지](https://github.com/phg98/korean-repo) : 보고 계신 이 페이지 입니다.
* [Hacktober Korea](https://github.com/phg98/hacktoberfestkorea) : 핵토버페스트 행사의 한국어 비공식 사이트입니다.
* _링크를 추가하시려면 [여기](https://github.com/phg98/korean-repo/edit/main/README.md)를 눌러주세요! 초보자분도 수정 가능합니다!_
<!-- 첫 줄을 복사하여 중간쯤에 붙여넣고 내용을 수정해 주세요 -->
<!-- 저장소 운영자 분들이니 초보자는 없으시겠죠. 혹시 초보자 이시라면 내용수정후 아래 'Propose Change'버튼 누르고 화면마다 녹색 버튼 누르면 됩니다. 아무 생각 하지 마시구요 -->
<!-- 이 사이트는 핵토버페스트 행사와 무관하며 여기에 PR을 보내셔도 핵토버페스트에 카운트되지 않습니다. 유의하세요! -->

긴 글 읽어주셔서 감사합니다!

```

이 문서를 수정하고 싶으시면 [여기](https://github.com/phg98/korean-repo/edit/main/README.md)를 눌러 주세요.
이 사이트에 문제가 있다거나 연락하고 싶으시다면 phg98@naver.com으로 메일을 보내주세요.


