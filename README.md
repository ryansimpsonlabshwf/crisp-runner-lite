# crisp-runner-lite

Platform engineer · Java and Kafka

处理日常小任务的工具

## 用法

```bash
cat data.txt | cargo run
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 安装

```bash
git clone https://github.com/USER/crisp-runner-lite.git
cd crisp-runner-lite
cargo build --release
```

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## License

MIT
