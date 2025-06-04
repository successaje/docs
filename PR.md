# MD to MDX File Conversion

This PR converts all `.md` documentation files to `.mdx` format to maintain consistency in our documentation system. The following files have been renamed:

## Converted Files

### Architecture Module Documentation
- `developers/architecture/modules/authority/messages.md` → `messages.mdx`
- `developers/architecture/modules/crosschain/messages.md` → `messages.mdx`
- `developers/architecture/modules/crosschain/overview.md` → `overview.mdx`
- `developers/architecture/modules/emissions/messages.md` → `messages.mdx`
- `developers/architecture/modules/emissions/overview.md` → `overview.mdx`
- `developers/architecture/modules/fungible/messages.md` → `messages.mdx`
- `developers/architecture/modules/fungible/overview.md` → `overview.mdx`
- `developers/architecture/modules/lightclient/messages.md` → `messages.mdx`
- `developers/architecture/modules/observer/messages.md` → `messages.mdx`
- `developers/architecture/modules/observer/overview.md` → `overview.mdx`

### Protocol Documentation
- `developers/architecture/protocol/README.md` → `README.mdx`
- `developers/architecture/protocol/SUMMARY.md` → `SUMMARY.mdx`

### Protocol Contracts Documentation
- `developers/architecture/protocol/contracts/README.md` → `README.mdx`
- `developers/architecture/protocol/contracts/Errors.sol/interface.INotSupportedMethods.md` → `INotSupportedMethods.mdx`
- `developers/architecture/protocol/contracts/Revert.sol/interface.Revertable.md` → `Revertable.mdx`
- `developers/architecture/protocol/contracts/Revert.sol/struct.RevertContext.md` → `RevertContext.mdx`
- `developers/architecture/protocol/contracts/Revert.sol/struct.RevertOptions.md` → `RevertOptions.mdx`

### EVM Contracts Documentation
- `developers/architecture/protocol/contracts/evm/README.md` → `README.mdx`
- `developers/architecture/protocol/contracts/evm/ERC20Custody.sol/contract.ERC20Custody.md` → `ERC20Custody.mdx`
- `developers/architecture/protocol/contracts/evm/GatewayEVM.sol/contract.GatewayEVM.md` → `GatewayEVM.mdx`
- `developers/architecture/protocol/contracts/evm/ZetaConnectorBase.sol/abstract.ZetaConnectorBase.md` → `ZetaConnectorBase.mdx`
- `developers/architecture/protocol/contracts/evm/ZetaConnectorNative.sol/contract.ZetaConnectorNative.md` → `ZetaConnectorNative.mdx`
- `developers/architecture/protocol/contracts/evm/ZetaConnectorNonNative.sol/contract.ZetaConnectorNonNative.md` → `ZetaConnectorNonNative.mdx`

### EVM Interfaces Documentation
- `developers/architecture/protocol/contracts/evm/interfaces/README.md` → `README.mdx`
- `developers/architecture/protocol/contracts/evm/interfaces/IERC20Custody.sol/interface.IERC20Custody.md` → `IERC20Custody.mdx`
- `developers/architecture/protocol/contracts/evm/interfaces/IERC20Custody.sol/interface.IERC20CustodyErrors.md` → `IERC20CustodyErrors.mdx`
- `developers/architecture/protocol/contracts/evm/interfaces/IERC20Custody.sol/interface.IERC20CustodyEvents.md` → `IERC20CustodyEvents.mdx`
- `developers/architecture/protocol/contracts/evm/interfaces/IGatewayEVM.sol/interface.Callable.md` → `Callable.mdx`
- `developers/architecture/protocol/contracts/evm/interfaces/IGatewayEVM.sol/interface.IGatewayEVM.md` → `IGatewayEVM.mdx`
- `developers/architecture/protocol/contracts/evm/interfaces/IGatewayEVM.sol/interface.IGatewayEVMErrors.md` → `IGatewayEVMErrors.mdx`
- `developers/architecture/protocol/contracts/evm/interfaces/IGatewayEVM.sol/interface.IGatewayEVMEvents.md` → `IGatewayEVMEvents.mdx`
- `developers/architecture/protocol/contracts/evm/interfaces/IGatewayEVM.sol/struct.MessageContext.md` → `MessageContext.mdx`
- `developers/architecture/protocol/contracts/evm/interfaces/IZetaConnector.sol/interface.IZetaConnectorEvents.md` → `IZetaConnectorEvents.mdx`
- `developers/architecture/protocol/contracts/evm/interfaces/IZetaNonEthNew.sol/interface.IZetaNonEthNew.md` → `IZetaNonEthNew.mdx`

### Legacy EVM Documentation
- `developers/architecture/protocol/contracts/evm/legacy/README.md` → `README.mdx`
- `developers/architecture/protocol/contracts/evm/legacy/Zeta.eth.sol/contract.ZetaEth.md` → `ZetaEth.mdx`
- `developers/architecture/protocol/contracts/evm/legacy/Zeta.non-eth.sol/contract.ZetaNonEth.md` → `ZetaNonEth.mdx`
- `developers/architecture/protocol/contracts/evm/legacy/ZetaConnector.base.sol/contract.ZetaConnectorBase.md` → `ZetaConnectorBase.mdx`
- `developers/architecture/protocol/contracts/evm/legacy/ZetaConnector.eth.sol/contract.ZetaConnectorEth.md` → `ZetaConnectorEth.mdx`
- `developers/architecture/protocol/contracts/evm/legacy/ZetaConnector.non-eth.sol/contract.ZetaConnectorNonEth.md` → `ZetaConnectorNonEth.mdx`
- `developers/architecture/protocol/contracts/evm/legacy/ZetaErrors.sol/interface.ZetaErrors.md` → `ZetaErrors.mdx`
- `developers/architecture/protocol/contracts/evm/legacy/ZetaInterfaces.sol/interface.ZetaCommonErrors.md` → `ZetaCommonErrors.mdx`
- `developers/architecture/protocol/contracts/evm/legacy/ZetaInterfaces.sol/interface.ZetaConnector.md` → `ZetaConnector.mdx`
- `developers/architecture/protocol/contracts/evm/legacy/ZetaInterfaces.sol/interface.ZetaInterfaces.md` → `ZetaInterfaces.mdx`
- `developers/architecture/protocol/contracts/evm/legacy/ZetaInterfaces.sol/interface.ZetaReceiver.md` → `ZetaReceiver.mdx`
- `developers/architecture/protocol/contracts/evm/legacy/ZetaInterfaces.sol/interface.ZetaTokenConsumer.md` → `ZetaTokenConsumer.mdx`
- `developers/architecture/protocol/contracts/evm/legacy/ZetaNonEthInterface.sol/interface.ZetaNonEthInterface.md` → `ZetaNonEthInterface.mdx`

## Special Files to Review
These files may require special attention due to their nature:
1. `SUMMARY.md` - This is typically a special file used by documentation generators
2. `README.md` files - These are typically special files that might have specific formatting requirements
3. Interface documentation files - These might have special formatting that needs to be preserved

## Notes
- All files have been renamed from `.md` to `.mdx`
- No content changes were made, only file extensions were changed
- This change ensures consistency in our documentation format
- Future documentation improvements can now leverage MDX features
