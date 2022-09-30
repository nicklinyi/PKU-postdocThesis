

# PKU-PostDoc-Thesis

**PKU-PostDoc-Thesis** 是 **P**e**K**ing **U**niversity **PostDoc** **Thesis** LaTeX Template 的缩写。

此宏包旨在建立一个简单易用的北京大学博士后出站报告 LaTeX 模板。该模板基于ThuThesis模板(https://github.com/tuna/thuthesis）。


## Makefile的用法

```shell
make [{all|thesis|spine|doc|clean|cleanall|distclean}]
```

### 目标
* `make thesis`    生成论文 thuthesis-example.pdf；
* `make spine`     生成书脊 spine.pdf；
* `make doc`       生成模板使用说明书 thuthesis.pdf；
* `make all`       生成论文和书脊，相当于 `make thesis && make spine`；
* `make clean`     删除示例文件的中间文件（不含 thuthesis-example.pdf）；
* `make cleanall`  删除示例文件的中间文件和 thuthesis-example.pdf；
* `make distclean` 删除示例文件和模板的所有中间文件和 PDF。

