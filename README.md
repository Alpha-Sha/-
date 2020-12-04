# 词云
python词云

import stylecloud

from IPython.display import Image

stylecloud.gen_stylecloud(file_path='bloom.txt', collocations=False,

                          palette='cartocolors.qualitative.Pastel_5',  # 配色

                          font_path=r'‪C:\Windows\Fonts\msyh.ttc',  # UTF-8的txt

                          # icon_name='fab fa-qq',  # 企鹅

                          # icon_name='fas fa-plane',  # 飞机

                          # icon_name='fas fa-smile',  # 笑脸

                          # icon_name='fas fa-cloud',  # 云朵

                          icon_name='fas fa-heart',  # 爱心

                          size=800,

                          output_name='词云.png')

Image(filename='词云.png')
