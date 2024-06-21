# sboot_docker_admin

sudo docker build -t shop_api_admin .

sudo docker run -p 8080:8080 --name shop_api_admin --rm -v $(pwd)/results_admin:/tool/results shop_api_admin

