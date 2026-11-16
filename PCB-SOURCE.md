# PCB 焊点射线图对比

原始射线样图来自 [BGA joint xray.jpg](https://commons.wikimedia.org/wiki/File:BGA_joint_xray.jpg)，上传者 DJGB，文件页标注为公有领域。这里的四张演示 PNG 由该图在 HiAgent 中显示的灰度预览裁剪并计算，尺寸为 209 × 192 像素。

| 文件 | 处理 |
| --- | --- |
| pcb-original.png | 原图预览裁剪 |
| pcb-denoise.png | 3×3 高斯平滑 |
| pcb-contrast.png | 固定灰度中心 128，对比度系数 1.15 |
| pcb-sharpen.png | 反锐化掩模，强度 0.75 |
