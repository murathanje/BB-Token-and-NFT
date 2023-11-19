
#  Storing Our Certificates as NFTs

  

###  While enjoying spending our BB tokens, it's time to store our certificate as a Non-Fungible Token (NFT) on the blockchain. ✒️

  

* First, let's open a new terminal through Cloud IT.

  

* Clone our repository on GitHub:

  ```git clone https://github.com/murathanje/bb_NFT.git```

  

Pull our project into our working environment with the command above.

  

* Then, navigate to our project folder with the command:

  ```cd bb_NFT/```

  
  

* After that, install the necessary libraries with the command:

  ``` npm i nft.storage mime fs path node-fetch```

  
  

**name:** name of the certificate

**description:** description of the certificate

  

* After the process, you will receive an output like:

  ```https://bafybeietzr7c43wx7vqxqmvzp3pcyd7pgaiymrsrjmvuduykl4pknevdia.ipfs.dweb.link/go.png```

  
  

Copy this output.

  

* Then, paste this code into the **image** part of the `file.json` file inside the **bb_NFT** folder.

  

Fill in the other **name** and **description** fields in **file.json** according to our certificate.

  

* Then return to the terminal screen and run the command:

  ``` node upload.mjs file.json "<name>" "<description>```

  
  

Paste the output into the **certificate** button at the bottom of the homepage of our application.

  

* Paste the copied output into the input field on the page, press the button, and approve it via **Metamask**.

* When the approval message arrives, copy our Metamask address and search for our wallet address on [Opensea](https://testnets.opensea.io/) to view our certificate.

  

###  Now, our certificate will be stored as an NFT on the blockchain.

  

##  That's it! 🎉🥳