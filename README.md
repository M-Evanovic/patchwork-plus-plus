# patchwork++
Seperate ground points and non-ground points

## Usage
```
// Main Function
// void EstimateGround(pcl::PointCloud<PointT> cloud_in,
                       pcl::PointCloud<PointT> &cloud_ground,
                       pcl::PointCloud<PointT> &cloud_nonground);

// Usage
std::shared_ptr<gs::GroundSeperator<PointType>> ground_seperator = nullptr;
ground_seperator = std::make_shared<gs::GroundSeperator<PointType>>();
ground_seperator->EstimateGround(src_pc, ground_pc, non_ground_pc);
```

## Reference
patchwork-plus-plus  
[code]([https://github.com/gisbi-kim/removert.git](https://github.com/url-kaist/patchwork-plusplus))  
[paper]([https://arxiv.org/abs/2207.11919](https://arxiv.org/abs/2207.11919))
