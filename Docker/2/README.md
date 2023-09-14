docker build ./ --tag stocks_products:0.0.1

docker run --name my_stocks_products -d -p 8000:8000 stocks_products:0.0.1
