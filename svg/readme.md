1. Download the sample skeleton SVG here.

2. Make a copy of the skeleton file and open it in your vector graphics editor of choice. 
   There will be 2 groups of objects: ' skeleton' and 'illustration'.
   
    * 'Skeleton' group note:
       a. Do not add, remove or rename the joints (circles) in this group. Pose Animator relies on these named paths to read the skeleton’s initial position. Missing joints will cause errors.
       b. However you can move the joints around to embed them into your illustration. See step 4.
       
    * ‘Illustration’ (this is the group where you can put all the paths for your illustration) group note: 
    
       c. Flatten all subgroups so that ‘illustration’ only contains path elements.
       
       d. Composite paths are not supported at the moment.
       
       e. The working file structure should look like this:
       
    |---- skeleton
    
    |---- illustration
    
          |---- path 1
          
          |---- path 2
          
          |---- path 3

            
3. Embed the sample skeleton in the ‘skeleton’ group into your illustration by moving the joints around.

4. Export the file as an SVG file.

5. Open Pose Animator camera demo. Once everything loads, drop your SVG file into the browser tab. You should be able to see it come to life :D

