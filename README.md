# python-on-docker

## 説明

python v3.9のdocker環境です。</br>
プロジェクトルートをappコンテナ上の`/app`にマウントしています。

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
