##1.このレポジトリをローカルにクローンしてください。
##2.Alexa developerアカウントにログインし、新規スキルを作成してください（名前はなんでもいいです）
##3.スキル開発画面に入り、対話モデル>JSONエディターにatumori_skill.jsonをインポートまたは中身を貼り付けてください。
##4.AWSアカウントで適当なLambda関数を作成し、atsumori.zipをアップロードしてください。（ランタイムはpython3.8)。念のため、実行時間の上限を10秒に変更してください。
##5.Alexa　developerコンソールでエンドポイント>AWS Lambda関数用のスキルIDをコピーしてください。
##6.AWSコンソール内でLambda関数にAlexaスキルトリガーを追加します。この際に5でコピーしたスキルIDを貼り付けてください。
##7.Alexa developerコンソールや実機で試してみてください。
