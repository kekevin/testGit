总结：看graph，手动合并过来second后续的分支，但是失踪丢了7的那次提交，手动也无法合并过来
git add . && git commit -m "2" && git pull && git push
git checkout saas-test && git pull
git merge --no-ff module_v1.0.0 && git push && git checkout module_v1.0.0
1
2
3
4
5
6
8
9
1
2