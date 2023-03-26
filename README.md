# CM_T

这个仓库主要用来我个人记录 测试智能合约 相关的内容


目录：
     一   测试智能合约的意义
     二   测试智能合约的方式
     三   测试智能合约的范围
     四   项目实操



一、为什么需要测试智能合约？
    1、  智能合约在Defi领域有大量的应用，智能合约上的漏洞会导致大量金融资产的流失，也会给项目方以及用户带来其他严重的损失。
    2、  智能合约是不可变的，一旦部署就很难再更改，虽然也有类似代理合约的升级机制，但其运行起来的成本和其他代价.
   
   
   
二、智能合约的测试方式主要分手工测试和自动化测试，这一点与web2测试基本一致

    1、  自动化测试：
        1. 使用moca测试
        1. 使用truffle套件进行测试， 在truffle使用solidity和JavaScript编写测试代码进行测试
    
    2、  手工测试：
        1. 代码走读
        
        
三、智能合约测试的范围
        1、单元测试
                1.检查函数返回值
                2.检查状态变量
        2、集成测试
                1.检查合约以及其他信息调用
                
        3、系统测试
                1.从用户角度遍历核心功能的整个过程
                2.关注用户体验
        
        
        
四、智能合约结合项目的实际操作
        分析测试需求
        1、部署测试环境
        2、部署待测示例项目
        3、编写自动化测试用例代码
        4、执行自动化测试
        5、智能合约测试报告的输出
        
        
        
        
        
