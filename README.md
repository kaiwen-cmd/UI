 环境需求：一台Docker,内部安装至少4个子docker，分别为umc-1,umc-2,umc-3,umc-4...................

    用途:    Casperjs_autotest :  作为运行casperjs的测试代码机器
             
    运行步骤：
            Step1:  创建外部docker: Casperjs_autotest
                    文件： ./umc_autotesting/compose/docker-compose.yml ，是创建外部docker文件

            Step2:  在 Casperjs_autotest 内创建 7个子docker

            Step3:  运行 all_start.sh 文件
