# xcode_codeSnippets
Xcode自定义代码块，方便编写代码

## 安装代码块步骤
1. git clone https://github.com/xuyuqiang/xcode_codeSnippets.git
2. cd xcode_codeSnippets
3. sh setup.sh (此步骤会覆盖xcode中名字相同的代码块)
4. 重启xcode

## 更新最新代码块到仓库步骤

1. 通过xcode编辑代码块
2. cd xcode_codeSnippets
3. sh update.sh 
4. git 提交修改记录


## 目前支持的代码块 (持续更新中) 
下面代码块说明： 快捷键 -> 具体代码块

### 创建属性相关

@strong ->	@property(nonatomic,strong) <#class#> *<#name#>;

@copy ->	@property(nonatomic,copy) NSString *<#name#>;

@weak ->	@property(nonatomic,weak) id<#protocol#> <#delegate#>;

@assign ->	@property(nonatomic,assign) NSInteger <#name#>;

@block ->	@property(nonatomic,copy) void (^<#blockName#>)(<#paramter#>);

### 创建View相关

@create ->	<#class#> *<#name#> = [[<#class#> alloc] init];

@createFrame ->	<#class#> *<#name#> = [[<#class#> alloc] initWithFrame:CGRectMake(x, y, w, h)];

### 其他

@f -> NSLog(@"%s",__FUNCTION__);