# EIP-week-2

Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 114s 2ms/step - loss: 0.0476 - acc: 0.9856 - val_loss: 0.0544 - val_acc: 0.9846
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 112s 2ms/step - loss: 0.0384 - acc: 0.9878 - val_loss: 0.0276 - val_acc: 0.9908
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 112s 2ms/step - loss: 0.0336 - acc: 0.9893 - val_loss: 0.0255 - val_acc: 0.9921
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 113s 2ms/step - loss: 0.0302 - acc: 0.9903 - val_loss: 0.0228 - val_acc: 0.9926
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 115s 2ms/step - loss: 0.0275 - acc: 0.9914 - val_loss: 0.0229 - val_acc: 0.9933
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 120s 2ms/step - loss: 0.0265 - acc: 0.9914 - val_loss: 0.0228 - val_acc: 0.9933
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 117s 2ms/step - loss: 0.0250 - acc: 0.9922 - val_loss: 0.0285 - val_acc: 0.9912
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 112s 2ms/step - loss: 0.0235 - acc: 0.9925 - val_loss: 0.0177 - val_acc: 0.9945
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 113s 2ms/step - loss: 0.0227 - acc: 0.9926 - val_loss: 0.0230 - val_acc: 0.9926
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 112s 2ms/step - loss: 0.0229 - acc: 0.9930 - val_loss: 0.0217 - val_acc: 0.9933
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 113s 2ms/step - loss: 0.0211 - acc: 0.9934 - val_loss: 0.0186 - val_acc: 0.9946
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 113s 2ms/step - loss: 0.0207 - acc: 0.9934 - val_loss: 0.0188 - val_acc: 0.9940
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 112s 2ms/step - loss: 0.0203 - acc: 0.9934 - val_loss: 0.0211 - val_acc: 0.9932
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 114s 2ms/step - loss: 0.0190 - acc: 0.9938 - val_loss: 0.0200 - val_acc: 0.9941
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 114s 2ms/step - loss: 0.0186 - acc: 0.9940 - val_loss: 0.0202 - val_acc: 0.9937
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 113s 2ms/step - loss: 0.0171 - acc: 0.9943 - val_loss: 0.0194 - val_acc: 0.9943
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 113s 2ms/step - loss: 0.0178 - acc: 0.9944 - val_loss: 0.0196 - val_acc: 0.9943
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 113s 2ms/step - loss: 0.0184 - acc: 0.9940 - val_loss: 0.0184 - val_acc: 0.9943
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 112s 2ms/step - loss: 0.0166 - acc: 0.9946 - val_loss: 0.0191 - val_acc: 0.9936
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 113s 2ms/step - loss: 0.0163 - acc: 0.9945 - val_loss: 0.0182 - val_acc: 0.9943
<keras.callbacks.History at 0x7faa87eef898>

# model.evaluate (on test data)

[0.018214585105333754, 0.9943]

# strategy 

Reduced the number of parameters in CNN and used droupouts to get the required accuracy.
