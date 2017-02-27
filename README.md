# MyGitIgnore
## MyGitIgnoreについて
ベースは参考URL先の.gitignoreを使用
【追加項目一覧】
- \*.log
- \*.pyc
【追加理由】
- \*.log
各種プラグインなどが作成することがあり，大体がログとして使われるファイル．version controlされるべきではない事が多いため．  
- \*.pyc
各種プラグインで勝手に作成されることがある．本来はpythonでのコンパイルされたbytecodeのcacheであり，コミットされても被害は少ないが気分的に．  
## 参考URL
Qiita「UnityでGit管理するときの設定項目」
http://qiita.com/takish/items/08d7281eb1f303985786