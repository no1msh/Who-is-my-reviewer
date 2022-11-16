## 🎯기능 목록

- 분할 관련 기능 - `Spliter` : `Class`
    - enumMap을 초기화 한다. - `init`
    - 로또의 숫자를 몇개를 맞추었는지 확인하여 등수를 알려준다. - `checkMyLotto()`


- 당첨등수 관련 기능 - `Win.kt` : `Enum Class`
    - 로또의 당첨등수를 알려준다. - `getMyPlace()`
    - 당첨등수에 따른 상금을 알려준다. - `getIncome()`


- 로또판매점 관련 기능 - `LottoMarket.kt` : `Class`
    - 1 ~ 45까지의 중복되지 않는 숫자 6개를 뽑는다. - `createLotto()`
    - 사용자가 로또를 구입하려는 금액에 맞추어 로또를 발행한다. - `buyLottos()`
    - 사용자가 구매하려는 금액에 맞춘 로또의 개수를 알려준다. - `getTheNumberOfLotto()`
