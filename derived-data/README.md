# 此地（PhotoStory）派生地理数据库

本目录是「此地」App 随包分发的地理数据库的**可下载副本**，用于满足
Open Database License 1.0（ODbL）第 4.4/4.6 条关于「向接收者提供衍生数据库」
与「保留许可声明」的要求。

- 版本：v1（与 App 1.2.1 随包数据一致）
- 生成日期：2026-10-21
- 许可：**ODbL 1.0**（全文见同目录 `ODbL-1.0.txt`）
- 署名：**© OpenStreetMap contributors** — https://www.openstreetmap.org/copyright

## 内容

| 路径 | 说明 | 来源 |
|---|---|---|
| `features/lakes.geojson` | 湖泊 | OpenStreetMap（ODbL 1.0） |
| `features/rivers.geojson`、`rivers-osm.geojson`、`river-names.tsv` | 河流 | OpenStreetMap / Natural Earth（公有领域） |
| `features/peaks.geojson` | 山峰 | OpenStreetMap（ODbL 1.0） |
| `features/passes.geojson` | 垭口 | OpenStreetMap（ODbL 1.0） |
| `features/viewpoints.geojson` | 观景台 | OpenStreetMap（ODbL 1.0） |
| `features/glaciers.geojson` | 冰川 | RGI 6.0（CC BY 4.0） |
| `features/protected-areas.geojson` | 保护区 | OpenStreetMap（ODbL 1.0） |
| `spots/candidates.json` | 机位候选（798 条，全部为待核验 candidate） | OpenStreetMap 派生（ODbL 1.0） |

数据经过裁剪、去重、几何简化与中文名整理；中文名部分来自 GeoNames（CC BY 4.0）。
逐文件许可说明见 `features/README.md`。

## 使用

- 你可以自由复制、分发、修改本数据库，但必须保留本许可与署名；
- 若你分发本数据库或其衍生作品，须同样以 ODbL 1.0 提供，并保留
  「© OpenStreetMap contributors」署名；
- 本数据库不含个人数据。

如有疑问：yang_sp@163.com
