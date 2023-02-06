# Mixture of experts on depression and anxiety detection

This repository contains the code to run a mixture of experts model on the detection of depression and anxiety on the SetembroBR corpus.

The file MoE contains all the methods necessary to run and predict each timeline. The method ``` run_train ``` expects the type of task (depression or anxiety), the selection ('all_br' gets all the data without any further split) and model name.

For each epoch, the model save the current weights and test them on validation set to decide the best option.
