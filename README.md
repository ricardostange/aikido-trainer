# 🥋 Aikido Trainer

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**[🔗 View Live Demo](https://ricardostange.github.io/aikido-trainer/)**


## Project Overview
The **Aikido Trainer** is a lightweight, single-page web application designed to help practitioners learn and review Aikido techniques. It provides a clean, accessible interface for exploring tutorials and movement classifications.

## 🥋 Supported Techniques

The application currently includes a comprehensive database of Aikido attacks (*Uke*) and defenses (*Tori/Nage*).

### ⚔️ Attacks (Ataques)
| Attack Type | Description |
| :--- | :--- |
| **Katatetori** | Single hand-grab to the wrist |
| **Shomen Uchi** | Overhead strike to the forehead |
| **Ryotetori** | Both hands grabbing both wrists |
| **Munetsuki** | Thrust/punch to the chest/stomach |
| **Ushiro Kubishime** | Rear chokehold |
| **Ryote Eri Tori** | Both hands grabbing the collar |
| **Ushiro Ryotetori** | Rear grab of both wrists |
| **Yokomen Uchi** | Diagonal strike to the side of the head |
| **Ushiro Katatori** | Rear shoulder grab |
| **Katate Munadori** | Single hand lapel grab |
| **Morotetori** | Two hands grabbing one wrist |

### 🛡️ Defenses (Defesas)

#### Control Techniques (Katame-waza)
* **Dai-Ikkio** (First teaching)
* **Dai-Nikio** (Second teaching)
* **Dai-Sankio** (Third teaching)
* **Dai-Yonkio** (Fourth teaching)
* **Dai-Gokio** (Fifth teaching)

#### Throwing Techniques (Nage-waza)
* **Irimi-Nage** (Entering throw)
* **Shiho-Nage** (Four-direction throw)
* **Kaiten-Nage** (Rotary throw)
* **Tenchi-Nage** (Heaven-and-earth throw)
* **Kokiu-Nage** (Breath throw)
* **Koshi-Nage** (Hip throw)
* **Mawashi-Nage** (Circular throw)
* **Sumi-Otoshi** (Corner drop)
* **Kote-Gaeshi** (Wrist turn)
* **Aiki-Otoshi** (Aiki drop)
* **Aiki-Nage** (Aiki throw)

#### Specialized Pins & Locks
* **Kata-Moshi**
* **Ushiro-Kokiu**
* **Hiji-Garami** (Elbow wrap)
* **Ude-Garami** (Arm wrap)
* **Juji-Garami** (Cross-arm entwinement)
  

## ⚙️ Difficulty Levels & Logic

The trainer uses a **weighted probability system** to determine which defense is drafted. Choosing a difficulty level changes the "odds" of receiving a defense later on.

## 🛠️ Developer Setup

If you wish to contribute or modify the source code:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ricardostange/aikido-trainer.git
   ```
