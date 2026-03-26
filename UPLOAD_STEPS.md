# GitHub 主页上传步骤

## 1. 创建同名仓库

如果你的 GitHub 用户名是 `zhengthirteen`，就创建一个 **公开仓库**：

- Repository name: `zhengthirteen`
- Visibility: Public
- 可以勾选 `Add a README file`，也可以不勾

> 这个同名仓库的根目录 `README.md` 会显示在你的个人主页顶部。

## 2. 上传本压缩包里的内容

把压缩包解压后，你会看到：

- `README.md`
- `UPLOAD_STEPS.md`
- `assets/`

把 `README.md` 和整个 `assets/` 文件夹上传到 **同名仓库根目录**。

最终仓库结构应类似：

```text
zhengthirteen/
├── README.md
└── assets/
    ├── hero-panel.svg
    ├── divider.svg
    └── orbit-mark.svg
```

## 3. 上传方式（网页最简单）

### 方式 A：网页上传

1. 打开你的同名仓库 `zhengthirteen`
2. 点击 `Add file` → `Upload files`
3. 把 `README.md` 和 `assets` 文件夹里的文件一起拖进去
4. 下方填写 commit message，例如：
   - `init profile readme`
5. 点击 `Commit changes`

### 方式 B：本地 git 上传

```bash
git clone https://github.com/zhengthirteen/zhengthirteen.git
cd zhengthirteen
```

然后把解压后的文件复制进去，再执行：

```bash
git add .
git commit -m "init profile readme"
git push
```

## 4. 设置 pinned repositories

上传好 README 后，回到你的 GitHub 个人主页：

1. 在 `Pinned` 区域点 `Customize your pins`
2. 选择最多 6 个仓库
3. 拖动调整顺序

## 5. 修改 bio

你选定的 bio 是：

```text
SCU 2 NJU. Still compiling.
```

修改路径：

1. 打开个人主页
2. 点击 `Edit profile`
3. 在 bio 里填入上面这句话
4. 保存

## 6. 如果图片没有显示

检查这几点：

- `assets` 文件夹是否在仓库根目录
- 文件名是否完全一致
- `README.md` 是否也在仓库根目录
- 仓库是否为 Public

