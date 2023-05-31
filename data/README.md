# Data access

The data used in this project consisted in:

1.	Audio recordings using [AudioMoths](https://www.openacousticdevices.info/audiomoth) sensors in four habitats:
	-	Agricultural field
	-	Riverside
	-	Forest ending
	-	Residential area

![AudioMoths sites. From left to right: Agricultural plot, riverside, forest ending and residential area.](https://github.com/LRiveroIribarne/IDV_RSGIC_BBOXGroup1/blob/4369dc72e79f4c7eac8cb44442f43e0fddd62c80/imgs/audiomoths_sites.png)
	
2.	Three Terrestrial Laser Scanning ([TLS](https://www.wur.nl/en/research-results/chair-groups/environmental-sciences/laboratory-of-geo-information-science-and-remote-sensing/research/sensing-measuring/terrestrial-laser-scanning-research.htm)) LiDAR point clouds in three forest conditions:
	-	Forest entrance
	-	Mature forest
	-	Forest ending

![Mature forest LiDAR point clouds examples.](https://github.com/LRiveroIribarne/IDV_RSGIC_BBOXGroup1/blob/877525c9575d31ac824eaf4f3b9f38b13ee87f3b/imgs/example_point_cloud.png)

3. Spatial data related to:

	-	AudioMoths coordinates
	-	LiDAR scaners sites
	-	Point of interest
	-	
![Sites map.](https://github.com/LRiveroIribarne/IDV_RSGIC_BBOXGroup1/blob/19ea7b354e19487c91ab2925ec59605304a8512a/imgs/sites_map.png)

Since the audio and LiDAR datasets are to heavy to be uploaded to the repository they can be downloaded from the following links:

1. [AudioMoths data](https://filesender.surf.nl/?s=download&token=60f94db8-51c9-4e57-bc8d-d11d29f8c507)
2. [LiDAR point clouds data](https://filesender.surf.nl/?s=download&token=4cdf413d-af36-4fcd-8eab-d3ca4acb10d7)

The download links are available until 20-07-2023. After that you could write us (lucas.riveroiribarne@wur.nl) to ask for the data :)

After downloading the data the folder structure will be the following:

####  AudioMoths recordings
```
├── audio
    ├── 1 [Forest entrance. Discarded due an error in the deployment]
     ├── empty 
    ├── 2 [Agricultural plot]
     ├── 20230524_090000.WAV
     ├── ...
    ├── 3 [Riverside]
     ├── 20230524_090000.WAV
     ├── ...
    ├── 4 [Forest ending]
     ├── 20230524_090000.WAV
     ├── ...
    ├── 5 [Residential area]
     ├── 20230524_090000.WAV
     ├── ...          
```
####  LiDAR Point clouds
```
├── pointclouds
    ├── location1.laz [Mature forest]
    ├── location2.laz [Forest entrance]
    ├── location3.laz [Forest ending]      
```
