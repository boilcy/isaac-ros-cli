# Isaac ROS CLI

A command-line interface for managing Isaac ROS development environments.

## Installation

### Using pipx

```bash 
git clone <repository-url>
cd isaac-ros-cli
make install-pipx
```

### Using pip

```bash
pip3 install --user .
```

### Debian/Ubuntu

```bash
sudo apt-get install isaac-ros-cli
```

## Usage

```bash
# Show help
isaac-ros --help

# Initialize environment (pick a mode)
sudo isaac-ros init docker

# Activate environment
isaac-ros activate
```

## Rebuilding Debian Package

To build a new local copy:
```bash
make build
```

## Develop and build

### build wheel
```bash
make build-wheel
```

### install in edit mode
```bash
make install-local
```

### 清理构建文件
```bash
make distclean
```
