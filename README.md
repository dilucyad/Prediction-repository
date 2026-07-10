# 研构智库发布页

下载地址：[dilucyad/Prediction-repository](https://github.com/dilucyad/Prediction-repository)

## 当前发布文件

- V 系列稳定版：`ScientificPlatformPrediction_V1.3.2.exe`
- T 系列模型版：`ScientificPlatformPrediction_T1.3.exe`

GitHub Release 仅保留最新一组发布文件：V 系列一份、T 系列一份。

## V 系列 V1.3.2

V 系列面向稳定分发，保留数据库匹配、数据库结果展示、SMILES 输入、结构绘制、预测提示、结果展示、主题切换、中英文切换和版本更新功能。

适用场景：需要稳定界面、数据库匹配结果和受约束预测流程的日常使用。

## T 系列 T1.3

T 系列面向模型直接预测，不通过数据库调用或数据库匹配展示性能结果。程序根据输入或绘制得到的 SMILES 计算分子描述符，并按用户选择的体系调用对应模型：

- PI：预测 Dieletric Constant、Dieletric Loss、Td5%、Tg，并计算 SA score。
- PBZ：预测 Dieletric Constant、Dieletric Loss、Tg，并计算 SA score。

预测界面支持 SMILES 输入、结构绘制、PI/PBZ 体系选择、10–20 秒随机进度条延迟展示、主题切换、中英文切换、启动说明和预测记录查看。预测记录保存在本机，可在界面中查看历史结果并回填对应 SMILES。

适用场景：需要绕过数据库、直接使用机器学习模型预测 PI/PBZ 结构性能的测试使用。

## 更新功能说明

V 系列和 T 系列使用不同附件前缀区分更新文件：

- V 系列只识别 `ScientificPlatformPrediction_*.exe`
- T 系列只识别 `ScientificPlatformPrediction_T*.exe`

这样两个系列可以放在同一个 GitHub Release 中，同时避免更新时下载到错误系列。

## 问题反馈

如有问题，请发送邮件到 Y17250018@mail.ecust.edu.cn。

## 使用说明

1. 进入 Release 页面。
2. 按需要下载 V 系列或 T 系列 exe。
3. 双击运行。
4. 输入 SMILES 或点击“绘制结构式”。
5. V 系列查看数据库匹配/预测提示；T 系列选择 PI 或 PBZ 后查看模型预测结果和 SA score。
