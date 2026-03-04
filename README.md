# Can-AI-Code-data

This repository contains data samples to support the reproduction of the results presented in the paper:
***"Can AI Code? A Head-to-Head Showdown Between Large Language Models and Student Programmers in C"***

## Repository structure

```plain-text
├── Can-AI-Code-data
│   ├── task_{1-14} - main directory for each task selected from Dante and used in research.
│   │   ├── task_description.txt - contains the task's description in English
│   |   ├── Llama   -|
│   |   ├── Gemini   |
|   |   |            |  Each subdirectory contains sample *.url files that point to the appropriate *.html
|   |   |            |- reports (that include error messages, tests, etc., see: "Assessment Report Format"
|   |   |            |  subsection in "Student C Programming Assessment System" section in the paper).
│   |   ├── Claude   |
│   |   ├── ChatGPT -|
```

## References

```bibtex
@inproceedings{duch2018dante,
  title={Dante-Automated Assessments Tool for Students' Programming Assignments},
  author={Duch, Piotr and Jaworski, Tomasz},
  booktitle={2018 11th International Conference on Human System Interaction (HSI)},
  series={HSI '18},
  year={2018},
  month={July},
  pages={162-168},
  publisher={IEEE},
  address={Gdańsk, Poland},
  doi={10.1109/HSI.2018.8431146},
}
```



