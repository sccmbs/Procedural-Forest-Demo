# Procedural-Forest-Demo
A procedural natural forest demo built with UE5 PCG, Niagara &amp; AI tools.
我是一名专注于程序化生成与技术美术的大一学生。本作是我利用 **大一下暑假** 独立完成的UE5场景作品，目标是探索“**AI辅助资产生成 + PCG程序化搭建**”的现代游戏内容管线。场景主题为“静谧森林之夜”，希望用技术呈现自然世界的宁静与生命力。

## 技术栈
- **Unreal Engine 5.5** - 场景搭建与整合
- **PCG 框架** - 实现依据地形坡度的植被自动分布、样条线道路生成
- **Meshy AI / WithPoly** - AI辅助生成核心3D资产与PBR材质
- **Niagara VFX** - 制作动态萤火虫粒子特效
- **3ds Max** - 基础模型修整与模块化木屋搭建

## 核心实现
1.  **程序化森林生态**
    -   通过PCG表面采样器与坡度过滤，让针叶林与阔叶林在平缓地与陡坡处自然过渡。
    -   样条线驱动道路系统，并自动降低周边植被密度。
2.  **PBR硬表面资产（传统流程展示）**
    -   独立完成了一个PBR全流程硬表面道具（木箱），展示标准次世代资产制作能力。
3.  **动态粒子特效**
    -   使用Niagara系统制作萤火虫，其分布密度与玩家位置、环境光源动态关联，引导视线。

## 视频演示
- Bilibili: [你的视频链接占位符]
- YouTube: [可选]

## 快速开始
1.  Clone 本仓库
2.  使用 Unreal Engine 5.5 打开 `PCG_Forest.uproject`
3.  点击 Play 即可漫游场景

## 联系我
- 邮箱：xxx@xxx
- 微信：xxx
