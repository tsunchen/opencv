# opencv
opencv on python
opencv-python
1. 下载opencv, 选择次优版本3.1.0
2. 解压缩opencv, 拷贝cv2.pyd(opencv/build/python/)到python的lib/site-packages
3. import cv2 
    print cv2.__version__
举例
>>> from matplotlib import pyplot as plt
>>> img = cv2.imread('e:\koala.jpg', 0)
>>> plt.imshow(img, cmap = 'gray', interpolation = 'bicubic')
<matplotlib.image.AxesImage object at 0x00000000046BC278>
>>> plt.xticks([]), plt.yticks([])
(([], <a list of 0 Text xticklabel objects>), ([], <a list of 0 Text yticklabel
objects>))
>>> plt.show()
