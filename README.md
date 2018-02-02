# Apimgr

    ng new apimgr -si --style=scss

    cd apimgr

    npm install

    ng g m core  // 创建核心模块（在系统中只加载一次）

    ng g m shared  // 创建共享模块

    ng g c core/header --spec=false

    npm install --save @angular/material@2.0.0-beta.7
    
    npm install --save date-fns
    
    npm install --save-dev @types/date-fns
    
    ## 注册组件
    ng g c login/register --spec=false
    
    ng g m project
    
    ng g c project/project-list --spec=false
    
    ng g c project/project-item --spec=false
    
    ng g c project/new-project --spec=false
    
    ng g c project/invite --spec=false
