1.In KiCad Schematic Editor place a new hierarchical sheet(A).
2.In the hierarchical sheet draw the single channel schematic. And rename designator(R1->R1_1, R2->R2_1...).
3.In top sheet copy and paste the hierarchical sheet(A).
4.Update PCB from Schematic.
5.In pcbnew use plugin [Replicate Layout](https://github.com/MitjaNemec/ReplicateLayout).

1.在原理图编辑器，防止一个层次原理图。
2.在层次原理图中，绘制单通道原理图。重命名位号：R1->R1_1,R2->R2_1...
3.在顶层原理图中，复制粘贴层次原理图。
4.根据原理图更新PCB。
5.在PCB编辑器中，使用插件Replicate Layout。选中某个通道的一个元器件作为锚，点击插件图标。按照提示操作。