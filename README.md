# Projeto-Classifica-o
Projeto de classificação de imagens para a disciplina de modelos preditivos conexionistas

# Projeto Final - Modelos Preditivos Conexionistas

### Nome do aluno: Bruno Wanderley de Freitas

|**Tipo de Projeto**|**Modelo Selecionado**|**Linguagem**|
|--|--|--|
|Classificação de Imagens|MobileNetV2|Tensorflow|

## Performance

O modelo treinado possui performance de **51.2%**.

### Output do bloco de treinamento

<details>
Epoch 1/830
6/6 [==============================] - ETA: 0s - loss: 0.5138 - accuracy: 0.4242
Epoch 1: saving model to training_1/cp.ckpt
6/6 [==============================] - 13s 977ms/step - loss: 0.5138 - accuracy: 0.4242 - val_loss: 0.3324 - val_accuracy: 0.3500
Epoch 2/830
6/6 [==============================] - ETA: 0s - loss: 0.4190 - accuracy: 0.2697
Epoch 2: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 811ms/step - loss: 0.4190 - accuracy: 0.2697 - val_loss: 0.2231 - val_accuracy: 0.2250
Epoch 3/830
6/6 [==============================] - ETA: 0s - loss: 0.3617 - accuracy: 0.1273
Epoch 3: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 806ms/step - loss: 0.3617 - accuracy: 0.1273 - val_loss: 0.1402 - val_accuracy: 0.1750
Epoch 4/830
6/6 [==============================] - ETA: 0s - loss: 0.3196 - accuracy: 0.0758
Epoch 4: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 818ms/step - loss: 0.3196 - accuracy: 0.0758 - val_loss: 0.1090 - val_accuracy: 0.1500
Epoch 5/830
6/6 [==============================] - ETA: 0s - loss: 0.2997 - accuracy: 0.0606
Epoch 5: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 881ms/step - loss: 0.2997 - accuracy: 0.0606 - val_loss: 0.0554 - val_accuracy: 0.0750
Epoch 6/830
6/6 [==============================] - ETA: 0s - loss: 0.2710 - accuracy: 0.0424
Epoch 6: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 808ms/step - loss: 0.2710 - accuracy: 0.0424 - val_loss: -0.0064 - val_accuracy: 0.0500
Epoch 7/830
6/6 [==============================] - ETA: 0s - loss: 0.2415 - accuracy: 0.0303
Epoch 7: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: 0.2415 - accuracy: 0.0303 - val_loss: -0.0447 - val_accuracy: 0.0500
Epoch 8/830
6/6 [==============================] - ETA: 0s - loss: 0.2215 - accuracy: 0.0273
Epoch 8: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 794ms/step - loss: 0.2215 - accuracy: 0.0273 - val_loss: -0.0837 - val_accuracy: 0.0000e+00
Epoch 9/830
6/6 [==============================] - ETA: 0s - loss: 0.2006 - accuracy: 0.0273
Epoch 9: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: 0.2006 - accuracy: 0.0273 - val_loss: -0.1231 - val_accuracy: 0.0000e+00
Epoch 10/830
6/6 [==============================] - ETA: 0s - loss: 0.1818 - accuracy: 0.0273
Epoch 10: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 813ms/step - loss: 0.1818 - accuracy: 0.0273 - val_loss: -0.1484 - val_accuracy: 0.0000e+00
Epoch 11/830
6/6 [==============================] - ETA: 0s - loss: 0.1653 - accuracy: 0.0273
Epoch 11: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 807ms/step - loss: 0.1653 - accuracy: 0.0273 - val_loss: -0.1882 - val_accuracy: 0.0000e+00
Epoch 12/830
6/6 [==============================] - ETA: 0s - loss: 0.1456 - accuracy: 0.0273
Epoch 12: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 798ms/step - loss: 0.1456 - accuracy: 0.0273 - val_loss: -0.2247 - val_accuracy: 0.0000e+00
Epoch 13/830
6/6 [==============================] - ETA: 0s - loss: 0.1282 - accuracy: 0.0273
Epoch 13: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 826ms/step - loss: 0.1282 - accuracy: 0.0273 - val_loss: -0.2455 - val_accuracy: 0.0000e+00
Epoch 14/830
6/6 [==============================] - ETA: 0s - loss: 0.1131 - accuracy: 0.0273
Epoch 14: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 767ms/step - loss: 0.1131 - accuracy: 0.0273 - val_loss: -0.2837 - val_accuracy: 0.0000e+00
Epoch 15/830
6/6 [==============================] - ETA: 0s - loss: 0.0958 - accuracy: 0.0273
Epoch 15: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: 0.0958 - accuracy: 0.0273 - val_loss: -0.3007 - val_accuracy: 0.0000e+00
Epoch 16/830
6/6 [==============================] - ETA: 0s - loss: 0.0827 - accuracy: 0.0273
Epoch 16: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: 0.0827 - accuracy: 0.0273 - val_loss: -0.3105 - val_accuracy: 0.0000e+00
Epoch 17/830
6/6 [==============================] - ETA: 0s - loss: 0.0700 - accuracy: 0.0273
Epoch 17: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: 0.0700 - accuracy: 0.0273 - val_loss: -0.3370 - val_accuracy: 0.0000e+00
Epoch 18/830
6/6 [==============================] - ETA: 0s - loss: 0.0553 - accuracy: 0.0273
Epoch 18: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 788ms/step - loss: 0.0553 - accuracy: 0.0273 - val_loss: -0.3725 - val_accuracy: 0.0000e+00
Epoch 19/830
6/6 [==============================] - ETA: 0s - loss: 0.0405 - accuracy: 0.0273
Epoch 19: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 766ms/step - loss: 0.0405 - accuracy: 0.0273 - val_loss: -0.3891 - val_accuracy: 0.0000e+00
Epoch 20/830
6/6 [==============================] - ETA: 0s - loss: 0.0299 - accuracy: 0.0273
Epoch 20: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: 0.0299 - accuracy: 0.0273 - val_loss: -0.4166 - val_accuracy: 0.0000e+00
Epoch 21/830
6/6 [==============================] - ETA: 0s - loss: 0.0149 - accuracy: 0.0273
Epoch 21: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 773ms/step - loss: 0.0149 - accuracy: 0.0273 - val_loss: -0.4385 - val_accuracy: 0.0000e+00
Epoch 22/830
6/6 [==============================] - ETA: 0s - loss: 0.0031 - accuracy: 0.0273
Epoch 22: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: 0.0031 - accuracy: 0.0273 - val_loss: -0.4570 - val_accuracy: 0.0000e+00
Epoch 23/830
6/6 [==============================] - ETA: 0s - loss: -0.0076 - accuracy: 0.0273
Epoch 23: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 776ms/step - loss: -0.0076 - accuracy: 0.0273 - val_loss: -0.4631 - val_accuracy: 0.0000e+00
Epoch 24/830
6/6 [==============================] - ETA: 0s - loss: -0.0185 - accuracy: 0.0273
Epoch 24: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -0.0185 - accuracy: 0.0273 - val_loss: -0.4706 - val_accuracy: 0.0000e+00
Epoch 25/830
6/6 [==============================] - ETA: 0s - loss: -0.0308 - accuracy: 0.0273
Epoch 25: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -0.0308 - accuracy: 0.0273 - val_loss: -0.4884 - val_accuracy: 0.0000e+00
Epoch 26/830
6/6 [==============================] - ETA: 0s - loss: -0.0428 - accuracy: 0.0273
Epoch 26: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 804ms/step - loss: -0.0428 - accuracy: 0.0273 - val_loss: -0.5016 - val_accuracy: 0.0000e+00
Epoch 27/830
6/6 [==============================] - ETA: 0s - loss: -0.0557 - accuracy: 0.0273
Epoch 27: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -0.0557 - accuracy: 0.0273 - val_loss: -0.5148 - val_accuracy: 0.0000e+00
Epoch 28/830
6/6 [==============================] - ETA: 0s - loss: -0.0673 - accuracy: 0.0273
Epoch 28: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 779ms/step - loss: -0.0673 - accuracy: 0.0273 - val_loss: -0.5281 - val_accuracy: 0.0000e+00
Epoch 29/830
6/6 [==============================] - ETA: 0s - loss: -0.0814 - accuracy: 0.0273
Epoch 29: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -0.0814 - accuracy: 0.0273 - val_loss: -0.5488 - val_accuracy: 0.0000e+00
Epoch 30/830
6/6 [==============================] - ETA: 0s - loss: -0.0939 - accuracy: 0.0273
Epoch 30: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -0.0939 - accuracy: 0.0273 - val_loss: -0.5647 - val_accuracy: 0.0000e+00
Epoch 31/830
6/6 [==============================] - ETA: 0s - loss: -0.1077 - accuracy: 0.0273
Epoch 31: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -0.1077 - accuracy: 0.0273 - val_loss: -0.5684 - val_accuracy: 0.0000e+00
Epoch 32/830
6/6 [==============================] - ETA: 0s - loss: -0.1202 - accuracy: 0.0273
Epoch 32: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 781ms/step - loss: -0.1202 - accuracy: 0.0273 - val_loss: -0.5861 - val_accuracy: 0.0000e+00
Epoch 33/830
6/6 [==============================] - ETA: 0s - loss: -0.1339 - accuracy: 0.0273
Epoch 33: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -0.1339 - accuracy: 0.0273 - val_loss: -0.6129 - val_accuracy: 0.0000e+00
Epoch 34/830
6/6 [==============================] - ETA: 0s - loss: -0.1450 - accuracy: 0.0273
Epoch 34: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -0.1450 - accuracy: 0.0273 - val_loss: -0.6065 - val_accuracy: 0.0000e+00
Epoch 35/830
6/6 [==============================] - ETA: 0s - loss: -0.1546 - accuracy: 0.0273
Epoch 35: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -0.1546 - accuracy: 0.0273 - val_loss: -0.6091 - val_accuracy: 0.0000e+00
Epoch 36/830
6/6 [==============================] - ETA: 0s - loss: -0.1645 - accuracy: 0.0273
Epoch 36: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: -0.1645 - accuracy: 0.0273 - val_loss: -0.6225 - val_accuracy: 0.0000e+00
Epoch 37/830
6/6 [==============================] - ETA: 0s - loss: -0.1754 - accuracy: 0.0273
Epoch 37: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -0.1754 - accuracy: 0.0273 - val_loss: -0.6311 - val_accuracy: 0.0000e+00
Epoch 38/830
6/6 [==============================] - ETA: 0s - loss: -0.1866 - accuracy: 0.0273
Epoch 38: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: -0.1866 - accuracy: 0.0273 - val_loss: -0.6516 - val_accuracy: 0.0000e+00
Epoch 39/830
6/6 [==============================] - ETA: 0s - loss: -0.1980 - accuracy: 0.0273
Epoch 39: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -0.1980 - accuracy: 0.0273 - val_loss: -0.6738 - val_accuracy: 0.0000e+00
Epoch 40/830
6/6 [==============================] - ETA: 0s - loss: -0.2095 - accuracy: 0.0273
Epoch 40: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -0.2095 - accuracy: 0.0273 - val_loss: -0.6812 - val_accuracy: 0.0000e+00
Epoch 41/830
6/6 [==============================] - ETA: 0s - loss: -0.2208 - accuracy: 0.0273
Epoch 41: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -0.2208 - accuracy: 0.0273 - val_loss: -0.6897 - val_accuracy: 0.0000e+00
Epoch 42/830
6/6 [==============================] - ETA: 0s - loss: -0.2318 - accuracy: 0.0273
Epoch 42: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 800ms/step - loss: -0.2318 - accuracy: 0.0273 - val_loss: -0.6932 - val_accuracy: 0.0000e+00
Epoch 43/830
6/6 [==============================] - ETA: 0s - loss: -0.2439 - accuracy: 0.0273
Epoch 43: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -0.2439 - accuracy: 0.0273 - val_loss: -0.7189 - val_accuracy: 0.0000e+00
Epoch 44/830
6/6 [==============================] - ETA: 0s - loss: -0.2544 - accuracy: 0.0273
Epoch 44: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -0.2544 - accuracy: 0.0273 - val_loss: -0.7252 - val_accuracy: 0.0000e+00
Epoch 45/830
6/6 [==============================] - ETA: 0s - loss: -0.2631 - accuracy: 0.0273
Epoch 45: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -0.2631 - accuracy: 0.0273 - val_loss: -0.7401 - val_accuracy: 0.0000e+00
Epoch 46/830
6/6 [==============================] - ETA: 0s - loss: -0.2746 - accuracy: 0.0273
Epoch 46: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -0.2746 - accuracy: 0.0273 - val_loss: -0.7497 - val_accuracy: 0.0000e+00
Epoch 47/830
6/6 [==============================] - ETA: 0s - loss: -0.2859 - accuracy: 0.0273
Epoch 47: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 811ms/step - loss: -0.2859 - accuracy: 0.0273 - val_loss: -0.7644 - val_accuracy: 0.0000e+00
Epoch 48/830
6/6 [==============================] - ETA: 0s - loss: -0.2970 - accuracy: 0.0273
Epoch 48: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -0.2970 - accuracy: 0.0273 - val_loss: -0.7729 - val_accuracy: 0.0000e+00
Epoch 49/830
6/6 [==============================] - ETA: 0s - loss: -0.3073 - accuracy: 0.0273
Epoch 49: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -0.3073 - accuracy: 0.0273 - val_loss: -0.7816 - val_accuracy: 0.0000e+00
Epoch 50/830
6/6 [==============================] - ETA: 0s - loss: -0.3204 - accuracy: 0.0273
Epoch 50: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -0.3204 - accuracy: 0.0273 - val_loss: -0.7778 - val_accuracy: 0.0000e+00
Epoch 51/830
6/6 [==============================] - ETA: 0s - loss: -0.3304 - accuracy: 0.0273
Epoch 51: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -0.3304 - accuracy: 0.0273 - val_loss: -0.7867 - val_accuracy: 0.0000e+00
Epoch 52/830
6/6 [==============================] - ETA: 0s - loss: -0.3418 - accuracy: 0.0273
Epoch 52: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -0.3418 - accuracy: 0.0273 - val_loss: -0.7932 - val_accuracy: 0.0000e+00
Epoch 53/830
6/6 [==============================] - ETA: 0s - loss: -0.3518 - accuracy: 0.0273
Epoch 53: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 807ms/step - loss: -0.3518 - accuracy: 0.0273 - val_loss: -0.7959 - val_accuracy: 0.0000e+00
Epoch 54/830
6/6 [==============================] - ETA: 0s - loss: -0.3634 - accuracy: 0.0273
Epoch 54: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -0.3634 - accuracy: 0.0273 - val_loss: -0.7960 - val_accuracy: 0.0000e+00
Epoch 55/830
6/6 [==============================] - ETA: 0s - loss: -0.3737 - accuracy: 0.0273
Epoch 55: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -0.3737 - accuracy: 0.0273 - val_loss: -0.8043 - val_accuracy: 0.0000e+00
Epoch 56/830
6/6 [==============================] - ETA: 0s - loss: -0.3836 - accuracy: 0.0273
Epoch 56: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: -0.3836 - accuracy: 0.0273 - val_loss: -0.8052 - val_accuracy: 0.0000e+00
Epoch 57/830
6/6 [==============================] - ETA: 0s - loss: -0.3947 - accuracy: 0.0303
Epoch 57: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -0.3947 - accuracy: 0.0303 - val_loss: -0.8178 - val_accuracy: 0.0000e+00
Epoch 58/830
6/6 [==============================] - ETA: 0s - loss: -0.4069 - accuracy: 0.0303
Epoch 58: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -0.4069 - accuracy: 0.0303 - val_loss: -0.8410 - val_accuracy: 0.0000e+00
Epoch 59/830
6/6 [==============================] - ETA: 0s - loss: -0.4188 - accuracy: 0.0303
Epoch 59: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -0.4188 - accuracy: 0.0303 - val_loss: -0.8431 - val_accuracy: 0.0000e+00
Epoch 60/830
6/6 [==============================] - ETA: 0s - loss: -0.4306 - accuracy: 0.0273
Epoch 60: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -0.4306 - accuracy: 0.0273 - val_loss: -0.8452 - val_accuracy: 0.0000e+00
Epoch 61/830
6/6 [==============================] - ETA: 0s - loss: -0.4406 - accuracy: 0.0273
Epoch 61: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -0.4406 - accuracy: 0.0273 - val_loss: -0.8674 - val_accuracy: 0.0000e+00
Epoch 62/830
6/6 [==============================] - ETA: 0s - loss: -0.4523 - accuracy: 0.0273
Epoch 62: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 799ms/step - loss: -0.4523 - accuracy: 0.0273 - val_loss: -0.8737 - val_accuracy: 0.0000e+00
Epoch 63/830
6/6 [==============================] - ETA: 0s - loss: -0.4635 - accuracy: 0.0273
Epoch 63: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -0.4635 - accuracy: 0.0273 - val_loss: -0.8973 - val_accuracy: 0.0000e+00
Epoch 64/830
6/6 [==============================] - ETA: 0s - loss: -0.4751 - accuracy: 0.0273
Epoch 64: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -0.4751 - accuracy: 0.0273 - val_loss: -0.9056 - val_accuracy: 0.0000e+00
Epoch 65/830
6/6 [==============================] - ETA: 0s - loss: -0.4861 - accuracy: 0.0273
Epoch 65: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -0.4861 - accuracy: 0.0273 - val_loss: -0.9140 - val_accuracy: 0.0000e+00
Epoch 66/830
6/6 [==============================] - ETA: 0s - loss: -0.4970 - accuracy: 0.0303
Epoch 66: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 822ms/step - loss: -0.4970 - accuracy: 0.0303 - val_loss: -0.9236 - val_accuracy: 0.0000e+00
Epoch 67/830
6/6 [==============================] - ETA: 0s - loss: -0.5087 - accuracy: 0.0303
Epoch 67: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -0.5087 - accuracy: 0.0303 - val_loss: -0.9468 - val_accuracy: 0.0000e+00
Epoch 68/830
6/6 [==============================] - ETA: 0s - loss: -0.5207 - accuracy: 0.0303
Epoch 68: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -0.5207 - accuracy: 0.0303 - val_loss: -0.9550 - val_accuracy: 0.0000e+00
Epoch 69/830
6/6 [==============================] - ETA: 0s - loss: -0.5316 - accuracy: 0.0303
Epoch 69: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -0.5316 - accuracy: 0.0303 - val_loss: -0.9565 - val_accuracy: 0.0000e+00
Epoch 70/830
6/6 [==============================] - ETA: 0s - loss: -0.5418 - accuracy: 0.0303
Epoch 70: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 753ms/step - loss: -0.5418 - accuracy: 0.0303 - val_loss: -0.9675 - val_accuracy: 0.0000e+00
Epoch 71/830
6/6 [==============================] - ETA: 0s - loss: -0.5536 - accuracy: 0.0303
Epoch 71: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -0.5536 - accuracy: 0.0303 - val_loss: -0.9897 - val_accuracy: 0.0000e+00
Epoch 72/830
6/6 [==============================] - ETA: 0s - loss: -0.5653 - accuracy: 0.0303
Epoch 72: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 792ms/step - loss: -0.5653 - accuracy: 0.0303 - val_loss: -1.0061 - val_accuracy: 0.0000e+00
Epoch 73/830
6/6 [==============================] - ETA: 0s - loss: -0.5758 - accuracy: 0.0303
Epoch 73: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -0.5758 - accuracy: 0.0303 - val_loss: -1.0139 - val_accuracy: 0.0000e+00
Epoch 74/830
6/6 [==============================] - ETA: 0s - loss: -0.5873 - accuracy: 0.0303
Epoch 74: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -0.5873 - accuracy: 0.0303 - val_loss: -1.0124 - val_accuracy: 0.0000e+00
Epoch 75/830
6/6 [==============================] - ETA: 0s - loss: -0.5960 - accuracy: 0.0303
Epoch 75: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -0.5960 - accuracy: 0.0303 - val_loss: -1.0280 - val_accuracy: 0.0000e+00
Epoch 76/830
6/6 [==============================] - ETA: 0s - loss: -0.6075 - accuracy: 0.0303
Epoch 76: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -0.6075 - accuracy: 0.0303 - val_loss: -1.0421 - val_accuracy: 0.0000e+00
Epoch 77/830
6/6 [==============================] - ETA: 0s - loss: -0.6174 - accuracy: 0.0303
Epoch 77: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 806ms/step - loss: -0.6174 - accuracy: 0.0303 - val_loss: -1.0590 - val_accuracy: 0.0000e+00
Epoch 78/830
6/6 [==============================] - ETA: 0s - loss: -0.6297 - accuracy: 0.0303
Epoch 78: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -0.6297 - accuracy: 0.0303 - val_loss: -1.0733 - val_accuracy: 0.0000e+00
Epoch 79/830
6/6 [==============================] - ETA: 0s - loss: -0.6396 - accuracy: 0.0303
Epoch 79: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -0.6396 - accuracy: 0.0303 - val_loss: -1.0707 - val_accuracy: 0.0000e+00
Epoch 80/830
6/6 [==============================] - ETA: 0s - loss: -0.6499 - accuracy: 0.0333
Epoch 80: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -0.6499 - accuracy: 0.0333 - val_loss: -1.0894 - val_accuracy: 0.0000e+00
Epoch 81/830
6/6 [==============================] - ETA: 0s - loss: -0.6603 - accuracy: 0.0333
Epoch 81: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 852ms/step - loss: -0.6603 - accuracy: 0.0333 - val_loss: -1.0957 - val_accuracy: 0.0000e+00
Epoch 82/830
6/6 [==============================] - ETA: 0s - loss: -0.6716 - accuracy: 0.0364
Epoch 82: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 771ms/step - loss: -0.6716 - accuracy: 0.0364 - val_loss: -1.1040 - val_accuracy: 0.0000e+00
Epoch 83/830
6/6 [==============================] - ETA: 0s - loss: -0.6829 - accuracy: 0.0364
Epoch 83: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 815ms/step - loss: -0.6829 - accuracy: 0.0364 - val_loss: -1.1164 - val_accuracy: 0.0000e+00
Epoch 84/830
6/6 [==============================] - ETA: 0s - loss: -0.6950 - accuracy: 0.0364
Epoch 84: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 789ms/step - loss: -0.6950 - accuracy: 0.0364 - val_loss: -1.1337 - val_accuracy: 0.0000e+00
Epoch 85/830
6/6 [==============================] - ETA: 0s - loss: -0.7074 - accuracy: 0.0364
Epoch 85: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -0.7074 - accuracy: 0.0364 - val_loss: -1.1414 - val_accuracy: 0.0000e+00
Epoch 86/830
6/6 [==============================] - ETA: 0s - loss: -0.7165 - accuracy: 0.0364
Epoch 86: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -0.7165 - accuracy: 0.0364 - val_loss: -1.1377 - val_accuracy: 0.0000e+00
Epoch 87/830
6/6 [==============================] - ETA: 0s - loss: -0.7280 - accuracy: 0.0364
Epoch 87: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 783ms/step - loss: -0.7280 - accuracy: 0.0364 - val_loss: -1.1496 - val_accuracy: 0.0000e+00
Epoch 88/830
6/6 [==============================] - ETA: 0s - loss: -0.7364 - accuracy: 0.0364
Epoch 88: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -0.7364 - accuracy: 0.0364 - val_loss: -1.1569 - val_accuracy: 0.0000e+00
Epoch 89/830
6/6 [==============================] - ETA: 0s - loss: -0.7471 - accuracy: 0.0364
Epoch 89: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -0.7471 - accuracy: 0.0364 - val_loss: -1.1757 - val_accuracy: 0.0000e+00
Epoch 90/830
6/6 [==============================] - ETA: 0s - loss: -0.7583 - accuracy: 0.0364
Epoch 90: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -0.7583 - accuracy: 0.0364 - val_loss: -1.1846 - val_accuracy: 0.0000e+00
Epoch 91/830
6/6 [==============================] - ETA: 0s - loss: -0.7690 - accuracy: 0.0364
Epoch 91: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 824ms/step - loss: -0.7690 - accuracy: 0.0364 - val_loss: -1.1953 - val_accuracy: 0.0000e+00
Epoch 92/830
6/6 [==============================] - ETA: 0s - loss: -0.7800 - accuracy: 0.0364
Epoch 92: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -0.7800 - accuracy: 0.0364 - val_loss: -1.1925 - val_accuracy: 0.0000e+00
Epoch 93/830
6/6 [==============================] - ETA: 0s - loss: -0.7908 - accuracy: 0.0364
Epoch 93: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -0.7908 - accuracy: 0.0364 - val_loss: -1.2051 - val_accuracy: 0.0000e+00
Epoch 94/830
6/6 [==============================] - ETA: 0s - loss: -0.8008 - accuracy: 0.0364
Epoch 94: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -0.8008 - accuracy: 0.0364 - val_loss: -1.2050 - val_accuracy: 0.0000e+00
Epoch 95/830
6/6 [==============================] - ETA: 0s - loss: -0.8091 - accuracy: 0.0394
Epoch 95: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 808ms/step - loss: -0.8091 - accuracy: 0.0394 - val_loss: -1.2144 - val_accuracy: 0.0000e+00
Epoch 96/830
6/6 [==============================] - ETA: 0s - loss: -0.8205 - accuracy: 0.0394
Epoch 96: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 755ms/step - loss: -0.8205 - accuracy: 0.0394 - val_loss: -1.2174 - val_accuracy: 0.0000e+00
Epoch 97/830
6/6 [==============================] - ETA: 0s - loss: -0.8295 - accuracy: 0.0394
Epoch 97: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -0.8295 - accuracy: 0.0394 - val_loss: -1.2141 - val_accuracy: 0.0000e+00
Epoch 98/830
6/6 [==============================] - ETA: 0s - loss: -0.8372 - accuracy: 0.0455
Epoch 98: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -0.8372 - accuracy: 0.0455 - val_loss: -1.2222 - val_accuracy: 0.0000e+00
Epoch 99/830
6/6 [==============================] - ETA: 0s - loss: -0.8469 - accuracy: 0.0455
Epoch 99: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -0.8469 - accuracy: 0.0455 - val_loss: -1.2386 - val_accuracy: 0.0000e+00
Epoch 100/830
6/6 [==============================] - ETA: 0s - loss: -0.8575 - accuracy: 0.0455
Epoch 100: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 821ms/step - loss: -0.8575 - accuracy: 0.0455 - val_loss: -1.2518 - val_accuracy: 0.0000e+00
Epoch 101/830
6/6 [==============================] - ETA: 0s - loss: -0.8683 - accuracy: 0.0394
Epoch 101: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -0.8683 - accuracy: 0.0394 - val_loss: -1.2721 - val_accuracy: 0.0000e+00
Epoch 102/830
6/6 [==============================] - ETA: 0s - loss: -0.8805 - accuracy: 0.0394
Epoch 102: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -0.8805 - accuracy: 0.0394 - val_loss: -1.2873 - val_accuracy: 0.0000e+00
Epoch 103/830
6/6 [==============================] - ETA: 0s - loss: -0.8911 - accuracy: 0.0394
Epoch 103: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -0.8911 - accuracy: 0.0394 - val_loss: -1.2951 - val_accuracy: 0.0000e+00
Epoch 104/830
6/6 [==============================] - ETA: 0s - loss: -0.9018 - accuracy: 0.0455
Epoch 104: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 796ms/step - loss: -0.9018 - accuracy: 0.0455 - val_loss: -1.3056 - val_accuracy: 0.0000e+00
Epoch 105/830
6/6 [==============================] - ETA: 0s - loss: -0.9124 - accuracy: 0.0424
Epoch 105: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -0.9124 - accuracy: 0.0424 - val_loss: -1.3142 - val_accuracy: 0.0000e+00
Epoch 106/830
6/6 [==============================] - ETA: 0s - loss: -0.9249 - accuracy: 0.0455
Epoch 106: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 822ms/step - loss: -0.9249 - accuracy: 0.0455 - val_loss: -1.3368 - val_accuracy: 0.0000e+00
Epoch 107/830
6/6 [==============================] - ETA: 0s - loss: -0.9368 - accuracy: 0.0424
Epoch 107: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -0.9368 - accuracy: 0.0424 - val_loss: -1.3529 - val_accuracy: 0.0000e+00
Epoch 108/830
6/6 [==============================] - ETA: 0s - loss: -0.9484 - accuracy: 0.0424
Epoch 108: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -0.9484 - accuracy: 0.0424 - val_loss: -1.3676 - val_accuracy: 0.0000e+00
Epoch 109/830
6/6 [==============================] - ETA: 0s - loss: -0.9594 - accuracy: 0.0424
Epoch 109: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -0.9594 - accuracy: 0.0424 - val_loss: -1.3710 - val_accuracy: 0.0000e+00
Epoch 110/830
6/6 [==============================] - ETA: 0s - loss: -0.9706 - accuracy: 0.0424
Epoch 110: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -0.9706 - accuracy: 0.0424 - val_loss: -1.3827 - val_accuracy: 0.0000e+00
Epoch 111/830
6/6 [==============================] - ETA: 0s - loss: -0.9827 - accuracy: 0.0424
Epoch 111: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -0.9827 - accuracy: 0.0424 - val_loss: -1.4009 - val_accuracy: 0.0000e+00
Epoch 112/830
6/6 [==============================] - ETA: 0s - loss: -0.9937 - accuracy: 0.0424
Epoch 112: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -0.9937 - accuracy: 0.0424 - val_loss: -1.4157 - val_accuracy: 0.0000e+00
Epoch 113/830
6/6 [==============================] - ETA: 0s - loss: -1.0049 - accuracy: 0.0424
Epoch 113: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -1.0049 - accuracy: 0.0424 - val_loss: -1.4117 - val_accuracy: 0.0000e+00
Epoch 114/830
6/6 [==============================] - ETA: 0s - loss: -1.0153 - accuracy: 0.0485
Epoch 114: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -1.0153 - accuracy: 0.0485 - val_loss: -1.4289 - val_accuracy: 0.0000e+00
Epoch 115/830
6/6 [==============================] - ETA: 0s - loss: -1.0245 - accuracy: 0.0455
Epoch 115: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 814ms/step - loss: -1.0245 - accuracy: 0.0455 - val_loss: -1.4403 - val_accuracy: 0.0000e+00
Epoch 116/830
6/6 [==============================] - ETA: 0s - loss: -1.0348 - accuracy: 0.0455
Epoch 116: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -1.0348 - accuracy: 0.0455 - val_loss: -1.4502 - val_accuracy: 0.0000e+00
Epoch 117/830
6/6 [==============================] - ETA: 0s - loss: -1.0454 - accuracy: 0.0424
Epoch 117: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -1.0454 - accuracy: 0.0424 - val_loss: -1.4634 - val_accuracy: 0.0000e+00
Epoch 118/830
6/6 [==============================] - ETA: 0s - loss: -1.0571 - accuracy: 0.0455
Epoch 118: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -1.0571 - accuracy: 0.0455 - val_loss: -1.4638 - val_accuracy: 0.0000e+00
Epoch 119/830
6/6 [==============================] - ETA: 0s - loss: -1.0651 - accuracy: 0.0485
Epoch 119: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 816ms/step - loss: -1.0651 - accuracy: 0.0485 - val_loss: -1.4658 - val_accuracy: 0.0000e+00
Epoch 120/830
6/6 [==============================] - ETA: 0s - loss: -1.0767 - accuracy: 0.0485
Epoch 120: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -1.0767 - accuracy: 0.0485 - val_loss: -1.4785 - val_accuracy: 0.0000e+00
Epoch 121/830
6/6 [==============================] - ETA: 0s - loss: -1.0875 - accuracy: 0.0485
Epoch 121: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -1.0875 - accuracy: 0.0485 - val_loss: -1.5032 - val_accuracy: 0.0000e+00
Epoch 122/830
6/6 [==============================] - ETA: 0s - loss: -1.0981 - accuracy: 0.0485
Epoch 122: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -1.0981 - accuracy: 0.0485 - val_loss: -1.5092 - val_accuracy: 0.0000e+00
Epoch 123/830
6/6 [==============================] - ETA: 0s - loss: -1.1076 - accuracy: 0.0485
Epoch 123: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 802ms/step - loss: -1.1076 - accuracy: 0.0485 - val_loss: -1.5186 - val_accuracy: 0.0000e+00
Epoch 124/830
6/6 [==============================] - ETA: 0s - loss: -1.1191 - accuracy: 0.0485
Epoch 124: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 760ms/step - loss: -1.1191 - accuracy: 0.0485 - val_loss: -1.5249 - val_accuracy: 0.0000e+00
Epoch 125/830
6/6 [==============================] - ETA: 0s - loss: -1.1294 - accuracy: 0.0515
Epoch 125: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -1.1294 - accuracy: 0.0515 - val_loss: -1.5397 - val_accuracy: 0.0000e+00
Epoch 126/830
6/6 [==============================] - ETA: 0s - loss: -1.1414 - accuracy: 0.0515
Epoch 126: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -1.1414 - accuracy: 0.0515 - val_loss: -1.5604 - val_accuracy: 0.0000e+00
Epoch 127/830
6/6 [==============================] - ETA: 0s - loss: -1.1517 - accuracy: 0.0485
Epoch 127: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -1.1517 - accuracy: 0.0485 - val_loss: -1.5577 - val_accuracy: 0.0000e+00
Epoch 128/830
6/6 [==============================] - ETA: 0s - loss: -1.1620 - accuracy: 0.0515
Epoch 128: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 781ms/step - loss: -1.1620 - accuracy: 0.0515 - val_loss: -1.5759 - val_accuracy: 0.0000e+00
Epoch 129/830
6/6 [==============================] - ETA: 0s - loss: -1.1720 - accuracy: 0.0485
Epoch 129: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -1.1720 - accuracy: 0.0485 - val_loss: -1.5776 - val_accuracy: 0.0000e+00
Epoch 130/830
6/6 [==============================] - ETA: 0s - loss: -1.1813 - accuracy: 0.0545
Epoch 130: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -1.1813 - accuracy: 0.0545 - val_loss: -1.5927 - val_accuracy: 0.0000e+00
Epoch 131/830
6/6 [==============================] - ETA: 0s - loss: -1.1917 - accuracy: 0.0515
Epoch 131: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -1.1917 - accuracy: 0.0515 - val_loss: -1.5890 - val_accuracy: 0.0000e+00
Epoch 132/830
6/6 [==============================] - ETA: 0s - loss: -1.2010 - accuracy: 0.0576
Epoch 132: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: -1.2010 - accuracy: 0.0576 - val_loss: -1.5961 - val_accuracy: 0.0000e+00
Epoch 133/830
6/6 [==============================] - ETA: 0s - loss: -1.2101 - accuracy: 0.0576
Epoch 133: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -1.2101 - accuracy: 0.0576 - val_loss: -1.6186 - val_accuracy: 0.0000e+00
Epoch 134/830
6/6 [==============================] - ETA: 0s - loss: -1.2204 - accuracy: 0.0545
Epoch 134: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -1.2204 - accuracy: 0.0545 - val_loss: -1.6363 - val_accuracy: 0.0000e+00
Epoch 135/830
6/6 [==============================] - ETA: 0s - loss: -1.2300 - accuracy: 0.0515
Epoch 135: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -1.2300 - accuracy: 0.0515 - val_loss: -1.6515 - val_accuracy: 0.0000e+00
Epoch 136/830
6/6 [==============================] - ETA: 0s - loss: -1.2395 - accuracy: 0.0515
Epoch 136: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -1.2395 - accuracy: 0.0515 - val_loss: -1.6590 - val_accuracy: 0.0000e+00
Epoch 137/830
6/6 [==============================] - ETA: 0s - loss: -1.2481 - accuracy: 0.0515
Epoch 137: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -1.2481 - accuracy: 0.0515 - val_loss: -1.6562 - val_accuracy: 0.0000e+00
Epoch 138/830
6/6 [==============================] - ETA: 0s - loss: -1.2572 - accuracy: 0.0545
Epoch 138: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -1.2572 - accuracy: 0.0545 - val_loss: -1.6648 - val_accuracy: 0.0000e+00
Epoch 139/830
6/6 [==============================] - ETA: 0s - loss: -1.2676 - accuracy: 0.0545
Epoch 139: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -1.2676 - accuracy: 0.0545 - val_loss: -1.6707 - val_accuracy: 0.0000e+00
Epoch 140/830
6/6 [==============================] - ETA: 0s - loss: -1.2775 - accuracy: 0.0545
Epoch 140: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -1.2775 - accuracy: 0.0545 - val_loss: -1.6827 - val_accuracy: 0.0000e+00
Epoch 141/830
6/6 [==============================] - ETA: 0s - loss: -1.2893 - accuracy: 0.0606
Epoch 141: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 781ms/step - loss: -1.2893 - accuracy: 0.0606 - val_loss: -1.6940 - val_accuracy: 0.0000e+00
Epoch 142/830
6/6 [==============================] - ETA: 0s - loss: -1.2999 - accuracy: 0.0606
Epoch 142: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 803ms/step - loss: -1.2999 - accuracy: 0.0606 - val_loss: -1.6927 - val_accuracy: 0.0250
Epoch 143/830
6/6 [==============================] - ETA: 0s - loss: -1.3092 - accuracy: 0.0606
Epoch 143: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -1.3092 - accuracy: 0.0606 - val_loss: -1.7085 - val_accuracy: 0.0000e+00
Epoch 144/830
6/6 [==============================] - ETA: 0s - loss: -1.3184 - accuracy: 0.0606
Epoch 144: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -1.3184 - accuracy: 0.0606 - val_loss: -1.7072 - val_accuracy: 0.0250
Epoch 145/830
6/6 [==============================] - ETA: 0s - loss: -1.3273 - accuracy: 0.0667
Epoch 145: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -1.3273 - accuracy: 0.0667 - val_loss: -1.7218 - val_accuracy: 0.0000e+00
Epoch 146/830
6/6 [==============================] - ETA: 0s - loss: -1.3373 - accuracy: 0.0667
Epoch 146: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 775ms/step - loss: -1.3373 - accuracy: 0.0667 - val_loss: -1.7292 - val_accuracy: 0.0250
Epoch 147/830
6/6 [==============================] - ETA: 0s - loss: -1.3473 - accuracy: 0.0667
Epoch 147: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 760ms/step - loss: -1.3473 - accuracy: 0.0667 - val_loss: -1.7373 - val_accuracy: 0.0250
Epoch 148/830
6/6 [==============================] - ETA: 0s - loss: -1.3581 - accuracy: 0.0697
Epoch 148: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -1.3581 - accuracy: 0.0697 - val_loss: -1.7436 - val_accuracy: 0.0250
Epoch 149/830
6/6 [==============================] - ETA: 0s - loss: -1.3685 - accuracy: 0.0697
Epoch 149: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -1.3685 - accuracy: 0.0697 - val_loss: -1.7572 - val_accuracy: 0.0250
Epoch 150/830
6/6 [==============================] - ETA: 0s - loss: -1.3798 - accuracy: 0.0697
Epoch 150: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -1.3798 - accuracy: 0.0697 - val_loss: -1.7706 - val_accuracy: 0.0250
Epoch 151/830
6/6 [==============================] - ETA: 0s - loss: -1.3922 - accuracy: 0.0727
Epoch 151: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -1.3922 - accuracy: 0.0727 - val_loss: -1.7921 - val_accuracy: 0.0000e+00
Epoch 152/830
6/6 [==============================] - ETA: 0s - loss: -1.4031 - accuracy: 0.0667
Epoch 152: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -1.4031 - accuracy: 0.0667 - val_loss: -1.8018 - val_accuracy: 0.0000e+00
Epoch 153/830
6/6 [==============================] - ETA: 0s - loss: -1.4134 - accuracy: 0.0727
Epoch 153: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -1.4134 - accuracy: 0.0727 - val_loss: -1.8161 - val_accuracy: 0.0000e+00
Epoch 154/830
6/6 [==============================] - ETA: 0s - loss: -1.4251 - accuracy: 0.0667
Epoch 154: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -1.4251 - accuracy: 0.0667 - val_loss: -1.8295 - val_accuracy: 0.0000e+00
Epoch 155/830
6/6 [==============================] - ETA: 0s - loss: -1.4351 - accuracy: 0.0667
Epoch 155: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -1.4351 - accuracy: 0.0667 - val_loss: -1.8405 - val_accuracy: 0.0000e+00
Epoch 156/830
6/6 [==============================] - ETA: 0s - loss: -1.4464 - accuracy: 0.0727
Epoch 156: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 826ms/step - loss: -1.4464 - accuracy: 0.0727 - val_loss: -1.8578 - val_accuracy: 0.0000e+00
Epoch 157/830
6/6 [==============================] - ETA: 0s - loss: -1.4577 - accuracy: 0.0636
Epoch 157: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -1.4577 - accuracy: 0.0636 - val_loss: -1.8566 - val_accuracy: 0.0250
Epoch 158/830
6/6 [==============================] - ETA: 0s - loss: -1.4676 - accuracy: 0.0727
Epoch 158: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -1.4676 - accuracy: 0.0727 - val_loss: -1.8722 - val_accuracy: 0.0000e+00
Epoch 159/830
6/6 [==============================] - ETA: 0s - loss: -1.4782 - accuracy: 0.0667
Epoch 159: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -1.4782 - accuracy: 0.0667 - val_loss: -1.8828 - val_accuracy: 0.0000e+00
Epoch 160/830
6/6 [==============================] - ETA: 0s - loss: -1.4887 - accuracy: 0.0697
Epoch 160: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 817ms/step - loss: -1.4887 - accuracy: 0.0697 - val_loss: -1.9016 - val_accuracy: 0.0000e+00
Epoch 161/830
6/6 [==============================] - ETA: 0s - loss: -1.4994 - accuracy: 0.0667
Epoch 161: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -1.4994 - accuracy: 0.0667 - val_loss: -1.9157 - val_accuracy: 0.0000e+00
Epoch 162/830
6/6 [==============================] - ETA: 0s - loss: -1.5112 - accuracy: 0.0636
Epoch 162: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -1.5112 - accuracy: 0.0636 - val_loss: -1.9300 - val_accuracy: 0.0000e+00
Epoch 163/830
6/6 [==============================] - ETA: 0s - loss: -1.5223 - accuracy: 0.0667
Epoch 163: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -1.5223 - accuracy: 0.0667 - val_loss: -1.9429 - val_accuracy: 0.0000e+00
Epoch 164/830
6/6 [==============================] - ETA: 0s - loss: -1.5337 - accuracy: 0.0667
Epoch 164: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 808ms/step - loss: -1.5337 - accuracy: 0.0667 - val_loss: -1.9484 - val_accuracy: 0.0000e+00
Epoch 165/830
6/6 [==============================] - ETA: 0s - loss: -1.5451 - accuracy: 0.0667
Epoch 165: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -1.5451 - accuracy: 0.0667 - val_loss: -1.9569 - val_accuracy: 0.0000e+00
Epoch 166/830
6/6 [==============================] - ETA: 0s - loss: -1.5543 - accuracy: 0.0667
Epoch 166: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -1.5543 - accuracy: 0.0667 - val_loss: -1.9700 - val_accuracy: 0.0000e+00
Epoch 167/830
6/6 [==============================] - ETA: 0s - loss: -1.5661 - accuracy: 0.0697
Epoch 167: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -1.5661 - accuracy: 0.0697 - val_loss: -1.9736 - val_accuracy: 0.0250
Epoch 168/830
6/6 [==============================] - ETA: 0s - loss: -1.5778 - accuracy: 0.0697
Epoch 168: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -1.5778 - accuracy: 0.0697 - val_loss: -1.9903 - val_accuracy: 0.0000e+00
Epoch 169/830
6/6 [==============================] - ETA: 0s - loss: -1.5882 - accuracy: 0.0697
Epoch 169: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 804ms/step - loss: -1.5882 - accuracy: 0.0697 - val_loss: -1.9957 - val_accuracy: 0.0000e+00
Epoch 170/830
6/6 [==============================] - ETA: 0s - loss: -1.5987 - accuracy: 0.0697
Epoch 170: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -1.5987 - accuracy: 0.0697 - val_loss: -2.0046 - val_accuracy: 0.0250
Epoch 171/830
6/6 [==============================] - ETA: 0s - loss: -1.6090 - accuracy: 0.0727
Epoch 171: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -1.6090 - accuracy: 0.0727 - val_loss: -2.0222 - val_accuracy: 0.0000e+00
Epoch 172/830
6/6 [==============================] - ETA: 0s - loss: -1.6217 - accuracy: 0.0697
Epoch 172: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -1.6217 - accuracy: 0.0697 - val_loss: -2.0434 - val_accuracy: 0.0000e+00
Epoch 173/830
6/6 [==============================] - ETA: 0s - loss: -1.6317 - accuracy: 0.0667
Epoch 173: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -1.6317 - accuracy: 0.0667 - val_loss: -2.0555 - val_accuracy: 0.0000e+00
Epoch 174/830
6/6 [==============================] - ETA: 0s - loss: -1.6410 - accuracy: 0.0667
Epoch 174: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -1.6410 - accuracy: 0.0667 - val_loss: -2.0599 - val_accuracy: 0.0000e+00
Epoch 175/830
6/6 [==============================] - ETA: 0s - loss: -1.6507 - accuracy: 0.0697
Epoch 175: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: -1.6507 - accuracy: 0.0697 - val_loss: -2.0617 - val_accuracy: 0.0000e+00
Epoch 176/830
6/6 [==============================] - ETA: 0s - loss: -1.6612 - accuracy: 0.0697
Epoch 176: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -1.6612 - accuracy: 0.0697 - val_loss: -2.0704 - val_accuracy: 0.0250
Epoch 177/830
6/6 [==============================] - ETA: 0s - loss: -1.6718 - accuracy: 0.0758
Epoch 177: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -1.6718 - accuracy: 0.0758 - val_loss: -2.0780 - val_accuracy: 0.0250
Epoch 178/830
6/6 [==============================] - ETA: 0s - loss: -1.6820 - accuracy: 0.0697
Epoch 178: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -1.6820 - accuracy: 0.0697 - val_loss: -2.0774 - val_accuracy: 0.0250
Epoch 179/830
6/6 [==============================] - ETA: 0s - loss: -1.6918 - accuracy: 0.0818
Epoch 179: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -1.6918 - accuracy: 0.0818 - val_loss: -2.0830 - val_accuracy: 0.0250
Epoch 180/830
6/6 [==============================] - ETA: 0s - loss: -1.7000 - accuracy: 0.0788
Epoch 180: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 760ms/step - loss: -1.7000 - accuracy: 0.0788 - val_loss: -2.0806 - val_accuracy: 0.0250
Epoch 181/830
6/6 [==============================] - ETA: 0s - loss: -1.7069 - accuracy: 0.0818
Epoch 181: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 803ms/step - loss: -1.7069 - accuracy: 0.0818 - val_loss: -2.0881 - val_accuracy: 0.0250
Epoch 182/830
6/6 [==============================] - ETA: 0s - loss: -1.7171 - accuracy: 0.0818
Epoch 182: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -1.7171 - accuracy: 0.0818 - val_loss: -2.0914 - val_accuracy: 0.0250
Epoch 183/830
6/6 [==============================] - ETA: 0s - loss: -1.7251 - accuracy: 0.0818
Epoch 183: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -1.7251 - accuracy: 0.0818 - val_loss: -2.0902 - val_accuracy: 0.0500
Epoch 184/830
6/6 [==============================] - ETA: 0s - loss: -1.7311 - accuracy: 0.0848
Epoch 184: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 781ms/step - loss: -1.7311 - accuracy: 0.0848 - val_loss: -2.0959 - val_accuracy: 0.0500
Epoch 185/830
6/6 [==============================] - ETA: 0s - loss: -1.7395 - accuracy: 0.0879
Epoch 185: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 755ms/step - loss: -1.7395 - accuracy: 0.0879 - val_loss: -2.0965 - val_accuracy: 0.0500
Epoch 186/830
6/6 [==============================] - ETA: 0s - loss: -1.7468 - accuracy: 0.0970
Epoch 186: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -1.7468 - accuracy: 0.0970 - val_loss: -2.1145 - val_accuracy: 0.0500
Epoch 187/830
6/6 [==============================] - ETA: 0s - loss: -1.7579 - accuracy: 0.0879
Epoch 187: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -1.7579 - accuracy: 0.0879 - val_loss: -2.1324 - val_accuracy: 0.0250
Epoch 188/830
6/6 [==============================] - ETA: 0s - loss: -1.7675 - accuracy: 0.0818
Epoch 188: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -1.7675 - accuracy: 0.0818 - val_loss: -2.1341 - val_accuracy: 0.0500
Epoch 189/830
6/6 [==============================] - ETA: 0s - loss: -1.7766 - accuracy: 0.0879
Epoch 189: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 777ms/step - loss: -1.7766 - accuracy: 0.0879 - val_loss: -2.1511 - val_accuracy: 0.0250
Epoch 190/830
6/6 [==============================] - ETA: 0s - loss: -1.7871 - accuracy: 0.0818
Epoch 190: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -1.7871 - accuracy: 0.0818 - val_loss: -2.1652 - val_accuracy: 0.0250
Epoch 191/830
6/6 [==============================] - ETA: 0s - loss: -1.7978 - accuracy: 0.0818
Epoch 191: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -1.7978 - accuracy: 0.0818 - val_loss: -2.1686 - val_accuracy: 0.0500
Epoch 192/830
6/6 [==============================] - ETA: 0s - loss: -1.8068 - accuracy: 0.0848
Epoch 192: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -1.8068 - accuracy: 0.0848 - val_loss: -2.1758 - val_accuracy: 0.0500
Epoch 193/830
6/6 [==============================] - ETA: 0s - loss: -1.8176 - accuracy: 0.0909
Epoch 193: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 801ms/step - loss: -1.8176 - accuracy: 0.0909 - val_loss: -2.2013 - val_accuracy: 0.0250
Epoch 194/830
6/6 [==============================] - ETA: 0s - loss: -1.8291 - accuracy: 0.0818
Epoch 194: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -1.8291 - accuracy: 0.0818 - val_loss: -2.2009 - val_accuracy: 0.0500
Epoch 195/830
6/6 [==============================] - ETA: 0s - loss: -1.8359 - accuracy: 0.0848
Epoch 195: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -1.8359 - accuracy: 0.0848 - val_loss: -2.2000 - val_accuracy: 0.0500
Epoch 196/830
6/6 [==============================] - ETA: 0s - loss: -1.8430 - accuracy: 0.0909
Epoch 196: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -1.8430 - accuracy: 0.0909 - val_loss: -2.2078 - val_accuracy: 0.0500
Epoch 197/830
6/6 [==============================] - ETA: 0s - loss: -1.8528 - accuracy: 0.0939
Epoch 197: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 807ms/step - loss: -1.8528 - accuracy: 0.0939 - val_loss: -2.2254 - val_accuracy: 0.0500
Epoch 198/830
6/6 [==============================] - ETA: 0s - loss: -1.8631 - accuracy: 0.0879
Epoch 198: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 762ms/step - loss: -1.8631 - accuracy: 0.0879 - val_loss: -2.2424 - val_accuracy: 0.0500
Epoch 199/830
6/6 [==============================] - ETA: 0s - loss: -1.8744 - accuracy: 0.0848
Epoch 199: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -1.8744 - accuracy: 0.0848 - val_loss: -2.2535 - val_accuracy: 0.0500
Epoch 200/830
6/6 [==============================] - ETA: 0s - loss: -1.8856 - accuracy: 0.0879
Epoch 200: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -1.8856 - accuracy: 0.0879 - val_loss: -2.2756 - val_accuracy: 0.0250
Epoch 201/830
6/6 [==============================] - ETA: 0s - loss: -1.8939 - accuracy: 0.0818
Epoch 201: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -1.8939 - accuracy: 0.0818 - val_loss: -2.2849 - val_accuracy: 0.0250
Epoch 202/830
6/6 [==============================] - ETA: 0s - loss: -1.9059 - accuracy: 0.0818
Epoch 202: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -1.9059 - accuracy: 0.0818 - val_loss: -2.3030 - val_accuracy: 0.0250
Epoch 203/830
6/6 [==============================] - ETA: 0s - loss: -1.9165 - accuracy: 0.0818
Epoch 203: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 805ms/step - loss: -1.9165 - accuracy: 0.0818 - val_loss: -2.3198 - val_accuracy: 0.0250
Epoch 204/830
6/6 [==============================] - ETA: 0s - loss: -1.9266 - accuracy: 0.0818
Epoch 204: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -1.9266 - accuracy: 0.0818 - val_loss: -2.3197 - val_accuracy: 0.0250
Epoch 205/830
6/6 [==============================] - ETA: 0s - loss: -1.9349 - accuracy: 0.0818
Epoch 205: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -1.9349 - accuracy: 0.0818 - val_loss: -2.3289 - val_accuracy: 0.0250
Epoch 206/830
6/6 [==============================] - ETA: 0s - loss: -1.9451 - accuracy: 0.0818
Epoch 206: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -1.9451 - accuracy: 0.0818 - val_loss: -2.3370 - val_accuracy: 0.0250
Epoch 207/830
6/6 [==============================] - ETA: 0s - loss: -1.9556 - accuracy: 0.0818
Epoch 207: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 753ms/step - loss: -1.9556 - accuracy: 0.0818 - val_loss: -2.3477 - val_accuracy: 0.0250
Epoch 208/830
6/6 [==============================] - ETA: 0s - loss: -1.9656 - accuracy: 0.0818
Epoch 208: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -1.9656 - accuracy: 0.0818 - val_loss: -2.3683 - val_accuracy: 0.0250
Epoch 209/830
6/6 [==============================] - ETA: 0s - loss: -1.9766 - accuracy: 0.0818
Epoch 209: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -1.9766 - accuracy: 0.0818 - val_loss: -2.3704 - val_accuracy: 0.0250
Epoch 210/830
6/6 [==============================] - ETA: 0s - loss: -1.9856 - accuracy: 0.0818
Epoch 210: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -1.9856 - accuracy: 0.0818 - val_loss: -2.3700 - val_accuracy: 0.0500
Epoch 211/830
6/6 [==============================] - ETA: 0s - loss: -1.9942 - accuracy: 0.0848
Epoch 211: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -1.9942 - accuracy: 0.0848 - val_loss: -2.3896 - val_accuracy: 0.0250
Epoch 212/830
6/6 [==============================] - ETA: 0s - loss: -2.0051 - accuracy: 0.0818
Epoch 212: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -2.0051 - accuracy: 0.0818 - val_loss: -2.3970 - val_accuracy: 0.0250
Epoch 213/830
6/6 [==============================] - ETA: 0s - loss: -2.0141 - accuracy: 0.0818
Epoch 213: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 779ms/step - loss: -2.0141 - accuracy: 0.0818 - val_loss: -2.4137 - val_accuracy: 0.0250
Epoch 214/830
6/6 [==============================] - ETA: 0s - loss: -2.0263 - accuracy: 0.0818
Epoch 214: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 755ms/step - loss: -2.0263 - accuracy: 0.0818 - val_loss: -2.4174 - val_accuracy: 0.0250
Epoch 215/830
6/6 [==============================] - ETA: 0s - loss: -2.0354 - accuracy: 0.0818
Epoch 215: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.0354 - accuracy: 0.0818 - val_loss: -2.4253 - val_accuracy: 0.0500
Epoch 216/830
6/6 [==============================] - ETA: 0s - loss: -2.0457 - accuracy: 0.0848
Epoch 216: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.0457 - accuracy: 0.0848 - val_loss: -2.4315 - val_accuracy: 0.0500
Epoch 217/830
6/6 [==============================] - ETA: 0s - loss: -2.0552 - accuracy: 0.0909
Epoch 217: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 790ms/step - loss: -2.0552 - accuracy: 0.0909 - val_loss: -2.4463 - val_accuracy: 0.0500
Epoch 218/830
6/6 [==============================] - ETA: 0s - loss: -2.0673 - accuracy: 0.0848
Epoch 218: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: -2.0673 - accuracy: 0.0848 - val_loss: -2.4675 - val_accuracy: 0.0250
Epoch 219/830
6/6 [==============================] - ETA: 0s - loss: -2.0776 - accuracy: 0.0818
Epoch 219: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -2.0776 - accuracy: 0.0818 - val_loss: -2.4708 - val_accuracy: 0.0250
Epoch 220/830
6/6 [==============================] - ETA: 0s - loss: -2.0872 - accuracy: 0.0818
Epoch 220: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -2.0872 - accuracy: 0.0818 - val_loss: -2.4793 - val_accuracy: 0.0500
Epoch 221/830
6/6 [==============================] - ETA: 0s - loss: -2.0964 - accuracy: 0.0818
Epoch 221: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.0964 - accuracy: 0.0818 - val_loss: -2.4817 - val_accuracy: 0.0500
Epoch 222/830
6/6 [==============================] - ETA: 0s - loss: -2.1053 - accuracy: 0.0848
Epoch 222: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 755ms/step - loss: -2.1053 - accuracy: 0.0848 - val_loss: -2.4901 - val_accuracy: 0.0500
Epoch 223/830
6/6 [==============================] - ETA: 0s - loss: -2.1146 - accuracy: 0.0909
Epoch 223: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -2.1146 - accuracy: 0.0909 - val_loss: -2.5074 - val_accuracy: 0.0500
Epoch 224/830
6/6 [==============================] - ETA: 0s - loss: -2.1260 - accuracy: 0.0879
Epoch 224: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -2.1260 - accuracy: 0.0879 - val_loss: -2.5075 - val_accuracy: 0.0500
Epoch 225/830
6/6 [==============================] - ETA: 0s - loss: -2.1349 - accuracy: 0.0909
Epoch 225: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -2.1349 - accuracy: 0.0909 - val_loss: -2.5226 - val_accuracy: 0.0500
Epoch 226/830
6/6 [==============================] - ETA: 0s - loss: -2.1439 - accuracy: 0.0818
Epoch 226: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.1439 - accuracy: 0.0818 - val_loss: -2.5395 - val_accuracy: 0.0500
Epoch 227/830
6/6 [==============================] - ETA: 0s - loss: -2.1543 - accuracy: 0.0818
Epoch 227: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 775ms/step - loss: -2.1543 - accuracy: 0.0818 - val_loss: -2.5575 - val_accuracy: 0.0250
Epoch 228/830
6/6 [==============================] - ETA: 0s - loss: -2.1650 - accuracy: 0.0818
Epoch 228: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -2.1650 - accuracy: 0.0818 - val_loss: -2.5710 - val_accuracy: 0.0250
Epoch 229/830
6/6 [==============================] - ETA: 0s - loss: -2.1744 - accuracy: 0.0818
Epoch 229: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.1744 - accuracy: 0.0818 - val_loss: -2.5736 - val_accuracy: 0.0250
Epoch 230/830
6/6 [==============================] - ETA: 0s - loss: -2.1842 - accuracy: 0.0818
Epoch 230: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -2.1842 - accuracy: 0.0818 - val_loss: -2.5927 - val_accuracy: 0.0250
Epoch 231/830
6/6 [==============================] - ETA: 0s - loss: -2.1933 - accuracy: 0.0818
Epoch 231: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 755ms/step - loss: -2.1933 - accuracy: 0.0818 - val_loss: -2.6054 - val_accuracy: 0.0250
Epoch 232/830
6/6 [==============================] - ETA: 0s - loss: -2.2049 - accuracy: 0.0818
Epoch 232: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -2.2049 - accuracy: 0.0818 - val_loss: -2.6137 - val_accuracy: 0.0250
Epoch 233/830
6/6 [==============================] - ETA: 0s - loss: -2.2141 - accuracy: 0.0818
Epoch 233: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -2.2141 - accuracy: 0.0818 - val_loss: -2.6290 - val_accuracy: 0.0250
Epoch 234/830
6/6 [==============================] - ETA: 0s - loss: -2.2247 - accuracy: 0.0818
Epoch 234: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -2.2247 - accuracy: 0.0818 - val_loss: -2.6445 - val_accuracy: 0.0250
Epoch 235/830
6/6 [==============================] - ETA: 0s - loss: -2.2364 - accuracy: 0.0818
Epoch 235: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.2364 - accuracy: 0.0818 - val_loss: -2.6447 - val_accuracy: 0.0250
Epoch 236/830
6/6 [==============================] - ETA: 0s - loss: -2.2453 - accuracy: 0.0818
Epoch 236: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 821ms/step - loss: -2.2453 - accuracy: 0.0818 - val_loss: -2.6517 - val_accuracy: 0.0250
Epoch 237/830
6/6 [==============================] - ETA: 0s - loss: -2.2550 - accuracy: 0.0818
Epoch 237: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.2550 - accuracy: 0.0818 - val_loss: -2.6552 - val_accuracy: 0.0500
Epoch 238/830
6/6 [==============================] - ETA: 0s - loss: -2.2643 - accuracy: 0.0848
Epoch 238: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 752ms/step - loss: -2.2643 - accuracy: 0.0848 - val_loss: -2.6580 - val_accuracy: 0.0500
Epoch 239/830
6/6 [==============================] - ETA: 0s - loss: -2.2738 - accuracy: 0.0909
Epoch 239: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 755ms/step - loss: -2.2738 - accuracy: 0.0909 - val_loss: -2.6762 - val_accuracy: 0.0500
Epoch 240/830
6/6 [==============================] - ETA: 0s - loss: -2.2846 - accuracy: 0.0879
Epoch 240: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -2.2846 - accuracy: 0.0879 - val_loss: -2.6810 - val_accuracy: 0.0500
Epoch 241/830
6/6 [==============================] - ETA: 0s - loss: -2.2943 - accuracy: 0.0909
Epoch 241: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 755ms/step - loss: -2.2943 - accuracy: 0.0909 - val_loss: -2.6964 - val_accuracy: 0.0500
Epoch 242/830
6/6 [==============================] - ETA: 0s - loss: -2.3043 - accuracy: 0.0909
Epoch 242: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 774ms/step - loss: -2.3043 - accuracy: 0.0909 - val_loss: -2.7147 - val_accuracy: 0.0500
Epoch 243/830
6/6 [==============================] - ETA: 0s - loss: -2.3147 - accuracy: 0.0848
Epoch 243: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -2.3147 - accuracy: 0.0848 - val_loss: -2.7179 - val_accuracy: 0.0500
Epoch 244/830
6/6 [==============================] - ETA: 0s - loss: -2.3254 - accuracy: 0.0909
Epoch 244: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -2.3254 - accuracy: 0.0909 - val_loss: -2.7369 - val_accuracy: 0.0250
Epoch 245/830
6/6 [==============================] - ETA: 0s - loss: -2.3358 - accuracy: 0.0818
Epoch 245: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -2.3358 - accuracy: 0.0818 - val_loss: -2.7406 - val_accuracy: 0.0500
Epoch 246/830
6/6 [==============================] - ETA: 0s - loss: -2.3443 - accuracy: 0.0909
Epoch 246: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -2.3443 - accuracy: 0.0909 - val_loss: -2.7567 - val_accuracy: 0.0500
Epoch 247/830
6/6 [==============================] - ETA: 0s - loss: -2.3563 - accuracy: 0.0848
Epoch 247: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 780ms/step - loss: -2.3563 - accuracy: 0.0848 - val_loss: -2.7730 - val_accuracy: 0.0250
Epoch 248/830
6/6 [==============================] - ETA: 0s - loss: -2.3647 - accuracy: 0.0848
Epoch 248: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 759ms/step - loss: -2.3647 - accuracy: 0.0848 - val_loss: -2.7750 - val_accuracy: 0.0500
Epoch 249/830
6/6 [==============================] - ETA: 0s - loss: -2.3750 - accuracy: 0.0848
Epoch 249: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -2.3750 - accuracy: 0.0848 - val_loss: -2.7872 - val_accuracy: 0.0500
Epoch 250/830
6/6 [==============================] - ETA: 0s - loss: -2.3837 - accuracy: 0.0848
Epoch 250: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -2.3837 - accuracy: 0.0848 - val_loss: -2.8076 - val_accuracy: 0.0250
Epoch 251/830
6/6 [==============================] - ETA: 0s - loss: -2.3952 - accuracy: 0.0818
Epoch 251: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.3952 - accuracy: 0.0818 - val_loss: -2.8072 - val_accuracy: 0.0500
Epoch 252/830
6/6 [==============================] - ETA: 0s - loss: -2.4025 - accuracy: 0.0848
Epoch 252: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 777ms/step - loss: -2.4025 - accuracy: 0.0848 - val_loss: -2.8245 - val_accuracy: 0.0250
Epoch 253/830
6/6 [==============================] - ETA: 0s - loss: -2.4123 - accuracy: 0.0818
Epoch 253: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 760ms/step - loss: -2.4123 - accuracy: 0.0818 - val_loss: -2.8349 - val_accuracy: 0.0250
Epoch 254/830
6/6 [==============================] - ETA: 0s - loss: -2.4217 - accuracy: 0.0818
Epoch 254: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.4217 - accuracy: 0.0818 - val_loss: -2.8374 - val_accuracy: 0.0500
Epoch 255/830
6/6 [==============================] - ETA: 0s - loss: -2.4316 - accuracy: 0.0848
Epoch 255: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.4316 - accuracy: 0.0848 - val_loss: -2.8472 - val_accuracy: 0.0500
Epoch 256/830
6/6 [==============================] - ETA: 0s - loss: -2.4412 - accuracy: 0.0848
Epoch 256: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -2.4412 - accuracy: 0.0848 - val_loss: -2.8604 - val_accuracy: 0.0250
Epoch 257/830
6/6 [==============================] - ETA: 0s - loss: -2.4519 - accuracy: 0.0848
Epoch 257: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -2.4519 - accuracy: 0.0848 - val_loss: -2.8709 - val_accuracy: 0.0500
Epoch 258/830
6/6 [==============================] - ETA: 0s - loss: -2.4608 - accuracy: 0.0848
Epoch 258: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 815ms/step - loss: -2.4608 - accuracy: 0.0848 - val_loss: -2.8844 - val_accuracy: 0.0250
Epoch 259/830
6/6 [==============================] - ETA: 0s - loss: -2.4744 - accuracy: 0.0818
Epoch 259: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 795ms/step - loss: -2.4744 - accuracy: 0.0818 - val_loss: -2.8982 - val_accuracy: 0.0250
Epoch 260/830
6/6 [==============================] - ETA: 0s - loss: -2.4830 - accuracy: 0.0818
Epoch 260: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -2.4830 - accuracy: 0.0818 - val_loss: -2.9009 - val_accuracy: 0.0500
Epoch 261/830
6/6 [==============================] - ETA: 0s - loss: -2.4936 - accuracy: 0.0848
Epoch 261: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -2.4936 - accuracy: 0.0848 - val_loss: -2.9101 - val_accuracy: 0.0500
Epoch 262/830
6/6 [==============================] - ETA: 0s - loss: -2.5042 - accuracy: 0.0879
Epoch 262: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -2.5042 - accuracy: 0.0879 - val_loss: -2.9206 - val_accuracy: 0.0500
Epoch 263/830
6/6 [==============================] - ETA: 0s - loss: -2.5146 - accuracy: 0.0909
Epoch 263: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.5146 - accuracy: 0.0909 - val_loss: -2.9249 - val_accuracy: 0.0500
Epoch 264/830
6/6 [==============================] - ETA: 0s - loss: -2.5253 - accuracy: 0.0909
Epoch 264: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 774ms/step - loss: -2.5253 - accuracy: 0.0909 - val_loss: -2.9291 - val_accuracy: 0.0500
Epoch 265/830
6/6 [==============================] - ETA: 0s - loss: -2.5352 - accuracy: 0.0909
Epoch 265: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.5352 - accuracy: 0.0909 - val_loss: -2.9485 - val_accuracy: 0.0500
Epoch 266/830
6/6 [==============================] - ETA: 0s - loss: -2.5476 - accuracy: 0.0909
Epoch 266: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -2.5476 - accuracy: 0.0909 - val_loss: -2.9685 - val_accuracy: 0.0500
Epoch 267/830
6/6 [==============================] - ETA: 0s - loss: -2.5586 - accuracy: 0.0879
Epoch 267: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -2.5586 - accuracy: 0.0879 - val_loss: -2.9724 - val_accuracy: 0.0500
Epoch 268/830
6/6 [==============================] - ETA: 0s - loss: -2.5688 - accuracy: 0.0909
Epoch 268: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.5688 - accuracy: 0.0909 - val_loss: -2.9836 - val_accuracy: 0.0500
Epoch 269/830
6/6 [==============================] - ETA: 0s - loss: -2.5802 - accuracy: 0.0909
Epoch 269: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -2.5802 - accuracy: 0.0909 - val_loss: -2.9979 - val_accuracy: 0.0500
Epoch 270/830
6/6 [==============================] - ETA: 0s - loss: -2.5910 - accuracy: 0.0879
Epoch 270: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.5910 - accuracy: 0.0879 - val_loss: -3.0111 - val_accuracy: 0.0500
Epoch 271/830
6/6 [==============================] - ETA: 0s - loss: -2.6029 - accuracy: 0.0879
Epoch 271: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -2.6029 - accuracy: 0.0879 - val_loss: -3.0306 - val_accuracy: 0.0500
Epoch 272/830
6/6 [==============================] - ETA: 0s - loss: -2.6132 - accuracy: 0.0818
Epoch 272: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -2.6132 - accuracy: 0.0818 - val_loss: -3.0431 - val_accuracy: 0.0500
Epoch 273/830
6/6 [==============================] - ETA: 0s - loss: -2.6246 - accuracy: 0.0848
Epoch 273: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.6246 - accuracy: 0.0848 - val_loss: -3.0503 - val_accuracy: 0.0500
Epoch 274/830
6/6 [==============================] - ETA: 0s - loss: -2.6350 - accuracy: 0.0879
Epoch 274: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -2.6350 - accuracy: 0.0879 - val_loss: -3.0702 - val_accuracy: 0.0250
Epoch 275/830
6/6 [==============================] - ETA: 0s - loss: -2.6454 - accuracy: 0.0818
Epoch 275: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -2.6454 - accuracy: 0.0818 - val_loss: -3.0676 - val_accuracy: 0.0500
Epoch 276/830
6/6 [==============================] - ETA: 0s - loss: -2.6525 - accuracy: 0.0848
Epoch 276: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 755ms/step - loss: -2.6525 - accuracy: 0.0848 - val_loss: -3.0747 - val_accuracy: 0.0500
Epoch 277/830
6/6 [==============================] - ETA: 0s - loss: -2.6620 - accuracy: 0.0879
Epoch 277: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -2.6620 - accuracy: 0.0879 - val_loss: -3.0808 - val_accuracy: 0.0500
Epoch 278/830
6/6 [==============================] - ETA: 0s - loss: -2.6698 - accuracy: 0.0909
Epoch 278: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -2.6698 - accuracy: 0.0909 - val_loss: -3.0923 - val_accuracy: 0.0500
Epoch 279/830
6/6 [==============================] - ETA: 0s - loss: -2.6815 - accuracy: 0.0879
Epoch 279: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -2.6815 - accuracy: 0.0879 - val_loss: -3.1025 - val_accuracy: 0.0500
Epoch 280/830
6/6 [==============================] - ETA: 0s - loss: -2.6924 - accuracy: 0.0909
Epoch 280: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -2.6924 - accuracy: 0.0909 - val_loss: -3.1193 - val_accuracy: 0.0500
Epoch 281/830
6/6 [==============================] - ETA: 0s - loss: -2.7036 - accuracy: 0.0879
Epoch 281: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -2.7036 - accuracy: 0.0879 - val_loss: -3.1313 - val_accuracy: 0.0500
Epoch 282/830
6/6 [==============================] - ETA: 0s - loss: -2.7138 - accuracy: 0.0848
Epoch 282: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.7138 - accuracy: 0.0848 - val_loss: -3.1496 - val_accuracy: 0.0500
Epoch 283/830
6/6 [==============================] - ETA: 0s - loss: -2.7259 - accuracy: 0.0879
Epoch 283: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 800ms/step - loss: -2.7259 - accuracy: 0.0879 - val_loss: -3.1643 - val_accuracy: 0.0250
Epoch 284/830
6/6 [==============================] - ETA: 0s - loss: -2.7366 - accuracy: 0.0848
Epoch 284: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -2.7366 - accuracy: 0.0848 - val_loss: -3.1746 - val_accuracy: 0.0250
Epoch 285/830
6/6 [==============================] - ETA: 0s - loss: -2.7469 - accuracy: 0.0848
Epoch 285: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -2.7469 - accuracy: 0.0848 - val_loss: -3.1873 - val_accuracy: 0.0250
Epoch 286/830
6/6 [==============================] - ETA: 0s - loss: -2.7586 - accuracy: 0.0818
Epoch 286: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 755ms/step - loss: -2.7586 - accuracy: 0.0818 - val_loss: -3.2037 - val_accuracy: 0.0250
Epoch 287/830
6/6 [==============================] - ETA: 0s - loss: -2.7704 - accuracy: 0.0818
Epoch 287: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -2.7704 - accuracy: 0.0818 - val_loss: -3.2176 - val_accuracy: 0.0000e+00
Epoch 288/830
6/6 [==============================] - ETA: 0s - loss: -2.7809 - accuracy: 0.0818
Epoch 288: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 758ms/step - loss: -2.7809 - accuracy: 0.0818 - val_loss: -3.2174 - val_accuracy: 0.0500
Epoch 289/830
6/6 [==============================] - ETA: 0s - loss: -2.7912 - accuracy: 0.0818
Epoch 289: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.7912 - accuracy: 0.0818 - val_loss: -3.2231 - val_accuracy: 0.0500
Epoch 290/830
6/6 [==============================] - ETA: 0s - loss: -2.8013 - accuracy: 0.0879
Epoch 290: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.8013 - accuracy: 0.0879 - val_loss: -3.2350 - val_accuracy: 0.0500
Epoch 291/830
6/6 [==============================] - ETA: 0s - loss: -2.8106 - accuracy: 0.0909
Epoch 291: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.8106 - accuracy: 0.0909 - val_loss: -3.2367 - val_accuracy: 0.0500
Epoch 292/830
6/6 [==============================] - ETA: 0s - loss: -2.8202 - accuracy: 0.0909
Epoch 292: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.8202 - accuracy: 0.0909 - val_loss: -3.2530 - val_accuracy: 0.0500
Epoch 293/830
6/6 [==============================] - ETA: 0s - loss: -2.8293 - accuracy: 0.0909
Epoch 293: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -2.8293 - accuracy: 0.0909 - val_loss: -3.2590 - val_accuracy: 0.0500
Epoch 294/830
6/6 [==============================] - ETA: 0s - loss: -2.8396 - accuracy: 0.0909
Epoch 294: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -2.8396 - accuracy: 0.0909 - val_loss: -3.2776 - val_accuracy: 0.0500
Epoch 295/830
6/6 [==============================] - ETA: 0s - loss: -2.8495 - accuracy: 0.0879
Epoch 295: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.8495 - accuracy: 0.0879 - val_loss: -3.2827 - val_accuracy: 0.0500
Epoch 296/830
6/6 [==============================] - ETA: 0s - loss: -2.8591 - accuracy: 0.0909
Epoch 296: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 805ms/step - loss: -2.8591 - accuracy: 0.0909 - val_loss: -3.2973 - val_accuracy: 0.0500
Epoch 297/830
6/6 [==============================] - ETA: 0s - loss: -2.8689 - accuracy: 0.0909
Epoch 297: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.8689 - accuracy: 0.0909 - val_loss: -3.3056 - val_accuracy: 0.0500
Epoch 298/830
6/6 [==============================] - ETA: 0s - loss: -2.8793 - accuracy: 0.0879
Epoch 298: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -2.8793 - accuracy: 0.0879 - val_loss: -3.3099 - val_accuracy: 0.0500
Epoch 299/830
6/6 [==============================] - ETA: 0s - loss: -2.8900 - accuracy: 0.0909
Epoch 299: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.8900 - accuracy: 0.0909 - val_loss: -3.3275 - val_accuracy: 0.0500
Epoch 300/830
6/6 [==============================] - ETA: 0s - loss: -2.9002 - accuracy: 0.0879
Epoch 300: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 812ms/step - loss: -2.9002 - accuracy: 0.0879 - val_loss: -3.3387 - val_accuracy: 0.0500
Epoch 301/830
6/6 [==============================] - ETA: 0s - loss: -2.9116 - accuracy: 0.0879
Epoch 301: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.9116 - accuracy: 0.0879 - val_loss: -3.3497 - val_accuracy: 0.0500
Epoch 302/830
6/6 [==============================] - ETA: 0s - loss: -2.9230 - accuracy: 0.0909
Epoch 302: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.9230 - accuracy: 0.0909 - val_loss: -3.3647 - val_accuracy: 0.0500
Epoch 303/830
6/6 [==============================] - ETA: 0s - loss: -2.9347 - accuracy: 0.0909
Epoch 303: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -2.9347 - accuracy: 0.0909 - val_loss: -3.3687 - val_accuracy: 0.0500
Epoch 304/830
6/6 [==============================] - ETA: 0s - loss: -2.9460 - accuracy: 0.0909
Epoch 304: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.9460 - accuracy: 0.0909 - val_loss: -3.3901 - val_accuracy: 0.0500
Epoch 305/830
6/6 [==============================] - ETA: 0s - loss: -2.9555 - accuracy: 0.0879
Epoch 305: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -2.9555 - accuracy: 0.0879 - val_loss: -3.4024 - val_accuracy: 0.0500
Epoch 306/830
6/6 [==============================] - ETA: 0s - loss: -2.9652 - accuracy: 0.0909
Epoch 306: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -2.9652 - accuracy: 0.0909 - val_loss: -3.4189 - val_accuracy: 0.0250
Epoch 307/830
6/6 [==============================] - ETA: 0s - loss: -2.9760 - accuracy: 0.0848
Epoch 307: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -2.9760 - accuracy: 0.0848 - val_loss: -3.4227 - val_accuracy: 0.0500
Epoch 308/830
6/6 [==============================] - ETA: 0s - loss: -2.9858 - accuracy: 0.0879
Epoch 308: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -2.9858 - accuracy: 0.0879 - val_loss: -3.4412 - val_accuracy: 0.0000e+00
Epoch 309/830
6/6 [==============================] - ETA: 0s - loss: -2.9960 - accuracy: 0.0848
Epoch 309: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -2.9960 - accuracy: 0.0848 - val_loss: -3.4439 - val_accuracy: 0.0500
Epoch 310/830
6/6 [==============================] - ETA: 0s - loss: -3.0044 - accuracy: 0.0879
Epoch 310: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.0044 - accuracy: 0.0879 - val_loss: -3.4629 - val_accuracy: 0.0000e+00
Epoch 311/830
6/6 [==============================] - ETA: 0s - loss: -3.0138 - accuracy: 0.0818
Epoch 311: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -3.0138 - accuracy: 0.0818 - val_loss: -3.4643 - val_accuracy: 0.0500
Epoch 312/830
6/6 [==============================] - ETA: 0s - loss: -3.0219 - accuracy: 0.0879
Epoch 312: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -3.0219 - accuracy: 0.0879 - val_loss: -3.4788 - val_accuracy: 0.0000e+00
Epoch 313/830
6/6 [==============================] - ETA: 0s - loss: -3.0305 - accuracy: 0.0879
Epoch 313: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -3.0305 - accuracy: 0.0879 - val_loss: -3.4817 - val_accuracy: 0.0500
Epoch 314/830
6/6 [==============================] - ETA: 0s - loss: -3.0386 - accuracy: 0.0879
Epoch 314: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 777ms/step - loss: -3.0386 - accuracy: 0.0879 - val_loss: -3.4868 - val_accuracy: 0.0500
Epoch 315/830
6/6 [==============================] - ETA: 0s - loss: -3.0494 - accuracy: 0.0909
Epoch 315: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 753ms/step - loss: -3.0494 - accuracy: 0.0909 - val_loss: -3.5021 - val_accuracy: 0.0500
Epoch 316/830
6/6 [==============================] - ETA: 0s - loss: -3.0598 - accuracy: 0.0879
Epoch 316: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -3.0598 - accuracy: 0.0879 - val_loss: -3.5048 - val_accuracy: 0.0500
Epoch 317/830
6/6 [==============================] - ETA: 0s - loss: -3.0694 - accuracy: 0.0909
Epoch 317: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -3.0694 - accuracy: 0.0909 - val_loss: -3.5262 - val_accuracy: 0.0250
Epoch 318/830
6/6 [==============================] - ETA: 0s - loss: -3.0798 - accuracy: 0.0879
Epoch 318: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -3.0798 - accuracy: 0.0879 - val_loss: -3.5316 - val_accuracy: 0.0500
Epoch 319/830
6/6 [==============================] - ETA: 0s - loss: -3.0874 - accuracy: 0.0848
Epoch 319: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -3.0874 - accuracy: 0.0848 - val_loss: -3.5421 - val_accuracy: 0.0250
Epoch 320/830
6/6 [==============================] - ETA: 0s - loss: -3.0975 - accuracy: 0.0879
Epoch 320: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -3.0975 - accuracy: 0.0879 - val_loss: -3.5602 - val_accuracy: 0.0000e+00
Epoch 321/830
6/6 [==============================] - ETA: 0s - loss: -3.1074 - accuracy: 0.0848
Epoch 321: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -3.1074 - accuracy: 0.0848 - val_loss: -3.5716 - val_accuracy: 0.0000e+00
Epoch 322/830
6/6 [==============================] - ETA: 0s - loss: -3.1172 - accuracy: 0.0818
Epoch 322: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -3.1172 - accuracy: 0.0818 - val_loss: -3.5822 - val_accuracy: 0.0000e+00
Epoch 323/830
6/6 [==============================] - ETA: 0s - loss: -3.1266 - accuracy: 0.0879
Epoch 323: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -3.1266 - accuracy: 0.0879 - val_loss: -3.5855 - val_accuracy: 0.0250
Epoch 324/830
6/6 [==============================] - ETA: 0s - loss: -3.1373 - accuracy: 0.0879
Epoch 324: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -3.1373 - accuracy: 0.0879 - val_loss: -3.5933 - val_accuracy: 0.0250
Epoch 325/830
6/6 [==============================] - ETA: 0s - loss: -3.1474 - accuracy: 0.0909
Epoch 325: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 755ms/step - loss: -3.1474 - accuracy: 0.0909 - val_loss: -3.6042 - val_accuracy: 0.0250
Epoch 326/830
6/6 [==============================] - ETA: 0s - loss: -3.1582 - accuracy: 0.0879
Epoch 326: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -3.1582 - accuracy: 0.0879 - val_loss: -3.6045 - val_accuracy: 0.0500
Epoch 327/830
6/6 [==============================] - ETA: 0s - loss: -3.1684 - accuracy: 0.0909
Epoch 327: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 806ms/step - loss: -3.1684 - accuracy: 0.0909 - val_loss: -3.6135 - val_accuracy: 0.0500
Epoch 328/830
6/6 [==============================] - ETA: 0s - loss: -3.1778 - accuracy: 0.0909
Epoch 328: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -3.1778 - accuracy: 0.0909 - val_loss: -3.6190 - val_accuracy: 0.0500
Epoch 329/830
6/6 [==============================] - ETA: 0s - loss: -3.1884 - accuracy: 0.0909
Epoch 329: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -3.1884 - accuracy: 0.0909 - val_loss: -3.6282 - val_accuracy: 0.0500
Epoch 330/830
6/6 [==============================] - ETA: 0s - loss: -3.1966 - accuracy: 0.0939
Epoch 330: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -3.1966 - accuracy: 0.0939 - val_loss: -3.6401 - val_accuracy: 0.0500
Epoch 331/830
6/6 [==============================] - ETA: 0s - loss: -3.2082 - accuracy: 0.0909
Epoch 331: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 800ms/step - loss: -3.2082 - accuracy: 0.0909 - val_loss: -3.6550 - val_accuracy: 0.0500
Epoch 332/830
6/6 [==============================] - ETA: 0s - loss: -3.2182 - accuracy: 0.0909
Epoch 332: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 792ms/step - loss: -3.2182 - accuracy: 0.0909 - val_loss: -3.6584 - val_accuracy: 0.0500
Epoch 333/830
6/6 [==============================] - ETA: 0s - loss: -3.2267 - accuracy: 0.0909
Epoch 333: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 793ms/step - loss: -3.2267 - accuracy: 0.0909 - val_loss: -3.6651 - val_accuracy: 0.0500
Epoch 334/830
6/6 [==============================] - ETA: 0s - loss: -3.2381 - accuracy: 0.0939
Epoch 334: saving model to training_1/cp.ckpt
6/6 [==============================] - 8s 896ms/step - loss: -3.2381 - accuracy: 0.0939 - val_loss: -3.6764 - val_accuracy: 0.0500
Epoch 335/830
6/6 [==============================] - ETA: 0s - loss: -3.2478 - accuracy: 0.0939
Epoch 335: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 760ms/step - loss: -3.2478 - accuracy: 0.0939 - val_loss: -3.6878 - val_accuracy: 0.0500
Epoch 336/830
6/6 [==============================] - ETA: 0s - loss: -3.2598 - accuracy: 0.0939
Epoch 336: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 777ms/step - loss: -3.2598 - accuracy: 0.0939 - val_loss: -3.7051 - val_accuracy: 0.0500
Epoch 337/830
6/6 [==============================] - ETA: 0s - loss: -3.2706 - accuracy: 0.0909
Epoch 337: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -3.2706 - accuracy: 0.0909 - val_loss: -3.7110 - val_accuracy: 0.0500
Epoch 338/830
6/6 [==============================] - ETA: 0s - loss: -3.2811 - accuracy: 0.0939
Epoch 338: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -3.2811 - accuracy: 0.0939 - val_loss: -3.7207 - val_accuracy: 0.0500
Epoch 339/830
6/6 [==============================] - ETA: 0s - loss: -3.2909 - accuracy: 0.0939
Epoch 339: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -3.2909 - accuracy: 0.0939 - val_loss: -3.7343 - val_accuracy: 0.0500
Epoch 340/830
6/6 [==============================] - ETA: 0s - loss: -3.3025 - accuracy: 0.0939
Epoch 340: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 773ms/step - loss: -3.3025 - accuracy: 0.0939 - val_loss: -3.7476 - val_accuracy: 0.0500
Epoch 341/830
6/6 [==============================] - ETA: 0s - loss: -3.3133 - accuracy: 0.0939
Epoch 341: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -3.3133 - accuracy: 0.0939 - val_loss: -3.7586 - val_accuracy: 0.0500
Epoch 342/830
6/6 [==============================] - ETA: 0s - loss: -3.3245 - accuracy: 0.0939
Epoch 342: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -3.3245 - accuracy: 0.0939 - val_loss: -3.7655 - val_accuracy: 0.0500
Epoch 343/830
6/6 [==============================] - ETA: 0s - loss: -3.3358 - accuracy: 0.0939
Epoch 343: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -3.3358 - accuracy: 0.0939 - val_loss: -3.7773 - val_accuracy: 0.0500
Epoch 344/830
6/6 [==============================] - ETA: 0s - loss: -3.3468 - accuracy: 0.0939
Epoch 344: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -3.3468 - accuracy: 0.0939 - val_loss: -3.7943 - val_accuracy: 0.0500
Epoch 345/830
6/6 [==============================] - ETA: 0s - loss: -3.3580 - accuracy: 0.0939
Epoch 345: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -3.3580 - accuracy: 0.0939 - val_loss: -3.8093 - val_accuracy: 0.0500
Epoch 346/830
6/6 [==============================] - ETA: 0s - loss: -3.3703 - accuracy: 0.0939
Epoch 346: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -3.3703 - accuracy: 0.0939 - val_loss: -3.8265 - val_accuracy: 0.0500
Epoch 347/830
6/6 [==============================] - ETA: 0s - loss: -3.3814 - accuracy: 0.0939
Epoch 347: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -3.3814 - accuracy: 0.0939 - val_loss: -3.8452 - val_accuracy: 0.0250
Epoch 348/830
6/6 [==============================] - ETA: 0s - loss: -3.3920 - accuracy: 0.0909
Epoch 348: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -3.3920 - accuracy: 0.0909 - val_loss: -3.8584 - val_accuracy: 0.0250
Epoch 349/830
6/6 [==============================] - ETA: 0s - loss: -3.4015 - accuracy: 0.0879
Epoch 349: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 806ms/step - loss: -3.4015 - accuracy: 0.0879 - val_loss: -3.8568 - val_accuracy: 0.0500
Epoch 350/830
6/6 [==============================] - ETA: 0s - loss: -3.4104 - accuracy: 0.0909
Epoch 350: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -3.4104 - accuracy: 0.0909 - val_loss: -3.8601 - val_accuracy: 0.0500
Epoch 351/830
6/6 [==============================] - ETA: 0s - loss: -3.4196 - accuracy: 0.0939
Epoch 351: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -3.4196 - accuracy: 0.0939 - val_loss: -3.8677 - val_accuracy: 0.0500
Epoch 352/830
6/6 [==============================] - ETA: 0s - loss: -3.4282 - accuracy: 0.0939
Epoch 352: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -3.4282 - accuracy: 0.0939 - val_loss: -3.8834 - val_accuracy: 0.0500
Epoch 353/830
6/6 [==============================] - ETA: 0s - loss: -3.4394 - accuracy: 0.0939
Epoch 353: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.4394 - accuracy: 0.0939 - val_loss: -3.8967 - val_accuracy: 0.0500
Epoch 354/830
6/6 [==============================] - ETA: 0s - loss: -3.4502 - accuracy: 0.0939
Epoch 354: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: -3.4502 - accuracy: 0.0939 - val_loss: -3.9013 - val_accuracy: 0.0500
Epoch 355/830
6/6 [==============================] - ETA: 0s - loss: -3.4583 - accuracy: 0.0939
Epoch 355: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 755ms/step - loss: -3.4583 - accuracy: 0.0939 - val_loss: -3.9093 - val_accuracy: 0.0500
Epoch 356/830
6/6 [==============================] - ETA: 0s - loss: -3.4700 - accuracy: 0.0939
Epoch 356: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 754ms/step - loss: -3.4700 - accuracy: 0.0939 - val_loss: -3.9170 - val_accuracy: 0.0500
Epoch 357/830
6/6 [==============================] - ETA: 0s - loss: -3.4806 - accuracy: 0.0939
Epoch 357: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -3.4806 - accuracy: 0.0939 - val_loss: -3.9254 - val_accuracy: 0.0500
Epoch 358/830
6/6 [==============================] - ETA: 0s - loss: -3.4905 - accuracy: 0.0939
Epoch 358: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -3.4905 - accuracy: 0.0939 - val_loss: -3.9353 - val_accuracy: 0.0500
Epoch 359/830
6/6 [==============================] - ETA: 0s - loss: -3.5021 - accuracy: 0.0939
Epoch 359: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 773ms/step - loss: -3.5021 - accuracy: 0.0939 - val_loss: -3.9371 - val_accuracy: 0.0500
Epoch 360/830
6/6 [==============================] - ETA: 0s - loss: -3.5105 - accuracy: 0.0939
Epoch 360: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -3.5105 - accuracy: 0.0939 - val_loss: -3.9417 - val_accuracy: 0.0500
Epoch 361/830
6/6 [==============================] - ETA: 0s - loss: -3.5210 - accuracy: 0.0970
Epoch 361: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -3.5210 - accuracy: 0.0970 - val_loss: -3.9490 - val_accuracy: 0.0500
Epoch 362/830
6/6 [==============================] - ETA: 0s - loss: -3.5302 - accuracy: 0.1000
Epoch 362: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -3.5302 - accuracy: 0.1000 - val_loss: -3.9525 - val_accuracy: 0.0500
Epoch 363/830
6/6 [==============================] - ETA: 0s - loss: -3.5397 - accuracy: 0.1030
Epoch 363: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.5397 - accuracy: 0.1030 - val_loss: -3.9751 - val_accuracy: 0.0500
Epoch 364/830
6/6 [==============================] - ETA: 0s - loss: -3.5502 - accuracy: 0.0970
Epoch 364: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.5502 - accuracy: 0.0970 - val_loss: -3.9739 - val_accuracy: 0.0500
Epoch 365/830
6/6 [==============================] - ETA: 0s - loss: -3.5568 - accuracy: 0.1000
Epoch 365: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -3.5568 - accuracy: 0.1000 - val_loss: -3.9788 - val_accuracy: 0.0500
Epoch 366/830
6/6 [==============================] - ETA: 0s - loss: -3.5635 - accuracy: 0.1000
Epoch 366: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 798ms/step - loss: -3.5635 - accuracy: 0.1000 - val_loss: -3.9979 - val_accuracy: 0.0500
Epoch 367/830
6/6 [==============================] - ETA: 0s - loss: -3.5734 - accuracy: 0.1000
Epoch 367: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.5734 - accuracy: 0.1000 - val_loss: -4.0127 - val_accuracy: 0.0500
Epoch 368/830
6/6 [==============================] - ETA: 0s - loss: -3.5814 - accuracy: 0.0939
Epoch 368: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -3.5814 - accuracy: 0.0939 - val_loss: -4.0219 - val_accuracy: 0.0500
Epoch 369/830
6/6 [==============================] - ETA: 0s - loss: -3.5916 - accuracy: 0.0970
Epoch 369: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -3.5916 - accuracy: 0.0970 - val_loss: -4.0313 - val_accuracy: 0.0500
Epoch 370/830
6/6 [==============================] - ETA: 0s - loss: -3.6000 - accuracy: 0.0939
Epoch 370: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 755ms/step - loss: -3.6000 - accuracy: 0.0939 - val_loss: -4.0515 - val_accuracy: 0.0500
Epoch 371/830
6/6 [==============================] - ETA: 0s - loss: -3.6103 - accuracy: 0.0939
Epoch 371: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -3.6103 - accuracy: 0.0939 - val_loss: -4.0556 - val_accuracy: 0.0500
Epoch 372/830
6/6 [==============================] - ETA: 0s - loss: -3.6180 - accuracy: 0.0939
Epoch 372: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -3.6180 - accuracy: 0.0939 - val_loss: -4.0659 - val_accuracy: 0.0500
Epoch 373/830
6/6 [==============================] - ETA: 0s - loss: -3.6273 - accuracy: 0.0939
Epoch 373: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 780ms/step - loss: -3.6273 - accuracy: 0.0939 - val_loss: -4.0731 - val_accuracy: 0.0500
Epoch 374/830
6/6 [==============================] - ETA: 0s - loss: -3.6367 - accuracy: 0.0939
Epoch 374: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 755ms/step - loss: -3.6367 - accuracy: 0.0939 - val_loss: -4.0825 - val_accuracy: 0.0500
Epoch 375/830
6/6 [==============================] - ETA: 0s - loss: -3.6466 - accuracy: 0.0939
Epoch 375: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -3.6466 - accuracy: 0.0939 - val_loss: -4.0962 - val_accuracy: 0.0500
Epoch 376/830
6/6 [==============================] - ETA: 0s - loss: -3.6568 - accuracy: 0.0939
Epoch 376: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -3.6568 - accuracy: 0.0939 - val_loss: -4.1037 - val_accuracy: 0.0500
Epoch 377/830
6/6 [==============================] - ETA: 0s - loss: -3.6679 - accuracy: 0.0939
Epoch 377: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 799ms/step - loss: -3.6679 - accuracy: 0.0939 - val_loss: -4.1102 - val_accuracy: 0.0500
Epoch 378/830
6/6 [==============================] - ETA: 0s - loss: -3.6782 - accuracy: 0.0939
Epoch 378: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -3.6782 - accuracy: 0.0939 - val_loss: -4.1306 - val_accuracy: 0.0500
Epoch 379/830
6/6 [==============================] - ETA: 0s - loss: -3.6889 - accuracy: 0.0939
Epoch 379: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.6889 - accuracy: 0.0939 - val_loss: -4.1377 - val_accuracy: 0.0500
Epoch 380/830
6/6 [==============================] - ETA: 0s - loss: -3.6995 - accuracy: 0.0970
Epoch 380: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.6995 - accuracy: 0.0970 - val_loss: -4.1440 - val_accuracy: 0.0500
Epoch 381/830
6/6 [==============================] - ETA: 0s - loss: -3.7073 - accuracy: 0.0939
Epoch 381: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.7073 - accuracy: 0.0939 - val_loss: -4.1496 - val_accuracy: 0.0500
Epoch 382/830
6/6 [==============================] - ETA: 0s - loss: -3.7180 - accuracy: 0.0970
Epoch 382: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 775ms/step - loss: -3.7180 - accuracy: 0.0970 - val_loss: -4.1501 - val_accuracy: 0.0500
Epoch 383/830
6/6 [==============================] - ETA: 0s - loss: -3.7259 - accuracy: 0.1000
Epoch 383: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.7259 - accuracy: 0.1000 - val_loss: -4.1595 - val_accuracy: 0.0500
Epoch 384/830
6/6 [==============================] - ETA: 0s - loss: -3.7352 - accuracy: 0.0970
Epoch 384: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -3.7352 - accuracy: 0.0970 - val_loss: -4.1643 - val_accuracy: 0.0500
Epoch 385/830
6/6 [==============================] - ETA: 0s - loss: -3.7441 - accuracy: 0.1000
Epoch 385: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -3.7441 - accuracy: 0.1000 - val_loss: -4.1839 - val_accuracy: 0.0500
Epoch 386/830
6/6 [==============================] - ETA: 0s - loss: -3.7554 - accuracy: 0.1000
Epoch 386: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -3.7554 - accuracy: 0.1000 - val_loss: -4.1855 - val_accuracy: 0.0500
Epoch 387/830
6/6 [==============================] - ETA: 0s - loss: -3.7623 - accuracy: 0.1000
Epoch 387: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -3.7623 - accuracy: 0.1000 - val_loss: -4.2035 - val_accuracy: 0.0500
Epoch 388/830
6/6 [==============================] - ETA: 0s - loss: -3.7728 - accuracy: 0.1000
Epoch 388: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.7728 - accuracy: 0.1000 - val_loss: -4.2140 - val_accuracy: 0.0500
Epoch 389/830
6/6 [==============================] - ETA: 0s - loss: -3.7823 - accuracy: 0.1000
Epoch 389: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.7823 - accuracy: 0.1000 - val_loss: -4.2141 - val_accuracy: 0.0500
Epoch 390/830
6/6 [==============================] - ETA: 0s - loss: -3.7895 - accuracy: 0.1000
Epoch 390: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.7895 - accuracy: 0.1000 - val_loss: -4.2267 - val_accuracy: 0.0500
Epoch 391/830
6/6 [==============================] - ETA: 0s - loss: -3.7994 - accuracy: 0.0970
Epoch 391: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.7994 - accuracy: 0.0970 - val_loss: -4.2319 - val_accuracy: 0.0500
Epoch 392/830
6/6 [==============================] - ETA: 0s - loss: -3.8085 - accuracy: 0.1000
Epoch 392: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -3.8085 - accuracy: 0.1000 - val_loss: -4.2519 - val_accuracy: 0.0500
Epoch 393/830
6/6 [==============================] - ETA: 0s - loss: -3.8187 - accuracy: 0.1000
Epoch 393: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -3.8187 - accuracy: 0.1000 - val_loss: -4.2671 - val_accuracy: 0.0500
Epoch 394/830
6/6 [==============================] - ETA: 0s - loss: -3.8292 - accuracy: 0.0970
Epoch 394: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -3.8292 - accuracy: 0.0970 - val_loss: -4.2723 - val_accuracy: 0.0500
Epoch 395/830
6/6 [==============================] - ETA: 0s - loss: -3.8388 - accuracy: 0.1000
Epoch 395: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 808ms/step - loss: -3.8388 - accuracy: 0.1000 - val_loss: -4.2856 - val_accuracy: 0.0500
Epoch 396/830
6/6 [==============================] - ETA: 0s - loss: -3.8487 - accuracy: 0.0970
Epoch 396: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -3.8487 - accuracy: 0.0970 - val_loss: -4.3000 - val_accuracy: 0.0500
Epoch 397/830
6/6 [==============================] - ETA: 0s - loss: -3.8595 - accuracy: 0.0970
Epoch 397: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -3.8595 - accuracy: 0.0970 - val_loss: -4.3076 - val_accuracy: 0.0500
Epoch 398/830
6/6 [==============================] - ETA: 0s - loss: -3.8691 - accuracy: 0.0970
Epoch 398: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -3.8691 - accuracy: 0.0970 - val_loss: -4.3094 - val_accuracy: 0.0500
Epoch 399/830
6/6 [==============================] - ETA: 0s - loss: -3.8781 - accuracy: 0.1000
Epoch 399: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.8781 - accuracy: 0.1000 - val_loss: -4.3232 - val_accuracy: 0.0500
Epoch 400/830
6/6 [==============================] - ETA: 0s - loss: -3.8892 - accuracy: 0.1000
Epoch 400: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 777ms/step - loss: -3.8892 - accuracy: 0.1000 - val_loss: -4.3251 - val_accuracy: 0.0500
Epoch 401/830
6/6 [==============================] - ETA: 0s - loss: -3.8977 - accuracy: 0.1000
Epoch 401: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -3.8977 - accuracy: 0.1000 - val_loss: -4.3308 - val_accuracy: 0.0500
Epoch 402/830
6/6 [==============================] - ETA: 0s - loss: -3.9050 - accuracy: 0.1091
Epoch 402: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -3.9050 - accuracy: 0.1091 - val_loss: -4.3464 - val_accuracy: 0.0500
Epoch 403/830
6/6 [==============================] - ETA: 0s - loss: -3.9156 - accuracy: 0.1000
Epoch 403: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -3.9156 - accuracy: 0.1000 - val_loss: -4.3517 - val_accuracy: 0.0500
Epoch 404/830
6/6 [==============================] - ETA: 0s - loss: -3.9246 - accuracy: 0.1000
Epoch 404: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -3.9246 - accuracy: 0.1000 - val_loss: -4.3576 - val_accuracy: 0.0500
Epoch 405/830
6/6 [==============================] - ETA: 0s - loss: -3.9327 - accuracy: 0.1030
Epoch 405: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -3.9327 - accuracy: 0.1030 - val_loss: -4.3594 - val_accuracy: 0.0500
Epoch 406/830
6/6 [==============================] - ETA: 0s - loss: -3.9419 - accuracy: 0.1121
Epoch 406: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -3.9419 - accuracy: 0.1121 - val_loss: -4.3630 - val_accuracy: 0.0500
Epoch 407/830
6/6 [==============================] - ETA: 0s - loss: -3.9505 - accuracy: 0.1152
Epoch 407: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 802ms/step - loss: -3.9505 - accuracy: 0.1152 - val_loss: -4.3670 - val_accuracy: 0.0500
Epoch 408/830
6/6 [==============================] - ETA: 0s - loss: -3.9570 - accuracy: 0.1152
Epoch 408: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -3.9570 - accuracy: 0.1152 - val_loss: -4.3826 - val_accuracy: 0.0500
Epoch 409/830
6/6 [==============================] - ETA: 0s - loss: -3.9689 - accuracy: 0.1152
Epoch 409: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -3.9689 - accuracy: 0.1152 - val_loss: -4.3860 - val_accuracy: 0.0500
Epoch 410/830
6/6 [==============================] - ETA: 0s - loss: -3.9767 - accuracy: 0.1152
Epoch 410: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -3.9767 - accuracy: 0.1152 - val_loss: -4.3886 - val_accuracy: 0.0500
Epoch 411/830
6/6 [==============================] - ETA: 0s - loss: -3.9843 - accuracy: 0.1152
Epoch 411: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -3.9843 - accuracy: 0.1152 - val_loss: -4.4088 - val_accuracy: 0.0500
Epoch 412/830
6/6 [==============================] - ETA: 0s - loss: -3.9956 - accuracy: 0.1152
Epoch 412: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -3.9956 - accuracy: 0.1152 - val_loss: -4.4260 - val_accuracy: 0.0500
Epoch 413/830
6/6 [==============================] - ETA: 0s - loss: -4.0050 - accuracy: 0.1061
Epoch 413: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 814ms/step - loss: -4.0050 - accuracy: 0.1061 - val_loss: -4.4342 - val_accuracy: 0.0500
Epoch 414/830
6/6 [==============================] - ETA: 0s - loss: -4.0133 - accuracy: 0.1061
Epoch 414: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -4.0133 - accuracy: 0.1061 - val_loss: -4.4407 - val_accuracy: 0.0500
Epoch 415/830
6/6 [==============================] - ETA: 0s - loss: -4.0225 - accuracy: 0.1061
Epoch 415: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -4.0225 - accuracy: 0.1061 - val_loss: -4.4467 - val_accuracy: 0.0500
Epoch 416/830
6/6 [==============================] - ETA: 0s - loss: -4.0321 - accuracy: 0.1152
Epoch 416: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -4.0321 - accuracy: 0.1152 - val_loss: -4.4642 - val_accuracy: 0.0500
Epoch 417/830
6/6 [==============================] - ETA: 0s - loss: -4.0432 - accuracy: 0.1091
Epoch 417: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 812ms/step - loss: -4.0432 - accuracy: 0.1091 - val_loss: -4.4829 - val_accuracy: 0.0500
Epoch 418/830
6/6 [==============================] - ETA: 0s - loss: -4.0535 - accuracy: 0.1030
Epoch 418: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -4.0535 - accuracy: 0.1030 - val_loss: -4.4861 - val_accuracy: 0.0500
Epoch 419/830
6/6 [==============================] - ETA: 0s - loss: -4.0636 - accuracy: 0.1061
Epoch 419: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -4.0636 - accuracy: 0.1061 - val_loss: -4.5000 - val_accuracy: 0.0500
Epoch 420/830
6/6 [==============================] - ETA: 0s - loss: -4.0731 - accuracy: 0.1030
Epoch 420: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -4.0731 - accuracy: 0.1030 - val_loss: -4.5070 - val_accuracy: 0.0500
Epoch 421/830
6/6 [==============================] - ETA: 0s - loss: -4.0835 - accuracy: 0.1061
Epoch 421: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -4.0835 - accuracy: 0.1061 - val_loss: -4.5189 - val_accuracy: 0.0500
Epoch 422/830
6/6 [==============================] - ETA: 0s - loss: -4.0940 - accuracy: 0.1091
Epoch 422: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 806ms/step - loss: -4.0940 - accuracy: 0.1091 - val_loss: -4.5317 - val_accuracy: 0.0500
Epoch 423/830
6/6 [==============================] - ETA: 0s - loss: -4.1053 - accuracy: 0.1091
Epoch 423: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -4.1053 - accuracy: 0.1091 - val_loss: -4.5528 - val_accuracy: 0.0500
Epoch 424/830
6/6 [==============================] - ETA: 0s - loss: -4.1171 - accuracy: 0.1000
Epoch 424: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.1171 - accuracy: 0.1000 - val_loss: -4.5722 - val_accuracy: 0.0500
Epoch 425/830
6/6 [==============================] - ETA: 0s - loss: -4.1271 - accuracy: 0.1000
Epoch 425: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -4.1271 - accuracy: 0.1000 - val_loss: -4.5793 - val_accuracy: 0.0500
Epoch 426/830
6/6 [==============================] - ETA: 0s - loss: -4.1369 - accuracy: 0.1000
Epoch 426: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 807ms/step - loss: -4.1369 - accuracy: 0.1000 - val_loss: -4.5811 - val_accuracy: 0.0500
Epoch 427/830
6/6 [==============================] - ETA: 0s - loss: -4.1448 - accuracy: 0.1000
Epoch 427: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -4.1448 - accuracy: 0.1000 - val_loss: -4.5993 - val_accuracy: 0.0500
Epoch 428/830
6/6 [==============================] - ETA: 0s - loss: -4.1559 - accuracy: 0.1000
Epoch 428: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -4.1559 - accuracy: 0.1000 - val_loss: -4.6096 - val_accuracy: 0.0500
Epoch 429/830
6/6 [==============================] - ETA: 0s - loss: -4.1664 - accuracy: 0.1000
Epoch 429: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.1664 - accuracy: 0.1000 - val_loss: -4.6243 - val_accuracy: 0.0500
Epoch 430/830
6/6 [==============================] - ETA: 0s - loss: -4.1745 - accuracy: 0.1000
Epoch 430: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -4.1745 - accuracy: 0.1000 - val_loss: -4.6383 - val_accuracy: 0.0500
Epoch 431/830
6/6 [==============================] - ETA: 0s - loss: -4.1872 - accuracy: 0.0970
Epoch 431: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 784ms/step - loss: -4.1872 - accuracy: 0.0970 - val_loss: -4.6404 - val_accuracy: 0.0500
Epoch 432/830
6/6 [==============================] - ETA: 0s - loss: -4.1962 - accuracy: 0.1000
Epoch 432: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -4.1962 - accuracy: 0.1000 - val_loss: -4.6433 - val_accuracy: 0.0500
Epoch 433/830
6/6 [==============================] - ETA: 0s - loss: -4.2050 - accuracy: 0.1000
Epoch 433: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -4.2050 - accuracy: 0.1000 - val_loss: -4.6465 - val_accuracy: 0.0500
Epoch 434/830
6/6 [==============================] - ETA: 0s - loss: -4.2134 - accuracy: 0.1030
Epoch 434: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.2134 - accuracy: 0.1030 - val_loss: -4.6593 - val_accuracy: 0.0500
Epoch 435/830
6/6 [==============================] - ETA: 0s - loss: -4.2242 - accuracy: 0.1061
Epoch 435: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.2242 - accuracy: 0.1061 - val_loss: -4.6668 - val_accuracy: 0.0500
Epoch 436/830
6/6 [==============================] - ETA: 0s - loss: -4.2337 - accuracy: 0.1030
Epoch 436: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -4.2337 - accuracy: 0.1030 - val_loss: -4.6771 - val_accuracy: 0.0500
Epoch 437/830
6/6 [==============================] - ETA: 0s - loss: -4.2442 - accuracy: 0.1030
Epoch 437: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.2442 - accuracy: 0.1030 - val_loss: -4.6912 - val_accuracy: 0.0500
Epoch 438/830
6/6 [==============================] - ETA: 0s - loss: -4.2550 - accuracy: 0.1061
Epoch 438: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -4.2550 - accuracy: 0.1061 - val_loss: -4.7095 - val_accuracy: 0.0500
Epoch 439/830
6/6 [==============================] - ETA: 0s - loss: -4.2653 - accuracy: 0.1000
Epoch 439: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -4.2653 - accuracy: 0.1000 - val_loss: -4.7165 - val_accuracy: 0.0500
Epoch 440/830
6/6 [==============================] - ETA: 0s - loss: -4.2761 - accuracy: 0.1061
Epoch 440: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 786ms/step - loss: -4.2761 - accuracy: 0.1061 - val_loss: -4.7335 - val_accuracy: 0.0500
Epoch 441/830
6/6 [==============================] - ETA: 0s - loss: -4.2881 - accuracy: 0.1000
Epoch 441: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.2881 - accuracy: 0.1000 - val_loss: -4.7494 - val_accuracy: 0.0500
Epoch 442/830
6/6 [==============================] - ETA: 0s - loss: -4.2990 - accuracy: 0.1000
Epoch 442: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -4.2990 - accuracy: 0.1000 - val_loss: -4.7492 - val_accuracy: 0.0500
Epoch 443/830
6/6 [==============================] - ETA: 0s - loss: -4.3076 - accuracy: 0.1030
Epoch 443: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -4.3076 - accuracy: 0.1030 - val_loss: -4.7509 - val_accuracy: 0.0500
Epoch 444/830
6/6 [==============================] - ETA: 0s - loss: -4.3157 - accuracy: 0.1061
Epoch 444: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -4.3157 - accuracy: 0.1061 - val_loss: -4.7655 - val_accuracy: 0.0500
Epoch 445/830
6/6 [==============================] - ETA: 0s - loss: -4.3252 - accuracy: 0.1061
Epoch 445: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 804ms/step - loss: -4.3252 - accuracy: 0.1061 - val_loss: -4.7849 - val_accuracy: 0.0500
Epoch 446/830
6/6 [==============================] - ETA: 0s - loss: -4.3360 - accuracy: 0.1000
Epoch 446: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -4.3360 - accuracy: 0.1000 - val_loss: -4.7909 - val_accuracy: 0.0500
Epoch 447/830
6/6 [==============================] - ETA: 0s - loss: -4.3445 - accuracy: 0.1030
Epoch 447: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.3445 - accuracy: 0.1030 - val_loss: -4.8012 - val_accuracy: 0.0500
Epoch 448/830
6/6 [==============================] - ETA: 0s - loss: -4.3548 - accuracy: 0.1000
Epoch 448: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -4.3548 - accuracy: 0.1000 - val_loss: -4.8185 - val_accuracy: 0.0500
Epoch 449/830
6/6 [==============================] - ETA: 0s - loss: -4.3660 - accuracy: 0.1000
Epoch 449: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -4.3660 - accuracy: 0.1000 - val_loss: -4.8336 - val_accuracy: 0.0500
Epoch 450/830
6/6 [==============================] - ETA: 0s - loss: -4.3764 - accuracy: 0.1000
Epoch 450: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 775ms/step - loss: -4.3764 - accuracy: 0.1000 - val_loss: -4.8531 - val_accuracy: 0.0500
Epoch 451/830
6/6 [==============================] - ETA: 0s - loss: -4.3863 - accuracy: 0.0970
Epoch 451: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.3863 - accuracy: 0.0970 - val_loss: -4.8617 - val_accuracy: 0.0500
Epoch 452/830
6/6 [==============================] - ETA: 0s - loss: -4.3965 - accuracy: 0.0970
Epoch 452: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -4.3965 - accuracy: 0.0970 - val_loss: -4.8718 - val_accuracy: 0.0500
Epoch 453/830
6/6 [==============================] - ETA: 0s - loss: -4.4066 - accuracy: 0.0970
Epoch 453: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -4.4066 - accuracy: 0.0970 - val_loss: -4.8750 - val_accuracy: 0.0500
Epoch 454/830
6/6 [==============================] - ETA: 0s - loss: -4.4168 - accuracy: 0.1000
Epoch 454: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -4.4168 - accuracy: 0.1000 - val_loss: -4.8921 - val_accuracy: 0.0500
Epoch 455/830
6/6 [==============================] - ETA: 0s - loss: -4.4283 - accuracy: 0.1000
Epoch 455: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 813ms/step - loss: -4.4283 - accuracy: 0.1000 - val_loss: -4.9002 - val_accuracy: 0.0500
Epoch 456/830
6/6 [==============================] - ETA: 0s - loss: -4.4377 - accuracy: 0.1000
Epoch 456: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.4377 - accuracy: 0.1000 - val_loss: -4.9023 - val_accuracy: 0.0500
Epoch 457/830
6/6 [==============================] - ETA: 0s - loss: -4.4480 - accuracy: 0.1000
Epoch 457: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -4.4480 - accuracy: 0.1000 - val_loss: -4.9124 - val_accuracy: 0.0500
Epoch 458/830
6/6 [==============================] - ETA: 0s - loss: -4.4578 - accuracy: 0.1000
Epoch 458: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -4.4578 - accuracy: 0.1000 - val_loss: -4.9187 - val_accuracy: 0.0500
Epoch 459/830
6/6 [==============================] - ETA: 0s - loss: -4.4680 - accuracy: 0.1030
Epoch 459: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 801ms/step - loss: -4.4680 - accuracy: 0.1030 - val_loss: -4.9338 - val_accuracy: 0.0500
Epoch 460/830
6/6 [==============================] - ETA: 0s - loss: -4.4794 - accuracy: 0.1000
Epoch 460: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -4.4794 - accuracy: 0.1000 - val_loss: -4.9494 - val_accuracy: 0.0500
Epoch 461/830
6/6 [==============================] - ETA: 0s - loss: -4.4897 - accuracy: 0.1000
Epoch 461: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -4.4897 - accuracy: 0.1000 - val_loss: -4.9594 - val_accuracy: 0.0500
Epoch 462/830
6/6 [==============================] - ETA: 0s - loss: -4.5010 - accuracy: 0.1000
Epoch 462: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.5010 - accuracy: 0.1000 - val_loss: -4.9668 - val_accuracy: 0.0500
Epoch 463/830
6/6 [==============================] - ETA: 0s - loss: -4.5110 - accuracy: 0.1030
Epoch 463: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -4.5110 - accuracy: 0.1030 - val_loss: -4.9744 - val_accuracy: 0.0500
Epoch 464/830
6/6 [==============================] - ETA: 0s - loss: -4.5205 - accuracy: 0.1061
Epoch 464: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 820ms/step - loss: -4.5205 - accuracy: 0.1061 - val_loss: -4.9923 - val_accuracy: 0.0500
Epoch 465/830
6/6 [==============================] - ETA: 0s - loss: -4.5319 - accuracy: 0.1000
Epoch 465: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -4.5319 - accuracy: 0.1000 - val_loss: -5.0044 - val_accuracy: 0.0500
Epoch 466/830
6/6 [==============================] - ETA: 0s - loss: -4.5420 - accuracy: 0.1000
Epoch 466: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -4.5420 - accuracy: 0.1000 - val_loss: -5.0040 - val_accuracy: 0.0500
Epoch 467/830
6/6 [==============================] - ETA: 0s - loss: -4.5499 - accuracy: 0.1061
Epoch 467: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -4.5499 - accuracy: 0.1061 - val_loss: -5.0145 - val_accuracy: 0.0500
Epoch 468/830
6/6 [==============================] - ETA: 0s - loss: -4.5599 - accuracy: 0.1000
Epoch 468: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -4.5599 - accuracy: 0.1000 - val_loss: -5.0311 - val_accuracy: 0.0500
Epoch 469/830
6/6 [==============================] - ETA: 0s - loss: -4.5691 - accuracy: 0.1000
Epoch 469: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.5691 - accuracy: 0.1000 - val_loss: -5.0330 - val_accuracy: 0.0500
Epoch 470/830
6/6 [==============================] - ETA: 0s - loss: -4.5784 - accuracy: 0.1030
Epoch 470: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -4.5784 - accuracy: 0.1030 - val_loss: -5.0425 - val_accuracy: 0.0500
Epoch 471/830
6/6 [==============================] - ETA: 0s - loss: -4.5886 - accuracy: 0.1000
Epoch 471: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -4.5886 - accuracy: 0.1000 - val_loss: -5.0440 - val_accuracy: 0.0500
Epoch 472/830
6/6 [==============================] - ETA: 0s - loss: -4.5965 - accuracy: 0.1091
Epoch 472: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -4.5965 - accuracy: 0.1091 - val_loss: -5.0531 - val_accuracy: 0.0500
Epoch 473/830
6/6 [==============================] - ETA: 0s - loss: -4.6058 - accuracy: 0.1091
Epoch 473: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 756ms/step - loss: -4.6058 - accuracy: 0.1091 - val_loss: -5.0626 - val_accuracy: 0.0500
Epoch 474/830
6/6 [==============================] - ETA: 0s - loss: -4.6171 - accuracy: 0.1091
Epoch 474: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 759ms/step - loss: -4.6171 - accuracy: 0.1091 - val_loss: -5.0720 - val_accuracy: 0.0500
Epoch 475/830
6/6 [==============================] - ETA: 0s - loss: -4.6270 - accuracy: 0.1091
Epoch 475: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -4.6270 - accuracy: 0.1091 - val_loss: -5.0769 - val_accuracy: 0.0500
Epoch 476/830
6/6 [==============================] - ETA: 0s - loss: -4.6352 - accuracy: 0.1091
Epoch 476: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -4.6352 - accuracy: 0.1091 - val_loss: -5.0847 - val_accuracy: 0.0500
Epoch 477/830
6/6 [==============================] - ETA: 0s - loss: -4.6461 - accuracy: 0.1091
Epoch 477: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.6461 - accuracy: 0.1091 - val_loss: -5.1023 - val_accuracy: 0.0500
Epoch 478/830
6/6 [==============================] - ETA: 0s - loss: -4.6576 - accuracy: 0.1091
Epoch 478: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -4.6576 - accuracy: 0.1091 - val_loss: -5.1163 - val_accuracy: 0.0500
Epoch 479/830
6/6 [==============================] - ETA: 0s - loss: -4.6687 - accuracy: 0.1091
Epoch 479: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -4.6687 - accuracy: 0.1091 - val_loss: -5.1194 - val_accuracy: 0.0500
Epoch 480/830
6/6 [==============================] - ETA: 0s - loss: -4.6781 - accuracy: 0.1091
Epoch 480: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -4.6781 - accuracy: 0.1091 - val_loss: -5.1395 - val_accuracy: 0.0500
Epoch 481/830
6/6 [==============================] - ETA: 0s - loss: -4.6897 - accuracy: 0.1091
Epoch 481: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 757ms/step - loss: -4.6897 - accuracy: 0.1091 - val_loss: -5.1520 - val_accuracy: 0.0500
Epoch 482/830
6/6 [==============================] - ETA: 0s - loss: -4.6997 - accuracy: 0.1091
Epoch 482: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -4.6997 - accuracy: 0.1091 - val_loss: -5.1677 - val_accuracy: 0.0500
Epoch 483/830
6/6 [==============================] - ETA: 0s - loss: -4.7103 - accuracy: 0.1061
Epoch 483: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.7103 - accuracy: 0.1061 - val_loss: -5.1793 - val_accuracy: 0.0500
Epoch 484/830
6/6 [==============================] - ETA: 0s - loss: -4.7208 - accuracy: 0.1091
Epoch 484: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -4.7208 - accuracy: 0.1091 - val_loss: -5.1916 - val_accuracy: 0.0500
Epoch 485/830
6/6 [==============================] - ETA: 0s - loss: -4.7312 - accuracy: 0.1061
Epoch 485: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 784ms/step - loss: -4.7312 - accuracy: 0.1061 - val_loss: -5.1906 - val_accuracy: 0.0500
Epoch 486/830
6/6 [==============================] - ETA: 0s - loss: -4.7399 - accuracy: 0.1091
Epoch 486: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -4.7399 - accuracy: 0.1091 - val_loss: -5.2061 - val_accuracy: 0.0500
Epoch 487/830
6/6 [==============================] - ETA: 0s - loss: -4.7505 - accuracy: 0.1091
Epoch 487: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 800ms/step - loss: -4.7505 - accuracy: 0.1091 - val_loss: -5.2213 - val_accuracy: 0.0500
Epoch 488/830
6/6 [==============================] - ETA: 0s - loss: -4.7608 - accuracy: 0.1061
Epoch 488: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.7608 - accuracy: 0.1061 - val_loss: -5.2264 - val_accuracy: 0.0500
Epoch 489/830
6/6 [==============================] - ETA: 0s - loss: -4.7694 - accuracy: 0.1091
Epoch 489: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -4.7694 - accuracy: 0.1091 - val_loss: -5.2295 - val_accuracy: 0.0500
Epoch 490/830
6/6 [==============================] - ETA: 0s - loss: -4.7788 - accuracy: 0.1091
Epoch 490: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -4.7788 - accuracy: 0.1091 - val_loss: -5.2431 - val_accuracy: 0.0500
Epoch 491/830
6/6 [==============================] - ETA: 0s - loss: -4.7898 - accuracy: 0.1091
Epoch 491: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -4.7898 - accuracy: 0.1091 - val_loss: -5.2570 - val_accuracy: 0.0500
Epoch 492/830
6/6 [==============================] - ETA: 0s - loss: -4.8007 - accuracy: 0.1091
Epoch 492: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.8007 - accuracy: 0.1091 - val_loss: -5.2683 - val_accuracy: 0.0500
Epoch 493/830
6/6 [==============================] - ETA: 0s - loss: -4.8117 - accuracy: 0.1091
Epoch 493: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -4.8117 - accuracy: 0.1091 - val_loss: -5.2846 - val_accuracy: 0.0500
Epoch 494/830
6/6 [==============================] - ETA: 0s - loss: -4.8233 - accuracy: 0.1091
Epoch 494: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -4.8233 - accuracy: 0.1091 - val_loss: -5.2872 - val_accuracy: 0.0500
Epoch 495/830
6/6 [==============================] - ETA: 0s - loss: -4.8328 - accuracy: 0.1091
Epoch 495: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -4.8328 - accuracy: 0.1091 - val_loss: -5.2940 - val_accuracy: 0.0500
Epoch 496/830
6/6 [==============================] - ETA: 0s - loss: -4.8399 - accuracy: 0.1091
Epoch 496: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -4.8399 - accuracy: 0.1091 - val_loss: -5.3043 - val_accuracy: 0.0500
Epoch 497/830
6/6 [==============================] - ETA: 0s - loss: -4.8529 - accuracy: 0.1091
Epoch 497: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -4.8529 - accuracy: 0.1091 - val_loss: -5.3251 - val_accuracy: 0.0500
Epoch 498/830
6/6 [==============================] - ETA: 0s - loss: -4.8631 - accuracy: 0.1091
Epoch 498: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -4.8631 - accuracy: 0.1091 - val_loss: -5.3347 - val_accuracy: 0.0500
Epoch 499/830
6/6 [==============================] - ETA: 0s - loss: -4.8722 - accuracy: 0.1091
Epoch 499: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -4.8722 - accuracy: 0.1091 - val_loss: -5.3472 - val_accuracy: 0.0500
Epoch 500/830
6/6 [==============================] - ETA: 0s - loss: -4.8815 - accuracy: 0.1061
Epoch 500: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -4.8815 - accuracy: 0.1061 - val_loss: -5.3603 - val_accuracy: 0.0500
Epoch 501/830
6/6 [==============================] - ETA: 0s - loss: -4.8917 - accuracy: 0.1061
Epoch 501: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 778ms/step - loss: -4.8917 - accuracy: 0.1061 - val_loss: -5.3589 - val_accuracy: 0.0500
Epoch 502/830
6/6 [==============================] - ETA: 0s - loss: -4.8996 - accuracy: 0.1091
Epoch 502: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -4.8996 - accuracy: 0.1091 - val_loss: -5.3773 - val_accuracy: 0.0500
Epoch 503/830
6/6 [==============================] - ETA: 0s - loss: -4.9094 - accuracy: 0.1091
Epoch 503: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -4.9094 - accuracy: 0.1091 - val_loss: -5.3799 - val_accuracy: 0.0500
Epoch 504/830
6/6 [==============================] - ETA: 0s - loss: -4.9158 - accuracy: 0.1091
Epoch 504: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -4.9158 - accuracy: 0.1091 - val_loss: -5.3920 - val_accuracy: 0.0500
Epoch 505/830
6/6 [==============================] - ETA: 0s - loss: -4.9241 - accuracy: 0.1030
Epoch 505: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -4.9241 - accuracy: 0.1030 - val_loss: -5.3966 - val_accuracy: 0.0500
Epoch 506/830
6/6 [==============================] - ETA: 0s - loss: -4.9328 - accuracy: 0.1091
Epoch 506: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -4.9328 - accuracy: 0.1091 - val_loss: -5.4064 - val_accuracy: 0.0500
Epoch 507/830
6/6 [==============================] - ETA: 0s - loss: -4.9427 - accuracy: 0.1091
Epoch 507: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -4.9427 - accuracy: 0.1091 - val_loss: -5.4130 - val_accuracy: 0.0500
Epoch 508/830
6/6 [==============================] - ETA: 0s - loss: -4.9520 - accuracy: 0.1091
Epoch 508: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -4.9520 - accuracy: 0.1091 - val_loss: -5.4175 - val_accuracy: 0.0500
Epoch 509/830
6/6 [==============================] - ETA: 0s - loss: -4.9613 - accuracy: 0.1091
Epoch 509: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -4.9613 - accuracy: 0.1091 - val_loss: -5.4341 - val_accuracy: 0.0500
Epoch 510/830
6/6 [==============================] - ETA: 0s - loss: -4.9722 - accuracy: 0.1091
Epoch 510: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -4.9722 - accuracy: 0.1091 - val_loss: -5.4407 - val_accuracy: 0.0500
Epoch 511/830
6/6 [==============================] - ETA: 0s - loss: -4.9820 - accuracy: 0.1091
Epoch 511: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -4.9820 - accuracy: 0.1091 - val_loss: -5.4558 - val_accuracy: 0.0500
Epoch 512/830
6/6 [==============================] - ETA: 0s - loss: -4.9933 - accuracy: 0.1091
Epoch 512: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -4.9933 - accuracy: 0.1091 - val_loss: -5.4722 - val_accuracy: 0.0500
Epoch 513/830
6/6 [==============================] - ETA: 0s - loss: -5.0029 - accuracy: 0.1091
Epoch 513: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -5.0029 - accuracy: 0.1091 - val_loss: -5.4911 - val_accuracy: 0.0500
Epoch 514/830
6/6 [==============================] - ETA: 0s - loss: -5.0150 - accuracy: 0.1061
Epoch 514: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 782ms/step - loss: -5.0150 - accuracy: 0.1061 - val_loss: -5.5026 - val_accuracy: 0.0500
Epoch 515/830
6/6 [==============================] - ETA: 0s - loss: -5.0247 - accuracy: 0.1030
Epoch 515: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -5.0247 - accuracy: 0.1030 - val_loss: -5.5053 - val_accuracy: 0.0500
Epoch 516/830
6/6 [==============================] - ETA: 0s - loss: -5.0332 - accuracy: 0.1091
Epoch 516: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -5.0332 - accuracy: 0.1091 - val_loss: -5.5141 - val_accuracy: 0.0500
Epoch 517/830
6/6 [==============================] - ETA: 0s - loss: -5.0425 - accuracy: 0.1091
Epoch 517: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -5.0425 - accuracy: 0.1091 - val_loss: -5.5263 - val_accuracy: 0.0500
Epoch 518/830
6/6 [==============================] - ETA: 0s - loss: -5.0528 - accuracy: 0.1061
Epoch 518: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -5.0528 - accuracy: 0.1061 - val_loss: -5.5295 - val_accuracy: 0.0500
Epoch 519/830
6/6 [==============================] - ETA: 0s - loss: -5.0619 - accuracy: 0.1091
Epoch 519: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -5.0619 - accuracy: 0.1091 - val_loss: -5.5429 - val_accuracy: 0.0500
Epoch 520/830
6/6 [==============================] - ETA: 0s - loss: -5.0728 - accuracy: 0.1091
Epoch 520: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 817ms/step - loss: -5.0728 - accuracy: 0.1091 - val_loss: -5.5461 - val_accuracy: 0.0500
Epoch 521/830
6/6 [==============================] - ETA: 0s - loss: -5.0819 - accuracy: 0.1091
Epoch 521: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -5.0819 - accuracy: 0.1091 - val_loss: -5.5657 - val_accuracy: 0.0500
Epoch 522/830
6/6 [==============================] - ETA: 0s - loss: -5.0921 - accuracy: 0.1091
Epoch 522: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -5.0921 - accuracy: 0.1091 - val_loss: -5.5739 - val_accuracy: 0.0500
Epoch 523/830
6/6 [==============================] - ETA: 0s - loss: -5.1020 - accuracy: 0.1091
Epoch 523: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -5.1020 - accuracy: 0.1091 - val_loss: -5.5940 - val_accuracy: 0.0500
Epoch 524/830
6/6 [==============================] - ETA: 0s - loss: -5.1124 - accuracy: 0.1030
Epoch 524: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 797ms/step - loss: -5.1124 - accuracy: 0.1030 - val_loss: -5.5977 - val_accuracy: 0.0500
Epoch 525/830
6/6 [==============================] - ETA: 0s - loss: -5.1209 - accuracy: 0.1061
Epoch 525: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 777ms/step - loss: -5.1209 - accuracy: 0.1061 - val_loss: -5.6072 - val_accuracy: 0.0500
Epoch 526/830
6/6 [==============================] - ETA: 0s - loss: -5.1307 - accuracy: 0.1061
Epoch 526: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -5.1307 - accuracy: 0.1061 - val_loss: -5.6224 - val_accuracy: 0.0500
Epoch 527/830
6/6 [==============================] - ETA: 0s - loss: -5.1404 - accuracy: 0.1061
Epoch 527: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -5.1404 - accuracy: 0.1061 - val_loss: -5.6389 - val_accuracy: 0.0250
Epoch 528/830
6/6 [==============================] - ETA: 0s - loss: -5.1500 - accuracy: 0.1030
Epoch 528: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -5.1500 - accuracy: 0.1030 - val_loss: -5.6544 - val_accuracy: 0.0250
Epoch 529/830
6/6 [==============================] - ETA: 0s - loss: -5.1616 - accuracy: 0.1000
Epoch 529: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -5.1616 - accuracy: 0.1000 - val_loss: -5.6616 - val_accuracy: 0.0250
Epoch 530/830
6/6 [==============================] - ETA: 0s - loss: -5.1713 - accuracy: 0.1000
Epoch 530: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -5.1713 - accuracy: 0.1000 - val_loss: -5.6817 - val_accuracy: 0.0250
Epoch 531/830
6/6 [==============================] - ETA: 0s - loss: -5.1816 - accuracy: 0.1000
Epoch 531: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -5.1816 - accuracy: 0.1000 - val_loss: -5.6929 - val_accuracy: 0.0250
Epoch 532/830
6/6 [==============================] - ETA: 0s - loss: -5.1920 - accuracy: 0.1000
Epoch 532: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -5.1920 - accuracy: 0.1000 - val_loss: -5.7056 - val_accuracy: 0.0250
Epoch 533/830
6/6 [==============================] - ETA: 0s - loss: -5.2019 - accuracy: 0.1000
Epoch 533: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -5.2019 - accuracy: 0.1000 - val_loss: -5.7070 - val_accuracy: 0.0250
Epoch 534/830
6/6 [==============================] - ETA: 0s - loss: -5.2116 - accuracy: 0.1000
Epoch 534: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -5.2116 - accuracy: 0.1000 - val_loss: -5.7230 - val_accuracy: 0.0250
Epoch 535/830
6/6 [==============================] - ETA: 0s - loss: -5.2225 - accuracy: 0.1000
Epoch 535: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -5.2225 - accuracy: 0.1000 - val_loss: -5.7398 - val_accuracy: 0.0250
Epoch 536/830
6/6 [==============================] - ETA: 0s - loss: -5.2328 - accuracy: 0.1000
Epoch 536: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -5.2328 - accuracy: 0.1000 - val_loss: -5.7520 - val_accuracy: 0.0250
Epoch 537/830
6/6 [==============================] - ETA: 0s - loss: -5.2432 - accuracy: 0.1000
Epoch 537: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 781ms/step - loss: -5.2432 - accuracy: 0.1000 - val_loss: -5.7689 - val_accuracy: 0.0250
Epoch 538/830
6/6 [==============================] - ETA: 0s - loss: -5.2536 - accuracy: 0.0970
Epoch 538: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 766ms/step - loss: -5.2536 - accuracy: 0.0970 - val_loss: -5.7738 - val_accuracy: 0.0250
Epoch 539/830
6/6 [==============================] - ETA: 0s - loss: -5.2633 - accuracy: 0.1000
Epoch 539: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -5.2633 - accuracy: 0.1000 - val_loss: -5.7738 - val_accuracy: 0.0250
Epoch 540/830
6/6 [==============================] - ETA: 0s - loss: -5.2694 - accuracy: 0.1000
Epoch 540: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -5.2694 - accuracy: 0.1000 - val_loss: -5.7782 - val_accuracy: 0.0250
Epoch 541/830
6/6 [==============================] - ETA: 0s - loss: -5.2801 - accuracy: 0.1000
Epoch 541: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -5.2801 - accuracy: 0.1000 - val_loss: -5.7951 - val_accuracy: 0.0250
Epoch 542/830
6/6 [==============================] - ETA: 0s - loss: -5.2905 - accuracy: 0.1000
Epoch 542: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -5.2905 - accuracy: 0.1000 - val_loss: -5.8005 - val_accuracy: 0.0250
Epoch 543/830
6/6 [==============================] - ETA: 0s - loss: -5.2995 - accuracy: 0.1000
Epoch 543: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -5.2995 - accuracy: 0.1000 - val_loss: -5.8029 - val_accuracy: 0.0250
Epoch 544/830
6/6 [==============================] - ETA: 0s - loss: -5.3075 - accuracy: 0.1030
Epoch 544: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -5.3075 - accuracy: 0.1030 - val_loss: -5.8208 - val_accuracy: 0.0250
Epoch 545/830
6/6 [==============================] - ETA: 0s - loss: -5.3173 - accuracy: 0.1000
Epoch 545: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -5.3173 - accuracy: 0.1000 - val_loss: -5.8365 - val_accuracy: 0.0250
Epoch 546/830
6/6 [==============================] - ETA: 0s - loss: -5.3270 - accuracy: 0.1000
Epoch 546: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -5.3270 - accuracy: 0.1000 - val_loss: -5.8429 - val_accuracy: 0.0250
Epoch 547/830
6/6 [==============================] - ETA: 0s - loss: -5.3371 - accuracy: 0.1000
Epoch 547: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 804ms/step - loss: -5.3371 - accuracy: 0.1000 - val_loss: -5.8543 - val_accuracy: 0.0250
Epoch 548/830
6/6 [==============================] - ETA: 0s - loss: -5.3472 - accuracy: 0.1000
Epoch 548: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -5.3472 - accuracy: 0.1000 - val_loss: -5.8703 - val_accuracy: 0.0250
Epoch 549/830
6/6 [==============================] - ETA: 0s - loss: -5.3582 - accuracy: 0.1000
Epoch 549: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -5.3582 - accuracy: 0.1000 - val_loss: -5.8737 - val_accuracy: 0.0250
Epoch 550/830
6/6 [==============================] - ETA: 0s - loss: -5.3676 - accuracy: 0.1000
Epoch 550: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -5.3676 - accuracy: 0.1000 - val_loss: -5.8879 - val_accuracy: 0.0250
Epoch 551/830
6/6 [==============================] - ETA: 0s - loss: -5.3778 - accuracy: 0.1000
Epoch 551: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -5.3778 - accuracy: 0.1000 - val_loss: -5.9077 - val_accuracy: 0.0250
Epoch 552/830
6/6 [==============================] - ETA: 0s - loss: -5.3885 - accuracy: 0.1000
Epoch 552: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -5.3885 - accuracy: 0.1000 - val_loss: -5.9092 - val_accuracy: 0.0250
Epoch 553/830
6/6 [==============================] - ETA: 0s - loss: -5.3962 - accuracy: 0.1000
Epoch 553: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -5.3962 - accuracy: 0.1000 - val_loss: -5.9140 - val_accuracy: 0.0250
Epoch 554/830
6/6 [==============================] - ETA: 0s - loss: -5.4057 - accuracy: 0.1000
Epoch 554: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -5.4057 - accuracy: 0.1000 - val_loss: -5.9210 - val_accuracy: 0.0250
Epoch 555/830
6/6 [==============================] - ETA: 0s - loss: -5.4152 - accuracy: 0.1000
Epoch 555: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -5.4152 - accuracy: 0.1000 - val_loss: -5.9386 - val_accuracy: 0.0250
Epoch 556/830
6/6 [==============================] - ETA: 0s - loss: -5.4256 - accuracy: 0.1000
Epoch 556: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 782ms/step - loss: -5.4256 - accuracy: 0.1000 - val_loss: -5.9468 - val_accuracy: 0.0250
Epoch 557/830
6/6 [==============================] - ETA: 0s - loss: -5.4346 - accuracy: 0.1000
Epoch 557: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 769ms/step - loss: -5.4346 - accuracy: 0.1000 - val_loss: -5.9649 - val_accuracy: 0.0250
Epoch 558/830
6/6 [==============================] - ETA: 0s - loss: -5.4462 - accuracy: 0.1000
Epoch 558: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -5.4462 - accuracy: 0.1000 - val_loss: -5.9774 - val_accuracy: 0.0250
Epoch 559/830
6/6 [==============================] - ETA: 0s - loss: -5.4550 - accuracy: 0.1000
Epoch 559: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -5.4550 - accuracy: 0.1000 - val_loss: -5.9888 - val_accuracy: 0.0250
Epoch 560/830
6/6 [==============================] - ETA: 0s - loss: -5.4659 - accuracy: 0.1000
Epoch 560: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -5.4659 - accuracy: 0.1000 - val_loss: -5.9955 - val_accuracy: 0.0250
Epoch 561/830
6/6 [==============================] - ETA: 0s - loss: -5.4763 - accuracy: 0.1000
Epoch 561: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 761ms/step - loss: -5.4763 - accuracy: 0.1000 - val_loss: -6.0118 - val_accuracy: 0.0250
Epoch 562/830
6/6 [==============================] - ETA: 0s - loss: -5.4868 - accuracy: 0.1000
Epoch 562: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -5.4868 - accuracy: 0.1000 - val_loss: -6.0282 - val_accuracy: 0.0250
Epoch 563/830
6/6 [==============================] - ETA: 0s - loss: -5.4975 - accuracy: 0.0970
Epoch 563: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -5.4975 - accuracy: 0.0970 - val_loss: -6.0353 - val_accuracy: 0.0250
Epoch 564/830
6/6 [==============================] - ETA: 0s - loss: -5.5069 - accuracy: 0.1000
Epoch 564: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 805ms/step - loss: -5.5069 - accuracy: 0.1000 - val_loss: -6.0442 - val_accuracy: 0.0250
Epoch 565/830
6/6 [==============================] - ETA: 0s - loss: -5.5172 - accuracy: 0.1000
Epoch 565: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 822ms/step - loss: -5.5172 - accuracy: 0.1000 - val_loss: -6.0619 - val_accuracy: 0.0250
Epoch 566/830
6/6 [==============================] - ETA: 0s - loss: -5.5283 - accuracy: 0.0970
Epoch 566: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -5.5283 - accuracy: 0.0970 - val_loss: -6.0625 - val_accuracy: 0.0250
Epoch 567/830
6/6 [==============================] - ETA: 0s - loss: -5.5367 - accuracy: 0.1000
Epoch 567: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -5.5367 - accuracy: 0.1000 - val_loss: -6.0661 - val_accuracy: 0.0250
Epoch 568/830
6/6 [==============================] - ETA: 0s - loss: -5.5455 - accuracy: 0.1000
Epoch 568: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -5.5455 - accuracy: 0.1000 - val_loss: -6.0687 - val_accuracy: 0.0250
Epoch 569/830
6/6 [==============================] - ETA: 0s - loss: -5.5537 - accuracy: 0.1000
Epoch 569: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -5.5537 - accuracy: 0.1000 - val_loss: -6.0797 - val_accuracy: 0.0250
Epoch 570/830
6/6 [==============================] - ETA: 0s - loss: -5.5644 - accuracy: 0.1000
Epoch 570: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 778ms/step - loss: -5.5644 - accuracy: 0.1000 - val_loss: -6.0812 - val_accuracy: 0.0250
Epoch 571/830
6/6 [==============================] - ETA: 0s - loss: -5.5727 - accuracy: 0.1030
Epoch 571: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -5.5727 - accuracy: 0.1030 - val_loss: -6.0915 - val_accuracy: 0.0250
Epoch 572/830
6/6 [==============================] - ETA: 0s - loss: -5.5830 - accuracy: 0.1030
Epoch 572: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -5.5830 - accuracy: 0.1030 - val_loss: -6.1070 - val_accuracy: 0.0250
Epoch 573/830
6/6 [==============================] - ETA: 0s - loss: -5.5936 - accuracy: 0.1030
Epoch 573: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -5.5936 - accuracy: 0.1030 - val_loss: -6.1155 - val_accuracy: 0.0250
Epoch 574/830
6/6 [==============================] - ETA: 0s - loss: -5.6043 - accuracy: 0.1030
Epoch 574: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 780ms/step - loss: -5.6043 - accuracy: 0.1030 - val_loss: -6.1299 - val_accuracy: 0.0250
Epoch 575/830
6/6 [==============================] - ETA: 0s - loss: -5.6141 - accuracy: 0.1000
Epoch 575: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 760ms/step - loss: -5.6141 - accuracy: 0.1000 - val_loss: -6.1453 - val_accuracy: 0.0250
Epoch 576/830
6/6 [==============================] - ETA: 0s - loss: -5.6259 - accuracy: 0.1000
Epoch 576: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 758ms/step - loss: -5.6259 - accuracy: 0.1000 - val_loss: -6.1479 - val_accuracy: 0.0250
Epoch 577/830
6/6 [==============================] - ETA: 0s - loss: -5.6352 - accuracy: 0.1030
Epoch 577: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -5.6352 - accuracy: 0.1030 - val_loss: -6.1579 - val_accuracy: 0.0250
Epoch 578/830
6/6 [==============================] - ETA: 0s - loss: -5.6455 - accuracy: 0.1030
Epoch 578: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -5.6455 - accuracy: 0.1030 - val_loss: -6.1629 - val_accuracy: 0.0250
Epoch 579/830
6/6 [==============================] - ETA: 0s - loss: -5.6558 - accuracy: 0.1061
Epoch 579: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -5.6558 - accuracy: 0.1061 - val_loss: -6.1755 - val_accuracy: 0.0250
Epoch 580/830
6/6 [==============================] - ETA: 0s - loss: -5.6664 - accuracy: 0.1061
Epoch 580: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -5.6664 - accuracy: 0.1061 - val_loss: -6.1940 - val_accuracy: 0.0250
Epoch 581/830
6/6 [==============================] - ETA: 0s - loss: -5.6766 - accuracy: 0.1030
Epoch 581: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -5.6766 - accuracy: 0.1030 - val_loss: -6.1933 - val_accuracy: 0.0250
Epoch 582/830
6/6 [==============================] - ETA: 0s - loss: -5.6840 - accuracy: 0.1091
Epoch 582: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -5.6840 - accuracy: 0.1091 - val_loss: -6.2063 - val_accuracy: 0.0250
Epoch 583/830
6/6 [==============================] - ETA: 0s - loss: -5.6938 - accuracy: 0.1061
Epoch 583: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -5.6938 - accuracy: 0.1061 - val_loss: -6.2200 - val_accuracy: 0.0250
Epoch 584/830
6/6 [==============================] - ETA: 0s - loss: -5.7034 - accuracy: 0.1030
Epoch 584: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 786ms/step - loss: -5.7034 - accuracy: 0.1030 - val_loss: -6.2265 - val_accuracy: 0.0250
Epoch 585/830
6/6 [==============================] - ETA: 0s - loss: -5.7111 - accuracy: 0.1091
Epoch 585: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -5.7111 - accuracy: 0.1091 - val_loss: -6.2428 - val_accuracy: 0.0250
Epoch 586/830
6/6 [==============================] - ETA: 0s - loss: -5.7223 - accuracy: 0.1030
Epoch 586: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -5.7223 - accuracy: 0.1030 - val_loss: -6.2586 - val_accuracy: 0.0250
Epoch 587/830
6/6 [==============================] - ETA: 0s - loss: -5.7326 - accuracy: 0.1000
Epoch 587: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -5.7326 - accuracy: 0.1000 - val_loss: -6.2688 - val_accuracy: 0.0250
Epoch 588/830
6/6 [==============================] - ETA: 0s - loss: -5.7425 - accuracy: 0.1000
Epoch 588: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -5.7425 - accuracy: 0.1000 - val_loss: -6.2785 - val_accuracy: 0.0250
Epoch 589/830
6/6 [==============================] - ETA: 0s - loss: -5.7522 - accuracy: 0.1000
Epoch 589: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 825ms/step - loss: -5.7522 - accuracy: 0.1000 - val_loss: -6.2791 - val_accuracy: 0.0250
Epoch 590/830
6/6 [==============================] - ETA: 0s - loss: -5.7616 - accuracy: 0.1030
Epoch 590: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -5.7616 - accuracy: 0.1030 - val_loss: -6.2914 - val_accuracy: 0.0250
Epoch 591/830
6/6 [==============================] - ETA: 0s - loss: -5.7718 - accuracy: 0.1030
Epoch 591: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -5.7718 - accuracy: 0.1030 - val_loss: -6.2952 - val_accuracy: 0.0250
Epoch 592/830
6/6 [==============================] - ETA: 0s - loss: -5.7815 - accuracy: 0.1030
Epoch 592: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -5.7815 - accuracy: 0.1030 - val_loss: -6.2970 - val_accuracy: 0.0500
Epoch 593/830
6/6 [==============================] - ETA: 0s - loss: -5.7907 - accuracy: 0.1091
Epoch 593: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 760ms/step - loss: -5.7907 - accuracy: 0.1091 - val_loss: -6.3122 - val_accuracy: 0.0250
Epoch 594/830
6/6 [==============================] - ETA: 0s - loss: -5.8011 - accuracy: 0.1091
Epoch 594: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -5.8011 - accuracy: 0.1091 - val_loss: -6.3277 - val_accuracy: 0.0250
Epoch 595/830
6/6 [==============================] - ETA: 0s - loss: -5.8123 - accuracy: 0.1061
Epoch 595: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -5.8123 - accuracy: 0.1061 - val_loss: -6.3392 - val_accuracy: 0.0250
Epoch 596/830
6/6 [==============================] - ETA: 0s - loss: -5.8232 - accuracy: 0.1091
Epoch 596: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -5.8232 - accuracy: 0.1091 - val_loss: -6.3549 - val_accuracy: 0.0250
Epoch 597/830
6/6 [==============================] - ETA: 0s - loss: -5.8347 - accuracy: 0.1030
Epoch 597: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -5.8347 - accuracy: 0.1030 - val_loss: -6.3546 - val_accuracy: 0.0250
Epoch 598/830
6/6 [==============================] - ETA: 0s - loss: -5.8422 - accuracy: 0.1091
Epoch 598: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -5.8422 - accuracy: 0.1091 - val_loss: -6.3670 - val_accuracy: 0.0250
Epoch 599/830
6/6 [==============================] - ETA: 0s - loss: -5.8532 - accuracy: 0.1091
Epoch 599: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 773ms/step - loss: -5.8532 - accuracy: 0.1091 - val_loss: -6.3807 - val_accuracy: 0.0250
Epoch 600/830
6/6 [==============================] - ETA: 0s - loss: -5.8624 - accuracy: 0.1091
Epoch 600: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -5.8624 - accuracy: 0.1091 - val_loss: -6.3927 - val_accuracy: 0.0250
Epoch 601/830
6/6 [==============================] - ETA: 0s - loss: -5.8737 - accuracy: 0.1030
Epoch 601: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -5.8737 - accuracy: 0.1030 - val_loss: -6.3957 - val_accuracy: 0.0250
Epoch 602/830
6/6 [==============================] - ETA: 0s - loss: -5.8818 - accuracy: 0.1091
Epoch 602: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -5.8818 - accuracy: 0.1091 - val_loss: -6.3996 - val_accuracy: 0.0500
Epoch 603/830
6/6 [==============================] - ETA: 0s - loss: -5.8917 - accuracy: 0.1091
Epoch 603: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 766ms/step - loss: -5.8917 - accuracy: 0.1091 - val_loss: -6.4191 - val_accuracy: 0.0250
Epoch 604/830
6/6 [==============================] - ETA: 0s - loss: -5.9013 - accuracy: 0.1091
Epoch 604: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: -5.9013 - accuracy: 0.1091 - val_loss: -6.4248 - val_accuracy: 0.0250
Epoch 605/830
6/6 [==============================] - ETA: 0s - loss: -5.9104 - accuracy: 0.1091
Epoch 605: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 798ms/step - loss: -5.9104 - accuracy: 0.1091 - val_loss: -6.4340 - val_accuracy: 0.0250
Epoch 606/830
6/6 [==============================] - ETA: 0s - loss: -5.9184 - accuracy: 0.1091
Epoch 606: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -5.9184 - accuracy: 0.1091 - val_loss: -6.4363 - val_accuracy: 0.0500
Epoch 607/830
6/6 [==============================] - ETA: 0s - loss: -5.9279 - accuracy: 0.1091
Epoch 607: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 796ms/step - loss: -5.9279 - accuracy: 0.1091 - val_loss: -6.4518 - val_accuracy: 0.0250
Epoch 608/830
6/6 [==============================] - ETA: 0s - loss: -5.9374 - accuracy: 0.1091
Epoch 608: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -5.9374 - accuracy: 0.1091 - val_loss: -6.4690 - val_accuracy: 0.0250
Epoch 609/830
6/6 [==============================] - ETA: 0s - loss: -5.9475 - accuracy: 0.1061
Epoch 609: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -5.9475 - accuracy: 0.1061 - val_loss: -6.4752 - val_accuracy: 0.0250
Epoch 610/830
6/6 [==============================] - ETA: 0s - loss: -5.9571 - accuracy: 0.1091
Epoch 610: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -5.9571 - accuracy: 0.1091 - val_loss: -6.4890 - val_accuracy: 0.0250
Epoch 611/830
6/6 [==============================] - ETA: 0s - loss: -5.9677 - accuracy: 0.1091
Epoch 611: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 779ms/step - loss: -5.9677 - accuracy: 0.1091 - val_loss: -6.4990 - val_accuracy: 0.0250
Epoch 612/830
6/6 [==============================] - ETA: 0s - loss: -5.9775 - accuracy: 0.1061
Epoch 612: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -5.9775 - accuracy: 0.1061 - val_loss: -6.5133 - val_accuracy: 0.0250
Epoch 613/830
6/6 [==============================] - ETA: 0s - loss: -5.9890 - accuracy: 0.1061
Epoch 613: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -5.9890 - accuracy: 0.1061 - val_loss: -6.5282 - val_accuracy: 0.0250
Epoch 614/830
6/6 [==============================] - ETA: 0s - loss: -6.0000 - accuracy: 0.1030
Epoch 614: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -6.0000 - accuracy: 0.1030 - val_loss: -6.5437 - val_accuracy: 0.0250
Epoch 615/830
6/6 [==============================] - ETA: 0s - loss: -6.0118 - accuracy: 0.1030
Epoch 615: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.0118 - accuracy: 0.1030 - val_loss: -6.5623 - val_accuracy: 0.0250
Epoch 616/830
6/6 [==============================] - ETA: 0s - loss: -6.0229 - accuracy: 0.1030
Epoch 616: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 778ms/step - loss: -6.0229 - accuracy: 0.1030 - val_loss: -6.5772 - val_accuracy: 0.0250
Epoch 617/830
6/6 [==============================] - ETA: 0s - loss: -6.0329 - accuracy: 0.1030
Epoch 617: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -6.0329 - accuracy: 0.1030 - val_loss: -6.5902 - val_accuracy: 0.0250
Epoch 618/830
6/6 [==============================] - ETA: 0s - loss: -6.0411 - accuracy: 0.1000
Epoch 618: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -6.0411 - accuracy: 0.1000 - val_loss: -6.5892 - val_accuracy: 0.0250
Epoch 619/830
6/6 [==============================] - ETA: 0s - loss: -6.0504 - accuracy: 0.1030
Epoch 619: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -6.0504 - accuracy: 0.1030 - val_loss: -6.6022 - val_accuracy: 0.0250
Epoch 620/830
6/6 [==============================] - ETA: 0s - loss: -6.0601 - accuracy: 0.1030
Epoch 620: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -6.0601 - accuracy: 0.1030 - val_loss: -6.6110 - val_accuracy: 0.0250
Epoch 621/830
6/6 [==============================] - ETA: 0s - loss: -6.0672 - accuracy: 0.1030
Epoch 621: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -6.0672 - accuracy: 0.1030 - val_loss: -6.6188 - val_accuracy: 0.0250
Epoch 622/830
6/6 [==============================] - ETA: 0s - loss: -6.0773 - accuracy: 0.1030
Epoch 622: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -6.0773 - accuracy: 0.1030 - val_loss: -6.6383 - val_accuracy: 0.0250
Epoch 623/830
6/6 [==============================] - ETA: 0s - loss: -6.0871 - accuracy: 0.1000
Epoch 623: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.0871 - accuracy: 0.1000 - val_loss: -6.6397 - val_accuracy: 0.0250
Epoch 624/830
6/6 [==============================] - ETA: 0s - loss: -6.0935 - accuracy: 0.1030
Epoch 624: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 813ms/step - loss: -6.0935 - accuracy: 0.1030 - val_loss: -6.6471 - val_accuracy: 0.0250
Epoch 625/830
6/6 [==============================] - ETA: 0s - loss: -6.1030 - accuracy: 0.1030
Epoch 625: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.1030 - accuracy: 0.1030 - val_loss: -6.6620 - val_accuracy: 0.0250
Epoch 626/830
6/6 [==============================] - ETA: 0s - loss: -6.1127 - accuracy: 0.1000
Epoch 626: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -6.1127 - accuracy: 0.1000 - val_loss: -6.6649 - val_accuracy: 0.0250
Epoch 627/830
6/6 [==============================] - ETA: 0s - loss: -6.1214 - accuracy: 0.1030
Epoch 627: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -6.1214 - accuracy: 0.1030 - val_loss: -6.6715 - val_accuracy: 0.0250
Epoch 628/830
6/6 [==============================] - ETA: 0s - loss: -6.1305 - accuracy: 0.1030
Epoch 628: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -6.1305 - accuracy: 0.1030 - val_loss: -6.6712 - val_accuracy: 0.0250
Epoch 629/830
6/6 [==============================] - ETA: 0s - loss: -6.1394 - accuracy: 0.1091
Epoch 629: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -6.1394 - accuracy: 0.1091 - val_loss: -6.6899 - val_accuracy: 0.0250
Epoch 630/830
6/6 [==============================] - ETA: 0s - loss: -6.1487 - accuracy: 0.1030
Epoch 630: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -6.1487 - accuracy: 0.1030 - val_loss: -6.6989 - val_accuracy: 0.0250
Epoch 631/830
6/6 [==============================] - ETA: 0s - loss: -6.1566 - accuracy: 0.1030
Epoch 631: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -6.1566 - accuracy: 0.1030 - val_loss: -6.7030 - val_accuracy: 0.0250
Epoch 632/830
6/6 [==============================] - ETA: 0s - loss: -6.1656 - accuracy: 0.1061
Epoch 632: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -6.1656 - accuracy: 0.1061 - val_loss: -6.7134 - val_accuracy: 0.0250
Epoch 633/830
6/6 [==============================] - ETA: 0s - loss: -6.1753 - accuracy: 0.1030
Epoch 633: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -6.1753 - accuracy: 0.1030 - val_loss: -6.7225 - val_accuracy: 0.0250
Epoch 634/830
6/6 [==============================] - ETA: 0s - loss: -6.1853 - accuracy: 0.1030
Epoch 634: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -6.1853 - accuracy: 0.1030 - val_loss: -6.7396 - val_accuracy: 0.0250
Epoch 635/830
6/6 [==============================] - ETA: 0s - loss: -6.1935 - accuracy: 0.1061
Epoch 635: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -6.1935 - accuracy: 0.1061 - val_loss: -6.7511 - val_accuracy: 0.0250
Epoch 636/830
6/6 [==============================] - ETA: 0s - loss: -6.2061 - accuracy: 0.1030
Epoch 636: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -6.2061 - accuracy: 0.1030 - val_loss: -6.7574 - val_accuracy: 0.0250
Epoch 637/830
6/6 [==============================] - ETA: 0s - loss: -6.2154 - accuracy: 0.1030
Epoch 637: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -6.2154 - accuracy: 0.1030 - val_loss: -6.7661 - val_accuracy: 0.0250
Epoch 638/830
6/6 [==============================] - ETA: 0s - loss: -6.2245 - accuracy: 0.1061
Epoch 638: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 808ms/step - loss: -6.2245 - accuracy: 0.1061 - val_loss: -6.7743 - val_accuracy: 0.0250
Epoch 639/830
6/6 [==============================] - ETA: 0s - loss: -6.2345 - accuracy: 0.1030
Epoch 639: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 764ms/step - loss: -6.2345 - accuracy: 0.1030 - val_loss: -6.7846 - val_accuracy: 0.0250
Epoch 640/830
6/6 [==============================] - ETA: 0s - loss: -6.2449 - accuracy: 0.1061
Epoch 640: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.2449 - accuracy: 0.1061 - val_loss: -6.7952 - val_accuracy: 0.0250
Epoch 641/830
6/6 [==============================] - ETA: 0s - loss: -6.2561 - accuracy: 0.1061
Epoch 641: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 801ms/step - loss: -6.2561 - accuracy: 0.1061 - val_loss: -6.8107 - val_accuracy: 0.0250
Epoch 642/830
6/6 [==============================] - ETA: 0s - loss: -6.2664 - accuracy: 0.1030
Epoch 642: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -6.2664 - accuracy: 0.1030 - val_loss: -6.8157 - val_accuracy: 0.0250
Epoch 643/830
6/6 [==============================] - ETA: 0s - loss: -6.2768 - accuracy: 0.1091
Epoch 643: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.2768 - accuracy: 0.1091 - val_loss: -6.8279 - val_accuracy: 0.0250
Epoch 644/830
6/6 [==============================] - ETA: 0s - loss: -6.2873 - accuracy: 0.1061
Epoch 644: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 786ms/step - loss: -6.2873 - accuracy: 0.1061 - val_loss: -6.8277 - val_accuracy: 0.0250
Epoch 645/830
6/6 [==============================] - ETA: 0s - loss: -6.2954 - accuracy: 0.1091
Epoch 645: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.2954 - accuracy: 0.1091 - val_loss: -6.8319 - val_accuracy: 0.0250
Epoch 646/830
6/6 [==============================] - ETA: 0s - loss: -6.3037 - accuracy: 0.1091
Epoch 646: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -6.3037 - accuracy: 0.1091 - val_loss: -6.8495 - val_accuracy: 0.0250
Epoch 647/830
6/6 [==============================] - ETA: 0s - loss: -6.3135 - accuracy: 0.1091
Epoch 647: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -6.3135 - accuracy: 0.1091 - val_loss: -6.8518 - val_accuracy: 0.0250
Epoch 648/830
6/6 [==============================] - ETA: 0s - loss: -6.3219 - accuracy: 0.1091
Epoch 648: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 806ms/step - loss: -6.3219 - accuracy: 0.1091 - val_loss: -6.8707 - val_accuracy: 0.0250
Epoch 649/830
6/6 [==============================] - ETA: 0s - loss: -6.3303 - accuracy: 0.1091
Epoch 649: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 764ms/step - loss: -6.3303 - accuracy: 0.1091 - val_loss: -6.8829 - val_accuracy: 0.0250
Epoch 650/830
6/6 [==============================] - ETA: 0s - loss: -6.3399 - accuracy: 0.1091
Epoch 650: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -6.3399 - accuracy: 0.1091 - val_loss: -6.8861 - val_accuracy: 0.0250
Epoch 651/830
6/6 [==============================] - ETA: 0s - loss: -6.3481 - accuracy: 0.1091
Epoch 651: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.3481 - accuracy: 0.1091 - val_loss: -6.9022 - val_accuracy: 0.0250
Epoch 652/830
6/6 [==============================] - ETA: 0s - loss: -6.3587 - accuracy: 0.1030
Epoch 652: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -6.3587 - accuracy: 0.1030 - val_loss: -6.9166 - val_accuracy: 0.0250
Epoch 653/830
6/6 [==============================] - ETA: 0s - loss: -6.3677 - accuracy: 0.1030
Epoch 653: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -6.3677 - accuracy: 0.1030 - val_loss: -6.9235 - val_accuracy: 0.0250
Epoch 654/830
6/6 [==============================] - ETA: 0s - loss: -6.3769 - accuracy: 0.1030
Epoch 654: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 783ms/step - loss: -6.3769 - accuracy: 0.1030 - val_loss: -6.9368 - val_accuracy: 0.0250
Epoch 655/830
6/6 [==============================] - ETA: 0s - loss: -6.3873 - accuracy: 0.1030
Epoch 655: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -6.3873 - accuracy: 0.1030 - val_loss: -6.9461 - val_accuracy: 0.0250
Epoch 656/830
6/6 [==============================] - ETA: 0s - loss: -6.3975 - accuracy: 0.1061
Epoch 656: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.3975 - accuracy: 0.1061 - val_loss: -6.9631 - val_accuracy: 0.0250
Epoch 657/830
6/6 [==============================] - ETA: 0s - loss: -6.4072 - accuracy: 0.1030
Epoch 657: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: -6.4072 - accuracy: 0.1030 - val_loss: -6.9676 - val_accuracy: 0.0250
Epoch 658/830
6/6 [==============================] - ETA: 0s - loss: -6.4167 - accuracy: 0.1030
Epoch 658: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -6.4167 - accuracy: 0.1030 - val_loss: -6.9795 - val_accuracy: 0.0250
Epoch 659/830
6/6 [==============================] - ETA: 0s - loss: -6.4279 - accuracy: 0.1030
Epoch 659: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 827ms/step - loss: -6.4279 - accuracy: 0.1030 - val_loss: -6.9885 - val_accuracy: 0.0250
Epoch 660/830
6/6 [==============================] - ETA: 0s - loss: -6.4374 - accuracy: 0.1030
Epoch 660: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -6.4374 - accuracy: 0.1030 - val_loss: -7.0042 - val_accuracy: 0.0250
Epoch 661/830
6/6 [==============================] - ETA: 0s - loss: -6.4476 - accuracy: 0.1030
Epoch 661: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -6.4476 - accuracy: 0.1030 - val_loss: -7.0088 - val_accuracy: 0.0250
Epoch 662/830
6/6 [==============================] - ETA: 0s - loss: -6.4563 - accuracy: 0.1030
Epoch 662: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.4563 - accuracy: 0.1030 - val_loss: -7.0072 - val_accuracy: 0.0250
Epoch 663/830
6/6 [==============================] - ETA: 0s - loss: -6.4649 - accuracy: 0.1091
Epoch 663: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 802ms/step - loss: -6.4649 - accuracy: 0.1091 - val_loss: -7.0188 - val_accuracy: 0.0250
Epoch 664/830
6/6 [==============================] - ETA: 0s - loss: -6.4728 - accuracy: 0.1091
Epoch 664: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -6.4728 - accuracy: 0.1091 - val_loss: -7.0348 - val_accuracy: 0.0250
Epoch 665/830
6/6 [==============================] - ETA: 0s - loss: -6.4821 - accuracy: 0.1061
Epoch 665: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -6.4821 - accuracy: 0.1061 - val_loss: -7.0440 - val_accuracy: 0.0250
Epoch 666/830
6/6 [==============================] - ETA: 0s - loss: -6.4905 - accuracy: 0.1030
Epoch 666: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -6.4905 - accuracy: 0.1030 - val_loss: -7.0514 - val_accuracy: 0.0250
Epoch 667/830
6/6 [==============================] - ETA: 0s - loss: -6.4994 - accuracy: 0.1061
Epoch 667: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.4994 - accuracy: 0.1061 - val_loss: -7.0587 - val_accuracy: 0.0250
Epoch 668/830
6/6 [==============================] - ETA: 0s - loss: -6.5097 - accuracy: 0.1061
Epoch 668: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 778ms/step - loss: -6.5097 - accuracy: 0.1061 - val_loss: -7.0728 - val_accuracy: 0.0250
Epoch 669/830
6/6 [==============================] - ETA: 0s - loss: -6.5213 - accuracy: 0.1030
Epoch 669: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.5213 - accuracy: 0.1030 - val_loss: -7.0852 - val_accuracy: 0.0250
Epoch 670/830
6/6 [==============================] - ETA: 0s - loss: -6.5321 - accuracy: 0.1091
Epoch 670: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -6.5321 - accuracy: 0.1091 - val_loss: -7.0930 - val_accuracy: 0.0250
Epoch 671/830
6/6 [==============================] - ETA: 0s - loss: -6.5433 - accuracy: 0.1091
Epoch 671: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -6.5433 - accuracy: 0.1091 - val_loss: -7.1145 - val_accuracy: 0.0250
Epoch 672/830
6/6 [==============================] - ETA: 0s - loss: -6.5546 - accuracy: 0.1030
Epoch 672: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -6.5546 - accuracy: 0.1030 - val_loss: -7.1189 - val_accuracy: 0.0250
Epoch 673/830
6/6 [==============================] - ETA: 0s - loss: -6.5641 - accuracy: 0.1030
Epoch 673: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 785ms/step - loss: -6.5641 - accuracy: 0.1030 - val_loss: -7.1357 - val_accuracy: 0.0250
Epoch 674/830
6/6 [==============================] - ETA: 0s - loss: -6.5735 - accuracy: 0.1030
Epoch 674: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -6.5735 - accuracy: 0.1030 - val_loss: -7.1408 - val_accuracy: 0.0250
Epoch 675/830
6/6 [==============================] - ETA: 0s - loss: -6.5836 - accuracy: 0.1030
Epoch 675: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.5836 - accuracy: 0.1030 - val_loss: -7.1540 - val_accuracy: 0.0250
Epoch 676/830
6/6 [==============================] - ETA: 0s - loss: -6.5926 - accuracy: 0.1061
Epoch 676: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -6.5926 - accuracy: 0.1061 - val_loss: -7.1715 - val_accuracy: 0.0250
Epoch 677/830
6/6 [==============================] - ETA: 0s - loss: -6.6037 - accuracy: 0.1030
Epoch 677: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -6.6037 - accuracy: 0.1030 - val_loss: -7.1801 - val_accuracy: 0.0250
Epoch 678/830
6/6 [==============================] - ETA: 0s - loss: -6.6119 - accuracy: 0.1030
Epoch 678: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -6.6119 - accuracy: 0.1030 - val_loss: -7.1826 - val_accuracy: 0.0250
Epoch 679/830
6/6 [==============================] - ETA: 0s - loss: -6.6209 - accuracy: 0.1030
Epoch 679: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.6209 - accuracy: 0.1030 - val_loss: -7.1998 - val_accuracy: 0.0250
Epoch 680/830
6/6 [==============================] - ETA: 0s - loss: -6.6312 - accuracy: 0.1030
Epoch 680: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -6.6312 - accuracy: 0.1030 - val_loss: -7.2076 - val_accuracy: 0.0250
Epoch 681/830
6/6 [==============================] - ETA: 0s - loss: -6.6404 - accuracy: 0.1030
Epoch 681: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 763ms/step - loss: -6.6404 - accuracy: 0.1030 - val_loss: -7.2083 - val_accuracy: 0.0250
Epoch 682/830
6/6 [==============================] - ETA: 0s - loss: -6.6485 - accuracy: 0.1061
Epoch 682: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -6.6485 - accuracy: 0.1061 - val_loss: -7.2186 - val_accuracy: 0.0250
Epoch 683/830
6/6 [==============================] - ETA: 0s - loss: -6.6580 - accuracy: 0.1030
Epoch 683: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 804ms/step - loss: -6.6580 - accuracy: 0.1030 - val_loss: -7.2204 - val_accuracy: 0.0250
Epoch 684/830
6/6 [==============================] - ETA: 0s - loss: -6.6670 - accuracy: 0.1091
Epoch 684: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 817ms/step - loss: -6.6670 - accuracy: 0.1091 - val_loss: -7.2346 - val_accuracy: 0.0250
Epoch 685/830
6/6 [==============================] - ETA: 0s - loss: -6.6771 - accuracy: 0.1091
Epoch 685: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -6.6771 - accuracy: 0.1091 - val_loss: -7.2490 - val_accuracy: 0.0250
Epoch 686/830
6/6 [==============================] - ETA: 0s - loss: -6.6877 - accuracy: 0.1061
Epoch 686: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -6.6877 - accuracy: 0.1061 - val_loss: -7.2694 - val_accuracy: 0.0250
Epoch 687/830
6/6 [==============================] - ETA: 0s - loss: -6.6970 - accuracy: 0.1030
Epoch 687: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -6.6970 - accuracy: 0.1030 - val_loss: -7.2742 - val_accuracy: 0.0250
Epoch 688/830
6/6 [==============================] - ETA: 0s - loss: -6.7060 - accuracy: 0.1030
Epoch 688: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 783ms/step - loss: -6.7060 - accuracy: 0.1030 - val_loss: -7.2877 - val_accuracy: 0.0250
Epoch 689/830
6/6 [==============================] - ETA: 0s - loss: -6.7141 - accuracy: 0.1030
Epoch 689: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -6.7141 - accuracy: 0.1030 - val_loss: -7.2916 - val_accuracy: 0.0250
Epoch 690/830
6/6 [==============================] - ETA: 0s - loss: -6.7233 - accuracy: 0.1030
Epoch 690: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -6.7233 - accuracy: 0.1030 - val_loss: -7.2967 - val_accuracy: 0.0250
Epoch 691/830
6/6 [==============================] - ETA: 0s - loss: -6.7316 - accuracy: 0.1030
Epoch 691: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -6.7316 - accuracy: 0.1030 - val_loss: -7.3084 - val_accuracy: 0.0250
Epoch 692/830
6/6 [==============================] - ETA: 0s - loss: -6.7421 - accuracy: 0.1091
Epoch 692: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -6.7421 - accuracy: 0.1091 - val_loss: -7.3240 - val_accuracy: 0.0250
Epoch 693/830
6/6 [==============================] - ETA: 0s - loss: -6.7538 - accuracy: 0.1030
Epoch 693: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -6.7538 - accuracy: 0.1030 - val_loss: -7.3363 - val_accuracy: 0.0250
Epoch 694/830
6/6 [==============================] - ETA: 0s - loss: -6.7647 - accuracy: 0.1030
Epoch 694: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 821ms/step - loss: -6.7647 - accuracy: 0.1030 - val_loss: -7.3425 - val_accuracy: 0.0250
Epoch 695/830
6/6 [==============================] - ETA: 0s - loss: -6.7748 - accuracy: 0.1030
Epoch 695: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -6.7748 - accuracy: 0.1030 - val_loss: -7.3513 - val_accuracy: 0.0250
Epoch 696/830
6/6 [==============================] - ETA: 0s - loss: -6.7859 - accuracy: 0.1061
Epoch 696: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -6.7859 - accuracy: 0.1061 - val_loss: -7.3541 - val_accuracy: 0.0250
Epoch 697/830
6/6 [==============================] - ETA: 0s - loss: -6.7962 - accuracy: 0.1091
Epoch 697: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.7962 - accuracy: 0.1091 - val_loss: -7.3683 - val_accuracy: 0.0250
Epoch 698/830
6/6 [==============================] - ETA: 0s - loss: -6.8057 - accuracy: 0.1091
Epoch 698: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -6.8057 - accuracy: 0.1091 - val_loss: -7.3814 - val_accuracy: 0.0250
Epoch 699/830
6/6 [==============================] - ETA: 0s - loss: -6.8158 - accuracy: 0.1061
Epoch 699: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -6.8158 - accuracy: 0.1061 - val_loss: -7.3978 - val_accuracy: 0.0250
Epoch 700/830
6/6 [==============================] - ETA: 0s - loss: -6.8276 - accuracy: 0.1061
Epoch 700: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -6.8276 - accuracy: 0.1061 - val_loss: -7.4149 - val_accuracy: 0.0250
Epoch 701/830
6/6 [==============================] - ETA: 0s - loss: -6.8381 - accuracy: 0.1030
Epoch 701: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -6.8381 - accuracy: 0.1030 - val_loss: -7.4308 - val_accuracy: 0.0250
Epoch 702/830
6/6 [==============================] - ETA: 0s - loss: -6.8463 - accuracy: 0.1030
Epoch 702: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -6.8463 - accuracy: 0.1030 - val_loss: -7.4465 - val_accuracy: 0.0250
Epoch 703/830
6/6 [==============================] - ETA: 0s - loss: -6.8568 - accuracy: 0.1030
Epoch 703: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -6.8568 - accuracy: 0.1030 - val_loss: -7.4477 - val_accuracy: 0.0250
Epoch 704/830
6/6 [==============================] - ETA: 0s - loss: -6.8653 - accuracy: 0.1030
Epoch 704: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -6.8653 - accuracy: 0.1030 - val_loss: -7.4562 - val_accuracy: 0.0250
Epoch 705/830
6/6 [==============================] - ETA: 0s - loss: -6.8747 - accuracy: 0.1030
Epoch 705: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -6.8747 - accuracy: 0.1030 - val_loss: -7.4675 - val_accuracy: 0.0250
Epoch 706/830
6/6 [==============================] - ETA: 0s - loss: -6.8851 - accuracy: 0.1030
Epoch 706: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 789ms/step - loss: -6.8851 - accuracy: 0.1030 - val_loss: -7.4791 - val_accuracy: 0.0250
Epoch 707/830
6/6 [==============================] - ETA: 0s - loss: -6.8949 - accuracy: 0.1030
Epoch 707: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -6.8949 - accuracy: 0.1030 - val_loss: -7.4835 - val_accuracy: 0.0250
Epoch 708/830
6/6 [==============================] - ETA: 0s - loss: -6.9055 - accuracy: 0.1030
Epoch 708: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -6.9055 - accuracy: 0.1030 - val_loss: -7.4958 - val_accuracy: 0.0250
Epoch 709/830
6/6 [==============================] - ETA: 0s - loss: -6.9163 - accuracy: 0.1030
Epoch 709: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -6.9163 - accuracy: 0.1030 - val_loss: -7.4988 - val_accuracy: 0.0250
Epoch 710/830
6/6 [==============================] - ETA: 0s - loss: -6.9257 - accuracy: 0.1030
Epoch 710: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: -6.9257 - accuracy: 0.1030 - val_loss: -7.5028 - val_accuracy: 0.0250
Epoch 711/830
6/6 [==============================] - ETA: 0s - loss: -6.9344 - accuracy: 0.1091
Epoch 711: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 826ms/step - loss: -6.9344 - accuracy: 0.1091 - val_loss: -7.5138 - val_accuracy: 0.0250
Epoch 712/830
6/6 [==============================] - ETA: 0s - loss: -6.9454 - accuracy: 0.1091
Epoch 712: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -6.9454 - accuracy: 0.1091 - val_loss: -7.5237 - val_accuracy: 0.0250
Epoch 713/830
6/6 [==============================] - ETA: 0s - loss: -6.9558 - accuracy: 0.1091
Epoch 713: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -6.9558 - accuracy: 0.1091 - val_loss: -7.5404 - val_accuracy: 0.0250
Epoch 714/830
6/6 [==============================] - ETA: 0s - loss: -6.9670 - accuracy: 0.1091
Epoch 714: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -6.9670 - accuracy: 0.1091 - val_loss: -7.5607 - val_accuracy: 0.0250
Epoch 715/830
6/6 [==============================] - ETA: 0s - loss: -6.9772 - accuracy: 0.1030
Epoch 715: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 829ms/step - loss: -6.9772 - accuracy: 0.1030 - val_loss: -7.5726 - val_accuracy: 0.0250
Epoch 716/830
6/6 [==============================] - ETA: 0s - loss: -6.9863 - accuracy: 0.1030
Epoch 716: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -6.9863 - accuracy: 0.1030 - val_loss: -7.5841 - val_accuracy: 0.0250
Epoch 717/830
6/6 [==============================] - ETA: 0s - loss: -6.9951 - accuracy: 0.1030
Epoch 717: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -6.9951 - accuracy: 0.1030 - val_loss: -7.5916 - val_accuracy: 0.0250
Epoch 718/830
6/6 [==============================] - ETA: 0s - loss: -7.0053 - accuracy: 0.1030
Epoch 718: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -7.0053 - accuracy: 0.1030 - val_loss: -7.6085 - val_accuracy: 0.0250
Epoch 719/830
6/6 [==============================] - ETA: 0s - loss: -7.0152 - accuracy: 0.1030
Epoch 719: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 776ms/step - loss: -7.0152 - accuracy: 0.1030 - val_loss: -7.6242 - val_accuracy: 0.0250
Epoch 720/830
6/6 [==============================] - ETA: 0s - loss: -7.0258 - accuracy: 0.1000
Epoch 720: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -7.0258 - accuracy: 0.1000 - val_loss: -7.6366 - val_accuracy: 0.0250
Epoch 721/830
6/6 [==============================] - ETA: 0s - loss: -7.0354 - accuracy: 0.1000
Epoch 721: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -7.0354 - accuracy: 0.1000 - val_loss: -7.6357 - val_accuracy: 0.0250
Epoch 722/830
6/6 [==============================] - ETA: 0s - loss: -7.0444 - accuracy: 0.1030
Epoch 722: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -7.0444 - accuracy: 0.1030 - val_loss: -7.6431 - val_accuracy: 0.0250
Epoch 723/830
6/6 [==============================] - ETA: 0s - loss: -7.0529 - accuracy: 0.1030
Epoch 723: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 789ms/step - loss: -7.0529 - accuracy: 0.1030 - val_loss: -7.6543 - val_accuracy: 0.0250
Epoch 724/830
6/6 [==============================] - ETA: 0s - loss: -7.0640 - accuracy: 0.1030
Epoch 724: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 766ms/step - loss: -7.0640 - accuracy: 0.1030 - val_loss: -7.6707 - val_accuracy: 0.0250
Epoch 725/830
6/6 [==============================] - ETA: 0s - loss: -7.0754 - accuracy: 0.1030
Epoch 725: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 805ms/step - loss: -7.0754 - accuracy: 0.1030 - val_loss: -7.6819 - val_accuracy: 0.0250
Epoch 726/830
6/6 [==============================] - ETA: 0s - loss: -7.0857 - accuracy: 0.1030
Epoch 726: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -7.0857 - accuracy: 0.1030 - val_loss: -7.6975 - val_accuracy: 0.0250
Epoch 727/830
6/6 [==============================] - ETA: 0s - loss: -7.0962 - accuracy: 0.1000
Epoch 727: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -7.0962 - accuracy: 0.1000 - val_loss: -7.7118 - val_accuracy: 0.0250
Epoch 728/830
6/6 [==============================] - ETA: 0s - loss: -7.1063 - accuracy: 0.1030
Epoch 728: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 783ms/step - loss: -7.1063 - accuracy: 0.1030 - val_loss: -7.7262 - val_accuracy: 0.0250
Epoch 729/830
6/6 [==============================] - ETA: 0s - loss: -7.1163 - accuracy: 0.1000
Epoch 729: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -7.1163 - accuracy: 0.1000 - val_loss: -7.7413 - val_accuracy: 0.0250
Epoch 730/830
6/6 [==============================] - ETA: 0s - loss: -7.1267 - accuracy: 0.1000
Epoch 730: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -7.1267 - accuracy: 0.1000 - val_loss: -7.7549 - val_accuracy: 0.0250
Epoch 731/830
6/6 [==============================] - ETA: 0s - loss: -7.1369 - accuracy: 0.1000
Epoch 731: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 773ms/step - loss: -7.1369 - accuracy: 0.1000 - val_loss: -7.7548 - val_accuracy: 0.0250
Epoch 732/830
6/6 [==============================] - ETA: 0s - loss: -7.1455 - accuracy: 0.1000
Epoch 732: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 778ms/step - loss: -7.1455 - accuracy: 0.1000 - val_loss: -7.7654 - val_accuracy: 0.0250
Epoch 733/830
6/6 [==============================] - ETA: 0s - loss: -7.1550 - accuracy: 0.1000
Epoch 733: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -7.1550 - accuracy: 0.1000 - val_loss: -7.7710 - val_accuracy: 0.0250
Epoch 734/830
6/6 [==============================] - ETA: 0s - loss: -7.1642 - accuracy: 0.1000
Epoch 734: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -7.1642 - accuracy: 0.1000 - val_loss: -7.7777 - val_accuracy: 0.0250
Epoch 735/830
6/6 [==============================] - ETA: 0s - loss: -7.1736 - accuracy: 0.1030
Epoch 735: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -7.1736 - accuracy: 0.1030 - val_loss: -7.7852 - val_accuracy: 0.0250
Epoch 736/830
6/6 [==============================] - ETA: 0s - loss: -7.1844 - accuracy: 0.1030
Epoch 736: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 831ms/step - loss: -7.1844 - accuracy: 0.1030 - val_loss: -7.7974 - val_accuracy: 0.0250
Epoch 737/830
6/6 [==============================] - ETA: 0s - loss: -7.1949 - accuracy: 0.1030
Epoch 737: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 776ms/step - loss: -7.1949 - accuracy: 0.1030 - val_loss: -7.8024 - val_accuracy: 0.0250
Epoch 738/830
6/6 [==============================] - ETA: 0s - loss: -7.2058 - accuracy: 0.1030
Epoch 738: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -7.2058 - accuracy: 0.1030 - val_loss: -7.8065 - val_accuracy: 0.0250
Epoch 739/830
6/6 [==============================] - ETA: 0s - loss: -7.2148 - accuracy: 0.1030
Epoch 739: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -7.2148 - accuracy: 0.1030 - val_loss: -7.8128 - val_accuracy: 0.0250
Epoch 740/830
6/6 [==============================] - ETA: 0s - loss: -7.2243 - accuracy: 0.1030
Epoch 740: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -7.2243 - accuracy: 0.1030 - val_loss: -7.8183 - val_accuracy: 0.0250
Epoch 741/830
6/6 [==============================] - ETA: 0s - loss: -7.2324 - accuracy: 0.1091
Epoch 741: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 776ms/step - loss: -7.2324 - accuracy: 0.1091 - val_loss: -7.8363 - val_accuracy: 0.0250
Epoch 742/830
6/6 [==============================] - ETA: 0s - loss: -7.2445 - accuracy: 0.1030
Epoch 742: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -7.2445 - accuracy: 0.1030 - val_loss: -7.8342 - val_accuracy: 0.0250
Epoch 743/830
6/6 [==============================] - ETA: 0s - loss: -7.2513 - accuracy: 0.1091
Epoch 743: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -7.2513 - accuracy: 0.1091 - val_loss: -7.8425 - val_accuracy: 0.0250
Epoch 744/830
6/6 [==============================] - ETA: 0s - loss: -7.2598 - accuracy: 0.1091
Epoch 744: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -7.2598 - accuracy: 0.1091 - val_loss: -7.8484 - val_accuracy: 0.0250
Epoch 745/830
6/6 [==============================] - ETA: 0s - loss: -7.2693 - accuracy: 0.1091
Epoch 745: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 774ms/step - loss: -7.2693 - accuracy: 0.1091 - val_loss: -7.8611 - val_accuracy: 0.0250
Epoch 746/830
6/6 [==============================] - ETA: 0s - loss: -7.2791 - accuracy: 0.1091
Epoch 746: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -7.2791 - accuracy: 0.1091 - val_loss: -7.8685 - val_accuracy: 0.0250
Epoch 747/830
6/6 [==============================] - ETA: 0s - loss: -7.2872 - accuracy: 0.1091
Epoch 747: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -7.2872 - accuracy: 0.1091 - val_loss: -7.8874 - val_accuracy: 0.0250
Epoch 748/830
6/6 [==============================] - ETA: 0s - loss: -7.2978 - accuracy: 0.1091
Epoch 748: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 763ms/step - loss: -7.2978 - accuracy: 0.1091 - val_loss: -7.8888 - val_accuracy: 0.0250
Epoch 749/830
6/6 [==============================] - ETA: 0s - loss: -7.3068 - accuracy: 0.1091
Epoch 749: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 820ms/step - loss: -7.3068 - accuracy: 0.1091 - val_loss: -7.8933 - val_accuracy: 0.0250
Epoch 750/830
6/6 [==============================] - ETA: 0s - loss: -7.3156 - accuracy: 0.1091
Epoch 750: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: -7.3156 - accuracy: 0.1091 - val_loss: -7.9058 - val_accuracy: 0.0250
Epoch 751/830
6/6 [==============================] - ETA: 0s - loss: -7.3245 - accuracy: 0.1091
Epoch 751: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -7.3245 - accuracy: 0.1091 - val_loss: -7.9046 - val_accuracy: 0.0250
Epoch 752/830
6/6 [==============================] - ETA: 0s - loss: -7.3318 - accuracy: 0.1091
Epoch 752: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -7.3318 - accuracy: 0.1091 - val_loss: -7.9122 - val_accuracy: 0.0250
Epoch 753/830
6/6 [==============================] - ETA: 0s - loss: -7.3410 - accuracy: 0.1091
Epoch 753: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -7.3410 - accuracy: 0.1091 - val_loss: -7.9240 - val_accuracy: 0.0250
Epoch 754/830
6/6 [==============================] - ETA: 0s - loss: -7.3489 - accuracy: 0.1091
Epoch 754: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 781ms/step - loss: -7.3489 - accuracy: 0.1091 - val_loss: -7.9410 - val_accuracy: 0.0250
Epoch 755/830
6/6 [==============================] - ETA: 0s - loss: -7.3586 - accuracy: 0.1091
Epoch 755: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -7.3586 - accuracy: 0.1091 - val_loss: -7.9428 - val_accuracy: 0.0250
Epoch 756/830
6/6 [==============================] - ETA: 0s - loss: -7.3686 - accuracy: 0.1091
Epoch 756: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 773ms/step - loss: -7.3686 - accuracy: 0.1091 - val_loss: -7.9601 - val_accuracy: 0.0250
Epoch 757/830
6/6 [==============================] - ETA: 0s - loss: -7.3775 - accuracy: 0.1091
Epoch 757: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -7.3775 - accuracy: 0.1091 - val_loss: -7.9729 - val_accuracy: 0.0250
Epoch 758/830
6/6 [==============================] - ETA: 0s - loss: -7.3879 - accuracy: 0.1091
Epoch 758: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -7.3879 - accuracy: 0.1091 - val_loss: -7.9751 - val_accuracy: 0.0250
Epoch 759/830
6/6 [==============================] - ETA: 0s - loss: -7.3956 - accuracy: 0.1091
Epoch 759: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 833ms/step - loss: -7.3956 - accuracy: 0.1091 - val_loss: -7.9757 - val_accuracy: 0.0250
Epoch 760/830
6/6 [==============================] - ETA: 0s - loss: -7.4032 - accuracy: 0.1091
Epoch 760: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -7.4032 - accuracy: 0.1091 - val_loss: -7.9928 - val_accuracy: 0.0250
Epoch 761/830
6/6 [==============================] - ETA: 0s - loss: -7.4129 - accuracy: 0.1091
Epoch 761: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -7.4129 - accuracy: 0.1091 - val_loss: -8.0026 - val_accuracy: 0.0250
Epoch 762/830
6/6 [==============================] - ETA: 0s - loss: -7.4231 - accuracy: 0.1091
Epoch 762: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -7.4231 - accuracy: 0.1091 - val_loss: -8.0110 - val_accuracy: 0.0250
Epoch 763/830
6/6 [==============================] - ETA: 0s - loss: -7.4326 - accuracy: 0.1091
Epoch 763: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 802ms/step - loss: -7.4326 - accuracy: 0.1091 - val_loss: -8.0211 - val_accuracy: 0.0250
Epoch 764/830
6/6 [==============================] - ETA: 0s - loss: -7.4428 - accuracy: 0.1091
Epoch 764: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 777ms/step - loss: -7.4428 - accuracy: 0.1091 - val_loss: -8.0357 - val_accuracy: 0.0250
Epoch 765/830
6/6 [==============================] - ETA: 0s - loss: -7.4542 - accuracy: 0.1091
Epoch 765: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -7.4542 - accuracy: 0.1091 - val_loss: -8.0395 - val_accuracy: 0.0250
Epoch 766/830
6/6 [==============================] - ETA: 0s - loss: -7.4639 - accuracy: 0.1091
Epoch 766: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -7.4639 - accuracy: 0.1091 - val_loss: -8.0473 - val_accuracy: 0.0250
Epoch 767/830
6/6 [==============================] - ETA: 0s - loss: -7.4740 - accuracy: 0.1091
Epoch 767: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -7.4740 - accuracy: 0.1091 - val_loss: -8.0687 - val_accuracy: 0.0250
Epoch 768/830
6/6 [==============================] - ETA: 0s - loss: -7.4851 - accuracy: 0.1091
Epoch 768: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 816ms/step - loss: -7.4851 - accuracy: 0.1091 - val_loss: -8.0675 - val_accuracy: 0.0250
Epoch 769/830
6/6 [==============================] - ETA: 0s - loss: -7.4923 - accuracy: 0.1091
Epoch 769: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 767ms/step - loss: -7.4923 - accuracy: 0.1091 - val_loss: -8.0671 - val_accuracy: 0.0250
Epoch 770/830
6/6 [==============================] - ETA: 0s - loss: -7.4985 - accuracy: 0.1091
Epoch 770: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -7.4985 - accuracy: 0.1091 - val_loss: -8.0797 - val_accuracy: 0.0250
Epoch 771/830
6/6 [==============================] - ETA: 0s - loss: -7.5081 - accuracy: 0.1091
Epoch 771: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -7.5081 - accuracy: 0.1091 - val_loss: -8.0895 - val_accuracy: 0.0250
Epoch 772/830
6/6 [==============================] - ETA: 0s - loss: -7.5168 - accuracy: 0.1091
Epoch 772: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 811ms/step - loss: -7.5168 - accuracy: 0.1091 - val_loss: -8.1045 - val_accuracy: 0.0250
Epoch 773/830
6/6 [==============================] - ETA: 0s - loss: -7.5261 - accuracy: 0.1091
Epoch 773: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -7.5261 - accuracy: 0.1091 - val_loss: -8.1199 - val_accuracy: 0.0250
Epoch 774/830
6/6 [==============================] - ETA: 0s - loss: -7.5371 - accuracy: 0.1091
Epoch 774: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -7.5371 - accuracy: 0.1091 - val_loss: -8.1336 - val_accuracy: 0.0250
Epoch 775/830
6/6 [==============================] - ETA: 0s - loss: -7.5475 - accuracy: 0.1091
Epoch 775: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -7.5475 - accuracy: 0.1091 - val_loss: -8.1442 - val_accuracy: 0.0250
Epoch 776/830
6/6 [==============================] - ETA: 0s - loss: -7.5566 - accuracy: 0.1091
Epoch 776: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: -7.5566 - accuracy: 0.1091 - val_loss: -8.1446 - val_accuracy: 0.0250
Epoch 777/830
6/6 [==============================] - ETA: 0s - loss: -7.5661 - accuracy: 0.1091
Epoch 777: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 777ms/step - loss: -7.5661 - accuracy: 0.1091 - val_loss: -8.1541 - val_accuracy: 0.0250
Epoch 778/830
6/6 [==============================] - ETA: 0s - loss: -7.5756 - accuracy: 0.1091
Epoch 778: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -7.5756 - accuracy: 0.1091 - val_loss: -8.1607 - val_accuracy: 0.0250
Epoch 779/830
6/6 [==============================] - ETA: 0s - loss: -7.5852 - accuracy: 0.1091
Epoch 779: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -7.5852 - accuracy: 0.1091 - val_loss: -8.1820 - val_accuracy: 0.0250
Epoch 780/830
6/6 [==============================] - ETA: 0s - loss: -7.5961 - accuracy: 0.1091
Epoch 780: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -7.5961 - accuracy: 0.1091 - val_loss: -8.1846 - val_accuracy: 0.0250
Epoch 781/830
6/6 [==============================] - ETA: 0s - loss: -7.6038 - accuracy: 0.1091
Epoch 781: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -7.6038 - accuracy: 0.1091 - val_loss: -8.1985 - val_accuracy: 0.0250
Epoch 782/830
6/6 [==============================] - ETA: 0s - loss: -7.6130 - accuracy: 0.1091
Epoch 782: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 784ms/step - loss: -7.6130 - accuracy: 0.1091 - val_loss: -8.1970 - val_accuracy: 0.0250
Epoch 783/830
6/6 [==============================] - ETA: 0s - loss: -7.6205 - accuracy: 0.1091
Epoch 783: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -7.6205 - accuracy: 0.1091 - val_loss: -8.1993 - val_accuracy: 0.0250
Epoch 784/830
6/6 [==============================] - ETA: 0s - loss: -7.6274 - accuracy: 0.1091
Epoch 784: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 762ms/step - loss: -7.6274 - accuracy: 0.1091 - val_loss: -8.2051 - val_accuracy: 0.0250
Epoch 785/830
6/6 [==============================] - ETA: 0s - loss: -7.6361 - accuracy: 0.1091
Epoch 785: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -7.6361 - accuracy: 0.1091 - val_loss: -8.2148 - val_accuracy: 0.0250
Epoch 786/830
6/6 [==============================] - ETA: 0s - loss: -7.6448 - accuracy: 0.1091
Epoch 786: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 764ms/step - loss: -7.6448 - accuracy: 0.1091 - val_loss: -8.2289 - val_accuracy: 0.0250
Epoch 787/830
6/6 [==============================] - ETA: 0s - loss: -7.6557 - accuracy: 0.1091
Epoch 787: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -7.6557 - accuracy: 0.1091 - val_loss: -8.2406 - val_accuracy: 0.0250
Epoch 788/830
6/6 [==============================] - ETA: 0s - loss: -7.6664 - accuracy: 0.1091
Epoch 788: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -7.6664 - accuracy: 0.1091 - val_loss: -8.2509 - val_accuracy: 0.0250
Epoch 789/830
6/6 [==============================] - ETA: 0s - loss: -7.6760 - accuracy: 0.1091
Epoch 789: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -7.6760 - accuracy: 0.1091 - val_loss: -8.2670 - val_accuracy: 0.0250
Epoch 790/830
6/6 [==============================] - ETA: 0s - loss: -7.6879 - accuracy: 0.1091
Epoch 790: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -7.6879 - accuracy: 0.1091 - val_loss: -8.2874 - val_accuracy: 0.0250
Epoch 791/830
6/6 [==============================] - ETA: 0s - loss: -7.6994 - accuracy: 0.1091
Epoch 791: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -7.6994 - accuracy: 0.1091 - val_loss: -8.2881 - val_accuracy: 0.0250
Epoch 792/830
6/6 [==============================] - ETA: 0s - loss: -7.7074 - accuracy: 0.1091
Epoch 792: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -7.7074 - accuracy: 0.1091 - val_loss: -8.3041 - val_accuracy: 0.0250
Epoch 793/830
6/6 [==============================] - ETA: 0s - loss: -7.7175 - accuracy: 0.1091
Epoch 793: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -7.7175 - accuracy: 0.1091 - val_loss: -8.3126 - val_accuracy: 0.0250
Epoch 794/830
6/6 [==============================] - ETA: 0s - loss: -7.7254 - accuracy: 0.1091
Epoch 794: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -7.7254 - accuracy: 0.1091 - val_loss: -8.3135 - val_accuracy: 0.0250
Epoch 795/830
6/6 [==============================] - ETA: 0s - loss: -7.7335 - accuracy: 0.1091
Epoch 795: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 770ms/step - loss: -7.7335 - accuracy: 0.1091 - val_loss: -8.3264 - val_accuracy: 0.0250
Epoch 796/830
6/6 [==============================] - ETA: 0s - loss: -7.7447 - accuracy: 0.1091
Epoch 796: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 765ms/step - loss: -7.7447 - accuracy: 0.1091 - val_loss: -8.3454 - val_accuracy: 0.0250
Epoch 797/830
6/6 [==============================] - ETA: 0s - loss: -7.7540 - accuracy: 0.1091
Epoch 797: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 773ms/step - loss: -7.7540 - accuracy: 0.1091 - val_loss: -8.3530 - val_accuracy: 0.0250
Epoch 798/830
6/6 [==============================] - ETA: 0s - loss: -7.7631 - accuracy: 0.1091
Epoch 798: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 772ms/step - loss: -7.7631 - accuracy: 0.1091 - val_loss: -8.3613 - val_accuracy: 0.0250
Epoch 799/830
6/6 [==============================] - ETA: 0s - loss: -7.7722 - accuracy: 0.1091
Epoch 799: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 776ms/step - loss: -7.7722 - accuracy: 0.1091 - val_loss: -8.3807 - val_accuracy: 0.0250
Epoch 800/830
6/6 [==============================] - ETA: 0s - loss: -7.7831 - accuracy: 0.1091
Epoch 800: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 784ms/step - loss: -7.7831 - accuracy: 0.1091 - val_loss: -8.3905 - val_accuracy: 0.0250
Epoch 801/830
6/6 [==============================] - ETA: 0s - loss: -7.7913 - accuracy: 0.1091
Epoch 801: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 775ms/step - loss: -7.7913 - accuracy: 0.1091 - val_loss: -8.3920 - val_accuracy: 0.0250
Epoch 802/830
6/6 [==============================] - ETA: 0s - loss: -7.7999 - accuracy: 0.1091
Epoch 802: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 810ms/step - loss: -7.7999 - accuracy: 0.1091 - val_loss: -8.4090 - val_accuracy: 0.0250
Epoch 803/830
6/6 [==============================] - ETA: 0s - loss: -7.8101 - accuracy: 0.1091
Epoch 803: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 780ms/step - loss: -7.8101 - accuracy: 0.1091 - val_loss: -8.4185 - val_accuracy: 0.0250
Epoch 804/830
6/6 [==============================] - ETA: 0s - loss: -7.8195 - accuracy: 0.1091
Epoch 804: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 764ms/step - loss: -7.8195 - accuracy: 0.1091 - val_loss: -8.4204 - val_accuracy: 0.0250
Epoch 805/830
6/6 [==============================] - ETA: 0s - loss: -7.8288 - accuracy: 0.1091
Epoch 805: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -7.8288 - accuracy: 0.1091 - val_loss: -8.4234 - val_accuracy: 0.0250
Epoch 806/830
6/6 [==============================] - ETA: 0s - loss: -7.8377 - accuracy: 0.1091
Epoch 806: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 767ms/step - loss: -7.8377 - accuracy: 0.1091 - val_loss: -8.4323 - val_accuracy: 0.0250
Epoch 807/830
6/6 [==============================] - ETA: 0s - loss: -7.8458 - accuracy: 0.1091
Epoch 807: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -7.8458 - accuracy: 0.1091 - val_loss: -8.4487 - val_accuracy: 0.0250
Epoch 808/830
6/6 [==============================] - ETA: 0s - loss: -7.8573 - accuracy: 0.1091
Epoch 808: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 802ms/step - loss: -7.8573 - accuracy: 0.1091 - val_loss: -8.4588 - val_accuracy: 0.0250
Epoch 809/830
6/6 [==============================] - ETA: 0s - loss: -7.8661 - accuracy: 0.1091
Epoch 809: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -7.8661 - accuracy: 0.1091 - val_loss: -8.4782 - val_accuracy: 0.0250
Epoch 810/830
6/6 [==============================] - ETA: 0s - loss: -7.8773 - accuracy: 0.1091
Epoch 810: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -7.8773 - accuracy: 0.1091 - val_loss: -8.4929 - val_accuracy: 0.0250
Epoch 811/830
6/6 [==============================] - ETA: 0s - loss: -7.8857 - accuracy: 0.1091
Epoch 811: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -7.8857 - accuracy: 0.1091 - val_loss: -8.4943 - val_accuracy: 0.0250
Epoch 812/830
6/6 [==============================] - ETA: 0s - loss: -7.8939 - accuracy: 0.1091
Epoch 812: saving model to training_1/cp.ckpt
6/6 [==============================] - 7s 769ms/step - loss: -7.8939 - accuracy: 0.1091 - val_loss: -8.5005 - val_accuracy: 0.0250
Epoch 813/830
6/6 [==============================] - ETA: 0s - loss: -7.9023 - accuracy: 0.1091
Epoch 813: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -7.9023 - accuracy: 0.1091 - val_loss: -8.5055 - val_accuracy: 0.0250
Epoch 814/830
6/6 [==============================] - ETA: 0s - loss: -7.9114 - accuracy: 0.1091
Epoch 814: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -7.9114 - accuracy: 0.1091 - val_loss: -8.5117 - val_accuracy: 0.0250
Epoch 815/830
6/6 [==============================] - ETA: 0s - loss: -7.9207 - accuracy: 0.1091
Epoch 815: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 769ms/step - loss: -7.9207 - accuracy: 0.1091 - val_loss: -8.5141 - val_accuracy: 0.0250
Epoch 816/830
6/6 [==============================] - ETA: 0s - loss: -7.9297 - accuracy: 0.1091
Epoch 816: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 816ms/step - loss: -7.9297 - accuracy: 0.1091 - val_loss: -8.5286 - val_accuracy: 0.0250
Epoch 817/830
6/6 [==============================] - ETA: 0s - loss: -7.9401 - accuracy: 0.1091
Epoch 817: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -7.9401 - accuracy: 0.1091 - val_loss: -8.5351 - val_accuracy: 0.0250
Epoch 818/830
6/6 [==============================] - ETA: 0s - loss: -7.9500 - accuracy: 0.1091
Epoch 818: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 761ms/step - loss: -7.9500 - accuracy: 0.1091 - val_loss: -8.5505 - val_accuracy: 0.0250
Epoch 819/830
6/6 [==============================] - ETA: 0s - loss: -7.9609 - accuracy: 0.1091
Epoch 819: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -7.9609 - accuracy: 0.1091 - val_loss: -8.5686 - val_accuracy: 0.0250
Epoch 820/830
6/6 [==============================] - ETA: 0s - loss: -7.9709 - accuracy: 0.1091
Epoch 820: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -7.9709 - accuracy: 0.1091 - val_loss: -8.5712 - val_accuracy: 0.0250
Epoch 821/830
6/6 [==============================] - ETA: 0s - loss: -7.9791 - accuracy: 0.1091
Epoch 821: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 783ms/step - loss: -7.9791 - accuracy: 0.1091 - val_loss: -8.5804 - val_accuracy: 0.0250
Epoch 822/830
6/6 [==============================] - ETA: 0s - loss: -7.9897 - accuracy: 0.1091
Epoch 822: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 774ms/step - loss: -7.9897 - accuracy: 0.1091 - val_loss: -8.5879 - val_accuracy: 0.0250
Epoch 823/830
6/6 [==============================] - ETA: 0s - loss: -8.0004 - accuracy: 0.1091
Epoch 823: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -8.0004 - accuracy: 0.1091 - val_loss: -8.5963 - val_accuracy: 0.0250
Epoch 824/830
6/6 [==============================] - ETA: 0s - loss: -8.0103 - accuracy: 0.1091
Epoch 824: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 768ms/step - loss: -8.0103 - accuracy: 0.1091 - val_loss: -8.6180 - val_accuracy: 0.0250
Epoch 825/830
6/6 [==============================] - ETA: 0s - loss: -8.0205 - accuracy: 0.1091
Epoch 825: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 766ms/step - loss: -8.0205 - accuracy: 0.1091 - val_loss: -8.6352 - val_accuracy: 0.0250
Epoch 826/830
6/6 [==============================] - ETA: 0s - loss: -8.0310 - accuracy: 0.1091
Epoch 826: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 764ms/step - loss: -8.0310 - accuracy: 0.1091 - val_loss: -8.6400 - val_accuracy: 0.0250
Epoch 827/830
6/6 [==============================] - ETA: 0s - loss: -8.0393 - accuracy: 0.1091
Epoch 827: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -8.0393 - accuracy: 0.1091 - val_loss: -8.6542 - val_accuracy: 0.0250
Epoch 828/830
6/6 [==============================] - ETA: 0s - loss: -8.0475 - accuracy: 0.1091
Epoch 828: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 770ms/step - loss: -8.0475 - accuracy: 0.1091 - val_loss: -8.6538 - val_accuracy: 0.0250
Epoch 829/830
6/6 [==============================] - ETA: 0s - loss: -8.0571 - accuracy: 0.1091
Epoch 829: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 774ms/step - loss: -8.0571 - accuracy: 0.1091 - val_loss: -8.6620 - val_accuracy: 0.0250
Epoch 830/830
6/6 [==============================] - ETA: 0s - loss: -8.0664 - accuracy: 0.1091
Epoch 830: saving model to training_1/cp.ckpt
6/6 [==============================] - 6s 771ms/step - loss: -8.0664 - accuracy: 0.1091 - val_loss: -8.6683 - val_accuracy: 0.0250
  
  ```text
    Você deve colar aqui a saída do bloco de treinamento do notebook, contendo todas as épocas e saídas do treinamento
  ```
</details>

### Evidências do treinamento

Nessa seção você deve colocar qualquer evidência do treinamento, como por exemplo gráficos de perda, performance, matriz de confusão etc.

![image](https://user-images.githubusercontent.com/51498834/201501079-94b7a077-9005-49d8-841d-3cd78eacdc09.png)


## Roboflow

Nessa seção deve colocar o link para acessar o dataset no Roboflow

Exemplo de link:(https://app.roboflow.com/ds/UgxXuChaJw?key=TFxFxlYDA8)

## HuggingFace

Nessa seção você deve publicar o link para o HuggingFace
