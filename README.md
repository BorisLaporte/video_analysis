# Video Analysis

Source tutorial : [link](http://douglasduhaime.com/posts/identifying-similar-images-with-tensorflow.html)

## Install
```
mkvirtualenv video_analysis --python=python3
pip install -r requirement.txt
```

## To run
```
# download a collection of jpg images (or use one you have)
wget https://goo.gl/Lf9vmN -O images.tar.gz
tar -zxf images.tar.gz

# run the script on a glob of images
python classify_images.py "images/*"
```