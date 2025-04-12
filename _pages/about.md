---
permalink: /
title: "欢迎来到我的学术殿堂"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

2018年度山东省高等学校优秀学生，2021年山东省优秀毕业生，2022年校优秀研究生。2021年获齐鲁工业大学（山东省科学院）计算机科学与技术学士学位，2024年毕业于广西科技大学，获计算机科学与技术硕士学位。2024年7月至2025年1月在中电科新型智慧城市研究院有限公司担任算法工程师。在国际会议AAMAS（CCF B类）、期刊IEEE Transactions on Intelligent Transportation Systems、《计算机工程与应用》等上发表多篇论文，申请两项发明专利，已获授权三项软件著作权。主持广西财经大数据重点实验室开放基金项目，并参与国家自然科学基金等多项课题。获得第一届山东省高校大学生人工智能大赛团体二等奖和最佳应用奖、第十七届山东省大学生软件设计大赛三等奖和2021年RoboCup机器人世界杯中国赛仿真3D组三等奖等，持有中级软件设计师资格证书。研究方向涵盖多智能体系统的协同优化、群体智能自主决策，以及大模型与强化学习结合。

主要研究方向
======
1. 多智能体强化学习
2. 大模型智能体
3. 具身智能

论文列表 (*表示通讯作者)
======
1. **Zhang Haipeng**, Wang Zhiwen*, Li Na. MATLight: Traffic Signal Coordinated Control Algorithm based on Heterogeneous-Agent Mirror Learning with Transformer. Proceedings of the 23rd International Conference on Autonomous Agents and Multiagent Systems. 2024. (**CCF-B**, AAMAS会议)
2. **Zhang Haipeng**, Wang Zhiwen*, Yu Jilin, etc. Learning Simultaneous and Sequential Decisions in Multi-Agent Systems with Application to Traffic Signal Control. IEEE Transactions on Intelligent Transportation Systems. 2024. **in press** (**CCF-B**, IF=7.9, JCR Q1, **TOP期刊**)
3. Wanyuan Wang, **Haipeng Zhang**, Tianchi Qiao, etc. Real-Time Network-Level Traffic Signal Control An Explicit Multiagent Coordination Method. IEEE Transactions on Intelligent Transportation Systems. 2024. (**CCF-B**, IF=7.9, JCR Q1, **TOP期刊**)
4. Liu Guoqing, Wang Zhiwen, **Zhang Haipeng**, Guo Xin, Wang Yuhang, Zhang Canlong. A novel violent video detection method based on improved C3D and transfer learning. CIBDA 2022; 3rd International Conference on Computer Information and Big Data Applications. VDE, 2022.
5. 王智文，卢玉梅，**张海鹏**，庞钰丽. 多智能体序列决策的多交叉口交通信号控制方法. 计算机工程与应用, 2024. (中文核心, **CCF-C**)
6. 吴颢，**张海鹏***，谭铭威，林旭彬，黄家润. 基于新型智慧城市治理及服务的低空巡管运营模式初探. 智能城市, 2024.

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
