# flutter_youtube_clone_app

flutter_youtube_clone_app project has "main.dart" as Entry Point.


![flutter_youtube_clone_app](https://user-images.githubusercontent.com/48312656/118349503-8bcb1580-b4fd-11eb-9923-51b0c0c845c1.jpg)


= = = To Generate Android release steps = = =

Generate FAT APK 
- flutter clean 
- flutter build apk --release

Generate split APK's 
- flutter clean
- flutter build apk --split-per-abi --release

= = = iOS release steps = = =

Set iOS deployment target

Follow below steps

- setup flutter sdk
- get packages
- open runner.xcworkspace from ids folder
- update version code in yaml


Bellow commands will generate the runner.app file

- flutter clean
- flutter build ios --release


Now open the xcode run/build to check if project has error

Select Product -> Archive
Follow the uploading steps



