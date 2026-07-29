# Student Manager

一个使用 Python 编写的命令行学生管理系统。

## 功能

- 添加学生
- 查看学生
- 删除学生
- 修改学生
- JSON数据持久化
- 数据校验

## 技术栈

- Python 3.12
- uv
- pytest
- ruff
- black

## 项目结构
student-manager
│
├── src
│ └── student_manager
│ ├── main.py
│ ├── manager.py
│ ├── student.py
│ └── database.py
│
├── tests
│
├── data
│
├── pyproject.toml
└── README.md


## 运行

安装依赖：

```bash
uv sync```

运行：

```uv run python -m student_manager.main```

测试：

```uv run pytest```

代码检查：

```uv run ruff check .```

格式化：

```uv run black .```
