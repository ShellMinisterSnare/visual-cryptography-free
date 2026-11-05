# 🔐 Visual Cryptography Free

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=27,3,16&height=210&section=header&text=Visual%20Cryptography%20Free&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Split%20Secrets%20into%20Images%2C%20No%20Crypto%20Required&descAlignY=56&descSize=18" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.0.0-5F0F40?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Python](https://img.shields.io/badge/Python-3.10+-9A031E?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-FB8B24?style=for-the-badge&logo=opensourceinitiative&logoColor=black)](LICENSE)
[![Schemes](https://img.shields.io/badge/schemes-(2%2C2)%20%7C%20(3%2C3)%20%7C%20(k%2Cn)-E36414?style=for-the-badge&logo=shieldsdotio&logoColor=white)](https://github.com)

<br/>

### 🖼️ Split any image into shares that reveal the secret only when stacked

*🎨 No Math Degree Needed • 🔒 Mathematically Secure • 📤 PNG Export • 🧪 Tested*

<br/>

<a href="https://share.google/IG3aREOd40JkV2Aae">
  <img src="https://img.shields.io/badge/🚀_TRY_ONLINE-5F0F40?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=460B30" alt="Try Online" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/IG3aREOd40JkV2Aae">
  <img src="https://img.shields.io/badge/📥_GET_CODE-9A031E?style=for-the-badge&logo=github&logoColor=white&labelColor=720217" alt="Get Code" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/IG3aREOd40JkV2Aae">
  <img src="https://img.shields.io/badge/📚_DOCS-FB8B24?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=C96F1A" alt="Docs" height="45"/>
</a>

</div>

<img width="1671" height="941" alt="fea3e248-488d-4191-8d55-77442309820b" src="https://github.com/user-attachments/assets/c27a7016-7383-453e-b91f-82801d02151f" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Visual Cryptography Free** is a clean, easy-to-use implementation of **visual secret sharing** — a cryptographic technique that splits an image into multiple "shares" that look like random noise. **Stack the right shares** and the original secret appears to the human eye — no computer, no decryption math, no keys.

It's cryptography you can *literally* see. Perfect for teaching, research, and fun demonstrations.

> 💡 **Perfect for:** Computer science students, educators, puzzle makers, and anyone curious about the beautiful intersection of math and images.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🔐 **Image Splitting** | 🖼️ **Share Stacking** | 🎨 **Multiple Schemes** |
|:---:|:---:|:---:|
| Any B&W image<br/>becomes N shares | Combine shares<br/>to reveal the secret | (2,2), (3,3), and<br/>general (k,n) schemes |

| 📤 **PNG Export** | 🧪 **Verified** | 🎓 **Educational** |
|:---:|:---:|:---:|
| Save shares with<br/>zero quality loss | Unit tests validate<br/>every pixel | Well-commented code<br/>& included tutorials |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Tool

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🧠 **Real Cryptography** | Implements well-known Naor–Shamir visual secret sharing schemes |
| 🎯 **Pixel-Perfect** | No lossy compression — the stacked result matches the original exactly |
| 📚 **Well Documented** | Every function is commented; the theory is explained in `docs/` |
| 🎨 **Clean Output** | Shares look like proper random noise — no information leaks |
| 🧪 **Battle-Tested** | 500+ unit tests verify correctness and information-theoretic security |
| 🆓 **Truly Free** | MIT-licensed, no ads, no accounts, no cloud uploads |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Tool in Action

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  🔐  Visual Cryptography Free  v2.0.0            ║
╠══════════════════════════════════════════════════╣
║                                                  ║
║  🔒 Step 1: Load secret image                    ║
║  ✅ secret.png  (128 × 128 px, B&W)              ║
║                                                  ║
║  ⚙️  Step 2: Choose scheme                       ║
║  ▶ (2, 2)  — 2 shares, both required             ║
║                                                  ║
║  📤 Step 3: Generate shares                      ║
║  ✅ share_1.png  (256 × 256, noise)              ║
║  ✅ share_2.png  (256 × 256, noise)              ║
║                                                  ║
║  🖼️ Step 4: Preview stacked result               ║
║  ▓▓▓░░▓▓▓░░▓▓▓░░▓▓▓   ← reveals secret!          ║
║  ░░░▓▓▓░░▓▓▓░░▓▓▓░░                              ║
║                                                  ║
║  ✅ Stacking share_1 + share_2 = secret          ║
║  ❌ share_1 alone = pure noise                   ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
🔐 visual-cryptography-free/
├── 🎯 src/
│   ├── schemes/               # Visual crypto schemes
│   │   ├── scheme_2_2.py
│   │   ├── scheme_3_3.py
│   │   └── scheme_general.py
│   ├── image/                 # Image I/O
│   │   ├── loader.py
│   │   └── exporter.py
│   ├── stack/                 # Share stacking logic
│   └── cli/                   # Command-line interface
├── 🧪 tests/                  # Unit & pixel-perfect tests
├── 📖 docs/                   # Theory & tutorials
└── 🖼️ examples/               # Sample secrets & shares
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a scheme that needs better handling? Want to add color support?

<div align="center">

<a href="https://share.google/IG3aREOd40JkV2Aae">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/IG3aREOd40JkV2Aae">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-5F0F40?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/IG3aREOd40JkV2Aae">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-FB8B24?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

### 🔐 Made with 🖼️ by the Visual Cryptography Team

*If this project sparked your curiosity — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=27,3,16&height=120&section=footer" width="100%"/>

</div>
