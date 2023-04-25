# twitter-etl-hands_on
This is my hands-on apache-airflow project that I learn from a youtube tutorial (https://www.youtube.com/watch?v=q8q3OFFfY6c) on Darshil Parmar channel. The project is about using API to get user data from Twitter and manage the pipeline by using airflow. Then save the data into AWS s3. I practice by following the tutorial and trying many 
bug fix and this is the summary. 
The overall step is 
1. Create an EC2 instance on AWS and launch
2. Remote ssh into the EC2 machine (don't forget to edit the security inbound rule)
3. install python, apache-airflow, and the required package
4. launch the airflow server (running airlow standalone)
5. In airflow.cfg, change dags_folder into the project directory name
6. relaunch the server
  After finish launching airflow server, in the airflow web UI you will see the DAG that you created with python. 
  
