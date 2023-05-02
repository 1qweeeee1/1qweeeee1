- 👋 Hi, I’m @1qweeeee1
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
1qweeeee1/1qweeeee1 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
@@ -1,5 +1,5 @@
<div align=center>
  <img width=400 src="https://github.com/yangbisheng2009/nsfw-resnet/blob/master/image/nsfw-logo.jpg" >
  <img width=400 src="https://github.com/yangbisheng2009/nsfw-resnet/blob/master/image/nsfw_logo.jpg" >
</div>

# NSFW
@@ -27,6 +27,9 @@ pytorch 0.4.0
#train
python train.py --model resnet101 --epochs 90 --batch-size 512 --checkpoint ./checkpoint --data-dir ./data
#test
python test_confusion_matrix.py
#predict
python predict --model resnet101 --checkpoint ./checkpoint/x
@@ -37,7 +40,11 @@ Special thanks to the [nsfw_data_scraper](https://github.com/alexkimxyz/nsfw_dat
If you want make better result.Contact [me](https://twitter.com/yangbisheng2009).I can provide you the best training data.  

## Current status
<div align=center>
  <img width=400 src="https://github.com/yangbisheng2009/nsfw-resnet/blob/master/image/test_confusion_matrix.jpg" >
</div>

Sexy and porn is a tille similar.In my view,it does'nt matter.
## Detail
I have tried various methods include some pretrained models like resnet/inceptionv3 and data augumentation and finetuing.
