# numcalc_practice
## notebooks
### 常微分方程式の数値計算法(ODE)
1. オイラー法 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/moqumo/numcalc_practice/blob/ODE/notebooks/ODE/01_euler_method.ipynb).
2. ホイン法
3. ルンゲクッタ法
4. 多変数の常微分方程式の数値計算   
### 常微分方程式の数理モデル(ODE_model)
1. 捕食者-被捕食者モデル -ロトカ・ヴォルテラ方程式-
2. 感染症 -SIRモデル-
3. 神経活動1 -フィッツヒュー・南雲方程式-
4. 神経活動2 -ホジキンハクスレー方程式-
5. BZ反応
6. カオス1 ローレンツ方程式
7. カオス2 レスラー方程式   
### 偏微分方程式の数値計算(PDE)
1. 陽解法[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/moqumo/numcalc_practice/blob/main/notebooks/PDE/01_explicit_method.ipynb)
3. 陰解法
4. ADI法
5. 有限体積法
### 偏微分方程式の数理モデル(PDE_model)
1. 波の伝播 -移流方程式-
2. 体表パターン -チューリングパターン-
3. BZ反応のらせん波

### ニューラルネットワークによる数値計算（PINN）
1. PINNs

## setup
1. このリポジトリをクローン（クローンしたいディレクトリ下で実行）
    ```
    git clone https://github.com/moqumo/numcalc_practice
    ```
2. venv環境を作る(``.gitignore``に記載済み)   
    ```
    python -m venv .venv
    ```
3. venvを起動する   
    Mac,Linux,WSLの場合
    ```
    source venv/bin/activate
    ```
    Windowsの場合
    ```
    .venv\Scripts\activate
    ```
4. ライブラリをインストールする
    ```
    pip install -r requirements.txt
    ```
    上手くできない場合
    ```
    pip install numpy matplotlib ipykernel nbconvert
    ```
5. vscodeでjupyterの拡張機能をインストールする

# 参考文献
[“私にとっての”反応拡散系数値シミュレーション入門基礎編](https://mmc01.es.hokudai.ac.jp/else/cdrom/main_part1.pdf) (2025/01閲覧)

