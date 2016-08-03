#gpg sign commit
##步骤
	
	gpg --armor --export XXXXXXXX
	把这一段输出拷到github的gpg key处
	git commit -S -m "XXX"

##用处
- 可以证明代码是你提交的
- 不可以帮助你push success
