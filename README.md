# DataXchain
DataXchain is a website that allows users to sell their datasets to the potential buyers. It was coded in HTML and Node.js. While creating the website we used WordPress.com to create a template for our website and then we uploaded the HTML files which we got from WordPress.com to Cloud9 Amazon Web Service. In Cloud9 we used many differen libraries such as bitcoinjs. In addition to those librarires, we used different API's which are mongodb and REST API to make theis website functional. We used mongodb to keep the user names and passwords because there is no option to keep the datas of the users in REST API. In the website, a user can be both seller and buyer. Sellers can add informations about their datasets for example: what is that dataset about, dimension of the dataset, price of the dataset. When a buyer search the name of the dataset, he/she can see informations about that particular dataset. If a buyer wants to buy thay dataset, we ask the buyer to their bitcoin wallet address. If their wallet address is valid (we used bitcoin libraries to check the validity of wallets)       , website makes the transaction between the wallet of the buyer and the wallet of the seller. If the transaction is succesful, website sends the Google Drive link of that particular dataset to the buyer's e-mail address.   
