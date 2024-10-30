# java-lotto-precourse

# 로또

## 구현할 기능 목록

- [x] 사용자로부터 로또 구입 금액을 입력받는 기능 (1000원 단위로 입력 받아야 함)
- [x] 사용자로부터 당첨 번호를 입력받는 기능 (중복x)
- [x] 사용자로부터 보너스 번호를 입력받는 기능
- [x] 로또를 발행하는 기능
- [] 로또 번호를 오름차순으로 정렬하는 기능
- [x] 입력받은 로또 번호와 생성된 로또 번호를 비교하는 기능
- [] 발행한 로또 번호를 출력하는 기능
- [] 발행한 로또 개수를 출력하는 기능
- [] 당첨 통계를 출력하는 기능
- [] 총 수익률을 계산하는 기능
- [] 총 수익률을 출력하는 기능
- [] 수익률을 소수점 둘째 자리에서 반올림하는 기능
- [] 
- [] 

## 예외 사항 처리

- [] 로또 구입 금액이 1000원 단위로 나누어 떨어지지 않으면 예외 처리
- [x] 사용자로부터 입력받은 당첨 번호가 1부터 45 사이의 숫자가 아닌 경우 예외 처리
- [x] 사용자로가 중복된 당첨 번호를 입력받았을 때 예외 처리
- [x] 입력받은 로또 번호가 6개가 아닐 때 예외 처리
- [x] 입력받은 로또 금액이 음수일 경우 예외 처리
- [x] 입력받은 로또 금액이 1000원 미만일 경우 예외 처리
- [] 



기능 요구 사항

간단한 로또 발매기를 구현한다.

로또 번호의 숫자 범위는 1~45까지이다.
1개의 로또를 발행할 때 중복되지 않는 6개의 숫자를 뽑는다.
당첨 번호 추첨 시 중복되지 않는 숫자 6개와 보너스 번호 1개를 뽑는다.
당첨은 1등부터 5등까지 있다. 당첨 기준과 금액은 아래와 같다.
1등: 6개 번호 일치 / 2,000,000,000원
2등: 5개 번호 + 보너스 번호 일치 / 30,000,000원
3등: 5개 번호 일치 / 1,500,000원
4등: 4개 번호 일치 / 50,000원
5등: 3개 번호 일치 / 5,000원
로또 구입 금액을 입력하면 구입 금액에 해당하는 만큼 로또를 발행해야 한다.
로또 1장의 가격은 1,000원이다.
당첨 번호와 보너스 번호를 입력받는다.
사용자가 구매한 로또 번호와 당첨 번호를 비교하여 당첨 내역 및 수익률을 출력하고 로또 게임을 종료한다.
사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시키고, "[ERROR]"로 시작하는 에러 메시지를 출력 후 그 부분부터 입력을 다시 받는다.
Exception이 아닌 IllegalArgumentException, IllegalStateException 등과 같은 명확한 유형을 처리한다.