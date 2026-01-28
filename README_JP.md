
# 🦾 reBot-DevArm: Total Open Source Arm

<p align="center">
  <img src="./media/v1.5.jpg" alt="reBot-DevArm Banner">
</p>

<p align="center">
    <!-- CC BY-NC-SA 4.0 バッジに置換、非商用を明示 -->
    <a href="./LICENSE">
        <img src="https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg" alt="License: CC BY-NC-SA 4.0">
    </a>
    <img src="https://img.shields.io/badge/Commercial-Contact%20Us-red.svg" alt="yaohui.zhu@seeed.cc">
    <img src="https://img.shields.io/badge/ROS-Noetic%20%7C%20Humble-orange.svg" alt="ROS Support">
    <img src="https://img.shields.io/badge/Framework-LeRobot-yellow.svg" alt="LeRobot">
    <img src="https://img.shields.io/badge/Framework-Isaac Sim-yellow.svg" alt="LeRobot">
</p>

<p align="center">
  <strong>100% 完全オープンソース · 身体性知能 (Embodied AI) · ソフトウェアとハードウェアの統合 · 個人/教育利用無料 · 商用利用は要ライセンス</strong>
</p>

<p align="center">
  <strong>
    <a href="./README_zh.md">简体中文</a> &nbsp;|&nbsp;
    <a href="./README.md">English</a> &nbsp;|&nbsp;
    <a href="./README_JP.md">日本語</a>&nbsp;|&nbsp;
    <a href="./README_Fr.md">français</a>
  </strong>
</p>

<p align="center">
<a href="https://discord.gg/YKNfUMCk">
    <img src="https://img.shields.io/discord/1409155673572249672?color=7289DA&label=Discord&logo=discord&logoColor=white"></a>
<a href="https://wiki.seeedstudio.com/robotics_page/">  
    <img src="https://img.shields.io/badge/Documentation-📕-blue" alt="robotics wiki"></a>
</p


## 📖 プロジェクト紹介 (Introduction)

**reBot-DevArm (Total Open Source Arm)** は、身体性知能（Embodied AI）学習の敷居を下げることを目的としたロボットアームプロジェクトです。私たちは **「真のオープンソース」** を掲げており、コードだけでなく、以下を含むすべてを包み隠さず公開しています。

- 🛠️ **ハードウェア図面**：板金部品、3Dプリント部品のソースファイル。
- 🔩 **BOMリスト（部品表）**：ネジ1本の規格から購入リンクまで詳細に記載。
- 💻 **ソフトウェアおよびアルゴリズム**：Python SDK、ROS1/2、Isaac Sim、LeRobotなど。

**⚠️ 注意：本プロジェクトは教育および個人の学習促進を目的としています。個人開発者、学生、教育機関はすべてのリソースを完全に無料で利用できますが、無許可での商用利用（キットの直接販売、商用製品の一部としての利用などを含みますが、これに限定されません）は固く禁じられています。**

## 🗺️ ロードマップとステータス (Roadmap & Status)

私たちは、主流のロボット開発エコシステムへの継続的なメンテナンスと適合を約束します。現在の適合状況とリリース予定は以下の通りです。

