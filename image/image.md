1. Get image id from the image tag

   docker images -q <imagetag>
   02597a4990e8
   
2. How to untag image

   docker tag 0e5574283393 my-imaj
   docker tag 0e5574283393 my-image
   
   docker rmi my-imaj   # will remove that tag and leave the image present with the other correct tag