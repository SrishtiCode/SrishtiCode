<div align="center">

# Srishti Rathi

### Web3 Security Researcher | Smart Contract Auditor 

</div>

---

## About Me
```python
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

/// @title Web3SecurityResearcher
/// @author Srishti Rathi
/// @notice B.Tech. Computer Engineering | J.C. Bose University

contract Web3SecurityResearcher {

    string public name = "Srishti Rathi";
    string public role = "Web3 Security Researcher & Smart Contract Auditor";
    string public education = "B.Tech. Computer Engineering | J.C. Bose University";
    string public currentStatus = "Open to Web3 Security Research & Smart Contract Audit Opportunities";

    string[] public specializations = [
        "Smart Contract Auditing & Exploit Development",
        "DeFi Protocol Security & Economic Attack Research",
        "On-Chain Threat Intelligence & Blockchain Forensics",
        "EVM Internals, Opcodes & Bytecode Analysis",
        "CTF Research — Ethernaut, Damn Vulnerable DeFi, Paradigm"
    ];

    struct Expertise {
        string[] smartContractSecurity;
        string[] auditAndResearchTools;
        string[] onChainIntelligence;
        string[] evmInternals;
        string[] programming;
    }

    function getExpertise() external pure returns (Expertise memory) {
        string[] memory smartContractSecurity = new string[](6);
        smartContractSecurity[0] = "Reentrancy";
        smartContractSecurity[1] = "Access Control Flaws";
        smartContractSecurity[2] = "Delegatecall Abuse";
        smartContractSecurity[3] = "Storage Collisions";
        smartContractSecurity[4] = "Oracle Manipulation";
        smartContractSecurity[5] = "Flash Loan Attacks";

        string[] memory auditAndResearchTools = new string[](6);
        auditAndResearchTools[0] = "Foundry";
        auditAndResearchTools[1] = "Hardhat";
        auditAndResearchTools[2] = "Slither";
        auditAndResearchTools[3] = "Echidna";
        auditAndResearchTools[4] = "Mythril";
        auditAndResearchTools[5] = "Tenderly";

        string[] memory onChainIntelligence = new string[](5);
        onChainIntelligence[0] = "Blockchain Forensics";
        onChainIntelligence[1] = "Wallet Clustering";
        onChainIntelligence[2] = "Fund Tracing";
        onChainIntelligence[3] = "MEV Analysis";
        onChainIntelligence[4] = "Mempool Monitoring";

        string[] memory evmInternals = new string[](6);
        evmInternals[0] = "Opcodes";
        evmInternals[1] = "ABI Encoding";
        evmInternals[2] = "Storage Layout";
        evmInternals[3] = "Bytecode Analysis";
        evmInternals[4] = "Gas Optimization";
        evmInternals[5] = "Proxy Patterns";

        string[] memory programming = new string[](5);
        programming[0] = "Solidity";
        programming[1] = "Python";
        programming[2] = "Bash";
        programming[3] = "JavaScript";
        programming[4] = "Assembly (EVM/x86)";

        return Expertise({
            smartContractSecurity: smartContractSecurity,
            auditAndResearchTools: auditAndResearchTools,
            onChainIntelligence: onChainIntelligence,
            evmInternals: evmInternals,
            programming: programming
        });
    }
}
```

**Smart India Hackathon Winner** | **Top 1% TryHackMe** | **Active Bug Bounty Hunter** | **Web3 CTF Competitor**

---

## Professional Experience

### Independent Web3 Security Researcher
**July 2025 – Present**
```yaml
Smart Contract Auditing & Exploit Research:
  - Manual and automated auditing of DeFi protocols and ERC standards
  - Exploit development for reentrancy, access control, and storage collision bugs
  - Delegatecall abuse, proxy pattern vulnerabilities, and upgrade mechanism flaws
  - Flash loan attack simulations and economic attack modeling
  - Responsible disclosure to Web3 projects and bug bounty platforms (Immunefi, Code4rena)

CTF & Competitive Research:
  - Ethernaut CTF — all levels solved using Foundry with documented exploit scripts
  - Damn Vulnerable DeFi — DeFi-specific attack research (flash loans, oracle manipulation)
  - Paradigm CTF — EVM-level exploit and cryptographic challenge research
  - Write-ups covering vulnerability breakdowns from first principles

```

---

## Technical Arsenal

### Smart Contract Security & Auditing
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-1E1E1E?style=for-the-badge&logo=ethereum&logoColor=white)
![Hardhat](https://img.shields.io/badge/Hardhat-F7DF1E?style=for-the-badge&logo=hardhat&logoColor=black)
![Slither](https://img.shields.io/badge/Slither-4B0082?style=for-the-badge&logo=python&logoColor=white)
![Echidna](https://img.shields.io/badge/Echidna-CC0000?style=for-the-badge&logo=haskell&logoColor=white)

### EVM & Bytecode Analysis
![EVM](https://img.shields.io/badge/EVM_Opcodes-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![Mythril](https://img.shields.io/badge/Mythril-1E1E1E?style=for-the-badge&logo=ethereum&logoColor=white)
![Tenderly](https://img.shields.io/badge/Tenderly-6F4CFF?style=for-the-badge&logo=tenderly&logoColor=white)
![Etherscan](https://img.shields.io/badge/Etherscan-21325B?style=for-the-badge&logo=ethereum&logoColor=white)

### On-Chain Intelligence & Forensics
![Dune](https://img.shields.io/badge/Dune_Analytics-FF7B00?style=for-the-badge&logo=data&logoColor=white)
![Chainalysis](https://img.shields.io/badge/Chainalysis-0033A0?style=for-the-badge&logo=blockchain&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Web3.py](https://img.shields.io/badge/Web3.py-F16822?style=for-the-badge&logo=python&logoColor=white)

### Programming & Scripting
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### Platforms & Frameworks
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)

---

## Certifications & Achievements

<table>
<tr>
<td align="center" width="25%">

### TryHackMe
**Top 1% Globally**
Jr. Penetration Tester

</td>
<td align="center" width="25%">

### SIH Winner
**Smart India Hackathon**
Government Recognition

</td>
<td align="center" width="25%">

### Cisco Certified
Junior Cybersecurity Analyst
Networking Basics

</td>
<td align="center" width="25%">

### Bug Bounty
**Active Researcher**
Immunefi & Code4rena

</td>
</tr>
</table>

---

## Core Competencies

<div align="center">

| Smart Contract Security | EVM & Protocol Research | On-Chain Intelligence |
|:-----------------------:|:-----------------------:|:---------------------:|
| Web App VAPT | Opcode-Level Debugging | Blockchain Forensics |
| Smart Contract Auditing | Bytecode & ABI Analysis | Fund Tracing & Attribution |
| DeFi Exploit Research | Proxy & Upgrade Patterns | MEV Pattern Analysis |
| Reentrancy & Access Control | Storage Layout Analysis | Wallet Clustering |
| Flash Loan Attack Modeling | Gas Optimization Review | Exploit TX Monitoring |
| Responsible Disclosure | Fuzzing & Formal Verification | Threat Actor Profiling (On-Chain) |

</div>

---
