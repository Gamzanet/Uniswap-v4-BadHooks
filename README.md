# [Uniswap-v4-BadHooks](https://www.notion.so/entropy1110/Composable-Security-Threat-for-Uniswap-v4-Hooks-110ec224c99380fbafe0dcd1c09447f9?pvs=4)

예제 프로젝트는 모두 example 폴더 내부에 submodule로 구성되어 있습니다.
서로 구분된 환경에서 작업한 결과물을 취합한 결과, 의존성이 많아 설치에 다소 시간이 걸릴 수 있습니다.
구현 내용 및 결과는 [Notion](https://www.notion.so/entropy1110/Composable-Security-Threat-for-Uniswap-v4-Hooks-110ec224c99380fbafe0dcd1c09447f9?pvs=4)에 기록되어 있습니다.

# [ExploitSoir/Uniswap_v4_hook_sample](https://github.com/ExploitSori/Uniswap_v4_hook_sample.git)
> 기본 카운터 컨트랙트에 기능을 추가하여 나쁜 훅을 구현했습니다.
- [backdoor](example/Uniswap_v4_hook_sample/backdoor/src/Counter.sol)
- [not-implement](example/Uniswap_v4_hook_sample/not-implement/src/Counter.sol)
- [slot0-oracle](example/Uniswap_v4_hook_sample/slot0-oracle/src/Counter.sol)
- [time-out](example/Uniswap_v4_hook_sample/time-out/src/Counter.sol)

# entropy1110/vuln-hook-*
- [src/vuln-hook-withdraw-unabled](example/vuln-hook-withdraw-unabled/src/TakeProfitshook.sol)
- [test/vuln-hook-withdraw-unabled](example/vuln-hook-withdraw-unabled/test/TakeProfitshook.t.sol)

# [ooMia/bad-gas-hooks](https://github.com/ooMia/v4-template)
> gas 중심의 나쁜 훅을 구현하고, 테스트를 통해 검증했습니다. 
- [TooMuchGasHook](example/bad-gas-hooks/test/TooMuchGasHook.t.sol)
- [ExternalContractTooMuchGasHook](example/bad-gas-hooks/test/ExternalContractTooMuchGasHook.t.sol)
- [GasChangedByMessengerHook](example/bad-gas-hooks/test/GasChangedByMessengerHook.t.sol)
- [ZeroFeeHook](example/bad-gas-hooks/test/ZeroFeeHook.t.sol)

# [5hnnn/bad-hooks](https://github.com/55hnnn/bad-hooks)
> 외부의 나쁜 훅 사례를 조사하고, 발표를 통해 분석 결과를 공유했습니다.