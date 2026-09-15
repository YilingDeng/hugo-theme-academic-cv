---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      headings:
        about: 个人简介
        education: 教育背景
        interests: 研究兴趣
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    id: research
    content:
      title: '🔬 研究方向'
      subtitle: ''
      text: |-
        研究聚焦于**出行行为分析**与**交通系统优化**，具体方向包括：基于混合方法的出行行为分析、数据驱动的交通规划、通勤行为与幸福感、城市步行与骑行性、无障碍环境建设。

        **跨学科融合** —— 结合交通工程、行为地理、城乡规划、心理学（幸福感）、统计学（因果推断）等多学科视角。

        **技术驱动** —— 强调大数据与机器学习方法的应用。

        **人文关怀** —— 重视访谈等定性研究方法。

        **政策导向** —— 研究成果服务于步行友好型城市、无障碍环境建设示范城市、儿童友好城市、低碳城市等政策实践。
    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: 科研项目
      text: 主持国家自然科学基金 2 项、浙江省哲学社会科学规划课题 2 项，参与国家级课题 2 项。
      sort_by: Weight
      sort_ascending: true
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: false
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: false
  - block: markdown
    id: teaching
    content:
      title: '📚 教学课程'
      subtitle: ''
      text: |-
        **本科课程** —— 城乡道路与交通规划设计；城市规划系统工程学；城乡社会综合调查研究。

        **研究生课程** —— 城乡交通与基础设施规划；城乡规划系统工程学。
    design:
      columns: '1'
  - block: markdown
    id: papers
    content:
      title: '📄 论文成果'
      subtitle: ''
      text: |-
        第一或通讯作者发表国内外高水平期刊论文 **40 余篇**。完整论文列表请见以下学术主页：

        - [ORCID](https://orcid.org/0000-0002-6245-0352)
        - [Google Scholar（英文论文主页）](https://scholar.google.com/citations?user=VEuQqTQAAAAJ&hl=en)
        - [中国知网（中文论文主页）](https://au.cnki.net/author/personalInfo/000066222868)

        **专著**：《城市步行性理论、实证与应用》，浙江大学出版社，2024 年。获浙江省哲学社会科学优秀成果奖青年奖、钱学森城市学金奖提名奖。

        **教材**（参编 5 部）：《交通工程拓展训练与提高》《城市步行与自行车交通规划》《交通运输工程学》《城乡空间社会调查方法》等。
    design:
      columns: '1'
---
