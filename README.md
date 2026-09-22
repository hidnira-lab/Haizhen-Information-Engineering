# Haizhen (何海真): Information Engineering (NXU Double Degree)

Study notes, exercises, and exam materials for the Information Engineering
double-degree program at **Nanjing Xiaozhuang University (NXU)**, covering
Semester 5 through graduation.

何海真的信息工程双学位项目学习笔记、练习与考试资料，就读于**南京晓庄学院**，
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

## Subjects / 课程列表

Based on the School of Information Engineering curriculum for Semester 5-8.
基于信息工程学院第五至第八学期课程安排。

| Semester | Subject | Folder | Status |
| --- | --- | --- | --- |
| 5 | Chinese 1 | [`CHINESE-1`](SUBJECTS/CHINESE-1) | Not started |
| 5 | Robotics | [`ROBOTICS`](SUBJECTS/ROBOTICS) | Not started |
| 5 | Application of Database | [`APPLICATION-OF-DATABASE`](SUBJECTS/APPLICATION-OF-DATABASE) | Not started |
| 5 | Web Programming | [`WEB-PROGRAMMING`](SUBJECTS/WEB-PROGRAMMING) | Not started |
| 5 | English for IT | [`ENGLISH-FOR-IT`](SUBJECTS/ENGLISH-FOR-IT) | Not started |
| 5 | Advanced Programming | [`ADVANCED-JAVA-PROGRAMMING`](SUBJECTS/ADVANCED-JAVA-PROGRAMMING) | In progress |
| 5 | Understanding China | [`UNDERSTANDING-CHINA`](SUBJECTS/UNDERSTANDING-CHINA) | Not started |
| 6 | Human Computer Interaction | [`HUMAN-COMPUTER-INTERACTION`](SUBJECTS/HUMAN-COMPUTER-INTERACTION) | Not started |
| 6 | Data Mining | [`DATA-MINING`](SUBJECTS/DATA-MINING) | Not started |
| 6 | IOS Application Development | [`IOS-APPLICATION-DEVELOPMENT`](SUBJECTS/IOS-APPLICATION-DEVELOPMENT) | Not started |
| 6 | J2EE-Based Framework Technology | [`J2EE-BASED-FRAMEWORK-TECHNOLOGY`](SUBJECTS/J2EE-BASED-FRAMEWORK-TECHNOLOGY) | Not started |
| 6 | Software Design Patterns | [`SOFTWARE-DESIGN-PATTERNS`](SUBJECTS/SOFTWARE-DESIGN-PATTERNS) | Not started |
| 6 | Software Engineering | [`SOFTWARE-ENGINEERING`](SUBJECTS/SOFTWARE-ENGINEERING) | Not started |
| 6 | Chinese 2 | [`CHINESE-2`](SUBJECTS/CHINESE-2) | Not started |
| 7 | Selected Topics about Information Technology | [`SELECTED-TOPICS-ABOUT-INFORMATION-TECHNOLOGY`](SUBJECTS/SELECTED-TOPICS-ABOUT-INFORMATION-TECHNOLOGY) | Not started |
| 7 | Designing Mobile Applications | [`DESIGNING-MOBILE-APPLICATIONS`](SUBJECTS/DESIGNING-MOBILE-APPLICATIONS) | Not started |
| 7 | Internship and Professional Practice | [`INTERNSHIP-AND-PROFESSIONAL-PRACTICE`](SUBJECTS/INTERNSHIP-AND-PROFESSIONAL-PRACTICE) | Not started |
| 7 | Comprehensive Program Development | [`COMPREHENSIVE-PROGRAM-DEVELOPMENT`](SUBJECTS/COMPREHENSIVE-PROGRAM-DEVELOPMENT) | Not started |
| 7 | Research Methodology and Thesis Writing | [`RESEARCH-METHODOLOGY-AND-THESIS-WRITING`](SUBJECTS/RESEARCH-METHODOLOGY-AND-THESIS-WRITING) | Not started |
| 7 | Tutorial of HSK | [`TUTORIAL-OF-HSK`](SUBJECTS/TUTORIAL-OF-HSK) | Not started |
| 8 | Thesis | [`THESIS`](SUBJECTS/THESIS) | Not started |
| 8 | Thesis Seminar | [`THESIS-SEMINAR`](SUBJECTS/THESIS-SEMINAR) | Not started |

Note: the "Advanced Programming" course is tracked under the folder name
`ADVANCED-JAVA-PROGRAMMING` since its coursework is Java-based.

备注："Advanced Programming"（高级程序设计）课程对应的文件夹名为
`ADVANCED-JAVA-PROGRAMMING`，因为该课程作业内容为 Java。

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
