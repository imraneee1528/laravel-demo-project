# laravel-demo-project

cd ~

git clone https://github.com/imraneee1528/laravel-demo-project.git

# For App1 need to go there
 
cd laravel-demo-project/app1/src

docker-compose -p app1 -f docker-compose-app1.yml up -d

# For App2  need to go there

cd ~

laravel-demo-project/app2/src

docker-compose -p app2 -f docker-compose-app2.yml up -d
