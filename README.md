# Image to Point Cloud using Depth Estimation
  
- 2022년도 1학기 알파프로젝트 김준수  
- 이미지에서 깊이추정 후 이를 PointCloud로 변환
- LiDAR의 Sparse한 부분을 보강할 수 있을 것으로 기대
  
![image](https://user-images.githubusercontent.com/73662370/176345506-4b82ac36-be9a-42ec-be98-224e87aee9d0.png)

## Requirements

- Ubuntu 20.04 LTS
- Python 3.7.11
- Pytorch 1.10.1
- CUDA 11.1

## Structure

├── Image_to_Points  
│   ├── GLPN_imgtodepth.ipynb  
│   ├── MiDAS_imgtodepth.ipynb  
│   ├── bin_to_pcd.ipynb  
│   ├── data # 예제 데이터  
│   │   ├── 000002.bin  
│   │   ├── 000002.png  
│   │   ├── 000002.txt  
│   │   ├── 000002_lidar.pcd  
│   │   └── 000002_lidar.ply  
│   ├── depth_code.bin  # 결과물들  
│   ├── depth_code.jpg  
│   ├── depth_code.pcd  
│   ├── depth_code.ply  
│   └── depth_to_point.ipynb  
└── README.md  
-  파일 불러오는 경로 수정 필요

## Step

1. GLPN_imgtodepth
2. depth_to_point
3. bin_to_pcd
