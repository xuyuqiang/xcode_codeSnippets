# xcode_codeSnippets
Xcode自定义代码块，方便编写代码

## 安装代码块步骤
1. git clone https://github.com/xuyuqiang/xcode_codeSnippets.git
2. cd xcode_codeSnippets
3. sh setup.sh (此步骤会覆盖xcode中名字相同的代码块)
4. 重启xcode

## 更新仓库代码步骤

1. 通过xcode编辑代码块
2. cd xcode_codeSnippets
3. sh setup.sh


## 目前支持的代码块
@strong -> @property(nonatomic,strong) <#class#> *<#name#>;

@create -> <#class#> *<#name#> = [[<#class#> alloc] init];

@createFrame ->  <#class#> *<#name#> = [[<#class#> alloc] initWithFrame:CGRectMake(x, y, w, h)];
