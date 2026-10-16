# SC01 最小场景验证演示

打开站点后无需安装、登录平台或导入数据，即可逐项查看5大类28份真实执行记录、120条保留集预测、12张样本预览、损失曲线，并下载完整结果PDF或展示JSON。固定场景修订：`2fcd5a6b2dbf7e4b38e8d51246ca845052397126b629e54a63458102a9048683`。

这是已执行结果的静态查看与文件校验；页面访问不重新训练或执行模型。范围和未覆盖子项保留在每项记录中。原始证据哈希索引保留，模型权重、后端执行源码、原始证据包和运行数据库不随此目录公开。演示PDF包含全部28项正文和完整证据索引，不嵌入原始模型/源码附件；完整平台的PDF导出仍保留附件。

## GitHub Pages

独立公开演示仓库 `FieldQuantum/sc01-verification-demo` 的 `main` 分支根目录只保存本目录的静态文件，不包含平台源码历史。Settings → Pages → Deploy from a branch → `main` → `/(root)`。平台主仓库保持私有。

## 数据与许可

UCI Optical Recognition of Handwritten Digits，E. Alpaydin、C. Kaynak (1998)，CC BY 4.0，来源 https://doi.org/10.24432/C50P49 。展示使用8×8量化图像、原项目固定角色划分和自行训练模型的实际输出。报告嵌入Noto Sans SC字体，OFL许可见 `OFL-font.txt`。

可点击“校验演示文件”检查展示JSON、PDF和12张图片的SHA-256一致性；该检查是文件完整性检查，不代替原测试执行或正式符合认定。
