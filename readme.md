# First

Ok you have a video, you just need to use

colmap2nerf.py for creating a dataset from a video
You can do something like 
python3 colmap2nerf.py --video_in=input.mp4 --video_fps=2 --run_colmap --aabb_scale=4

# Second step

Use brush to load the dataset, create a nice .ply model

# Final step

convert.py to convert a model from .ply to .splat (smaller binary size)