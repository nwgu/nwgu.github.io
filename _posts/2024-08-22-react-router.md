---
layout: post
title: Outlet 컴포넌트
categories: [dev]
---

### React
```react
import { Outlet } from 'react-router-dom';

return (
    <Outlet/>
)

```
### 해당 컴포넌트는 router 를 감싼 Layout 에서 사용할 때 context API 처럼 자식에서 데이터를 받아올수도 있다.