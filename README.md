# Skin Disease Detection Using YOLOv8

![Skin Disease Detection](https://github.com/Nishant2018/YOLO-v8---Skin-Diseases---Detection/blob/main/1.png)

In this project, I trained a YOLOv8 model to detect various skin diseases from images. The YOLO (You Only Look Once) model is known for its real-time object detection capabilities, making it a suitable choice for medical image analysis where quick and accurate detection is crucial.

## Evaluation Metrics
- **mAP (Mean Average Precision):** 48.9%
- **Precision:** 55.8%
- **Recall:** 48.3%

These metrics indicate the model's performance in detecting skin diseases, with a precision of 55.8%, which means that out of all the positive predictions made by the model, 55.8% were correct. The recall of 48.3% indicates that the model was able to detect 48.3% of all actual positive cases.

## Model Architecture
The YOLOv8 model was chosen for its balance between speed and accuracy. The architecture was fine-tuned on a custom dataset of skin disease images, allowing the model to learn the unique features of various skin conditions.

## Training Process
The model was trained on a diverse dataset with multiple skin disease categories. Data augmentation techniques were applied to increase the robustness of the model, including random flips, rotations, and color adjustments. The training process was monitored using validation metrics, ensuring that the model did not overfit and could generalize well to unseen data.

## Results
Despite the challenges posed by the variability in skin disease appearances, the YOLOv8 model achieved promising results, as reflected in the evaluation metrics. Further improvements can be made by increasing the dataset size and applying more sophisticated augmentation techniques.

