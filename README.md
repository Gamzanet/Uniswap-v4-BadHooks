# [Uniswap-v4-BadHooks](https://www.notion.so/entropy1110/Composable-Security-Threat-for-Uniswap-v4-Hooks-110ec224c99380fbafe0dcd1c09447f9?pvs=4)

- 각 소스에 대해 GitHub Permalink로 정리했고, 로컬 git clone 과정 없이 확인하실 수 있습니다.
- 구현 내용 및 결과는 [Notion](https://www.notion.so/entropy1110/Composable-Security-Threat-for-Uniswap-v4-Hooks-110ec224c99380fbafe0dcd1c09447f9?pvs=4)에 기록되어 있습니다.
- 예제 프로젝트는 모두 example 폴더 내부에 submodule로 구성되어 있습니다. 로컬 실행이 필요하시다면 git clone 하시면 자동으로 설치됩니다. 설치에 다소 시간이 걸릴 수 있습니다.

# [ExploitSoir/Uniswap_v4_hook_sample](https://github.com/ExploitSori/Uniswap_v4_hook_sample/tree/da8bb7127e226aa3764bfcb9d670ad3a37a50347)
> 기본 카운터 컨트랙트에 기능을 추가하여 나쁜 훅을 구현했습니다.
- [backdoor](https://github.com/ExploitSori/Uniswap_v4_hook_sample/blob/da8bb7127e226aa3764bfcb9d670ad3a37a50347/backdoor/src/Counter.sol#L126)
- [not-implement](https://github.com/ExploitSori/Uniswap_v4_hook_sample/blob/da8bb7127e226aa3764bfcb9d670ad3a37a50347/not-implement/src/Counter.sol#L63)
- [slot0-oracle/src](https://github.com/ExploitSori/Uniswap_v4_hook_sample/blob/da8bb7127e226aa3764bfcb9d670ad3a37a50347/slot0-oracle/src/Counter.sol#L80)
- [slot0-oracle/test](https://github.com/ExploitSori/Uniswap_v4_hook_sample/blob/da8bb7127e226aa3764bfcb9d670ad3a37a50347/slot0-oracle/test/Counter.t.sol)
- [time-out](https://github.com/ExploitSori/Uniswap_v4_hook_sample/blob/da8bb7127e226aa3764bfcb9d670ad3a37a50347/time-out/src/Counter.sol#L31)

# [entropy1110/vuln-hooks](https://github.com/Entropy1110/vuln-hooks)
- [hookCallerModifier](https://github.com/Entropy1110/vuln-hooks/tree/main/hookCallerModifier)
- [hookUpgradable](https://github.com/Entropy1110/vuln-hooks/tree/main/hookUpgradable)
- [hookDoubleInit](https://github.com/Entropy1110/vuln-hooks/tree/main/hookDoubleInit)

# [ooMia/bad-gas-hooks](https://github.com/ooMia/v4-template/tree/c161984d149cdbdb953382433044cefa0582641b)
> gas 소비량에 대한 간단한 나쁜 훅을 구현하고, 테스트를 통해 검증했습니다.
- [TooMuchGasHook](https://github.com/ooMia/v4-template/blob/c161984d149cdbdb953382433044cefa0582641b/test/TooMuchGasHook.t.sol#L24)
- [ExternalContractTooMuchGasHook](https://github.com/ooMia/v4-template/blob/c161984d149cdbdb953382433044cefa0582641b/test/ExternalContractTooMuchGasHook.t.sol#L26)
- [GasChangedByMessengerHook](https://github.com/ooMia/v4-template/blob/c161984d149cdbdb953382433044cefa0582641b/test/GasChangedByMessengerHook.t.sol#L25)
- [ZeroFeeHook](https://github.com/ooMia/v4-template/blob/c161984d149cdbdb953382433044cefa0582641b/test/ZeroFeeHook.t.sol#L63)

# [5hnnn/bad-hooks](https://github.com/55hnnn/bad-hooks/tree/071a7b719403e81dea08dbe3e5a17926a91cc6ba)
> 외부의 나쁜 훅 사례를 조사하고, 발표를 통해 분석 결과를 공유했습니다.
