./src/pages/pool/invest.vue- [ ] Don't refetch whole pool, only update balances and weights with
./src/pages/pool/withdraw.vue- [ ] Don't refetch whole pool, only update balances and weights with
./src/dependencies/balancer-sdk.mocks.ts- [ ] move to sor mocks to subfile
./src/dependencies/Multicaller.mocks.ts - [ ] discover how we can discover different calls and responses
./src/components/cards/SwapCard/SwapRoute.vue- [ ] Fix types
./src/services/lido/lido.service.ts .times(1 - protocolFeePercentage) - [ ] check pool type and use protocol yield percentage cache when applicable
./src/services/staking/staking-rewards.service.ts - [ ] BETTER INTEGRATION OF REWARD TOKEN APRS
./src/services/pool/exchange/serializers/ExitParams.ts - [ ] do this more elegantly
./src/services/web3/connectors/trustwallet/walletconnect.connector.ts - [ ] type this
./src/services/web3/connectors/gnosis/gnosis.connector.ts - [ ] type this
./src/services/web3/connectors/metamask/metamask.connector.ts - [ ] type this
./src/services/web3/connectors/walletlink/walletlink.connector.ts - [ ] type this
./src/services/web3/connectors/tally/tally.connector.ts - [ ] type this
./src/services/balancer/contracts/balancer-contracts.service.ts - [ ] Fix affected tests by refactoring export balancerContractsService
./src/services/balancer/pools/exits/handlers/exact-in-exit.handler.ts ? - [ ] Fix this in the SDK, then remove this toLowerCase
./src/composables/useBlocknative.ts - [ ] blocknative is going to be deprecated for transaction tracking.
./src/composables/useTransactions.ts- [ ] What happens if the structure changes? Either keep a version or schema validator.