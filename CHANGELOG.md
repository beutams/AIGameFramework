# Changelog

## [0.2.0] - 2026-11-20

### Changed

- 架构数据改存到包根目录的 `architecture.json`，不再写入宿主项目的 `Assets/AIArchitecture/`。
- 数据路径按 `ArchitectureStore.cs` 所在包目录解析，不再依赖固定安装路径。

## [0.1.0] - 2026-11-20

### Added

- 将 AI 架构编辑器提取为独立 UPM 包，仅保留编辑器代码、配置和文档。
- 架构数据默认写入宿主项目的 `Assets/AIArchitecture/architecture.json`。
- 增加 `Tools/AI 架构编辑器` 菜单入口，工具栏注入失败时仍可打开窗口。
- 增加包内 AI 工作规范、编辑器说明、架构示例和 agent skill 模板。
