# rasa_plaground

- <https://rasa.com/docs/rasa/installation/>

```bash
# 网络代理
export http_proxy=http://127.0.0.1:10818
export https_proxy=http://127.0.0.1:10818
# 
python3 --version
pip3 --version
# 
python3 -m venv ./venv
# Activate the virtual environment:
source ./venv/bin/activate
.\venv\Scripts\activate # windows
# Install Rasa Open Source using pip (requires Python 3.7, or 3.8).
# brew install postgresql
pip3 install -U --user pip && pip3 install rasa
# 报错：ERROR: Can not perform a '--user' install. User site-packages are not visible in this virtualenv.
# 修改 pyvenv.cfg 中 include-system-site-packages = true，然后 source ./venv/bin/activate
```

```bash
# M1 Mac 安装numpy和pandas
# https://zhuanlan.zhihu.com/p/352483773
# conda create -n py39t numpy matplotlib pandas python=3.9
conda create -n py39t python=3.9
conda install -n py39t numpy
conda install -n py39t matplotlib
conda install -n py39t pandas
```

<!-- mac 安装 rasa 失败, 修改为在 ubuntu bytedesk4 安装测试 -->

```bash
# 
python3 -m venv ./venv
# Activate the virtual environment:
source ./venv/bin/activate
# windows
.\venv\Scripts\activate
#
pip3 install jieba
# 
pip3 install -U --user pip && pip3 install rasa
```
