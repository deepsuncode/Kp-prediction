KpNet_model.py changed in line 187 to be compatible with tensorflow 2.11:

self.model.compile(optimizer=tf.keras.optimizers.legacy.Adam(learning_rate=adam_lr),loss=loss, metrics=metrics)


Requirements:

tensorflow 2.11.0
tensorflow-probability 0.19.0
numpy 1.21.6
pandas 1.3.5
keras 2.11.0
scikit-learn 1.0.2
matplotlib 3.2.2
matplotlib_inline 0.1.6
seaborn 0.11.2
scipy 1.7.3
joblib 1.2.0