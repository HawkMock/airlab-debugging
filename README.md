# airlab-debugging
Just for me to move text across

dustinmo@airstation-01:~/AirStack$ docker login airlab-storage.andrew.cmu.edu:5001
Username: dustinmo
Password: 
time="2025-06-04T16:29:00-04:00" level=info msg="Error logging in to endpoint, trying next endpoint" endpoint="{false https://airlab-storage.andrew.cmu.edu:5001 false false false 0xc00020b2c0}" error="login attempt to https://airlab-storage.andrew.cmu.edu:5001/v2/ failed with status: 401 Unauthorized"
login attempt to https://airlab-storage.andrew.cmu.edu:5001/v2/ failed with status: 401 Unauthorized
dustinmo@airstation-01:~/AirStack$ docker login airlab-storage.andrew.cmu.edu:5001
Username: dustinmo
Password: 
time="2025-06-04T16:29:23-04:00" level=info msg="Error logging in to endpoint, trying next endpoint" endpoint="{false https://airlab-storage.andrew.cmu.edu:5001 false false false 0xc0000145a0}" error="login attempt to https://airlab-storage.andrew.cmu.edu:5001/v2/ failed with status: 401 Unauthorized"
login attempt to https://airlab-storage.andrew.cmu.edu:5001/v2/ failed with status: 401 Unauthorized
dustinmo@airstation-01:~/AirStack$ docker login airlab-storage.andrew.cmu.edu:5001
Username: dustinmo	
Password: 
time="2025-06-04T16:32:54-04:00" level=info msg="Error logging in to endpoint, trying next endpoint" endpoint="{false https://airlab-storage.andrew.cmu.edu:5001 false false false 0xc00018b0e0}" error="login attempt to https://airlab-storage.andrew.cmu.edu:5001/v2/ failed with status: 401 Unauthorized"
login attempt to https://airlab-storage.andrew.cmu.edu:5001/v2/ failed with status: 401 Unauthorized


![image](https://github.com/user-attachments/assets/51dfffca-de92-488b-983a-4c0df2d521e3)


dustinmo@airstation-01:~/AirStack$ docker compose pull
env file /home/dustinmo/AirStack/simulation/isaac-sim/docker/omni_pass.env not found: stat /home/dustinmo/AirStack/simulation/isaac-sim/docker/omni_pass.env: no such file or directory

dustinmo@airstation-01:~/AirStack$ docker compose pull
unable to get image 'airlab-storage.andrew.cmu.edu:5001/shared/airstack:v0.14.0_isaac-sim': permission denied while trying to connect to the Docker daemon socket at unix:///var/run/docker.sock: Get "http://%2Fvar%2Frun%2Fdocker.sock/v1.46/images/airlab-storage.andrew.cmu.edu:5001/shared/airstack:v0.14.0_isaac-sim/json": dial unix /var/run/docker.sock: connect: permission denied
