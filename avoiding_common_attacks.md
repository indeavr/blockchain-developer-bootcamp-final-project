# Contract security measures

### SWC-103 (Floating pragma)

Specific compiler pragma `0.8.10` used in contracts to avoid accidental bug inclusion through outdated compiler versions.

### Reentrancy (even tho it can't happen withou an untrusted call) - state changes before external calls.

### No overflow and underflow because solv > 0.8.0 --> SafeMath.

### OpenZeppelin Ownable implementation.
