README
=======================================================================================================

#环境依赖
##Anaconda、Pytorch

#项目结构
##README.md-本文件help
##example-模型参数转换示例
###f67_bias-0.1.pt-训练好的12层bert模型
###f67_change-经转换后模型的参数
##model_mxlite
##attention.py
##attention_softmax.py
##bert_params.py-用以转换bert模型中参数的脚本
##bert_symbols.py
##test.py
##tools.py
##pa.sh-用以自动化执行参数转换的shells脚本，输入参数为训练好模型的地址、该模型的层数、经转换模型的参数输出地址

#快速开始
##  #sh pa.sh
##根据提示输入参数（中间用空格分隔），得到转换后模型的参数

#Contributions
##压缩模型的大小，便于后续参数处理
