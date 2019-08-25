# numbers1
another repository
from sklearn.datasets import load_digits
import matplotlib.pyplot as ma

digits=load_digits()



for i in range(0,10):
  ma.matshow(digits.images[i])
  ma.show()
