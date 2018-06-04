# testrepo

主要な部分を簡単に説明します。
詳細は設計書にて。

■ブランチ周り
developブランチが開発主流
各機能はさらにdevelopからfeature_xxxブランチをきって終了時にdevelopへpull requrest
※xxxは機能名

■Assetsフォルダ構成
※先日の説明から変更しました。

音素材はAudioフォルダ
画像やフォントはDesignフォルダ以下にシーン名のフォルダを
その他はProgramフォルダへ

Assets/
 └ Mix2App/
      ├ Audio/
      ├ Design/
      │    ├ SceneA/
      │    │    └ image.png
      │    └ ・・・
      └ Program/
           ├ SceneA/
           │    ├ SceneA.unity
           │    ├ Scripts/
           │    └ ・・・
           └ Lib/
              └ Scripts/
