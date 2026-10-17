Hebei Shangxue Single-Enrollment Campus Score Analysis (static site)
河北尚学单招校区成绩分析（纯静态站点，无后端）

包含校区：
  龙泉校区  Longquan Campus   -> 龙泉校区.html
  星耀校区  Xingyao Campus    -> 星耀校区.html
  睿智校区  Ruizhi Campus     -> 未启用（index-404.html）

入口：index.html
数据：27届龙泉周测成绩.xlsx / 27届星耀周测成绩.xlsx（与页面同目录）

部署：GitHub Pages，详见 README.md
构建：python tools/build.py（两个校区页由同一母版生成，请勿手工分改）
