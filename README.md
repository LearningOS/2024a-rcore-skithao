# rCore-Camp-Code-2024A

### Code
- [Soure Code of labs for 2024A](https://github.com/LearningOS/rCore-Camp-Code-2024A)
### Documents

- Concise Manual: [rCore-Camp-Guide-2024A](https://LearningOS.github.io/rCore-Camp-Guide-2024A/)

- Detail Book [rCore-Tutorial-Book-v3](https://rcore-os.github.io/rCore-Tutorial-Book-v3/)


### OS API docs
- [ch1](https://learningos.github.io/rCore-Camp-Code-2024A/ch1/os/index.html) [ch2](https://learningos.github.io/rCore-Camp-Code-2024A/ch2/os/index.html) [ch3](https://learningos.github.io/rCore-Camp-Code-2024A/ch3/os/index.html) [ch4](https://learningos.github.io/rCore-Camp-Code-2024A/ch4/os/index.html)
- [ch5](https://learningos.github.io/rCore-Camp-Code-2024A/ch5/os/index.html) [ch6](https://learningos.github.io/rCore-Camp-Code-2024A/ch6/os/index.html) [ch7](https://learningos.github.io/rCore-Camp-Code-2024A/ch7/os/index.html) [ch8](https://learningos.github.io/rCore-Camp-Code-2024A/ch8/os/index.html)

### Related Resources
- [Learning Resource](https://github.com/LearningOS/rust-based-os-comp2022/blob/main/relatedinfo.md)


### Build & Run

Replace `<YourName>` with your github ID, and replace `<Number>` with the chapter ID.

Notice: `<Number>` is chosen from `[1,2,3,4,5,6,7,8]`

```bash
# 
$ git clone git@github.com:LearningOS/2024a-rcore-<YourName>
$ cd 2024a-rcore-<YourName>
$ git clone git@github.com:LearningOS/rCore-Tutorial-Test-2024A user
$ git checkout ch<Number>
$ cd os
$ make run
```

### Grading

Replace `<YourName>` with your github ID, and replace `<Number>` with the chapter ID.

Notice: `<Number>` is chosen from `[3,4,5,6,8]`

```bash
# Replace <YourName> with your github ID 
$ git clone git@github.com:LearningOS/2024a-rcore-<YourName>
$ cd 2024a-rcore-<YourName>
$ rm -rf ci-user
$ git clone git@github.com:LearningOS/rCore-Tutorial-Checker-2024A ci-user
$ git clone git@github.com:LearningOS/rCore-Tutorial-Test-2024A ci-user/user
$ git checkout ch<Number>
$ cd ci-user
$ make test CHAPTER=<Number>
```

# rCore-Camp-Code-2024A

### 代码
- [2024A 实验室源代码](https://github.com/LearningOS/rCore-Camp-Code-2024A)
### 文档

- 简明手册: [rCore-Camp-Guide-2024A](https://LearningOS.github.io/rCore-Camp-Guide-2024A/)

- 深度书籍 [rCore-Tutorial-Book-v3](https://rcore-os.github.io/rCore-Tutorial-Book-v3/)


### 操作系统 API 文档
- [第1章](https://learningos.github.io/rCore-Camp-Code-2024A/ch1/os/index.html) [第2章](https://learningos.github.io/rCore-Camp-Code-2024A/ch2/os/index.html) [第3章](https://learningos.github.io/rCore-Camp-Code-2024A/ch3/os/index.html) [第4章](https://learningos.github.io/rCore-Camp-Code-2024A/ch4/os/index.html)
- [第5章](https://learningos.github.io/rCore-Camp-Code-2024A/ch5/os/index.html) [第6章](https://learningos.github.io/rCore-Camp-Code-2024A/ch6/os/index.html) [第7章](https://learningos.github.io/rCore-Camp-Code-2024A/ch7/os/index.html) [第8章](https://learningos.github.io/rCore-Camp-Code-2024A/ch8/os/index.html)

### 相关资源
- [学习资源](https://github.com/LearningOS/rust-based-os-comp2022/blob/main/relatedinfo.md)


### 构建与运行

将 `<YourName>` 替换为你的 GitHub ID，将 `<Number>` 替换为章节 ID。

注意: `<Number>` 可以选择 `[1,2,3,4,5,6,7,8]` 中的数字。

```bash
# 
$ git clone git@github.com:LearningOS/2024a-rcore-<YourName>
$ cd 2024a-rcore-<YourName>
$ git clone git@github.com:LearningOS/rCore-Tutorial-Test-2024A user
$ git checkout ch<Number>
$ cd os
$ make run
```

### 评分

将 `<YourName>` 替换为你的 GitHub ID，将 `<Number>` 替换为章节 ID。

注意: `<Number>` 可以选择 `[3,4,5,6,8]` 中的数字。

```bash
# Replace <YourName> with your github ID 
$ git clone git@github.com:LearningOS/2024a-rcore-<YourName>
$ cd 2024a-rcore-<YourName>
$ rm -rf ci-user
$ git clone git@github.com:LearningOS/rCore-Tutorial-Checker-2024A ci-user
$ git clone git@github.com:LearningOS/rCore-Tutorial-Test-2024A ci-user/user
$ git checkout ch<Number>
$ cd ci-user
$ make test CHAPTER=<Number>
```