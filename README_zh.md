# Hexo Theme Frutiger Aero

[English](./README.md) | 简体中文

一款怀旧风格的 Hexo 主题，灵感源自 2000 年代中后期到 2010 年代初期的 Frutiger Aero 审美。

![预览图](./screenshot.png)

## 特性
- **拟物化玻璃效果**：利用 `backdrop-filter` 实现高质量的毛玻璃拟态。
- **鲜艳渐变色**：采用该时代典型的亮蓝色与绿色配色方案。
- **动态气泡**：背景中漂浮的 CSS 动画气泡，增强怀旧氛围。
- **响应式设计**：完美适配手机、平板及桌面端。
- **轻量快捷**：无沉重依赖，加载速度快。
- **特色功能**：内置 Bangumi 追番墙、怀旧时间轴归档及关于页。

## 安装方法

1. 进入你的 Hexo 根目录。
2. 克隆本仓库到主题目录：
   ```bash
   git clone https://github.com/tud8951/hexo-theme-frutiger-aero themes/frutiger-aero
   ```
3. 修改 Hexo 根目录下的 `_config.yml`：
   ```yaml
   theme: frutiger-aero
   language: zh-CN
   ```

## 配置说明

### 主题设置
编辑 `themes/frutiger-aero/_config.yml` 来自定义菜单、社交链接及 Bangumi ID：

```yaml
# 追番配置
bangumi:
  enabled: true
  user_id: 你的ID
```

### 网站图标
将你的 `favicon.jpg` 放入 `source/img/` 目录下，并在主题配置中指定路径。

## 许可证
MIT
