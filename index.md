
# STDFormer: Spatio-Temporal Disentanglement for 3D Human Mesh Recovery from Monocular Videos with Transformer
This project code [Code](https://github.com/STDFormer-3D-Human-Mesh-Recovery/STDFormer)

![ff963148652c68d6a8d21770c9dd530](https://github.com/Xushuolin/STDFormer/assets/121299261/38e5e823-e68d-43fc-947b-ce478ad92933)
The figure show the performance of our model in a sequential video task, showing the stability of the reconstruction results, the stability against occlusion interference and the advantages of limb position alignment.

![pipline](https://github.com/Xushuolin/STDFormer/assets/121299261/07bf372f-7d02-493f-bf72-bd7b2b0be288)
Overview of STDFormer. The figure illustrates STDFormer model's pipeline: input video frames are processed to extract features through a CNN, which are then disentangled by SD and TD modules, reweighted by a Sigmoid function, and finally decoded by a Transformer encoder to output the sequenced 3D human mesh.

## Abstract
A novel spatio-temporal disentanglement method, STDFormer is presented, specifically designed for reconstructing sequential 3D human meshes from monocular videos. Precise and stable dynamic meshes are recovered, significantly reducing the phenomenon of human mesh distortion and mesh-vertex jitter. STDFormer for the first time adopts a vertex-based paradigm, featuring two main innovative points: the spatial disentanglement (SD) and the temproal disentanglement (TD). The former is dedicated to extracting precise target features from coupled spatial information in frames, with a particular focus on feature extraction in complex backgrounds, and the latter, through the integration of temporal information across frames, effectively disentangles features in both spatial and temporal dimensions. The process mitigates estimation errors in inter-frame target features, ensuring highly accurate and motion-consistent reconstruction of human motion features in videos.  In comparisons of the SOTA performance on the 3DPW benchmark, our experimental results demonstrate that STDFormer effectively alleviates the issue of mesh smoothness in frames while enhancing the accuracy of human motion estimation.

![pipline](https://github.com/Xushuolin/STDFormer/assets/121299261/07bf372f-7d02-493f-bf72-bd7b2b0be288)
Overview of STDFormer. The figure illustrates STDFormer model's pipeline: input video frames are processed to extract features through a CNN, which are then disentangled by SD and TD modules, reweighted by a Sigmoid function, and finally decoded by a Transformer encoder to output the sequenced 3D human mesh.

## Result

![论文作图20](https://github.com/Xushuolin/STDFormer/assets/121299261/11078bc5-162b-4672-bc26-1a3dd279b9e9)
The image presents a comparative analysis of the performance of different algorithms in the task of video pose estimation, showcasing their ability to handle complex scenes such as a person riding a bicycle. The original video sequence is shown on the far left, serving as a benchmark.

### Video demonstrate
