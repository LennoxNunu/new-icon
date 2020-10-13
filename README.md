# new_icon

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application. What we will do is change the flutter icon manually, for both IOS and Android devices.

### Andriod

step 1 :
go to https://appicon.co drag image in the specified area, only select the android, click the generate button.

![android1](https://user-images.githubusercontent.com/68849219/95855324-7b30a200-0d58-11eb-9c68-936ccbd8ff3f.png)

step 2 :
open the following directory android/app/src/main/res

![android2 1](https://user-images.githubusercontent.com/68849219/95856203-f0e93d80-0d59-11eb-8ba4-353d23abbb42.png)

delete all the mipmap folders

![android2 2](https://user-images.githubusercontent.com/68849219/95856460-59d0b580-0d5a-11eb-8270-15a9ff17e9d3.png)

step 3 :
unzip downloaded folder from step 1. 
copy/cut all the mipmap folders to replace those deleted in step 2

![android3](https://user-images.githubusercontent.com/68849219/95857006-39edc180-0d5b-11eb-875c-00ece0fb2bef.png)

That it,we are done, we have changed the icons for android.


### IOS

step 1 : 
go to https://hotpot.ai/icon_resizer select the iOS Icon, upload image in the specified area, click the generate button

![ios1](https://user-images.githubusercontent.com/68849219/95858044-c351c380-0d5c-11eb-85e1-1feb78f2f101.png)

step 2 :
unzip the downloaded folder, open it and delete all the Apple-Watch-Icons.

![ios2](https://user-images.githubusercontent.com/68849219/95858123-dfedfb80-0d5c-11eb-9889-40a4d5f96e63.png)
 
copy all the remaining icons, open and paste icons in the following directory ios/Runner/Asset.cassets/AppIcon.appiconset

![ios3](https://user-images.githubusercontent.com/68849219/95858184-f85e1600-0d5c-11eb-95aa-d3866b54bddd.png)

identify equal size icons then delete each flutter icon before renaming your new icon with the old flutter icon name. 

![ios4](https://user-images.githubusercontent.com/68849219/95858220-09a72280-0d5d-11eb-8665-4d1c08e635e0.png)

delete the icons forwhich the name was not changed.

![ios5](https://user-images.githubusercontent.com/68849219/95858257-188dd500-0d5d-11eb-937f-9a4ec97b88ca.png)

That it,we are done, we have changed the icons for IOS.
