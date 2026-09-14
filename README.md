# Size 4GB

A utility for handling and managing large files up to 4GB with efficient resource usage.

## 📦 Overview

Size 4GB is designed to manage, process, and analyze large files efficiently without consuming excessive system resources.

## ✨ Features

- **Large File Support** - Handle files up to 4GB
- **Memory Efficient** - Streaming-based processing
- **Batch Operations** - Process multiple large files
- **Progress Tracking** - Real-time progress monitoring
- **File Analysis** - Analyze file contents
- **Compression** - Compress large files
- **Splitting** - Split files into smaller chunks
- **Merging** - Merge file chunks
- **Validation** - Verify file integrity

## 📋 Requirements

- Python 3.6+
- Available disk space
- Sufficient RAM (minimum 2GB)

## 🚀 Installation

```bash
git clone https://github.com/basimbinmalikofficial-sys/size4gb.git
cd size4gb
pip install -r requirements.txt
```

## 💻 Usage

### Split File
```bash
python3 size4gb.py split -i large_file.iso -s 1GB
```

### Merge Files
```bash
python3 size4gb.py merge -i chunk_*.bin -o output_file
```

### Compress
```bash
python3 size4gb.py compress -i large_file.zip -o compressed.zip
```

### Analyze
```bash
python3 size4gb.py analyze -i large_file.bin
```

## 🔧 Configuration

```ini
[processing]
chunk_size = 100MB
max_memory = 2GB
use_compression = true

[output]
overwrite = false
create_checksum = true
```

## 📊 Performance

- **Speed**: 50-200 MB/s (depends on disk)
- **Memory**: < 500MB for 4GB files
- **Compression**: 20-60% reduction

## 📝 License

MIT License

---

**Version**: 1.0  
**Last Updated**: 2024
