# 使い方

```
jobs:
  java:
    runs-on: ubuntu-latest
    steps:
      - name: teams webhook action
        uses: KEI0124/saito@v2.2
        with:
          webhook: 'Teamsのwebhook URL('https://~')'
          ami: 'エラーとして出力したい文字'
```