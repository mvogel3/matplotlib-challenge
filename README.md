# matplotlib-challenge
Berkeley Data Bootcamp module 5 challenge

After accounting for and removing any mice with duplicate timestamps from the dataset, the total number of mice in this analysis was reduced by 1 leaving 248 unique mice remaining in the study. The distribution of male to female mice was very close with 49% female and 51% male.

Summary statistics for tumor volumes by drug regimine showed that mice treated with Ramicane had the lowest tumor volume on average at 40.2 mm3. Capomulin was a close second at 40.6 mm3. 

After grabbing the maximum timepoint for each mouse in the study and creating a box and whisker plot showing the final tumor volumes at the end of each drug regimen. This chart showed mice treated with Capomulin and Ramicane had the lowest tumor volumes at the end of their treatment. However, when the total tumor volume for a single mouse treated with capomulin was tracked from the beginning of the study to the end, that mouse showed a decline in volume from day 25 to day 30 and then an increase from day 35 to day 45 despite remaining on the same treatment regimen.

Looking to other contributing factors, when a linear regression was run on the weight of a mouse and its tumor volume, a positive correlation was shown. This correlation had an r^2 value of .7 indicating that the correlation was moderately strong and one could reasonably conclude that a mouse's weight has a slight impact on its tumor volume.