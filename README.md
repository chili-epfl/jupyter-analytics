# Jupyter Analytics

This repository serves as the central hub for all components of the learning analytics system reported in our paper,
["Jupyter Analytics: A Toolkit for Collecting, Analyzing, and Visualizing Distributed Student Activity in Jupyter Notebooks"](https://doi.org/10.1145/3641554.3701971), 
published at the 56th ACM Technical Symposium on Computer Science Education (SIGCSE TS 2025).

Authors: [Zhenyu Cai](https://people.epfl.ch/zhenyu.cai), [Richard Lee Davis](https://www.kth.se/profile/rldavis), [Raphaël Mariétan](https://github.com/Rmarieta), [Roland Tormey](https://people.epfl.ch/roland.tormey?lang=en), [Pierre Dillenbourg](https://people.epfl.ch/pierre.dillenbourg?lang=en).

## Overview
Jupyter Analytics is an end-to-end solution for teachers to collect, analyze, and visualize both synchronous and asynchronous learning activities in Jupyter.
It consists of two JupyterLab extensions connected via a cloud-based backend.
On the student side, we introduce the Jupyter Analytics Telemetry extension to anonymously capture students' interaction activity with more structure and higher granularity than log data.
On the teacher side, we introduce the Jupyter Analytics Dashboard extension, which visualizes real-time student data directly in the notebook interface.
The Jupyter Analytics system was developed through an iterative co-design process with university instructors and teaching assistants, and has been implemented and tested in several university STEM courses.

![toolkit_overview](https://github.com/user-attachments/assets/8c16e388-ab94-4cd7-8a1d-a5a82c1cc3b6)

## System Architecture
The system consists of the following major components:
1. **JupyterLab Extension "Telemetry"**
* Repository: [Jupyter Analytics Telemetry](https://github.com/chili-epfl/jupyter-analytics-telemetry/)
2. **JupyterLab Extension "Dashboard"**
* Repository: [Jupyter Analytics Dashboard](https://github.com/chili-epfl/jupyter-analytics-dashboard/)
3. **Backend**
* Repository: [Jupyter Analytics Backend](https://github.com/chili-epfl/jupyter-analytics-backend/)

## Citation
If you find this repository useful, please cite our paper:
```
Cai, Z., Davis, R., Mariétan, R., Tormey, R., & Dillenbourg, P. (2025).
Jupyter Analytics: A Toolkit for Collecting, Analyzing, and Visualizing Distributed Student Activity in Jupyter Notebooks.
In Proceedings of the 56th ACM Technical Symposium on Computer Science Education (SIGCSE TS 2025).
```

## Copyright
© All rights reserved. ECOLE POLYTECHNIQUE FEDERALE DE LAUSANNE (EPFL), Switzerland, Computer-Human Interaction Lab for Learning & Instruction (CHILI), 2024

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/chili-epfl/jupyter-analytics/blob/main/LICENSE) file for details.
