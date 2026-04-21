# BetSolutions (betsolutions)
BetSolutions provides a casino and gaming platform API offering a two-way HTTP API with JSON data format for implementing requests and responses for slots, single and multiplayer games, and other casino platform services. The platform supports transfer and seamless wallet integration modes, slot campaigns with freespins, table games, provably fair games, poker, and third-party sportsbook integrations. Authentication uses SHA-256 hash-based signing with merchant secret keys.

**URL:** [https://docs.betsolutions.com/](https://docs.betsolutions.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Betting, Casinos, Gaming, Gambling, Slots, Sports Betting

## Timestamps

- **Created:** 2025-02-24
- **Modified:** 2026-04-19

## APIs

### BetSolutions Wallet API
Two-mode wallet integration for casino operators. Transfer mode provides deposit, withdraw, and balance operations managed by BetSolutions. Seamless mode enables operator-side wallet management with bet, win, cancel bet, change win, and balance endpoints called by BetSolutions on the operator's server.

**Human URL:** [https://docs.betsolutions.com/](https://docs.betsolutions.com/)

#### Tags:

 - Wallet, Payments, Transfer, Seamless

#### Properties

- [Documentation](https://docs.betsolutions.com/)
- [OpenAPI](openapi/betsolutions-wallet-api.yaml)

### BetSolutions Player API
Player information and data retrieval endpoints including player profile details, rake data by date range, and game list retrieval with product metadata.

**Human URL:** [https://docs.betsolutions.com/](https://docs.betsolutions.com/)

#### Tags:

 - Players, Accounts, Information

#### Properties

- [Documentation](https://docs.betsolutions.com/)

### BetSolutions Slots API
Slot game integration and campaign management including freespin campaign creation, deactivation, configuration retrieval, and player assignment for promotional campaigns.

**Human URL:** [https://docs.betsolutions.com/](https://docs.betsolutions.com/)

#### Tags:

 - Slots, Campaigns, Freespins, Gaming

#### Properties

- [Documentation](https://docs.betsolutions.com/)

### BetSolutions Table Games API
Multiplayer table game integration supporting Backgammon, Bura, Okey, Domino, and Seka. Includes tournament management with types and statuses, and achievement systems for player engagement.

**Human URL:** [https://docs.betsolutions.com/](https://docs.betsolutions.com/)

#### Tags:

 - Table Games, Multiplayer, Tournaments, Gaming

#### Properties

- [Documentation](https://docs.betsolutions.com/)

### BetSolutions Provably Fair Games API
Provably fair game integration for Zeppelin, High Low, Dice, Mines, and Plinko. Provides jackpot history, multiplier history, and freebet creation for provably fair game mechanics.

**Human URL:** [https://docs.betsolutions.com/](https://docs.betsolutions.com/)

#### Tags:

 - Provably Fair, Zeppelin, Gaming

#### Properties

- [Documentation](https://docs.betsolutions.com/)

### BetSolutions Third-Party Integration API
Third-party sportsbook integration starting with BCBetting, providing bet retrieval, bonus management, and player-specific bonus operations.

**Human URL:** [https://docs.betsolutions.com/](https://docs.betsolutions.com/)

#### Tags:

 - Sportsbook, BCBetting, Integration

#### Properties

- [Documentation](https://docs.betsolutions.com/)

## Common Properties

- [Documentation](https://docs.betsolutions.com/)
- [Authentication](https://docs.betsolutions.com/)
- [Website](https://betsolutions.com)
- [SDK - .NET SDK (NuGet)](https://www.nuget.org/packages/BetSolutions)
- [SDK - PHP SDK (Composer)](https://packagist.org/packages/betsolutions/casino-api)
- [SpectralRules](rules/betsolutions-spectral-rules.yml)
- [NaftikoCapability](capabilities/casino-platform.yaml)
- [Vocabulary](vocabulary/betsolutions-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Transfer Wallet Mode | BetSolutions-managed wallet with deposit, withdraw, and balance operations for casino operators. |
| Seamless Wallet Mode | Operator-side wallet integration where BetSolutions calls the operator's server for bet, win, and balance operations. |
| SHA-256 Authentication | Secure request signing using SHA-256 hash algorithm with merchant secret keys and pipe-separated parameter concatenation. |
| Slot Games | Slot game integration with freespin campaign management, player assignment, and campaign configuration. |
| Table Games | Multiplayer table games including Backgammon, Bura, Okey, Domino, and Seka with tournament support. |
| Provably Fair Games | Cryptographically verifiable games including Zeppelin, High Low, Dice, Mines, and Plinko. |
| Poker | Poker integration with jackpot tracking and daily financial reporting. |
| Third-Party Sportsbook | Integration with BCBetting sportsbook platform for bet and bonus management. |
| SDK Packages | Official SDK packages available for .NET (NuGet), PHP (Composer), and Java (JAR) platforms. |
| Multi-Language Support | API supports 11 languages for international casino operator deployments. |
| Multi-Currency Support | ISO 4217 currency codes for international payment processing. |

## Use Cases

| Name | Description |
|------|-------------|
| Casino Platform Integration | Online casino operators integrate BetSolutions APIs to offer slots, table games, and card games to players. |
| Wallet Integration | Casino operators choose transfer or seamless wallet mode to manage player funds and game transactions. |
| Freespin Campaigns | Marketing teams create and manage freespin slot campaigns to acquire and retain players. |
| Tournament Management | Operators run tournaments for multiplayer table games with configurable types and prize structures. |
| Provably Fair Gaming | Platforms offering cryptographically verifiable game results using BetSolutions' provably fair API. |
| Sportsbook Integration | Operators add sports betting capabilities through the BCBetting third-party integration. |

## Integrations

| Name | Description |
|------|-------------|
| BCBetting | Third-party sportsbook integration providing sports betting functionality for casino operators. |
| NuGet Package Manager | .NET SDK available via NuGet for easy integration in .NET casino platform backends. |
| Composer Package Manager | PHP SDK available via Composer for PHP-based casino platform implementations. |
| Java JAR | Java SDK available as a JAR package for Java-based casino platform implementations. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [BetSolutions Wallet API](openapi/betsolutions-wallet-api.yaml)

### JSON Schema

- [wallet-api-auth-response-schema.json](json-schema/wallet-api-auth-response-schema.json)
- [wallet-api-deposit-request-schema.json](json-schema/wallet-api-deposit-request-schema.json)
- [wallet-api-withdraw-request-schema.json](json-schema/wallet-api-withdraw-request-schema.json)
- [wallet-api-balance-request-schema.json](json-schema/wallet-api-balance-request-schema.json)
- [wallet-api-balance-response-schema.json](json-schema/wallet-api-balance-response-schema.json)
- [wallet-api-wallet-transaction-response-schema.json](json-schema/wallet-api-wallet-transaction-response-schema.json)
- [wallet-api-game-list-response-schema.json](json-schema/wallet-api-game-list-response-schema.json)
- [wallet-api-game-schema.json](json-schema/wallet-api-game-schema.json)
- [wallet-api-player-info-response-schema.json](json-schema/wallet-api-player-info-response-schema.json)

### JSON-LD

- [betsolutions-wallet-api-context.jsonld](json-ld/betsolutions-wallet-api-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [BetSolutions Wallet API](capabilities/shared/wallet-api.yaml) — 5 operations for casino wallet and game management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Casino Platform](capabilities/casino-platform.yaml) | Wallet, Player, Games | 5 | Casino Operator, Platform Developer |

## Vocabulary

- [BetSolutions Vocabulary](vocabulary/betsolutions-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 6 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [BetSolutions Spectral Rules](rules/betsolutions-spectral-rules.yml) — 25 rules across 9 categories enforcing BetSolutions API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
