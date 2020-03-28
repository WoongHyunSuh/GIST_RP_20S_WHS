# -*- coding: utf-8 -*-
"""
Created on Sat Mar 28 20:36:05 2020

@author: WoongSuh
"""

import numpy as np

l = []
for i in range(10):
    c = 0
    for j in range(100):
        r = (((np.random.rand(1)>0.4) and (np.random.rand(1)>0.4)) or (np.random.rand(1)>0.2) or (np.random.rand(1)>0.3)) and (np.random.rand(1)>0.1)
        if r == True:
            c += 1
    print("success rate",i+1,": ", c/100)
    l.append(c/100)
print("=========================")
print("mean success rate: ", np.mean(l))




