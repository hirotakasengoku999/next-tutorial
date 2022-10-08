---
title: 'アウトプット作成'
date: '2022-10-08'
---

DjangoRestFrameworkとNext.jsの勉強アウトプットとしてシンプルなレセプト電算コード検索アプリを作成してみました。

機能:

- ９桁のレセプト電算コードを入力して検索ボタンをクリック
- 診療行為名称、フリガナ、点数、入外区分、カテゴリーが表示される

使用技術:

- DjangoRestFramework : ObjectMultipleModelAPIView, ModelViewSet, APIView
- Next.js : useSWR, ISR, SSG
- React: useState, useEffect
- Tailwindcss, flowbire

URL
<https://receipt-search-next-front.vercel.app/receipt-search>