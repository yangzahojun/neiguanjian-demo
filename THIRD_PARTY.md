# 第三方组件与许可

本项目分发时保留下列版权声明与许可证全文（`licenses/`），导出包内同样包含这些文件。

| 组件 | 版本 | 来源 | 协议 | 版权 | 是否修改 |
|---|---|---|---|---|---|
| Godot Engine | 4.7.2 | https://godotengine.org | MIT | Godot Engine contributors；Juan Linietsky, Ariel Manzur | 否（引擎本体） |
| Phantom Camera | 0.11.0.4 | https://github.com/ramokz/phantom-camera | MIT | Marcus Skov (ramokz) | 否，`addons/phantom_camera/` 原样 |
| Dialogue Manager | 4.2.0 | https://github.com/nathanhoad/godot_dialogue_manager | MIT | Nathan Hoad | 否，`addons/dialogue_manager/` 原样；本项目只使用其运行时并另做对话气球外观 |
| LXGW WenKai / 霞鹜文楷 | 1.530 | https://github.com/lxgw/LxgwWenKai | SIL OFL 1.1 | LXGW 与 Klee Project Authors | 否，完整 Regular 字重，未子集化、未改名 |

许可证全文：

- `licenses/MIT-Godot.txt`
- `licenses/MIT-Phantom-Camera.txt`
- `licenses/MIT-Dialogue-Manager.txt`
- `licenses/OFL-LXGW-WenKai.txt`

## 明确未使用的代码

方案文档 §6.4 指出的两个结构相近仓库没有开源协议（默认保留所有权利）：

- `YJsnz/traveler-in-changan`
- `linyuchao123/jizhongju-web`

本项目**未复制**其任何代码、数据或美术，也未对任何第三方文件名、界面或资源做去水印处理。移动、碰撞、交互、手册、判定、提示、场景切换均为本项目自写（约千行 GDScript）。

## 原创素材

`art/` 下的地块、角色、道具、光晕、暗角与 `art/sfx/` 下的音效，全部由本仓库内的 `tools/gen_art.py`、`tools/gen_audio.py` 使用 Python 标准库程序化生成，不含第三方素材。

中文字体除外（见上表）。界面排版与配色来自项目自己的 `art/palette.json`。

## 参考资料

设计文档（`*.docx`）为团队自有内容。考据仅用于确定品级、补子、门禁等制度细节，未直接复制受版权保护的图片或长段文本。
