1. **LEO-RUST**
2.  The bootcamp was craeted on Coin Ex and Aleo to introduce developer to Leo Programming Language which is built on Rust.
   
3.  **WORKSHOP 1**
4.  The following processes were followed:

**PROCESS**
1.  Install rust on your user computer. This is after Microsoft Visual Studio code has been downloaded.
2.  next, clone the leo repo from their official  github page. git clone https//github.com/AleoHQ/leo
3.  Leo wallet extension was also installed.
4.  Leo wallet discord channel joined and token acquired.
5.  Next cd leo
6.  cargo install --path . to install the dependencies.
7.  leo new Lizzyexample. note: The name of your project must be in lowercase and can be any random name.
8.  cd todolist
9.  Next, change the PRIVATE_KEY in your .emv file to your PRIVATE_KEY. PRIVATE_KEY is available on the wallet.
10.  leo run
11.  leo deploy
12.  **Transaction ID **- at17h5p2697qwdvmdg7hj0xqq5u0fu79pqtts2ry7eqw6g7ssh0hs8q8rvqax


**WORKSHOP 2**
1. **PROCESS**
2. This workshop served to introduce the transfer process on leo.
3. create a new project in examples leo new newproject. NOTE also: the name of your project must be in lowercase and can be any random name.
4. Next process is to input the fpllowing commands:
5. cd newproject
6. Change the  PRIVATE_KEY in your .emv file to as in workshop 1 to yours.
7. leo run mint yourwalletaddress 1000u64 --network testnet.
8. leo deploy
9. **Transaction ID **- at1ryp4mexwcrze2y8s403urcegrsaskmjlpk94ut72s4k9wjl5ayrqxz3lga

**WORKSHOP 3**
**PROCESS**
1.  The final project was to demonstrate how an actual transfer works across sender and receiver wallets.
2.  Create a new project in examples leo new newproject. Note also the name of your project must be in lowercase and can be any random name.
3.  cd newproject
4.  Change the  PRIVATE_KEY in your .emv file to yours.
5.  leo run combine_hash_owner_receiver yourwalletaddress receiverwalletaddress
6.  leo run
7.  leo deploy
8.  **Transaction ID** - at1r09xp4p7zqjqrsau9k559qvwwh8kaagxfu0zeafsd9wzj7x8zgqqewtdp9
