# 说明
findSymbol.sh脚本可以用于扫描iOS工程的源代码和framework，扫描函数符号表和数据段里的字符串，
源码文件格式范围：*.a & .m & .cpp & .c & .swift
framework格式范围：*.framework
# 使用步骤
步骤1：chmod +x findsymbol.sh
步骤2：findsymbol.sh xxx
注意：不要使用sh findsymbol.sh 执行脚本，否则结果输出为空
