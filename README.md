# patchwork++
Seperate ground points and non-ground points

## Usage
```
// void EstimateGround(pcl::PointCloud<PointT> cloud_in, pcl::PointCloud<PointT> &cloud_ground, pcl::PointCloud<PointT> &cloud_nonground);
std::shared_ptr<GroundSeperator<PointType>> ground_seperator = nullptr;
ground_seperator->EstimateGround(src_pc, ground_pc, non_ground_pc);
```

## Reference
[code](https://github.com/gisbi-kim/removert.git)  
[paper](https://arxiv.org/abs/2207.11919)
