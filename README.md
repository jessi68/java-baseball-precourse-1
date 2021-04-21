# 숫자 야구 게임
## 게임 요구사항
### 입력사항
- [] 사용자가 세자리 숫자를 입력한다.

### 컴퓨터가 선택한 야구공 생성
 - 랜덤하게 세자리 숫자를 생성한다.
 - 제약 조건
-[o] 각 자릿수가 1보다 크거나 같고, 각 자릿수가 9 보다 작거나 같은지 확인
 -[] 각 숫자를 바탕으로 야구공을 만든다.

### 게임 진행 사항
* 사용자가 입력한 수와 컴퓨터가 선택한 수를 비교해 완전히 같을 때까지 아래 과정을 반복한다.
 - [] 수가 같고 같은 자리에 있으면 스트라이크를 매긴다.
-  [] 수가 같고 다른자리에 있으면 볼을 매긴다.
-  [] 같은 수가 전혀 없으면 포볼 또는 낫싱을 매긴다.

### 출력 사항
 - 게임을 1라운드 진행할때마다 매긴 점수를 출력하여 사용자에게 힌트를 준다.