| 適合エコシステム | ステータス | 説明 / リリース予定 | 関連ドキュメント |
| :--- | :---: | :--- | :--- |
| **モーターの基本使用** | ✅ 完了 | 基本的な運動制御とAPIのカプセル化 | [ドキュメントを見る](https://wiki.seeedstudio.com/cn/damiao_series/) |
| **新バージョンSTEP 3D構造部品およびBOM公開** | 🚧 進行中 | 新バージョンの全パーツSTEP形式、部品BOM、全加工部品の参考価格 | [2026.02 予定] |
| **組立動画** | 🚧 進行中 | 超詳細な組立手順と動画 | [2026.02 予定] |
| **ROS2 (Humble)** |⏳ 計画中 | コアドライバ完了、MoveIt2最適化中 |[2026.03 予定]|
| **LeRobot 適合** | ⏳ 計画中 | Hugging Face LeRobot 学習フレームワークへの適合 | [2026.03 予定]|
| **Pinocchio 適合** | ⏳ 計画中 | Pinocchioフレームワークへの適合、ロボットアームの順/逆運動学および動力学重力補償の実装 | [2026.03 予定]|
| **Isaac Sim シミュレーション** | ⏳ 計画中 | USDモデルのインポートとシミュレーション遠隔操作の実装 | [2026.03 予定]|
| **最新アルゴリズムの順次更新** | ⏳ 計画中 | 主流アルゴリズムの順次更新 | 継続中 |
| **完全無料コースシリーズの公開** | ⏳ 計画中 | チュートリアルシリーズの公開 | 継続中 |

---


### 🎓 ロボットフルスタックエコシステム (Full-Stack Ecosystem)
reBot-DevArmは単なるロボットアームではなく、ロボット学習コミュニティでもあります。以下の汎用チュートリアルを無料で共有しています。

#### 🖥️ エッジコンピューティングとメインコントローラ
*   [![Jetson](https://img.shields.io/badge/NVIDIA-reComputer%20Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white)](https://wiki.seeedstudio.com/NVIDIA_Jetson/) —— **AI 推論と計算コア**
*   [![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-4B%20%2F%205-C51A4A?style=for-the-badge&logo=Raspberry%20Pi&logoColor=white)](https://wiki.seeedstudio.com/raspberry-pi-devices/) —— **汎用 Linux 開発環境**
*   [![ESP32](https://img.shields.io/badge/MCU-Seeed%20XIAO%20(ESP32)-0091BD?style=for-the-badge&logo=espressif&logoColor=white)](https://wiki.seeedstudio.com/SeeedStudio_XIAO_Series_Introduction/) —— **低消費電力無線制御ノード**

#### 📡 センサーと周辺機器
*   **🚗 モーター・サーボ**: [Damiao (達妙) / Gogo (高擎) / Robstride (霊足) / Mita (脈塔) / Feite (飛特) / Fashion Star (華馨京)](https://wiki.seeedstudio.com/robotics_page/)
*   **👁️ 視覚認識**: [深度カメラ / LiDAR / ビジョンアルゴリズム](https://wiki.seeedstudio.com/robotics_page/)
*   **👂 聴覚インタラクション**: [ReSpeaker マイクアレイ / 音声認識](https://wiki.seeedstudio.com/ReSpeaker_Mic_Array_v2.0/)
*   **🧭 運動・姿勢**: [IMU (6軸/9軸) / ジャイロスコープ / 磁力計](https://wiki.seeedstudio.com/Sensor/IMU/)
*   **🤖 総合キット**: [その他のロボットセンサーとドライバ事例](https://wiki.seeedstudio.com/robotics_page/)


> 👉 **[Wiki ナレッジベースへアクセス](https://wiki.seeedstudio.com/)** (すべてのチュートリアルが閲覧無料)

---

## ⚙️ ハードウェア仕様 (Specifications)

reBot-DevArmはデスクトップ級の身体性知能アプリケーション向けに設計されており、負荷能力と柔軟性を兼ね備えています。

| パラメータ項目 | 数値 / 説明 |
| :--- | :--- |
| **可搬重量 (Payload)** | **1.5+ kg** |
| **最大リーチ (Reach)** | **650 mm** |
| **自重 (Weight)** | 約 4.0 kg |
| **繰り返し位置決め精度** | < 0.2 mm |
| **自由度 (DOF)** | 6 DOF + 1 グリッパー (CANサーボグリッパーおよび関節モーターグリッパーのオープンソース化準備中) |
| **対応プラットフォーム/エコシステム** | ROS1, ROS2, LeRobot, Pinocchio, Isaac Sim, Python SDK |
| **供給電圧** | DC 24V |

---

## 📂 オープンソース (Hardware Source)

私たちは、ハードウェアのオープンソース化こそがイノベーションを促進すると信じています。このアームの製作に必要なすべては、以下のディレクトリにあります。

*   [`/hardware/STEP`](./hardware/cad): 全機械構造の STEP/STL ファイル（プリント部品、金属部品、購入品を含む）。
*   [`/hardware/bom`](./hardware/bom): **BOMリスト** (外部購入部品の型番、モーターパラメータ、推奨販売店を含む)。
*   [`/tutorial/ROS`](./tutorial/ROS/): **ROS1/2 Noetic/Humble** での使用ソースコードおよびチュートリアル。
*   [`/tutorial/Lerobot`](./tutorial/lerobot/): **LeRobot** 使用ソースコードおよびチュートリアル。
*   [`/tutorial/Isaac`](./tutorial/Isaac/): **Isaac Sim** 使用ソースコードおよびチュートリアル。
---

## 🚀 クイックスタート (Getting Started)

開封からAIシミュレーションまで、完全な学習パスを計画しています。

### 🛠️ フェーズ1：ハードウェア構築と基礎
| 手順 | 説明 | リンク |
| :---: | :--- | :--- |
| **01** | **モーターの基本使用** (Basic Learning of Motors) | [📄 クリックして表示](https://wiki.seeedstudio.com/cn/damiao_series/) |
| **02** | **開封確認** (Unboxing) | 近日公開 |
| **03** | **組立ガイド** (Assemble) | 近日公開 |
| **04** | **原点キャリブレーション** (Calibration) | 近日公開 |
| **05** | **運動学テスト** (Kinematics) | 近日公開 |

### 💻 フェーズ2：アルゴリズムとシミュレーション応用
| 手順 | 説明 | リンク |
| :---: | :--- | :--- |
| **06** | **ROS エコシステム** (ROS2) | 🐢 近日公開 |
| **07** | **AI トレーニング** (Hugging Face) | 🤗 近日公開 |
| **08** | **シミュレーション** (NVIDIA) | 🌌 近日公開 |

---

## 🙌 参考文献と謝辞 (References & Acknowledgments)
オープンソースの道は決して孤独ではありません。reBot-DevArmプロジェクトの誕生は、Seeed Studioの全面的な支援、そして世界中のオープンソースコミュニティと優れたハードウェアパートナーなしにはあり得ませんでした。以下のプロジェクトとチームに心からの敬意を表します。

### 🌍 エコシステムとソフトウェアサポート
*   **[Seeed Studio](https://www.seeedstudio.com/)** - 包括的なハードウェアサプライチェーンと技術サポートの提供。
*   **[Hugging Face LeRobot](https://github.com/huggingface/lerobot)** - 優れたエンドツーエンドロボット学習フレームワーク。
*   **[NVIDIA Isaac Sim](https://developer.nvidia.com/isaac/sim)** - 強力なロボットシミュレーションおよび合成データプラットフォーム。

### ⚙️ コアハードウェアパートナー
高性能なモーターとアクチュエーターソリューションを提供してくださった以下のメーカーに感謝します。
*   **[Damiao Technology (達妙科技)](https://www.damiaokeji.com/)**
*   **[Robstride (霊足時代)](https://robstride.com/)**
*   **[Fashion Star (華馨京科技)](https://fashionrobo.com/)**

### 💡 インスピレーション (Inspiration)
本プロジェクトは、以下の優れたオープンソースプロジェクトから深い感銘を受けています。
*   **[SO-ARM100](https://github.com/TheRobotStudio/SO-ARM100/tree/main)**
*   **[Mobile ALOHA](https://github.com/tonyzhaozh/aloha)**
*   **[Dummy-Robot (Zhihui Jun)](https://github.com/peng-zhihui/Dummy-Robot)**
*   **[OpenArm](https://openarm.dev/)**
*   **[I2RT](https://i2rt.com/)**
*   **[TRLC-DK1](https://github.com/robot-learning-co/trlc-dk1)**

### 🎃 プロトタイプ貢献者
- **SeeedStudio AI Robotics Team's**: Yaohui Zhu (yaohui.zhu@seeed.cc)
- **SeeedStudio STU**: Wentao Dong
- **SeeedStudio STU**: Weiwei Xu
- **SeeedStudio Purchasing Department**: Fengqun Peng


### 👥 その他貢献者 (Contributors)

## Our Top Contributors 
<p align="center"><a href="https://github.com/Seeed-Projects/reBot-DevArm/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=Seeed-Projects/reBot-DevArm" />
</a></p>



*Coming soon... PRを提出してコントリビューターになりましょう！*



# reBot-DevArm プロジェクトライセンス
Copyright (c) [2025] [Seeed Studio AI Robotics Team]

本作品は **クリエイティブ・コモンズ 表示 - 非営利 - 継承 4.0 国際 ライセンス** の下に提供されています。
このライセンスのコピーを確認するには、以下のリンクにアクセスしてください：http://creativecommons.org/licenses/by-nc-sa/4.0/

--------------------------------------------------------------------------------

## 権利と制限事項
1. あなたは以下のことができます：
   - 共有：あらゆる媒体やフォーマットで資料を複製および再配布する。
   - 翻案：資料をリミックス、改変、および資料をベースに二次的著作物を作成する。

2. 以下の条件に従う必要があります：
   - 表示：適切なクレジットを表示し、ライセンスへのリンクを提供し、変更が加えられたかどうかを示す必要があります。
   - 非営利：**営利目的でこの資料を利用することはできません**。
     （関連キットの販売、プリント部品の販売、または明確な許可なく本ソフトウェアを有料製品に統合することを含みますが、これに限定されません）
   - 継承：資料をリミックス、改変、または資料をベースに二次的著作物を作成した場合、元のライセンスと同じライセンスの下で頒布しなければなりません。

3. 商用ライセンス：
   本プロジェクトを商用利用したい場合は、著者に連絡して商用ライセンスを取得してください。
   連絡先：yaohui.zhu@seeed.cc
