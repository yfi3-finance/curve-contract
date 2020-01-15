# Curve.fi contracts

These are contracts (with tests) for curve.fi - automated market-making for
highly correlated assets.

Branches:

* master - plain market-making for stablecoins in ERC20. Expected price = 1.0
* [compounded](https://github.com/curvefi/curve-contract/tree/compounded) - market-making for compounded coins (cUSDC, cDAI) with conversion
  DAI <> USDC when exchanging, to both accrue interest and earn fees. Currently
  deployed on curve.fi.

Description of the science behing the algorithm is coming soon.
