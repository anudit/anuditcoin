# Anudit Coin

[![Etherscan Link](https://img.shields.io/badge/Ropsten-0x363d2c0d90c7f18f69b5029ebb0ce038f8f877ea-blue.svg)](https://ropsten.etherscan.io/dapp/0x363d2c0d90c7f18f69b5029ebb0ce038f8f877ea)

[![Binance](https://img.shields.io/badge/Binance-tbnb16uq5gcvg25psr2gqt5y0svn4j53n39lzxkuvl7-yellow.svg)](https://testnet-explorer.binance.org/asset/ANC-3EF)

Implementation of a BaseERC20Token
## ERC20Token

## mintingFinished - view
_No parameters_
Return : if minting is finished or not.

## name - view
_No parameters_
Returns the name of the token.

## approve - read
|name |type |description
|-----|-----|-----------
|spender|address|
|value|uint256|
See `IERC20.approve`.
      * Requirements:
      * - `spender` cannot be the zero address.

## totalSupply - view
_No parameters_
See `IERC20.totalSupply`.

## transferFrom - read
|name |type |description
|-----|-----|-----------
|from|address|address The address which you want to send tokens from
|to|address|address The address which you want to transfer to
|value|uint256|uint256 the amount of tokens to be transferred
Transfer tokens from one address to another.
Return : A boolean that indicates if the operation was successful.

## renounceOperator - read
_No parameters_

## removeMinter - read
|name |type |description
|-----|-----|-----------
|account|address|Address you want to remove role
remove the `minter` role from address

## decimals - view
_No parameters_
Returns the number of decimals used to get its user representation.
 For example, if `decimals` equals `2`, a balance of `505` tokens should
 be displayed to a user as `5,05` (`505 / 10 ** 2`).
      * Tokens usually opt for a value of 18, imitating the relationship between
 Ether and Wei.
      * > Note that this information is only used for _display_ purposes: it in
 no way affects any of the arithmetic of the contract, including
 `IERC20.balanceOf` and `IERC20.transfer`.

## cap - view
_No parameters_
Returns the cap on the token's total supply.

## increaseAllowance - read
|name |type |description
|-----|-----|-----------
|spender|address|
|addedValue|uint256|
Atomically increases the allowance granted to `spender` by the caller.
      * This is an alternative to `approve` that can be used as a mitigation for
 problems described in `IERC20.approve`.
      * Emits an `Approval` event indicating the updated allowance.
      * Requirements:
      * - `spender` cannot be the zero address.

## mint - read
|name |type |description
|-----|-----|-----------
|to|address|The address that will receive the minted tokens.
|value|uint256|The amount of tokens to mint.
Function to mint tokens
Return : A boolean that indicates if the operation was successful.

## burn - read
|name |type |description
|-----|-----|-----------
|amount|uint256|
Destoys `amount` tokens from the caller.
      * See `ERC20._burn`.

## transferEnabled - view
_No parameters_
Return : if transfer is enabled or not.

## isOperator - view
|name |type |description
|-----|-----|-----------
|account|address|


## balanceOf - view
|name |type |description
|-----|-----|-----------
|account|address|
See `IERC20.balanceOf`.

## renounceOwnership - read
_No parameters_
Leaves the contract without owner. It will not be possible to call
 `onlyOwner` functions anymore. Can only be called by the current owner.
      * > Note: Renouncing ownership will leave the contract without an owner,
 thereby removing any functionality that is only available to the owner.

## burnFrom - read
|name |type |description
|-----|-----|-----------
|account|address|
|amount|uint256|
See `ERC20._burnFrom`.

## finishMinting - read
_No parameters_
Function to stop minting new tokens and enable transfer.

## recoverERC20 - read
|name |type |description
|-----|-----|-----------
|tokenAddress|address|The token contract address
|tokenAmount|uint256|Number of tokens to be sent
Remember that only owner can call so be careful when use on contracts generated from other contracts.

## owner - view
_No parameters_
Returns the address of the current owner.

## isOwner - view
_No parameters_
Returns true if the caller is the current owner.

## symbol - view
_No parameters_
Returns the symbol of the token, usually a shorter version of the
 name.

## addMinter - read
|name |type |description
|-----|-----|-----------
|account|address|


## renounceMinter - read
_No parameters_


## addOperator - read
|name |type |description
|-----|-----|-----------
|account|address|


## decreaseAllowance - read
|name |type |description
|-----|-----|-----------
|spender|address|
|subtractedValue|uint256|
Atomically decreases the allowance granted to `spender` by the caller.
      * This is an alternative to `approve` that can be used as a mitigation for
 problems described in `IERC20.approve`.
      * Emits an `Approval` event indicating the updated allowance.
      * Requirements:
      * - `spender` cannot be the zero address.
 - `spender` must have allowance for the caller of at least
 `subtractedValue`.

## transfer - read
|name |type |description
|-----|-----|-----------
|to|address|The address to transfer to.
|value|uint256|The amount to be transferred.
Transfer token to a specified address
Return : A boolean that indicates if the operation was successful.

## isMinter - view
|name |type |description
|-----|-----|-----------
|account|address|


## removeOperator - read
|name |type |description
|-----|-----|-----------
|account|address|Address you want to remove role
remove the `operator` role from address

## builtOn - view
_No parameters_


## allowance - view
|name |type |description
|-----|-----|-----------
|owner|address|
|spender|address|
See `IERC20.allowance`.

## enableTransfer - read
_No parameters_
Function to enable transfers.

## transferOwnership - read
|name |type |description
|-----|-----|-----------
|newOwner|address|
Transfers ownership of the contract to a new account (`newOwner`).
 Can only be called by the current owner.

## constructor - read
|name |type |description
|-----|-----|-----------
|name|string|
|symbol|string|
|decimals|uint8|
|cap|uint256|
|initialSupply|uint256|
function Object() { [native code] }

## MintFinished - read
_No parameters_


## TransferEnabled - read
_No parameters_


## OwnershipTransferred - read
|name |type |description
|-----|-----|-----------
|previousOwner|address|
|newOwner|address|


## OperatorAdded - read
|name |type |description
|-----|-----|-----------
|account|address|


## OperatorRemoved - read
|name |type |description
|-----|-----|-----------
|account|address|


## MinterAdded - read
|name |type |description
|-----|-----|-----------
|account|address|


## MinterRemoved - read
|name |type |description
|-----|-----|-----------
|account|address|


## Transfer - read
|name |type |description
|-----|-----|-----------
|from|address|
|to|address|
|value|uint256|
Function to enable transfers.

## Approval - read
|name |type |description
|-----|-----|-----------
|owner|address|
|spender|address|
|value|uint256|

