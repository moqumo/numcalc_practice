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
