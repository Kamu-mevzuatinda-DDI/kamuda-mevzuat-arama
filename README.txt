kanunum-nlp-doc-analysis-dataset.csv dosyası, Doğal Dil İşleme algoritmalarından "Bidirectional Encoder Representations from Transformers(BERT)" kullanılarak  0.8 training oranı ile eğitilmiştir. Bert algoritmasının yüksek GPU 'a ihtiyaç duyuyor olması eğitimi epey zorlaştırmaktadır. Çalışma, "Google Colab" aracılığı ile gerçekleştirilmiştir.Çalışma için ihtiyaç duyulan kütüphaneler ;

import numpy as np
import pandas as pd
import string
import operator
import re
import os
import nltk
pip install simpletransformers
import ClassificationModel
import train_test_split
import accuracy_score
import metrics



şeklindedir.


