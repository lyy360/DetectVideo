# 1. 使用 git reset（彻底回退到上一个版本，丢弃之后的提交）
（1）软重置（保留工作目录和暂存区的修改）
git reset --soft HEAD^
HEAD^ 表示上一个提交（HEAD~1 等效）
--soft 会保留你的工作目录和暂存区的修改，仅回退 commit