# flask_pytest_demo

### 执行单元测试命令
pip install -i https://pypi.douban.com/simple/ pytest==4.6.5 pytest-cov==2.8.1
py.test --junit-xml=unittest.xml --cov-report=xml --cov=./ --cov-branch || true
ls -lha

### 生成的报告文件
./unittest.xml
./coverage.xml
