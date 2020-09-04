# python-on-docker

## 説明

python v3.9のdocker環境です。</br>
`./jupyter`をappコンテナ上の`/jupyter`にマウントしています。</br>
</br>
jupyter notebookが標準で立ち上がります。</br>
起動時に表示される `http://127.0.0.1:8888/?token=xxxxxxxxxxxxxxxxxx` にアクセスしてください。

```bash
app_1  |     Or copy and paste one of these URLs:
app_1  |         http://4c135c852c65:8888/?token=xxxxxxxxxxxxxxxxxx
app_1  |      or http://127.0.0.1:8888/?token=xxxxxxxxxxxxxxxxxx
```

## 起動方法

### コンテナの起動

```bash
docker-compose up -d
```

### コンテナの終了

```bash
docker-compose down
```

### appコンテナに入る

```bash
docker-compose exec app /bin/bash
```
