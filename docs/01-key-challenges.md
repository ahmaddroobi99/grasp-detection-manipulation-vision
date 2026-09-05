# Key Challenges — Grasp Detection & Manipulation Vision

Nine perception and control problems from the infographic *Grasp Detection & Manipulation Vision in Robotics*.
About 30 curated GitHub repositories per challenge: official paper code, datasets, simulators, and shared hubs.

Pipeline this section feeds: **Perception → 3D Understanding → Grasp Detection → 6D Pose → Collision Avoidance → Grasp → Tactile Feedback → Correction → Intelligent Manipulation**

---

## 1. Clutter & Occlusion — Contact-GraspNet

Target is partially hidden by surrounding objects. Scene-level contact prediction beats instance-first pipelines when segmentation fails.

- [NVlabs/contact_graspnet](https://github.com/NVlabs/contact_graspnet) — Official Contact-GraspNet (ICRA 2021): 6-DoF grasps on raw cluttered clouds
- [graspnet/graspnet-baseline](https://github.com/graspnet/graspnet-baseline) — GraspNet-1Billion baseline for dense cluttered-scene detection
- [andyzeng/visual-pushing-grasping](https://github.com/andyzeng/visual-pushing-grasping) — Push-then-grasp RL for singulating piled objects
- [NVlabs/acronym](https://github.com/NVlabs/acronym) — ACRONYM: 8K objects / 17M grasps used to train Contact-GraspNet
- [chrisdxie/uois](https://github.com/chrisdxie/uois) — Unknown Object Instance Segmentation as clutter preprocess
- [NVlabs/6dof-graspnet](https://github.com/NVlabs/6dof-graspnet) — Sample-and-evaluate 6-DoF GraspNet (Mousavian et al.)
- [rhett-chen/graspness_implementation](https://github.com/rhett-chen/graspness_implementation) — GSNet / Graspness — graspable-region detection in clutter
- [THU-VCLab/HGGD](https://github.com/THU-VCLab/HGGD) — Heatmap-guided 6-DoF grasp detection in clutter
- [iSEE-Laboratory/EconomicGrasp](https://github.com/iSEE-Laboratory/EconomicGrasp) — ECCV 2024 compute-efficient 6-DoF detector
- [lianghongzhuo/PointNetGPD](https://github.com/lianghongzhuo/PointNetGPD) — PointNet grasp-quality scoring from local clouds
- [atenpas/gpd](https://github.com/atenpas/gpd) — Classic Grasp Pose Detection in point clouds
- [dougsm/ggcnn](https://github.com/dougsm/ggcnn) — Real-time generative grasping CNN (~50 Hz)
- [skumra/robotic-grasping](https://github.com/skumra/robotic-grasping) — GR-ConvNet antipodal grasp detection
- [NVlabs/GraspGen](https://github.com/NVlabs/GraspGen) — Diffusion framework for 6-DoF grasping
- [graspnet/graspnetAPI](https://github.com/graspnet/graspnetAPI) — Official API and eval kit for GraspNet-1Billion
- [ethz-asl/vgn](https://github.com/ethz-asl/vgn) — Volumetric Grasping Network on TSDF grids
- [facebookresearch/sam2](https://github.com/facebookresearch/sam2) — SAM 2 instance masks for clutter segmentation
- [IDEA-Research/Grounded-Segment-Anything](https://github.com/IDEA-Research/Grounded-Segment-Anything) — Open-vocab SAM for isolating objects in piles
- [facebookresearch/detectron2](https://github.com/facebookresearch/detectron2) — Instance-segmentation backbone used in grasp pipelines
- [IntelRealSense/librealsense](https://github.com/IntelRealSense/librealsense) — RGB-D capture stack for bin and clutter scenes
- [isl-org/Open3D](https://github.com/isl-org/Open3D) — Point-cloud processing, collision, and visualization
- [PointCloudLibrary/pcl](https://github.com/PointCloudLibrary/pcl) — Classic 3D perception for cluttered scenes
- [NVIDIA/MinkowskiEngine](https://github.com/NVIDIA/MinkowskiEngine) — Sparse convolutions used by AnyGrasp / GSNet
- [facebookresearch/segment-anything](https://github.com/facebookresearch/segment-anything) — SAM v1 class-agnostic masks in clutter
- [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) — YOLO detectors that seed many clutter pipelines
- [GeorgeDu/vision-based-robotic-grasping](https://github.com/GeorgeDu/vision-based-robotic-grasping) — Survey hub of vision-based grasping papers and code
- [BaiShuanghao/Awesome-Robotics-Manipulation](https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation) — Living survey of manipulation and grasping
- [Po-Jen/awesome-grasping](https://github.com/Po-Jen/awesome-grasping) — Curated grasping libraries and datasets
- [rhett-chen/Robotic-grasping-papers](https://github.com/rhett-chen/Robotic-grasping-papers) — Paper list covering clutter and general grasp
- [TX-Leo/Awesome-Robotic-Grasping](https://github.com/TX-Leo/Awesome-Robotic-Grasping) — Methods, datasets, and simulators for grasping

---

## 2. Unseen / Novel Objects — AnyGrasp

The robot must grasp objects never encountered in training. Zero-shot geometry + open-vocab semantics is the current stack.

- [graspnet/anygrasp_sdk](https://github.com/graspnet/anygrasp_sdk) — AnyGrasp SDK: zero-shot 7-DoF grasp and temporal tracking
- [graspnet/AnyDexGrasp](https://github.com/graspnet/AnyDexGrasp) — Dexterous extension of AnyGrasp for novel objects
- [NVlabs/FoundationPose](https://github.com/NVlabs/FoundationPose) — Unified 6D pose estimate and track of novel objects (CVPR 2024)
- [NVlabs/GraspGen](https://github.com/NVlabs/GraspGen) — Diffusion 6-DoF grasps that transfer to unseen shapes
- [Psi-Robot/DexGraspVLA](https://github.com/Psi-Robot/DexGraspVLA) — VLA framework for general dexterous grasping
- [NVlabs/contact_graspnet](https://github.com/NVlabs/contact_graspnet) — ACRONYM-trained; strong novel-object transfer in clutter
- [graspnet/graspnet-baseline](https://github.com/graspnet/graspnet-baseline) — Official seen / similar / novel evaluation splits
- [NVlabs/BundleSDF](https://github.com/NVlabs/BundleSDF) — Neural 6-DoF tracking and reconstruction of unknown objects
- [liuyuan-pal/Gen6D](https://github.com/liuyuan-pal/Gen6D) — Model-free generalizable 6-DoF pose from RGB
- [teal024/FoundationPose-plus-plus](https://github.com/teal024/FoundationPose-plus-plus) — Real-time FoundationPose tracker for dynamic scenes
- [ammar-n-abbas/FoundationPoseROS2](https://github.com/ammar-n-abbas/FoundationPoseROS2) — ROS 2 + RealSense + SAM2 FoundationPose stack
- [NVlabs/acronym](https://github.com/NVlabs/acronym) — Large synthetic grasp set for open-set training
- [graspnet/graspnetAPI](https://github.com/graspnet/graspnetAPI) — Eval protocol for novel-object grasp AP
- [facebookresearch/sam2](https://github.com/facebookresearch/sam2) — Class-agnostic segmentation of never-seen objects
- [IDEA-Research/GroundingDINO](https://github.com/IDEA-Research/GroundingDINO) — Open-vocabulary detector for language-specified items
- [IDEA-Research/Grounded-Segment-Anything](https://github.com/IDEA-Research/Grounded-Segment-Anything) — Grounded SAM for open-set isolation
- [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) — YOLO-World and open-set detection heads
- [openvla/openvla](https://github.com/openvla/openvla) — OpenVLA generalist policy including novel-object pick
- [Physical-Intelligence/openpi](https://github.com/Physical-Intelligence/openpi) — pi0 vision-language-action model
- [octo-models/octo](https://github.com/octo-models/octo) — Octo generalist robot policy
- [real-stanford/diffusion_policy](https://github.com/real-stanford/diffusion_policy) — Visuomotor diffusion policies for unseen instances
- [cliport/cliport](https://github.com/cliport/cliport) — Language-conditioned pick of unseen kits
- [google-research/ravens](https://github.com/google-research/ravens) — Transporter networks for novel-object rearrangement
- [facebookresearch/home-robot](https://github.com/facebookresearch/home-robot) — Open-vocabulary mobile manipulation stack
- [haosulab/ManiSkill](https://github.com/haosulab/ManiSkill) — GPU sim benchmark with many unseen assets
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) — Train policies on randomized novel objects
- [ARISE-Initiative/robosuite](https://github.com/ARISE-Initiative/robosuite) — Modular suite with object randomization
- [openai/CLIP](https://github.com/openai/CLIP) — Semantic embedding used by language-guided grasp
- [ZhongqunZHANG/awesome-6d-object](https://github.com/ZhongqunZHANG/awesome-6d-object) — Survey of novel-object 6D pose methods
- [huggingface/lerobot](https://github.com/huggingface/lerobot) — Imitation-learning hub for open-set pick skills
