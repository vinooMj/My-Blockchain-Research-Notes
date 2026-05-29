
Institutional-grade permissioned token standard
Built for:
KYC / AML
Transfer restrictions
Identity registry
Compliance modules
Forced transfers / freezing
Main Components:
Identity Registry
Compliance Contract
Trusted Issuers Registry
Claim Topics Registry
Used heavily in regulated RWA tokenization
Key Features
Permissioned transfers
Recovery & freezing
Modular compliance
ERC-20 compatible
2. github.com⁠�
Universal Real World Asset architecture
Vendor-neutral modular tokenization framework
Focus:
Cross-chain interoperability
Compliance abstraction
Institutional portability
Avoiding ecosystem lock-in
Concepts
Identity layer separation
Compliance engine modularization
Asset adapters
Multi-chain deployment model
3. github.com⁠�
Security token framework
Combines:
ERC-20
ERC-777 concepts
Partitioned balances
Core Features
Document management
Partitioned ownership
Transfer validation hooks
Controller operations
Main ERCs Inside ERC-1400
ERC-1410
ERC-1594
ERC-1643
ERC-1644
4. github.com⁠�
Simple restricted token standard
Lightweight compliance token
Best For
STOs
Simple whitelist models
Transfer-restricted tokens
Functions
Solidity
detectTransferRestriction()
messageForTransferRestriction()
5. docs.openzeppelin.com⁠�
Tokenized vault standard
Used in:
Yield vaults
Treasury products
DeFi asset management
Important Methods
Solidity
deposit()
withdraw()
mint()
redeem()
totalAssets()
6. github.com⁠�
Async vault extension for ERC-4626
Supports delayed settlement/redemption
Useful for:
RWAs
Institutional funds
Illiquid assets
7. github.com⁠�
Semi-fungible token standard
Mix between ERC-20 and ERC-721
Used For
Vesting
Bonds
Structured finance
Subscription shares
Core Concept
Plain text
tokenId + slot + value
8. github.com⁠�
Multi-class bond token standard
Designed For
Bonds
Derivatives
Debt instruments
Coupon payments
Features
Metadata-rich classes
Batch issuance
Redemption logic
Maturity handling
Best Architecture Choice (2026)
Use Case
Best Standard
Institutional RWA
ERC-3643
Security Tokens
ERC-1400
Simple STO
ERC-1404
Yield Vaults
ERC-4626
Async Institutional Vaults
ERC-7540
Semi-Fungible Finance
ERC-3525
Bonds & Debt
ERC-3475
Important Institutional Trend
Modern tokenization stacks now require:
On-chain identity
KYC/AML enforcement
Transfer compliance
Wallet screening
Asset freezing/recovery
Cross-chain interoperability
DeFi composability
Permissioned liquidity pools
Off-chain legal integration
Suggested Learning Order for Smart Contract Developers
ERC-20
ERC-721 / ERC-1155
ERC-1404
ERC-1400
ERC-3643
ERC-4626
ERC-3525
ERC-3475
Account Abstraction + RWA protocols
Most Important for Interviews (2026)
Companies now frequently ask:
Difference between ERC-1400 vs ERC-3643
How compliance enforcement works
Transfer restriction architecture
Identity registry design
Upgradeable regulated tokens
Permissioned DeFi
ERC-4626 vault math
RWA token lifecycle
Custody & recovery mechanisms
Cross-chain compliance models
