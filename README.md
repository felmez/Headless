# Headless

# Prerequisites and system requirements.
    -   Latest version of Docker.
    -   Node.js, version > 8.0.0, and yarn.
    -   imagemagick library.
    -   Elasticsearch and Redis server.
# Installation
    -   git clone https://github.com/felmez/Headless.git foldername
    -   cd foldername
    -   yarn install
    -   cd mage2vs/src 
    -   npm install
    -   edit src/config.js file in your mage2vs directory and provide magento_url, consumerKey, consumerSecret, accessToken, accessTokenSecret key.
# To import all the Products, Categories and other important stuff to your Elastic Search instance
	-   node cli.js taxrule
	-   node cli.js attributes
	-   node cli.js categories
	-   node cli.js productcategories
	-   node cli.js products