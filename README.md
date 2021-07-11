## check-duplicate-image

1. To execute the code, run the following command: 
  ```bash
  python3 check-duplicate-image.py --path {PATH}
  ```

2. Replace `{PATH}` with the images directory e.g.  
  ```bash
  python3 check-duplicate-image.py --path images
  ```

3. Then, a csv file is generated with the similarity percentage of images in the directory<br />

*This source code is referring the [answer from stackoverflow](https://stackoverflow.com/questions/62766942/is-there-a-way-to-run-opencvs-sift-faster). However, I have changed the code with ORB and Brute Force instead of SIFT and Flann in order to reduce the execution time. 