<div align="center">

<img src="docs/assets/ncu-logo.svg" width="560" alt="南昌大学 Nanchang University" />

# 食品科学与工程 · 全学期 16 周实验

**南昌大学　·　食品科学与工程专业　·　2026–2027 学年第一学期**

![School](https://img.shields.io/badge/南昌大学-Nanchang%20University-003D80?style=flat-square)
![Major](https://img.shields.io/badge/专业-食品科学与工程-0A5CB8?style=flat-square)
![Weeks](https://img.shields.io/badge/实验周数-16%20周-4B9B48?style=flat-square)
![License](https://img.shields.io/badge/用途-课程学习-888888?style=flat-square)

</div>

---

## 一、个人信息

| 项目 | 内容 |
| :--: | :-- |
| **学校** | 南昌大学（Nanchang University） |
| **专业** | 食品科学与工程 |
| **学号** | 7902126155 |
| **姓名** | 张紫萱 |
| **课程** | 全学期实验（16 周） |
| **学期** | 2026–2027 学年 第一学期 |
| **指导教师** | （待填写） |

---

## 二、仓库简介

本仓库用于记录与归档本人在**南昌大学食品科学与工程专业**全学期（共 **16 周**）实验课程中的
**实验方案、原始数据、处理代码与实验报告**。

- 数据可复现：`code/` 中的脚本可依据 `data/` 中数据复现结果；
- 过程可追溯：每周独立目录，配合 Git 提交历史记录演进过程；
- 报告可交付：`report/` 存放当周实验报告成品与图表。

---

## 三、目录结构（全学期 16 周目录树）

```text
codebuddy2.0/
├── .gitignore                 # Git 忽略规则
├── README.md                  # 仓库总说明（本文件）
├── docs/                      # 文档与素材
│   └── assets/
│       └── ncu-logo.svg       # 南昌大学标识
├── Week01/                    # 第 01 周实验
│   ├── README.md              # 本周实验说明（目的/原理/步骤/结果）
│   ├── code/                  # 实验代码与脚本
│   ├── data/                  # 原始数据与处理后数据
│   └── report/                # 实验报告与图表
├── Week02/                    # 第 02 周实验（内部结构同 Week01）
├── Week03/                    # 第 03 周实验
├── Week04/                    # 第 04 周实验
├── Week05/                    # 第 05 周实验
├── Week06/                    # 第 06 周实验
├── Week07/                    # 第 07 周实验
├── Week08/                    # 第 08 周实验（期中）
├── Week09/                    # 第 09 周实验
├── Week10/                    # 第 10 周实验
├── Week11/                    # 第 11 周实验
├── Week12/                    # 第 12 周实验
├── Week13/                    # 第 13 周实验
├── Week14/                    # 第 14 周实验
├── Week15/                    # 第 15 周实验
└── Week16/                    # 第 16 周实验（期末）
```

> 说明：`Week01` ~ `Week16` 目录结构完全一致，均包含 `code/`、`data/`、`report/` 三个子目录
> 及一份当周 `README.md`。

---

## 四、16 周实验一览

| 周次 | 实验名称 | 主要方法 / 关键字 | 状态 |
| :--: | :-- | :-- | :--: |
| Week01 | （待填写） | 实验室安全与基本操作 | 未开始 |
| Week02 | （待填写） |  | 未开始 |
| Week03 | （待填写） |  | 未开始 |
| Week04 | （待填写） |  | 未开始 |
| Week05 | （待填写） |  | 未开始 |
| Week06 | （待填写） |  | 未开始 |
| Week07 | （待填写） |  | 未开始 |
| Week08 | （待填写） |  | 未开始 |
| Week09 | （待填写） |  | 未开始 |
| Week10 | （待填写） |  | 未开始 |
| Week11 | （待填写） |  | 未开始 |
| Week12 | （待填写） |  | 未开始 |
| Week13 | （待填写） |  | 未开始 |
| Week14 | （待填写） |  | 未开始 |
| Week15 | （待填写） |  | 未开始 |
| Week16 | （待填写） | 综合实验 / 期末考核 | 未开始 |

> 状态取值：`未开始` / `进行中` / `已完成`。

---

## 五、环境与依赖

| 项目 | 版本 / 说明 |
| :-- | :-- |
| 操作系统 | Windows 10 / 11 |
| 版本控制 | Git ≥ 2.40 |
| 编辑环境 | VS Code / CodeBuddy |
| 数据处理 | Python 3.10+（NumPy / pandas / Matplotlib / SciPy） |
| 可选工具 | Jupyter Notebook、MATLAB、Origin |

安装依赖（示例）：

```bash
python -m venv .venv
.venv\Scripts\activate
pip install numpy pandas matplotlib scipy jupyter
```

---

## 六、使用说明

克隆仓库：

```bash
git clone <仓库地址>
cd codebuddy2.0
```

标准化提交流程：

```bash
git add .
git commit -m "exp(week01): 完成第 01 周实验报告与数据处理"
git push
```

提交信息建议采用 `exp(weekXX): 简述` 格式，便于按周追溯实验进度。

---

## 七、目录命名与规范约定

1. **周目录**：统一为 `WeekNN`（两位数字，如 `Week01`）。
2. **数据文件**：原始数据放 `data/raw/`，处理中间结果放 `data/`，命名含日期与前缀。
3. **代码文件**：脚本以 `w{NN}_*.py` 命名，保证可独立运行并注明随机种子。
4. **报告文件**：命名格式 `WeekNN_实验报告_张紫萱.docx`。
5. **大文件**：超过 20 MB 的数据或二进制结果不纳入版本控制（详见 `.gitignore`），必要时改用 Git LFS。

---

<div align="center">

<sub>© 2026 张紫萱 · 南昌大学 食品科学与工程专业　|　仅供课程学习与实验记录使用</sub>

</div>
