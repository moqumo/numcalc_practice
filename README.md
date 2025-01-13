# numcalc_practice

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

## notebooks
### 常微分方程式の数値計算法
- 01 オイラー法   
- 02 ルンゲクッタ法   
- 03 多変数の常微分方程式の数値計算   
### 常微分方程式の数理モデル
- 01 捕食者-被捕食者モデル -ロトカ・ヴォルテラ方程式-   
- 02 感染症 -SIRモデル-   
- 03 神経活動1 -フィッツヒュー・南雲方程式-   
- 04 神経活動2 -ホジキンハクスレー方程式-   
- 05 BZ反応   
- 06 カオス1 ローレンツ方程式   
- 07 カオス2 レスラー方程式   
### 偏微分方程式
