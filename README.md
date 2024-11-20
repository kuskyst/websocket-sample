# 使用例
wscatを使用する場合

## インストール
```
npm install -g wscat
```

## チャットサーバ立ち上げ
```
go run main.go
```

## 接続の確立 (複数のターミナルから)
```
npx wscat -c ws://localhost:8080/ws
```

チャットできればＯＫ
