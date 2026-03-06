# Freezer 1.4 使用说明 / User Guide

> 一个用于细胞冻存位置管理的小工具。  
> A lightweight tool for managing cryo-sample locations.

---

## 1) 快速开始 / Quick Start

### 中文
1. 直接用浏览器打开 `freezer-1.4.html`。  
2. 点击顶部 **新建**，先创建文件夹，再创建容器。  
3. 在左侧选择容器后，点击网格单元格，右侧填写细胞信息并保存。  

### English
1. Open `freezer-1.4.html` in your browser.  
2. Click **New** on the top toolbar, then create folders and boxes.  
3. Select a box on the left, click grid cells, fill sample info on the right, then save.

---

## 2) 语言切换 / Language Switch

### 中文
- 右上角有 **中/EN** 切换按钮。  
- 切换后，页面文本会自动更新。  

### English
- Use the **中文 / EN** switch at the top-right.  
- UI text updates immediately after switching.

---

## 3) 基本概念 / Core Concepts

### 中文
- **文件夹 (Folder)**：用于分类管理容器。  
- **容器 (Box)**：每个容器有行列规格（如 8x12）。  
- **单元格 (Cell)**：容器中的具体存储位点。  

### English
- **Folder**: category/group for boxes.  
- **Box**: storage container with row/column size (for example 8x12).  
- **Cell**: a specific position inside a box.

---

## 4) 常用操作 / Common Operations

### 4.1 新建文件夹与容器 / Create Folder & Box

**中文**
- 点击 **新建** → 选择“新建文件夹”或“新建容器”。  
- 新建容器时可选择预设规格，或自定义行列。  

**English**
- Click **New** → choose “New Folder” or “New Box”.  
- For boxes, choose a preset spec or use custom rows/cols.

### 4.2 录入与保存 / Edit & Save

**中文**
- 点击一个或多个单元格（可开启“多选”）。  
- 在右侧填写：细胞名称、代数、冻存日期。  
- 点击 **保存** 将信息写入选中单元格。  

**English**
- Select one or multiple cells (enable “Multi-select” if needed).  
- Fill in: cell name, passage, freeze date.  
- Click **Save** to apply to selected cells.

### 4.3 出库 / Clear

**中文**
- 选中单元格后点击 **出库**，确认后清空所选位置。  

**English**
- Select cells, click **Clear**, then confirm to remove data from selected positions.

### 4.4 复制与粘贴 / Copy & Paste

**中文**
- 选中单元格后可 **复制**。  
- 选择目标单元格后可 **粘贴**（支持单条覆盖多格、或一一对应）。  

**English**
- Select cells and click **Copy**.  
- Select target cells and click **Paste** (supports single-to-many or one-to-one mapping).

---

## 5) 库存定位 / Inventory Location Lookup

### 中文
- 当选中一个有细胞名称的单元格时，点击右侧“全库总余量”区域。  
- 会弹出库存位置窗口，显示同名细胞在所有容器中的位置。  
- 点击条目可快速跳转到对应容器和单元格。  

### English
- Select a cell with a valid cell name, then click the **Total Inventory** area.  
- A modal lists all matching locations across boxes.  
- Click an item to jump directly to that box/cell.

---

## 6) 数据导入导出 / Import & Export

### 中文
- 支持导入、导出 Excel、导出 JSON 备份。  
- 建议定期导出 JSON 以便迁移与恢复。  

### English
- Supports import, Excel export, and JSON backup export.  
- Export JSON regularly for migration and recovery.

---

## 7) 自动备份 / Auto Backup

### 中文
- 顶部工具栏可设置自动备份目录并手动触发备份。  
- 若浏览器不支持目录授权，会使用本地备份模式。  

### English
- Configure backup directory and trigger manual backup from the top toolbar.  
- If directory permission API is unavailable, local backup mode is used.

---

## 8) 使用建议 / Tips

### 中文
- 文件夹建议按温区或项目建立（如：液氮、-80、项目名）。  
- 容器命名建议统一规则（如：项目-批次-序号）。  
- 大量操作前先导出 JSON 备份。  

### English
- Organize folders by storage condition or project (e.g., LN2, -80, project name).  
- Use a consistent naming rule for boxes (e.g., project-batch-index).  
- Export JSON backup before large updates.

---

## 9) 故障排查 / Troubleshooting

### 中文
- 看不到数据：确认当前选择的是正确文件夹/容器。  
- 粘贴失败：检查是否已复制，或目标数量是否匹配。  
- 英文显示不全：尝试切换语言后刷新页面。  

### English
- Data not visible: verify selected folder/box.  
- Paste failed: ensure data is copied and target count is valid.  
- Incomplete English text: switch language once and refresh the page.

