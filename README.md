# sboot_docker_admin

docker build -t shop_api_admin .

docker run --name shop_api_admin --rm -v $(pwd)/results_admin:/tool/results shop_api_admin

