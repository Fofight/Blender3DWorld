PDB(Protein Data Bank)是一种标准文件格式, 其中包含原子的坐标等信息

PDB格式以文本格式给出信息, 每一行信息称为一个 记录(record). 一个PDB文件通常包括很多不同类型的记录, 它们以特定的顺序排列, 用以描述结构

PDB文件里面的每个记录都有着严格的格式. 每个记录中的字段, 如标识, 原子名称, 原子序号, 残基名称, 残基序号等, 不仅要按照严格的顺序书写, 而且每个字段所占的字符串长度, 及其所处的位置都是严格规定好的

准确的PDB格式文件对于分子数字建模意义重大

### 这是关于.pdb文件在blender展示的汇总

![](https://wiki.blender.org/skins/naiad/images/blender_logo.png)
##### 1.工欲善其事，必先利其器
    
blender中import pdb 文件功能插件网址[Import-Export/PDB](https://wiki.blender.org/index.php/Extensions:2.6/Py/Scripts/Import-Export/PDB)__[直接下载](http://development.root-1.de/X-Download/io_mesh_pdb.zip)

[Github Keyword](https://github.com/search?l=Python&o=desc&q=pdb&s=stars&type=Repositories&utf8=%E2%9C%93)


[格式说明参考](http://jerkwin.github.io/2015/06/05/PDB%E6%96%87%E4%BB%B6%E6%A0%BC%E5%BC%8F%E8%AF%B4%E6%98%8E/)

[PDB格式官方文档](http://www.wwpdb.org/documentation/file-format)

[PDB原子记录官方文档](http://www.wwpdb.org/documentation/file-format-content/format33/sect9.html)

[Github类似工作](https://github.com/bigwiv/Biopython-cn/blob/master/cn/chr11.rst)

[Introduction to Protein Data Bank Format](http://www.cgl.ucsf.edu/chimera/docs/UsersGuide//tutorials/framepdbintro.html)

分子模型引入游戏用作主要的模型必将是一场革命，纵观现在的游戏产业，普遍的3D模型给我的感觉就如充气的娃娃，撑起华丽酷炫的外表的却是空气，太虚。而分子模型就如配有优秀引擎的机器人，两种感觉是截然不同的。而建模的过程又像是常规机器学习和深度学习的比较，一个是通过大数据（经验）的堆彻，另一是规则的学习（自然规则）。一个是艺术的创作，另一个是科研的展示

##### 2.知己知彼，百战不殆

通过分子结构画3D模型的软件

Chem 3D

PyMOL

Maestro

Mercury

Avogadro

Chimera

Diamond

