# python_access_absolute_path


import os
from pathlib import Path


VOCAB_DIR = Path(__file__).resolve().parent.parent / "data"  # 获取绝对路径的方法
