# python-snappy

## Modify

- Add library dirs to support Windows module

## Windows

### 1. Build snappy

Using MSVC compiler tools. Open `Developer Command Prompt` of Visual Studio

```bash
git clone https://github.com/google/snappy
cd snappy
cmake .
cmake --build . --config Release
```

### 2. Install python-snappy

```
set SNAPPY_DIR=<cloned-snappy-path>
python setup.py install
```

## Others

```bash
## Library up to your platform
sudo apt-get install libsnappy-dev
sudo yum install libsnappy-devel
brew install snappy

## Python wrapper
pip install python-snappy
```