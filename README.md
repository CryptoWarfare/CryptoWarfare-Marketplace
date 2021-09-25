# CryptoWarfare-Marketplace
Cloned an NFT market website. View original website [here](https://opensea.io/).



* requires apache, API non-functional WIP**
```git clone https://github.com/c4pt000/OpenSea-Clone
tar -xvf html.tar.gz -> /var/www/html/
firefox 127.0.0.1
```


* docker-deployable
```
wget https://raw.githubusercontent.com/c4pt000/OpenSea-Clone/main/docker-deploy-opensea-clone-testing
chmod +x docker-deploy-opensea-clone-testing
cat docker-deploy-opensea-clone-testing
./docker-deploy-opensea-clone-testing
---> docker exec -it <docker_hash> bash
requires 'service apache2 start' 

```
