# Real-World Applications

Nine application areas from the *Grasp Detection & Manipulation Vision in Robotics* infographic. Compact listings — official paper code, datasets, frameworks, and production stacks. Hubs (AnyGrasp, Contact-GraspNet, GraspNet, MoveIt, cuRobo, SAM2, LeRobot, Stretch) appear under multiple topics on purpose.

## 1. Random Bin Picking

Finds collision-free grasps for randomly stacked objects.

- [graspnet/graspnet-baseline](https://github.com/graspnet/graspnet-baseline) — GraspNet-1Billion clutter baseline
- [graspnet/graspnetAPI](https://github.com/graspnet/graspnetAPI) — 1B-grasp dataset API + eval
- [graspnet/suctionnetAPI](https://github.com/graspnet/suctionnetAPI) — SuctionNet-1Billion suction labels
- [NVlabs/contact_graspnet](https://github.com/NVlabs/contact_graspnet) — 6-DoF grasps in cluttered bins
- [graspnet/anygrasp_sdk](https://github.com/graspnet/anygrasp_sdk) — AnyGrasp real-robot bin API
- [NVlabs/6dof-graspnet](https://github.com/NVlabs/6dof-graspnet) — variational 6-DoF grasp generation
- [NVlabs/acronym](https://github.com/NVlabs/acronym) — ACRONYM 17M simulated grasps
- [NVlabs/GraspGen](https://github.com/NVlabs/GraspGen) — diffusion 6-DoF grasp generation
- [ethz-asl/vgn](https://github.com/ethz-asl/vgn) — Volumetric Grasping Network (TSDF)
- [lianghongzhuo/PointNetGPD](https://github.com/lianghongzhuo/PointNetGPD) — PointNet grasp quality from clouds
- [atenpas/gpd](https://github.com/atenpas/gpd) — classic Grasp Pose Detection
- [dougsm/ggcnn](https://github.com/dougsm/ggcnn) — real-time generative grasp CNN
- [skumra/robotic-grasping](https://github.com/skumra/robotic-grasping) — GR-ConvNet antipodal grasps
- [BerkeleyAutomation/dex-net](https://github.com/BerkeleyAutomation/dex-net) — Dex-Net robust metrics / bin policies
- [BerkeleyAutomation/gqcnn](https://github.com/BerkeleyAutomation/gqcnn) — GQ-CNN train + ROS deploy
- [andyzeng/visual-pushing-grasping](https://github.com/andyzeng/visual-pushing-grasping) — push-then-grasp clutter RL
- [andyzeng/arc-robot-vision](https://github.com/andyzeng/arc-robot-vision) — Amazon Robotics Challenge vision
- [andyzeng/apc-vision-toolbox](https://github.com/andyzeng/apc-vision-toolbox) — APC shelf/bin toolbox
- [sunhan1997/IndusGrasp](https://github.com/sunhan1997/IndusGrasp) — industrial RGB-D bin picking
- [rcao-hk/UISN](https://github.com/rcao-hk/UISN) — uncertainty-aware suction in clutter
- [moveit/moveit_grasps](https://github.com/moveit/moveit_grasps) — geometric grasps + collision filter
- [NVlabs/curobo](https://github.com/NVlabs/curobo) — collision-free extract from a bin
- [intel/ros2_grasp_library](https://github.com/intel/ros2_grasp_library) — OpenVINO + MoveIt industrial grasp
- [haosulab/ManiSkill](https://github.com/haosulab/ManiSkill) — PickClutter / bin tasks
- [ARISE-Initiative/robosuite](https://github.com/ARISE-Initiative/robosuite) — PickPlace bin envs
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) — GPU bin/clutter sim
- [google-research/ravens](https://github.com/google-research/ravens) — Transporter pick-place
- [ivalab/grasp_multiObject](https://github.com/ivalab/grasp_multiObject) — multi-object multi-grasp RGB-D set
- [THU-VCLab/HGGD](https://github.com/THU-VCLab/HGGD) — heatmap-guided 6-DoF in clutter
- [GeorgeDu/vision-based-robotic-grasping](https://github.com/GeorgeDu/vision-based-robotic-grasping) — survey hub

## 2. Warehouse Order Picking

Identifies requested SKUs and determines the best grasp.

- [facebookresearch/home-robot](https://github.com/facebookresearch/home-robot) — open-vocab mobile pick-and-place
- [graspnet/anygrasp_sdk](https://github.com/graspnet/anygrasp_sdk) — warehouse-ready 6-DoF API
- [NVlabs/contact_graspnet](https://github.com/NVlabs/contact_graspnet) — cluttered shelf/tote grasps
- [graspnet/graspnet-baseline](https://github.com/graspnet/graspnet-baseline) — general object grasp in totes
- [cliport/cliport](https://github.com/cliport/cliport) — language-conditioned kitting
- [google-research/ravens](https://github.com/google-research/ravens) — kitting / packing benchmark
- [huangwl18/ReKep](https://github.com/huangwl18/ReKep) — relational keypoint constraints
- [huangwl18/VoxPoser](https://github.com/huangwl18/VoxPoser) — LLM 3D value maps for pick
- [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) — SKU / tote detectors
- [AILab-CVC/YOLO-World](https://github.com/AILab-CVC/YOLO-World) — open-vocab warehouse detection
- [IDEA-Research/GroundingDINO](https://github.com/IDEA-Research/GroundingDINO) — language SKU grounding
- [facebookresearch/sam2](https://github.com/facebookresearch/sam2) — instance masks on shelves
- [moveit/moveit2](https://github.com/moveit/moveit2) — pick-place planning
- [ros-planning/navigation2](https://github.com/ros-planning/navigation2) — aisle navigation to pick faces
- [open-rmf/rmf](https://github.com/open-rmf/rmf) — multi-robot warehouse fleet
- [NVlabs/curobo](https://github.com/NVlabs/curobo) — GPU collision-free pick motions
- [NVIDIA-ISAAC-ROS/isaac_ros_cumotion](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_cumotion) — cuMotion MoveIt plugin
- [hello-robot/stretch_ros2](https://github.com/hello-robot/stretch_ros2) — mobile pick in aisles
- [huggingface/lerobot](https://github.com/huggingface/lerobot) — learned warehouse policies
- [Physical-Intelligence/openpi](https://github.com/Physical-Intelligence/openpi) — π0 generalist pick skills
- [openvla/openvla](https://github.com/openvla/openvla) — language pick policies
- [octo-models/octo](https://github.com/octo-models/octo) — generalist robot transformer
- [haosulab/ManiSkill](https://github.com/haosulab/ManiSkill) — pick-place skill bench
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) — warehouse digital twins
- [BerkeleyAutomation/gqcnn](https://github.com/BerkeleyAutomation/gqcnn) — suction + jaw warehouse grasps
- [graspnet/suctionnetAPI](https://github.com/graspnet/suctionnetAPI) — suction on packaged goods
- [intel/ros2_grasp_library](https://github.com/intel/ros2_grasp_library) — industrial visual grasp
- [andyzeng/visual-pushing-grasping](https://github.com/andyzeng/visual-pushing-grasping) — singulate piled SKUs
- [BaiShuanghao/Awesome-Robotics-Manipulation](https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation) — survey hub
- [Po-Jen/awesome-grasping](https://github.com/Po-Jen/awesome-grasping) — grasping libraries list

## 3. Industrial Assembly

Grasps and aligns components for precise assembly.

- [clvrai/furniture-bench](https://github.com/clvrai/furniture-bench) — FurnitureBench real IKEA-style assembly
- [clvrai/furniture](https://github.com/clvrai/furniture) — IKEA furniture assembly sim (60+ models)
- [haosulab/ManiSkill](https://github.com/haosulab/ManiSkill) — PegInsertion and assembly skills
- [ARISE-Initiative/robosuite](https://github.com/ARISE-Initiative/robosuite) — TwoArmPegInHole / assembly
- [NVlabs/curobo](https://github.com/NVlabs/curobo) — collision-free assembly motion
- [NVlabs/cuTAMP](https://github.com/NVlabs/cuTAMP) — GPU-parallel task-and-motion planning
- [RobotLocomotion/drake](https://github.com/RobotLocomotion/drake) — assembly planning + contact
- [moveit/moveit_task_constructor](https://github.com/moveit/moveit_task_constructor) — pick-insert stage graphs
- [moveit/moveit2](https://github.com/moveit/moveit2) — industrial motion planning
- [ros-industrial](https://github.com/ros-industrial) — vendor drivers + assembly cells
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) — factory / IndustReal-style envs
- [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) — contact-rich insertion sim
- [stack-of-tasks/pinocchio](https://github.com/stack-of-tasks/pinocchio) — FK/IK + collision for cells
- [ompl/ompl](https://github.com/ompl/ompl) — sampling planners under tight tolerances
- [real-stanford/diffusion_policy](https://github.com/real-stanford/diffusion_policy) — visuomotor insertion policies
- [tonyzhaozh/act](https://github.com/tonyzhaozh/act) — Action Chunking Transformer assembly
- [huggingface/lerobot](https://github.com/huggingface/lerobot) — assembly imitation hub
- [Physical-Intelligence/openpi](https://github.com/Physical-Intelligence/openpi) — generalist assembly skills
- [google-research/ravens](https://github.com/google-research/ravens) — kit assembly / packing
- [cliport/cliport](https://github.com/cliport/cliport) — language assembly instructions
- [NVlabs/FoundationPose](https://github.com/NVlabs/FoundationPose) — part 6D pose for alignment
- [facebookresearch/sam2](https://github.com/facebookresearch/sam2) — part instance masks
- [daerduoCarey/where2act](https://github.com/daerduoCarey/where2act) — actionable parts (handles, lids)
- [haosulab/SAPIEN](https://github.com/haosulab/SAPIEN) — articulated assembly assets
- [frankaemika/franka_ros2](https://github.com/frankaemika/franka_ros2) — Franka assembly workcell
- [ros-industrial/universal_robot](https://github.com/ros-industrial/universal_robot) — UR industrial stacks
- [flexible-collision-library/fcl](https://github.com/flexible-collision-library/fcl) — collision checking
- [NVIDIA-ISAAC-ROS/isaac_ros_cumotion](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_cumotion) — cuMotion for cells
- [swri-robotics](https://github.com/swri-robotics) — NIST-style tactile assembly
- [BaiShuanghao/Awesome-Robotics-Manipulation](https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation) — assembly paper index

## 4. Food Handling & Packaging

Uses controlled grasping for fragile and deformable products.

- [armlabstanford/dexfruit](https://github.com/armlabstanford/dexfruit) — DexFruit tactile + 3DGS fruit handling
- [Xingyu-Lin/softgym](https://github.com/Xingyu-Lin/softgym) — SoftGym cloth/fluid/food-like deformables
- [dfki-ric/deformable_gym](https://github.com/dfki-ric/deformable_gym) — RL gym for 3D deformable grasp
- [NVlabs/DefGraspSim](https://github.com/NVlabs/DefGraspSim) — grasp quality on 3D deformables
- [BerkeleyAutomation/gqcnn](https://github.com/BerkeleyAutomation/gqcnn) — suction + parallel food picks
- [BerkeleyAutomation/dex-net](https://github.com/BerkeleyAutomation/dex-net) — robust metrics for fragile items
- [graspnet/anygrasp_sdk](https://github.com/graspnet/anygrasp_sdk) — irregular produce 6-DoF
- [NVlabs/contact_graspnet](https://github.com/NVlabs/contact_graspnet) — cluttered food bins
- [graspnet/suctionnetAPI](https://github.com/graspnet/suctionnetAPI) — packaged-goods suction
- [dougsm/ggcnn](https://github.com/dougsm/ggcnn) — fast planar food grasp
- [facebookresearch/digit-interface](https://github.com/facebookresearch/digit-interface) — DIGIT tactile slip on produce
- [facebookresearch/tacto](https://github.com/facebookresearch/tacto) — tactile sim for food textures
- [gelsightinc/gsrobotics](https://github.com/gelsightinc/gsrobotics) — GelSight Mini force/slip
- [Shreeyak/cleargrasp](https://github.com/Shreeyak/cleargrasp) — bowls, bottles, clamshells
- [Healthcare-Robotics/assistive-gym](https://github.com/Healthcare-Robotics/assistive-gym) — feeding / pouring tasks
- [google-research/ravens](https://github.com/google-research/ravens) — packing / kitting food SKUs
- [haosulab/ManiSkill](https://github.com/haosulab/ManiSkill) — pour / pick-clutter skills
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) — deformable PhysX food analogs
- [huggingface/lerobot](https://github.com/huggingface/lerobot) — food-handling imitation
- [real-stanford/diffusion_policy](https://github.com/real-stanford/diffusion_policy) — gentle contact-rich policies
- [moveit/moveit2](https://github.com/moveit/moveit2) — constrained packaging motions
- [NVlabs/curobo](https://github.com/NVlabs/curobo) — collision-free in pack cells
- [facebookresearch/sam2](https://github.com/facebookresearch/sam2) — produce instance masks
- [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) — food/defect detectors
- [Poom1150/YouOnlyGraspOnce](https://github.com/Poom1150/YouOnlyGraspOnce) — benign multi-finger agri/food grasp
- [andyzeng/visual-pushing-grasping](https://github.com/andyzeng/visual-pushing-grasping) — singulate packed items
- [ARISE-Initiative/robosuite](https://github.com/ARISE-Initiative/robosuite) — pick-place packaging envs
- [intel/ros2_grasp_library](https://github.com/intel/ros2_grasp_library) — pack-line visual grasp
- [Xingyu-Lin/softgym](https://github.com/Xingyu-Lin/softgym) — PourWater / TransportWater food analogs
- [linchangyi1/Awesome-Touch](https://github.com/linchangyi1/Awesome-Touch) — tactile survey for gentle grasp

## 5. Agricultural Harvesting

Detects fruit and determines accessible grasp points.

- [armlabstanford/dexfruit](https://github.com/armlabstanford/dexfruit) — DexFruit: tactile + FruitSplat inspection
- [DaviddNie/UR10e_vision_based_fruit_harvesting](https://github.com/DaviddNie/UR10e_vision_based_fruit_harvesting) — ROS2 UR10e + YOLO + MoveIt harvest
- [Now4czyk/arws](https://github.com/Now4czyk/arws) — UR3e + OAK-D Pro apple harvest
- [JVP15/fruit-detection](https://github.com/JVP15/fruit-detection) — Deep Fruit Vision (apple/papaya/pineapple)
- [PavanproJack/Fruit-Detection-in-Orchards](https://github.com/PavanproJack/Fruit-Detection-in-Orchards) — orchard detect + count for harvest
- [AgRoboticsResearch/corobotic-platform](https://github.com/AgRoboticsResearch/corobotic-platform) — co-robotic apple harvest platform
- [JPBG-USP/graspe](https://github.com/JPBG-USP/graspe) — grape thinning and harvest arm
- [AbhinavB7/RoboHarvest](https://github.com/AbhinavB7/RoboHarvest) — mobile UR10 fruit picker (Gazebo)
- [eric-mjk/BerryBot_YOLO-perception](https://github.com/eric-mjk/BerryBot_YOLO-perception) — berry harvest YOLO perception
- [NigerChel/WBC-UR5-Harvest](https://github.com/NigerChel/WBC-UR5-Harvest) — whole-body UR5 harvest control
- [SkeyPr/Autonomous-Agriculture-Bot](https://github.com/SkeyPr/Autonomous-Agriculture-Bot) — ROS2 greenhouse harvest sim
- [kofim0144/Team_Chale](https://github.com/kofim0144/Team_Chale) — RGB-D greenhouse harvest stack
- [markfrosty/Tree-Sensorization-for-Robotic-Fruit-Harvesting](https://github.com/markfrosty/Tree-Sensorization-for-Robotic-Fruit-Harvesting) — IMU tree sensing for apple pick
- [rishotics/Autono_Fruit_Plucking_Robot_TCTD](https://github.com/rishotics/Autono_Fruit_Plucking_Robot_TCTD) — FPGA fruit plucker
- [yongvc/Capstone-2526-M2G01](https://github.com/yongvc/Capstone-2526-M2G01) — lemon harvest visual servo
- [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) — YOLO used in most harvest rigs
- [graspnet/anygrasp_sdk](https://github.com/graspnet/anygrasp_sdk) — 6-DoF on irregular produce
- [NVlabs/contact_graspnet](https://github.com/NVlabs/contact_graspnet) — canopy / cluster grasps
- [dougsm/ggcnn](https://github.com/dougsm/ggcnn) — lightweight planar fruit grasp
- [BerkeleyAutomation/gqcnn](https://github.com/BerkeleyAutomation/gqcnn) — grasp quality on produce
- [facebookresearch/sam2](https://github.com/facebookresearch/sam2) — fruit instance masks in canopy
- [IDEA-Research/GroundingDINO](https://github.com/IDEA-Research/GroundingDINO) — open-vocab crop detection
- [DepthAnything/Depth-Anything-V2](https://github.com/DepthAnything/Depth-Anything-V2) — monocular orchard depth
- [IntelRealSense/librealsense](https://github.com/IntelRealSense/librealsense) — RGB-D harvest cameras
- [moveit/moveit2](https://github.com/moveit/moveit2) — harvest motion planning
- [ros-planning/navigation2](https://github.com/ros-planning/navigation2) — orchard row navigation
- [haosulab/ManiSkill](https://github.com/haosulab/ManiSkill) — harvest skill learning
- [huggingface/lerobot](https://github.com/huggingface/lerobot) — imitation harvest policies
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) — agri digital-twin envs
- [Poom1150/YouOnlyGraspOnce](https://github.com/Poom1150/YouOnlyGraspOnce) — damage-free multi-finger produce grasp

## 6. Recycling & Sorting

Grasps irregular waste objects for autonomous sorting.

- [YaelBenShalom/Recycler-Baxter](https://github.com/YaelBenShalom/Recycler-Baxter) — Baxter can/bottle sort (RealSense + MoveIt)
- [Gaurang-1402/MechaSort](https://github.com/Gaurang-1402/MechaSort) — recycling-line manipulator + CV
- [nhathout/trashformer](https://github.com/nhathout/trashformer) — YOLOv8 four-bin waste sorter
- [glarbi/Vision-based-waste-sorting](https://github.com/glarbi/Vision-based-waste-sorting) — CNN conveyor waste sort
- [Duks31/AMMR](https://github.com/Duks31/AMMR) — Cika mobile waste collector + sorter
- [jennifermarsman/PhiRecycling](https://github.com/jennifermarsman/PhiRecycling) — Phi-3 vision recycle classifier
- [seedahi/AGPGA-data](https://github.com/seedahi/AGPGA-data) — kitchen-waste grasp-point dataset
- [graspnet/anygrasp_sdk](https://github.com/graspnet/anygrasp_sdk) — irregular waste 6-DoF grasps
- [graspnet/suctionnetAPI](https://github.com/graspnet/suctionnetAPI) — suction on bottles and film
- [NVlabs/contact_graspnet](https://github.com/NVlabs/contact_graspnet) — cluttered scrap bins
- [atenpas/gpd](https://github.com/atenpas/gpd) — classic cloud grasp on scrap
- [dougsm/ggcnn](https://github.com/dougsm/ggcnn) — fast planar waste grasp
- [BerkeleyAutomation/dex-net](https://github.com/BerkeleyAutomation/dex-net) — suction/parallel metrics
- [BerkeleyAutomation/gqcnn](https://github.com/BerkeleyAutomation/gqcnn) — GQ-CNN on recyclables
- [Shreeyak/cleargrasp](https://github.com/Shreeyak/cleargrasp) — transparent PET bottles
- [PKU-EPIC/GraspNeRF](https://github.com/PKU-EPIC/GraspNeRF) — transparent/specular recyclables
- [PKU-EPIC/DREDS](https://github.com/PKU-EPIC/DREDS) — specular/transparent depth restore
- [jun7-shi/ASGrasp](https://github.com/jun7-shi/ASGrasp) — transparent reconstruction + 6-DoF
- [Galaxies99/TransCG](https://github.com/Galaxies99/TransCG) — real transparent depth + grasp
- [facebookresearch/sam2](https://github.com/facebookresearch/sam2) — waste instance masks
- [IDEA-Research/GroundingDINO](https://github.com/IDEA-Research/GroundingDINO) — open-vocab material classes
- [AILab-CVC/YOLO-World](https://github.com/AILab-CVC/YOLO-World) — open-vocab line detection
- [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) — production waste detectors
- [moveit/moveit2](https://github.com/moveit/moveit2) — sort-cell planning
- [intel/ros2_grasp_library](https://github.com/intel/ros2_grasp_library) — industrial visual grasp
- [andyzeng/visual-pushing-grasping](https://github.com/andyzeng/visual-pushing-grasping) — singulate piled waste
- [ethz-asl/vgn](https://github.com/ethz-asl/vgn) — volumetric grasp in clutter
- [NVlabs/acronym](https://github.com/NVlabs/acronym) — sim grasp transfer
- [huggingface/lerobot](https://github.com/huggingface/lerobot) — learned sort policies
- [haosulab/ManiSkill](https://github.com/haosulab/ManiSkill) — pick-and-place sort bench

## 7. Service & Home Robots

Manipulates unfamiliar everyday household objects.

- [jimmyyhwu/tidybot](https://github.com/jimmyyhwu/tidybot) — TidyBot LLM household tidy
- [jimmyyhwu/tidybot2](https://github.com/jimmyyhwu/tidybot2) — TidyBot++ holonomic mobile manipulator
- [facebookresearch/home-robot](https://github.com/facebookresearch/home-robot) — HomeRobot OVMM stack
- [notmahi/dobb-e](https://github.com/notmahi/dobb-e) — Dobb·E in-home imitation
- [hello-robot/stretch_ros2](https://github.com/hello-robot/stretch_ros2) — Stretch mobile manipulator ROS 2
- [hello-robot/stretch_ai](https://github.com/hello-robot/stretch_ai) — Stretch AI apps (grasp, OVMM, EQA)
- [hello-robot/stretch_body](https://github.com/hello-robot/stretch_body) — Stretch Python SDK
- [MarkFzp/mobile-aloha](https://github.com/MarkFzp/mobile-aloha) — Mobile ALOHA whole-body teleop
- [huggingface/lerobot](https://github.com/huggingface/lerobot) — home-robot imitation hub
- [Physical-Intelligence/openpi](https://github.com/Physical-Intelligence/openpi) — π0 VLA home skills
- [openvla/openvla](https://github.com/openvla/openvla) — OpenVLA household policies
- [octo-models/octo](https://github.com/octo-models/octo) — Octo generalist
- [thu-ml/RDT-1B](https://github.com/thu-ml/RDT-1B) — bimanual home manipulation
- [real-stanford/diffusion_policy](https://github.com/real-stanford/diffusion_policy) — visuomotor home skills
- [tonyzhaozh/act](https://github.com/tonyzhaozh/act) — Action Chunking Transformer
- [stepjam/RLBench](https://github.com/stepjam/RLBench) — 100+ household tasks
- [haosulab/ManiSkill](https://github.com/haosulab/ManiSkill) — home-like manipulation skills
- [facebookresearch/habitat-lab](https://github.com/facebookresearch/habitat-lab) — indoor mobile manipulation sim
- [graspnet/anygrasp_sdk](https://github.com/graspnet/anygrasp_sdk) — everyday object grasp
- [NVlabs/contact_graspnet](https://github.com/NVlabs/contact_graspnet) — cluttered tabletops
- [facebookresearch/sam2](https://github.com/facebookresearch/sam2) — household instance seg
- [IDEA-Research/GroundingDINO](https://github.com/IDEA-Research/GroundingDINO) — language-grounded tidy
- [HrushikeshBudhale/decluttering_domestic_robot](https://github.com/HrushikeshBudhale/decluttering_domestic_robot) — Tiago search-and-tidy
- [nourmorsy/Home_Service_Robot](https://github.com/nourmorsy/Home_Service_Robot) — NLP + vision home service
- [UT-Austin-RPL/GROOT](https://github.com/UT-Austin-RPL/GROOT) — foundation policies for homes
- [google-research/robotics_transformer](https://github.com/google-research/robotics_transformer) — RT-1 lineage
- [hello-robot/stretch_tool_share](https://github.com/hello-robot/stretch_tool_share) — household end-effectors
- [ARISE-Initiative/robosuite](https://github.com/ARISE-Initiative/robosuite) — household bench tasks
- [isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) — home digital twins
- [BaiShuanghao/Awesome-Robotics-Manipulation](https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation) — survey hub

## 8. Healthcare & Assistive Robots

Safely manipulates medicines, instruments, and daily-use objects.

- [Healthcare-Robotics/assistive-gym](https://github.com/Healthcare-Robotics/assistive-gym) — feeding, dressing, bathing, drinking sim
- [Healthcare-Robotics/visual-force-torque](https://github.com/Healthcare-Robotics/visual-force-torque) — camera-as-F/T for care grippers
- [robotology/assistive-rehab](https://github.com/robotology/assistive-rehab) — assistive / rehab robotics stack
- [dfreer15/BCIRobotControl](https://github.com/dfreer15/BCIRobotControl) — MIndGrasp EEG assistive grasp
- [rashwinr/grasp-rehabilitator](https://github.com/rashwinr/grasp-rehabilitator) — pincer-grasp rehab device
- [hello-robot/stretch_ros2](https://github.com/hello-robot/stretch_ros2) — Stretch widely used in care settings
- [hello-robot/stretch_tool_share](https://github.com/hello-robot/stretch_tool_share) — feeding / care end-effectors
- [facebookresearch/home-robot](https://github.com/facebookresearch/home-robot) — ADL mobile manipulation
- [jimmyyhwu/tidybot](https://github.com/jimmyyhwu/tidybot) — personalized physical assistance
- [graspnet/anygrasp_sdk](https://github.com/graspnet/anygrasp_sdk) — medicine bottles / ADL objects
- [Shreeyak/cleargrasp](https://github.com/Shreeyak/cleargrasp) — transparent vials and cups
- [Galaxies99/TransCG](https://github.com/Galaxies99/TransCG) — real transparent depth for meds
- [facebookresearch/digit-interface](https://github.com/facebookresearch/digit-interface) — DIGIT tactile for safe contact
- [gelsightinc/gsrobotics](https://github.com/gelsightinc/gsrobotics) — GelSight Mini clinical contact
- [BerkeleyAutomation/dex-net](https://github.com/BerkeleyAutomation/dex-net) — gentle / stable grasp metrics
- [BerkeleyAutomation/gqcnn](https://github.com/BerkeleyAutomation/gqcnn) — GQ-CNN on ADL objects
- [moveit/moveit2](https://github.com/moveit/moveit2) — constrained near-body planning
- [NVlabs/curobo](https://github.com/NVlabs/curobo) — collision-free motion near people
- [haosulab/ManiSkill](https://github.com/haosulab/ManiSkill) — assistive skill learning
- [huggingface/lerobot](https://github.com/huggingface/lerobot) — care-task imitation
- [facebookresearch/sam2](https://github.com/facebookresearch/sam2) — body / object masks
- [IDEA-Research/GroundingDINO](https://github.com/IDEA-Research/GroundingDINO) — “hand me the pill bottle”
- [DepthAnything/Depth-Anything-V2](https://github.com/DepthAnything/Depth-Anything-V2) — bedside monocular depth
- [openvla/openvla](https://github.com/openvla/openvla) — language-conditioned care
- [Physical-Intelligence/openpi](https://github.com/Physical-Intelligence/openpi) — generalist care skills
- [eigeneddie/rehab-bot-project](https://github.com/eigeneddie/rehab-bot-project) — post-stroke rehab bot
- [Kinova-Automation](https://github.com/Kinova-Automation) — Jaco assistive arm drivers
- [isaac-for-healthcare](https://github.com/isaac-for-healthcare) — NVIDIA Isaac Healthcare robotics
- [facebookresearch/tacto](https://github.com/facebookresearch/tacto) — tactile sim for safe grasp
- [linchangyi1/Awesome-Touch](https://github.com/linchangyi1/Awesome-Touch) — tactile survey for HRI

## 9. Autonomous Mobile Manipulation

Combines navigation, perception, and grasping into autonomous action.

- [MarkFzp/mobile-aloha](https://github.com/MarkFzp/mobile-aloha) — Mobile ALOHA bimanual mobile manip
- [facebookresearch/home-robot](https://github.com/facebookresearch/home-robot) — OVMM explore-find-grasp-place
- [jimmyyhwu/tidybot2](https://github.com/jimmyyhwu/tidybot2) — TidyBot++ holonomic mobile manip
- [jimmyyhwu/tidybot](https://github.com/jimmyyhwu/tidybot) — TidyBot language-guided tidy
- [real-stanford/umi-on-legs](https://github.com/real-stanford/umi-on-legs) — UMI on Legs whole-body mobile manip
- [hello-robot/stretch_ros2](https://github.com/hello-robot/stretch_ros2) — Stretch ROS 2 stack
- [hello-robot/stretch_ai](https://github.com/hello-robot/stretch_ai) — Stretch AI OVMM / grasp apps
- [AutonoBot-Lab/BestMan](https://github.com/AutonoBot-Lab/BestMan) — BestMan mobile manipulator platform
- [leggedrobotics/perceptive_mpc](https://github.com/leggedrobotics/perceptive_mpc) — perceptive MPC continuous mobile manip
- [NeuracoreAI/bigym](https://github.com/NeuracoreAI/bigym) — BiGym bimanual mobile benchmark
- [xxm19/hommi](https://github.com/xxm19/hommi) — HoMMI whole-body from human demo
- [BenBurgessLimerick/ManipulationOnTheMove](https://github.com/BenBurgessLimerick/ManipulationOnTheMove) — manipulation-on-the-move architecture
- [BJHYZJ/DovSG](https://github.com/BJHYZJ/DovSG) — dynamic open-vocab 3D scene graphs
- [InternRobotics/EBench](https://github.com/InternRobotics/EBench) — generalist mobile-manip diagnosis
- [m2diffuser/M2Diffuser](https://github.com/m2diffuser/M2Diffuser) — diffusion trajectory opt for MoMa
- [user432/gamma](https://github.com/user432/gamma) — GAMMA graspability-aware mobile manip
- [robot-learning-freiburg/MoMa-LLM](https://github.com/robot-learning-freiburg/MoMa-LLM) — language-grounded mobile manip
- [TIERS/isaac-marl-mobile-manipulation](https://github.com/TIERS/isaac-marl-mobile-manipulation) — Isaac MARL mobile manip
- [jimmyyhwu/spatial-intention-maps](https://github.com/jimmyyhwu/spatial-intention-maps) — multi-agent mobile manip RL
- [Jiayuan-Gu/hab-mobile-manipulation](https://github.com/Jiayuan-Gu/hab-mobile-manipulation) — Habitat mobile manipulation
- [UT-Austin-RobIn/telemoma](https://github.com/UT-Austin-RobIn/telemoma) — TeleMoMa modular teleop
- [facebookresearch/habitat-lab](https://github.com/facebookresearch/habitat-lab) — Habitat indoor MoMa sim
- [haosulab/ManiSkill](https://github.com/haosulab/ManiSkill) — mobile + arm skills
- [NVlabs/curobo](https://github.com/NVlabs/curobo) — GPU whole-body collision-free motion
- [moveit/moveit2](https://github.com/moveit/moveit2) — arm planning on a mobile base
- [ros-planning/navigation2](https://github.com/ros-planning/navigation2) — Nav2 base navigation
- [graspnet/anygrasp_sdk](https://github.com/graspnet/anygrasp_sdk) — onboard 6-DoF grasp
- [NVlabs/contact_graspnet](https://github.com/NVlabs/contact_graspnet) — onboard clutter grasp
- [Physical-Intelligence/openpi](https://github.com/Physical-Intelligence/openpi) — mobile VLA policies
- [huggingface/lerobot](https://github.com/huggingface/lerobot) — mobile imitation hub
- [shannon112/awesome-ros-mobile-robot](https://github.com/shannon112/awesome-ros-mobile-robot) — ROS mobile + manip list
