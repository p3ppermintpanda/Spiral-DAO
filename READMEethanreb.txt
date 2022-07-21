
---------------------------
Spiral DAO Proof of Concept
---------------------------

Setup:
 - Install Node.JS@v16.15.1
 - Install yarn@1.22.19
 - Install dependancies
    - Open Powershell Terminal

    ```

    yarn

    ```

 - Rename '.env.example' file to '.env' and fill in information

 - Install hardhat@2.10.1 ``` yarn add --dev hardhat ```




---------------------------------
*** To test DAO functionality ***
---------------------------------

Open a Terminal:

```

yarn hardhat test


```


-----------------------------
*** To deploy DAO Locally ***
-----------------------------


 Open a Terimanl:

 ```

 yarn hardhat Node
 

 ``` (starts a local blockchain [keep open!!])


 In second Terminal:


 ```

 yarn hardhat run scripts/deploy.ts --network localhost

 ``` (deploys smart contract)



--------------------------------------
*** To deploy to a rinkeby testnet ***
--------------------------------------


Open a Terminal:

```

yarn hardhat run scripts/deploy.ts --network rinkeby

``` (deploys smart contracts to rinkeby chain)


In second Terminal:

```

yarn hardhat run scripts/selection.js

``` (runs user interface)
