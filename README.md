# Universal Style Transfer
This is the Pytorch implementation which can support the latest pytorch version(1.11.0). This is based on the work by [Pietro Battilana](https://github.com/pietrocarbo/deep-transfer)

## Quick start
Make sure the images in "images/content" have the corresponding in "images/style". The result will save in "samples" folder.
```
python  WCT.py --alpha 0.2
```
Alpha is a study rate.

## Result
### 1.
<img src="https://user-images.githubusercontent.com/51788243/170738113-5f7be3f5-21d3-4b9e-b0b0-d8f52b22d1f2.jpg" width=300> <img src="https://user-images.githubusercontent.com/51788243/170738286-9f90007c-18fb-4efd-bee6-3a2b2ebef504.jpg" width=300> <img src="https://user-images.githubusercontent.com/51788243/170738091-aaaeb4d7-4b6b-4fe4-a8fd-628fea75d182.jpg" width=300>
### 2.
<img src="https://user-images.githubusercontent.com/51788243/170739459-3cb57787-3999-4f1c-8b9d-4234fa87999b.jpg" width=300> <img src="https://user-images.githubusercontent.com/51788243/170739517-8b891be1-2da6-4c7c-9351-8eb3b05c31bc.jpg" width=300> <img src="https://user-images.githubusercontent.com/51788243/170739531-976b6ae0-9d8b-49a0-8d43-067b8f796269.jpg" width=300>
