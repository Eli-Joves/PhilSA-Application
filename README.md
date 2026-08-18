# 15 August 2026
- First Commit
- Downloaded data

# 16 August 2026
- Re-mapped data, checked for invalids
- Coding UNet architecture
- Trained and validated model for a few epochs
- Tested model - Unfortunately, I ran the re-mapping code block multiple times, essentially removing all cloud shadows
- Fixed it by recopying and remaking the remapped files
- Leaving the code overnight to work for 45 epochs

# 17 August 2026
- In the interest of time, I only ran 40 epochs for 1300~ mins of run time
- Additionally, instead of going from 4 to 1024 channels leading to the bottleneck stage, I modified it to end at 512 instead.
- Uploading to save the status of my model training
- Successfully trained the model, validated, and chosen which iteration of the model to use for testing
- Tested the model, computed for metrics
- Plotted the 2-band output

# 18 August 2026
- Finished notebook notes and notations
- Added visualizations of the metrics (bar plots and heatmaps)
- Oversight, Band 2 in output is 0-1. Guide says values must range from 0-100.
- Proofreading markdowns.