# fastapi_tutorial
## 前提構築
- Pyenv
- Pipenv
## 環境構築
### Pythonのバージョン設定
```
$ pyenv local [Pythonバージョン]
```
※Pythonのバージョンは[Pipfile](/Pipfile)を参考
### 仮想環境の設定と起動
```
$ pipenv --python [Pythonバージョン]
$ pipenv shell
```
### ライブラリのダウンロード
```
$ pipenv install -r requirements.txt
```