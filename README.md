# 痒局长 · AinJuZen

> 把日常里那些「每次都要手动搞一遍」的破事，写成小工具。

做 ComfyUI 相关的小东西。都是自己先被卡住，才动手写的。

---

## 在做的

装一次 ComfyUI 到真正能干活，中间有三个坑。各有一个工具。

| 卡在哪 | 工具 | 一句话 |
|---|---|---|
| 缺模型，下不动 | [ComfyUI-ModelMirror](https://github.com/AinJuZen/ComfyUI-ModelMirror) | 点一下从镜像补齐，断点续传，不改官方文件 |
| 下好了，不知道放哪 | [ComfyUI-ModelSorter](https://github.com/AinJuZen/ComfyUI-ModelSorter) | 读文件里的张量名判类型，不靠文件名猜 |
| Manager 打开一片空白 | [ComfyUI-ManagerFix](https://github.com/AinJuZen/ComfyUI-ManagerFix) | 诊断 → 改镜像 → 真去拉一遍验证 |

```
拿到  →  放对  →  工具本身能用
```

三个都是 MIT。没有广告、没有登录、没有"升级会员"。

---

## 为什么这么写

**① 能不改官方文件就不改**

**改了就会随升级失效。所以 ModelMirror 是扩展、ModelSorter 是外部工具，只有 ManagerFix 不得不改——**
**而它把「升级后要重跑」写在了 README 第一屏。**

**② 判不出来就说判不出来**

**ModelSorter 遇到不认识的模型结构，只会说「判断不出来」，不会猜着放。**
**猜错了用户不会知道，直到加载报错。**

**③ 验证要真做一遍**

**「我改完了」不算数，「改完真能拉到 3015 KB」才算数。**

---

## 写下来的过程

**开发日志：[ainjuzen.github.io](https://ainjuzen.github.io/)**

每个工具为什么这么做、踩了什么坑：

- [官方那个「下载」按钮，在国内基本按不动](https://github.com/AinJuZen/ComfyUI-ModelMirror/discussions/1)
- [下了模型，然后站在目录前面发呆](https://github.com/AinJuZen/ComfyUI-ModelSorter/discussions/1)
- [Manager 装好了，打开是空的](https://github.com/AinJuZen/ComfyUI-ManagerFix/discussions/1)

---

## 联系

- B 站：[痒局长](https://space.bilibili.com/322892)
- 邮箱：821858285@qq.com

有问题直接开 issue，比私信快。
