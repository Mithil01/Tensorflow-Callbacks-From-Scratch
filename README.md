# Tensorflow-Callbacks-From-Scratch
- The goal of this project is to implement custom callbacks in tensorflow such as learningratescheduler,customMetrics, TerminatingTraining  from scratch along with using predefined callbacks provided by tensorflow.

## Incase you are unable to view the github code due to large file size then use the below colab code link:
[Link](https://colab.research.google.com/github/Mithil01/Tensorflow-Callbacks-From-Scratch/blob/main/Tensorflow_callbacks_from_scratch.ipynb)

## Callbacks Implemented

### 1. CustomMetrics
- Implementing custom callback(CustomMetrics) to find microf1 score and AUC score.

### 2. TerminateNaN
- Implementing custom callback(TerminateNaN) to terminate the training if loss is invalid or weights become NAN

### 3. lrate_scheduler
- Implementing custom callback(lrate_scheduler) decay learning based on below conditions :
1. If your validation accuracy at that epoch is less than previous epoch accuracy, you have to decrese the learning rate by 10%.
2. For every 3rd epoch, decay your learning rate by 5%.

### 4. Tensorflow callbacks
- Modelcheckpointing callback to save best weights
- Earlystopping callback to stop training if performance degrades.
- Tensorboard callback to display graphs for train and test accuracies.

## Model Architecture
! [Image Alt Text](cb_assignment_arch.png)
  
