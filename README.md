# Haizhen: Information Engineering (NXU Double Degree)

Study notes, exercises, and exam materials for the Information Engineering
double-degree program at **Nanjing Xiaozhuang University (NXU)**, covering
Semester 5 through graduation.

信息工程双学位项目的学习笔记、练习与考试资料，就读于**南京晓庄学院**，
记录范围为第五学期至毕业。

## Structure / 目录结构

```
.
├── SUBJECTS/
│   └── <SUBJECT-NAME>/
│       ├── EXERCISE/     # Coding exercises & assignments / 编程练习与作业
│       ├── MATERIAL/     # (gitignored) slides, textbooks, PDFs, kept local
│       │                 # only / 课件、教材、PDF（已忽略，仅本地保存）
│       └── EXAM/          # Exam papers & past exams / 试卷与历年考题
│
├── MATERIAL-NOTES/
│   └── <SUBJECT-NAME>/    # Personal study notes / 个人学习笔记
│
└── FOR-SUBMIT/            # (gitignored) staging folder before zipping for
                            # submission / 提交前打包用的暂存文件夹（已忽略）
```

- `<SUBJECT-NAME>` follows `UPPER-KEBAB-CASE`, matching the official course
  name (e.g. `ADVANCED-JAVA-PROGRAMMING`).
- `<SUBJECT-NAME>` 使用大写短横线命名（`UPPER-KEBAB-CASE`），与官方课程名称一致。

## Notes / 说明

`FOR-SUBMIT/` is excluded from version control. It's only a transit folder
used to stage files before compressing them into a `.zip` for coursework
submission.

`FOR-SUBMIT/` 不纳入版本控制，仅作为提交作业前打包成 `.zip` 的中转文件夹。

`SUBJECTS/<SUBJECT-NAME>/MATERIAL/` is also excluded. Slides and textbooks
are often large binary files (`.ppt`/`.pdf`) and are kept locally only.
Personal notes derived from them belong in `MATERIAL-NOTES/`, which is
tracked.

`SUBJECTS/<SUBJECT-NAME>/MATERIAL/` 同样不纳入版本控制。课件与教材多为体积较大
的二进制文件（`.ppt`/`.pdf`），仅保存在本地。由这些材料整理出的个人笔记应放在
`MATERIAL-NOTES/` 中，该目录会被跟踪。
