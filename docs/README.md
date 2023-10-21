## 📌 구상
1. 게임 시작 문구 출력
2. 컴퓨터 숫자 랜덤 생성
3. "숫자를 입력해 주세요 : " 메시지와 함께 콘솔 입력 받기
   - 있는 숫자 && 맞는 자리 → 스트라이크
   - 있는 숫자 && 다른 자리 → 볼
   - 하나도 없는 경우 → 낫싱
   - 모두 맞힌 경우 → 3스트라이크 후, 게임 종료
   - 유효하지 않은 값 → `throw`문으로 예외 발생 후 종료
4. 게임 시작/종료를 나누는 `1` 또는 `2` 콘솔 입력 받기
<br />
4-1. `1` 입력 시, 3번으로 돌아감 <br />
4-2. `2` 입력 시, 프로그램 종료

## 📌 주의 사항
- 우테코 자체 `Random` 및 `Console` API 사용
- 프로그램 종료 시, `process.exit()` 호출 X
- [JavaScript 코드 컨벤션](https://github.com/woowacourse/woowacourse-docs/tree/main/styleguide/javascript) 지키기