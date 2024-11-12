## 🌏六角學院每日任務 DAY6
- <NuxtLink to=""></NuxtLink> 等於html的<a href=""></a>
- external會將 <NuxtLink> 識別為外部連結
- target 屬性用於控制連結點擊後的打開方式,_self、_blank、_parent、_top

## 🛠️常用指令:
```
// nuxt.config加上router設定後 當連結匹配路由 會自動套用屬性
export default defineNuxtConfig({
  router: {
    options: {
      linkActiveClass: "active",
      linkExactActiveClass: "active",
    },
  },
});
```
