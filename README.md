# 码头钓记（本地版）

码头沉底钓的渔获和环境记录。纯前端，数据只存在你自己的设备上。

## 放到 GitHub Pages

1. 在 GitHub 新建一个 **Public** 仓库，比如 `wharf-log`。
2. 仓库页面点 **Add file → Upload files**，把这个文件夹里的 6 个文件全部拖进去（`index.html`、`sw.js`、`manifest.webmanifest` 和 3 个图标要在仓库根目录，不要套一层文件夹），点 **Commit changes**。
3. **Settings → Pages**，Source 选 **Deploy from a branch**，Branch 选 `main`、目录 `/ (root)`，Save。
4. 等一两分钟，页面上方会出现地址：`https://你的用户名.github.io/wharf-log/`

## 装到手机

- iPhone：用 **Safari** 打开上面的地址 → 分享按钮 → **添加到主屏幕**。
- Android：用 Chrome 打开 → 菜单 → **添加到主屏幕 / 安装应用**。

之后从主屏幕图标进入。有信号时打开过一次以后，没信号也能用。

iPhone 上主屏幕应用和 Safari 的数据是分开存的，所以**先添加到主屏幕，再开始记录**。

## 数据

- “记录”页底部：**备份全部数据**（.json，换手机时用）、**导出 CSV**（做分析用）、**导入**（两种文件都认，重复的自动跳过）。
- 删掉主屏幕图标或清除浏览器数据会把记录一起清掉，隔一阵备份一次。
- 从 Claude 里的旧版搬数据：旧版“记录”页导出 CSV，在这里点导入。

## 更新

替换仓库里的 `index.html` 后，把 `sw.js` 第 2 行的版本号加一（`wharflog-v1` → `wharflog-v2`）。手机上联网重开两次应用就是新版，数据不受影响。
