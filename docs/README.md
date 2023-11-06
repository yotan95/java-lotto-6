### 예외사항
> 사용자 입력시 : [ERROR] 문구를 포함한 안내문 출력후, 다시 시작
> * 로또의 번호의 숫자가 x < 0 || x > 45 일때
> * 금액 및 로또 숫자 입력시 문자, 공백 입력 했을때
> * 구분자를 쉼표(,)로 입력하지 않았을때
> * 구입금액이 1000원 단위로 떨어지지 않을때

### 함수 설정
```java
public void inputPrice(){ }
// 사용자가 지불할 금액 입력 함수

public ArrayList<Lotto> getUserLotto(){ return ArrayList<Lotto>; }
// 구입금액에 따른 랜덤으로 부여된 로또번호를 반환해주는 함수.

public Lotto drawWinner(String number){ return Lotto; }
// 입력된 당첨번호를 split해서 반환해주는 함수
// 구분자가 쉼표가 아니라면 ERROR

public Integer drawBonus(){ return bonus; )
// 당첨번호 보너스 숫자를 반환해주는함수

public Integer confirmationWinner(ArrayList<Lotto> list){ return matchCount; }
// 입력된 숫자와 랜덤으로 부여된 숫자가 몇개 일치하는지 확인하는 함수

public Double getMargin(Integer cost, Integer profit){ return margin; }
// 수익률을 반환하는 함수 ( 수익률 : profit / cost )

```
