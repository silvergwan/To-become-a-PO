## 토스 리더가 말하는 PO가 꼭 알아야할 개념 | Carrying Capacity

[
토스 리더가 말하는 PO가 꼭 알아야할 개념 | PO SESSION](https://youtu.be/tcrr2QiXt9M?si=EiIhK-UgQEA4Qe8w)

### 데이터 그로쓰 모델링 질문 5개

#### Q1.

You notice that your power users all have taken
some action (e.g. filled out their profile)
_당신은 당신의 파워 유저들이 모두가 어떤 행동( 프로필을 채워 넣음 )을 한다는 것을 알고있다._
so you try to encourage all users to fill out their profile
to get them more hooked on your product
_그래서 당신은 모든 유저가 제품에 더 많은 관심을 갖게 하기 위해(파워 유저로 만들기 위해) 그들의 프로필을 채워넣도록 장려한다._
Does this actually help?
_실제로 도움이 될까?_

#### Q2.

You have 24 hours of downtime,
_당신의 서비스가 24시간 동안 장애(중단시간)을 가졌다,_
the next day you come back up your traffic is down.
_다음 날 복구 후 트래픽이 감소한다._
Will this have a long-term effect you need to worry about?
_이 것은 장기적으로 걱정해야할 영향을 미칠까?_

### Q3.

You have 100K uniques per day and so does your competitor,
_당신과 경쟁사는 하루 10만명의 유저를 가지고 있다._
but are these 100K people who come back everyday
_하지만 이 유저들은 매일 방문하는 10만명일까?_
or 700K people who each come once per week?
_아니면 일주일에 한 번씩 방문하는 70만명일까?_
Does it matter?
_이것이 문제가 될까?_

**uniques - 순 방문자(중복제거)**

#### Q4.

You turn on a new advertising campaign
and see your # of unique visitors per day start to
increase,
_당신은 새로운 광고 캠페인을 시작해서_
_하루 순 방문자 수가 증가하는 것을 볼 수 있습니다._
you assume that this will continue increasing
so long as you keep the ads running, right?
_당신은 광고가 지속되는 한_
_이것(하루 순 방문자 수)이 게속 증가할 것이라고 추정합니다._

#### Q5.

You start having email deliverability problems
(or Facebook turns off notifications)
_당신의 서비스의 이메일 전달 기능이 더 이상 동작하지않습니다._
_(또는 페이스북이 알림 기능을 끕니다)_
so you can't notify users of new activity on the site.
The # of unique visitors decreases slightly
but you're not too worried, should you be?
_그래서 사이트에서 새로운 활동에 대해 사용자에게 알릴 수 없습니다._
_순 방문자 수가 약간 감소합니다._
_하지만 걱정하지 않아도 될까요?_

---

### 이 다섯가지 질문에 답을 줄 수 있는 핵심개념 - Carrying Capacity

#### Carrying Capacity를 한줄로 요약하면?

> 호숫가에 물의 높낮이가 어디까지 올라올까'

#### 호숫가의 물이 어디까지 올라올 수 있을까?

호숫가의 물의 높이는 땅의 지형과 상관 없이

- 호숫가의 물을 채우는 비( Inflow - 유입 )
- 호숫가에서 바닥으로 빠지는 물( Churn - 이탈)

이 두가지의 비율에 따라 호숫가의 물의 양이 결정된다.

#### Carrying Capacity(한계 수용 능력) 의 생태학에서의 의미

> 주어진 자원(먹이, 물, 서식지 등)으로 자연환경이 유지될 수 있는 특정 생물종의 최대 개체 수.

결국 호숫가의 물은 MAU(Monthly Active Users)이고

호숫가에 내리는 비는 Inflow(유입 유저)

물의 비율(MAU의 퍼센트)에 따라 바닥으로 빠지는 물은 Churn(이탈 유저)

---

### 결론

**Carrying Capacity가 결국 물의 양(MAU)를 결정하고**

**이 물의 양이 결정되는 데는 Inflow와 Churn 외에는 아무런 상관이 없다.**

**즉**

Total Customers(총 소비자 수)는

- New Customer Today(들어오는 유저)와
- Lost Customers Today(나가는 유저),

단 두 가지 요소만 영향을 미친다.

---

### Customer에 대한 정의

a. Active를 어떻게 정의하나

- I. 95%이상의 Visitor가 꼭 하게 되는 활동
- II. Page by Page, Repeatable하고, Meaningful한 Action인가?

b. Churn은 어떻게 정의하나?

- I. 얼마를 안써야 안오는거라고 정의할까? 1일? 4일?
- II. 상식적으로 이정도를 안썼으면 Loss될 것 같다를 정한다.**(나중에 바꾸면 안됨!)**
  1. ex, 샤잠 : 한 달에 한번 쓰는 앱, 3개월을 Churn으로 정의
  2. 토스 송금은? 30%가 이전달에 온 적이 없는 유저(매달 사용자 구성이 꽤 바뀐다는 뜻 -> 유입이 잦다는 뜻)
  3. 카톡은? 보통 매일 쓰는데 30일 동안 안 썼다면? -> 아마도 Churn

#### Zeta의 Active와 Churn은 어떻게 정의해볼까.

**Page by page, Repeatable, Meaningful한 기준으로 봤을 때 Active는**

- 대화 페이지에선 일단 일일 대화 5회 이상이 Active
- 홈탭이라면 플롯 1개 클릭 후 진입이 Active

> 대화는 반복적이고, 제타의 본질.

**그럼 Churn은**

- 아마도 30일,

  제타는 DAU와 사용시간이 높기 때문에 카카오톡과 비슷한 맥락일 듯

---

### Carrying Capacity(CC) 구하기

```
Carrying Capacity = # Of New Daily Customer / % Customers You Lost Each Day
```

> CC는 매일매일 새로 오는 유저 수를 매일 잃게 되는 유저의 비율로 나누는 것

예를 들어 75만 명의 유저수를 가진 서비스가 있음,
<br>1%가 매일매일 이탈하고 7500명이 유입됨

75만의 1% = 7500

유입되는 족족 이탈하기 때문에 CC는 그대로 유지됨(75만)

### 그런데

예를 들어 75만 명의 유저수를 가진 서비스가 있음
<br>1%가 매일매일 이탈하고 7000명이 유입됨

첫날에는 75만 명의 1%인 7500명이 이탈함,
<br>반면 신규 유입은 7000명이므로 전체 유저수는 500명이 준다.

> 750000 + 7000 - 7500 = 749500

이후 이터레이션에도 유입은 하루 7000명으로 일정하지만, <br>계속 500명이 빠지기에
1%에 해당하는 이탈자 수도 함께 줄어듬.

결국 하루 이탈자가 7000명이 되는 시점(평형점)에서 <br>유입과 이탈이 같아지고 유저수가 70만 명에서 더 이상 변하지 않음.

### 반대로 얘기하면

만약에 75만의 유저수를 가진 서비스의 유출이 1%에서 0.1%로 줄어버리면<br> 유출되는 양이 750명으로 줄고 <br>CC가 10배가 되서
MAU가 750만의 서비스가 될 수 있음.

### Carrying Capacity는 제품의 본질적인 체력(마케팅, 광고가 제외된)

광고나 마케팅 푸시 같은 것들을 걷어내고
<br>이 제품의 순수한 유저를 모으는 힘
<br>본질적인 체력이 튼튼해야 MAU도 많이 증가할 수 있다.

---

### 요점

광고, 마케팅 다 끄고 있을 때 매일매일 들어오는 유저 수가 얼마냐
<br>그리고 전체 MAU 중에 우리가 몇 퍼센트를 잃고 있냐
<br>이 두개의 숫자를 변화시키는 제품개선 활동 외에는
<br>**전부 MAU를 바꾸는데 일절 영향을 주지 못한다.**

- 나가는 유저의 비율을 줄이거나
- 가만히 있어도 들어오는 제품의 유저수를 늘리거나

---

### 답이 없는 퀴즈지만 나의 답

#### Q1.

현재 MAU 10만, Carrying Capacity는 75만. 광고를 해야할까?

#### A1.

> 해도 되고 안 해도 된다,
> <br>어차피 가만히 있어도 75만에 도달하게 되어있지만
> <br>더욱 빠르게 도달할 수 있고 유입이 늘어 CC가 늘 수도 있다.

#### Q2.

현재 MAU 70만, Carrying Capacity는 75만. 광고를 해야할까?

#### A2.

> 단순히 75만 까지 도달하는 것이 목적이라면 필요하지 않다.

#### Q3.

현재 MAU 100만, Carrying Capacity는 75만. MAU는 떨어질까?

#### A3.

> 떨어진다, 이탈이 1만, 유입이 7500이기 때문에 2500씩 떨어지고 <br>그에 따라 이탈 수도 줄어 결국 75만에 도달한다.

---

### 근본적인 제품의 개선 없이는 MAU가 증가하는게 불가능한 시점이 온다.

마케팅 활동을 통해
<br>일시적으로 Inflow Boosting은 가능하지만
<br>결국 광고를 끄면 그대로 다시 주저앉게 됩니다.
<br> Carrying Capacity가 변하지 않았기 때문

결국 근본적인 Carrying Capacity의 향상은
<br>제품 개선을 통한 Inflow와 Retention 향상,
<br>Churn 감소 외에는 방법이 없고,
<br>이것은 마케팅 활동으로는 바뀔 수 없습니다.

---

### 댓글 중에 좋은 내용

이해를 도와주는 댓글

```
CC가 스타트업에만 적용되는 어려운 개념이라기보다는 전통 비즈니스인 식당에도 적용이 가능하죠. 단골이 계속 늘면 그 식당은 잘될수 밖에 없다는 우리가 잘알고 있는 개념이네요. 다운타임은 식당이 하루 닫았다고 해서 문제가 없는 것과 마찬가지이구요. 식당 주인이 단골이 얼마나 느는지 주는지 신경써야 하는 이유이기도 합니다.
```

요약 같은 댓글

```
 cc=유입/유출인데, 1~2달내 계산된 cc가 일반적으로 현재 서비스의 최종적인 mau가된다. 즉, 광고를 제외하고 제품 자체로 유입을 늘리고 유출을 줄이는 방법에 대한 미친듯이 많은 실험과 성공사례를 뽑아내는 것이 중요하다.
```
