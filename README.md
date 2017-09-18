# gitignore-for-Unity-of-Mac-

## 用途
UnityProject内にOSにより自動生成されるファイル（DS_STOREや.mata）を無視してGitHub上で管理できるようになる

## 使い方
* GitHubにアップロードしたいUnityProjectファイルのなかに「.gitignore」ファイルを作る
（このリポジトリをクローンしたり、コピーして使う）
* UnityEditorのProjectSettingを変更する
`Edit/ProjectSetting/Editorの[Version Control] のModeを [Visible Meta Files] に、
[Asset Serialization] のModeを [Force Text] に変更`


