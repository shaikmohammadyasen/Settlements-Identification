# Optimized settlement identification through satellite imagery using SSD Mobile-Net
# Abstract
This research focuses on optimizing settlement identification through satellite imagery using the Single Shot Multi-Box Detector (SSD) Mobile-Net on the Jetson Nano platform.
The primary objective is to enhance the accuracy and efficiency of detecting human settlements in various geographic regions. We employed SSD Mobile-Net due to its balance of speed and precision, suitable for real-time applications on edge devices like the Jetson Nano. 
The methodology involved training the model on a diverse dataset of satellite images, followed by rigorous testing to evaluate performance metrics such as accuracy, precision, and recall. 
The results demonstrate a significant improvement in identifying settlements, with the optimized model achieving high accuracy rates while maintaining low computational requirements. 
This approach has the potential to aid in urban planning, disaster management, and resource allocation by providing reliable and timely settlement data. Future work will explore integrating additional contextual data and expanding the model’s applicability to other environmental monitoring tasks.
#  System Architecture
(Single Shot MultiBox Detector) architectures for ob
ject detection, using VGG16 (Figure a) and MobileNetv2 (Figure b) as backbone networks.
 VGG16 employs standard convolutions (blue blocks) to extract multi-scale feature maps,
 achieving high accuracy but with increased computational cost. In contrast, MobileNetv2
 uses Depthwise Separable Convolutions (green blocks) to reduce computational complexity
 and model size, making it more efficient for real-time applications. Both architectures gen
erate feature maps of varying sizes (38×38, 19×19, 10×10, etc.) for multi-scale detection,
 followed by Non-Maximum Suppression (NMS) to refine predictions. While VGG16-based
 SSD delivers better accuracy, MobileNetv2-based SSD offers faster inference and efficiency,
 making it ideal for resource-constrained environments.
 
 
