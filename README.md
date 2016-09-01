# hexoHumanThem
自动静态网站：http://www.staticgen.com/
hexo themes:https://github.com/hexojs/hexo/wiki/Themes

部署步骤：
  1.删除项目根目录中的.deploy_git文件夹
  2.hexo clean
  3.hexo g
  4.hexo d                      
    部署前需要配置_config.yml
    deploy:
      type: git
      repository: git@github.com:jiuchongxiao/jiuchongxiao.github.io.git
      branch: master
      name: jiuchongxiaos
  5.访问:https://github.com/jiuchongxiao/jiuchongxiao.github.io
注意：本地访问
  1.hexo s
  2.访问：http://localhost:4000/
  
  3.hexo g生成的静态文件在本地没法访问
  
