# HOW TO INSTALL (Windows)

1. install docker desktop  (or docker engine)  
2. git clone https://github.com/altarizer/semantic-segmentation-editor
3. $ cd semantic-segmentation-editor
4. $ mkdir images 
5. open git-bash 
`bash 
git-bash\>  METEOR_SETTINGS=$(cat ./settings.json) SSE_IMAGES=./images docker-compose -f sse-docker-stack.yml up
`
6. naviate to http://localhost 
7. upload pcd files in ./images
