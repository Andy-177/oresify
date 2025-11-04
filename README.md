# oresify
oresify是适用于docsify的oreui，可以创建oreui里的一些元素在你的文章里面，同时整个博客主题也是oreui

# 导入
使用以下标签导入oresify
```
<link rel="stylesheet" href="oresify.css">
```

> **注意：oresify.css要放在网页根目录**
# 添加元素
下面是oreui元素添加的示例
```
<header>
    <div class="header_title">OreUI 立体按钮展示</div>
</header>

<!-- 提示条区域 -->
<h2 class="section_title">提示条 (Banner)</h2>
<div class="banner neutral_banner">中性提示条 - 这是一条普通信息</div>
<div class="banner information_banner">信息提示条 - 这是一条重要信息</div>
<div class="banner important_banner">重要提示条 - 这是一条警告信息</div>

<!-- 徽章区域 -->
<h2 class="section_title">徽章 (Badge)</h2>
<div class="badge_area">
    <div class="badge green_badge"></div>
    <span>绿色徽章 - 表示成功或在线状态</span>
</div>
<div class="badge_area">
    <div class="badge blue_badge"></div>
    <span>蓝色徽章 - 表示信息或链接</span>
</div>
<div class="badge_area">
    <div class="badge yellow_badge"></div>
    <span>黄色徽章 - 表示警告或注意</span>
</div>
<div class="badge_area">
    <div class="badge red_badge"></div>
    <span>红色徽章 - 表示错误或离线状态</span>
</div>

<!-- 按钮区域 -->
<h2 class="section_title">标准按钮</h2>
<div class="btn_group">
    <button class="btn normal_btn extra_small_btn">超小按钮</button>
    <button class="btn normal_btn small_btn">小按钮</button>
    <button class="btn normal_btn middle_btn">中等大小按钮</button>
    <button class="btn normal_btn large_btn">大尺寸按钮</button>
</div>

<h2 class="section_title">功能按钮</h2>
<div class="btn_group">
    <button class="btn green_btn small_btn">确认</button>
    <button class="btn red_btn small_btn">取消</button>
    <button class="btn normal_btn small_btn">重置</button>
    <button class="btn disabled_btn small_btn">禁用</button>
</div>

<h2 class="section_title">带图标按钮</h2>
<div class="btn_group">
    <button class="btn normal_btn small_btn">
        <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM6dj0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxwYXRoIGQ9Ik0xOSA3TDIyIDEwVjE5QzIyIDIwLjEwNCAyMS4xMDQgMjEgMjAgMjFIMTRWMTlIMjBIMTRWMTBMMTkgN0g5Qzc4OTI1OCA3IDcgNy44OTI2IDcgOVYxOUg0QzIuODk1NCAxOSAyIDE4LjEwNCAyIDE3VjEwQzIgOC44OTU0IDguODk1NCA4IDkgOEgxOUMyMC4xMDQgOCAyMSA4Ljg5NTQgMjEgMTBWMjdIMjNWMTRDMjMgMTAuNjg2MyAyMC4zMTM3IDggMTcgOEgxOU03IDEzVjE1SDUuNVYxM0g3ek0xNyAxM1YxNUgxNS41VjEzSDE3ek03IDE3VjE5SDUuNVYxN0g3ek0xNyAxN1YxOUgxNS41VjE3SDE3eiIvPjwvc3ZnPg==" class="button_img left">
        左图标
    </button>
    <button class="btn green_btn small_btn">
        右图标
        <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM6dj0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxwYXRoIGQ9Ik0xNiAxMEg5VjdMMTQgMkgxN1Y3SDIwVjEwSDE2ek0yIDVIMTRWM0gyQzAuODk1NCAzIDAgMy44OTU0IDAgNUMwIDYuMTA0NiAwLjg5NTQgNyA2IDdIMTRWNUgyWiIvPjwvc3ZnPg==" class="button_img right">
    </button>
</div>

<h2 class="section_title">侧边栏按钮</h2>
<div class="btn_group">
    <button class="sidebar_btn">菜单选项1</button>
    <button class="sidebar_btn">菜单选项2</button>
    <button class="sidebar_btn">菜单选项3</button>
</div>
```
