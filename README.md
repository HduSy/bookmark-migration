# Bookmark Migration

浏览器收藏夹迁移工具，支持在不同浏览器之间迁移书签/收藏夹。

## 支持的浏览器

- Chrome
- Edge
- Tabbit
- Arc
- Brave
- Firefox
- Safari

## 功能特性

- 一键全量迁移
- 指定文件夹迁移
- 关键词匹配迁移
- 多账户自动遍历
- 预览模式（dry-run）
- 自动备份目标书签

## 使用方法

```bash
# 列出收藏夹
node migrate-bookmarks.mjs -s chrome -l

# 迁移指定文件夹
node migrate-bookmarks.mjs -s chrome -t tabbit -f "文件夹名"

# 预览迁移
node migrate-bookmarks.mjs -s chrome -t tabbit -f "文件夹名" -d

# 全量迁移
node migrate-bookmarks.mjs -s chrome -t edge

# 按关键词迁移
node migrate-bookmarks.mjs -s chrome -t arc -k github
```

## License

MIT
