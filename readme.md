# Blockchain Lab Setup

## Wallet

[Metamask](https://metamask.io/download/) für Browser installieren.  [Installationsanleitung](https://www.youtube.com/watch?v=MKIjb504qT8). 
Achtung: Geheimer Schlüssel muss nicht erstellt werden (Video von 2:40 - 4:20) kann übersprungen werden.

- [Chrome](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn)
- [Firefox](https://addons.mozilla.org/en-US/firefox/addon/ether-metamask/)
- [Edge](https://microsoftedge.microsoft.com/addons/detail/metamask/ejbalbakoplchlghecdalmeeeajnimhm?hl=en-US)

Dieser Schritt ist erfüllt, wenn ihr folgendes Bild beim öffnen von Metamask seht:

## Test Account Erstellen

 1. Metamask Add-In im Browser öffnen und auf Profilbild klicken 
 ![Accoun](https://github.com/WebThor/BlockchainLab/blob/main/images/Account1.png)
 2. Auf Account importieren klicken 
 ![Account2](https://github.com/WebThor/BlockchainLab/blob/main/images/Account2.png)
 3. Privaten Schlüssel aus Liste (unten) auswählen und importieren 
 ![Account3](https://github.com/WebThor/BlockchainLab/blob/main/images/Account3.png)
 4. Die Nummer unter eurem Account sollte nun gleich der Accountnummer eures privaten Schlüssel sein. Habt ihr zum Beispiel den ersten privaten Schlüssel (0x4f4b89dad...) gewählt, dann sollte unter Account die Zahl 0x30C8F9F4a... stehen. 
 ![Account 4](https://github.com/WebThor/BlockchainLab/blob/main/images/Account4.png)

Ihr habt euch erfolgreich einen Account auf dem Testnetz erstellt.

## Mit dem Testnetnetzwerk verbinden

 1. Metamask Add-In im Browser öffnen und auf Ethereum Hauptnetz klicken 
 ![Metamask](https://github.com/WebThor/BlockchainLab/blob/main/images/Metamask.png)
 2. Auf "Netzwerk hinzufügen" klicken 
 ![Schritt1](https://github.com/WebThor/BlockchainLab/blob/main/images/Schritt1.png)
 3. "Ein Netzwerk manuell hinzufügen" wählen 
 ![Schritt2](https://github.com/WebThor/BlockchainLab/blob/main/images/Schritt%202.png)
 4. Netzerk manuell hinzufügen.
	 - Netzwerkname: TestNetzwerkDHBW
	 - Neue RPC-URL: Siehe Tafel
	 - Ketten-ID: 4242
	 - Währungssymbol: ETH
Mit "Speichern" bestätigen
 5. Ihr solltet nun mit dem Tesnetz verbunden sein und ~100 ETH zur Verfügung haben

## Online Solidity IDE

 1. Sobald Matamask erfolgreich installiert wurde, geht auf die [Solidity IDE](http://remix.ethereum.org) website.
 2. Geht auf das unterste Icon.
 ![Inject1](https://github.com/WebThor/BlockchainLab/blob/main/images/Inject1.png)
 3. Wählt Injected Provider - MetaMask aus.
 ![Inject2](https://github.com/WebThor/BlockchainLab/blob/main/images/Inject2.png)
 4. Es sollte sich nun Metamask öffnen und nach einem Account fragen. Wählt dort den Test Account aus. 
 ![Inject21](https://github.com/WebThor/BlockchainLab/blob/main/images/Inject21.png)
 5. Bestätigt den Account mit Verbinden.
 ![Verbinden](https://github.com/WebThor/BlockchainLab/blob/main/images/Inject32.png)
6. Unter Account sollte nun euer Account auftauchen.

## Smart Contract Laden



 1. Gebt unter "At Address" folgende Blockhain Addresse ein: `0xB50D8C4d722073eD6F2FDe6A063dA7aa6516501e`





## Accounts

### Accounts Nummer
(0) 0x30C8F9F4a5bDaE41b83995F697C1837669b9702F (100 ETH)
(1) 0x21cD1c342B598505629cE5eb7cEdc3721CDB391F (100 ETH)
(2) 0xFc582936e97f183a7277843Dd8E686C4603Cf190 (100 ETH)
(3) 0x25e750022B5B9F1b9751cfD9ed70427B26222235 (100 ETH)
(4) 0x7af34321822aE799B0276bC8B45A3a7EB878FDA8 (100 ETH)
(5) 0x6fdbFcDEa67F0de5FeF1dF12A1905C840F6a232f (100 ETH)
(6) 0x5CFC504cb9ea174247dDB4A9bb15809A06e92EEf (100 ETH)
(7) 0x52056bBab2f371CCf2ef98604a7714fB20193B1d (100 ETH)
(8) 0x10e1683D787B9c1B8C0eF5EA2Cd1a3Ef59b8E37A (100 ETH)
(9) 0x7Ce730718263b3dE9536a798E3D04F10a4d276c8 (100 ETH)
(10) 0xF839D5075bA2d310b47CcEF2b0e84935243F18A0 (100 ETH)
(11) 0x68eb9044e06C865997F26D31f9E31f6718E09b4C (100 ETH)
(12) 0x68b6a2c58cfC38bfDb123495Ce1CA6f59B20F7b4 (100 ETH)
(13) 0x52736aF5F97ac7D7b107B53D5aA602C1A835255E (100 ETH)
(14) 0x7607C5190646b941a22630105e8DC232705eF828 (100 ETH)
(15) 0xb76bdDa6F0F02C5EaE430Be9643d9e2FCFB2C418 (100 ETH)
(16) 0x54638D88548216D6C9CD1E471297538813E725d0 (100 ETH)
(17) 0xBbB7acC67ef97216d3902411B95e7D6E47Cf2A98 (100 ETH)
(18) 0xde652A3536cd9D1F16C8B6cD433f9Bbc3d51Cc11 (100 ETH)
(19) 0x15FDe4F9cdeA0Ba2FF4e83F8FF4656A1F8288Edb (100 ETH)
(20) 0xc53486773C030dbF9b5B7B5c908ca7D78Cc5313c (100 ETH)
(21) 0x08E5816674387b6E16373842EBd2A36256aeb6c0 (100 ETH)
(22) 0x4524efeE1441742C3fC4DbF719Cd0F5269C6D238 (100 ETH)
(23) 0x14070032EC3Dac30F8A7562433E7d9191473dDaD (100 ETH)
(24) 0x20d748C29FFFE7A9ca1f91F671fb733631C53DeF (100 ETH)
(25) 0x5E7786DcD254520f8dcEf2E6EB8F5E8fD98b1f1E (100 ETH)
(26) 0x93E817542B0Aa345464cDc062e5527eD7044c966 (100 ETH)
(27) 0xdCBC0b398d8706C9aab4F3E5e1c984E68D0684Cd (100 ETH)
(28) 0x6ACF0f6e9A87e9372Feb4E88D0247E9F7bDde89E (100 ETH)
(29) 0xb41679f3CC1e0D6d4D6397A847085A1Ac808ae89 (100 ETH)
(30) 0x223E83939e5b53eF83720908E478b61b4Ac3a634 (100 ETH)
(31) 0x36517C7a2E1bFc192F594689649bC1383B56a99D (100 ETH)
(32) 0xF011eA67A424Da61e09154e448773Dc4012cb6Df (100 ETH)
(33) 0x12887875973546dB541300099900eACdd0bA606d (100 ETH)
(34) 0x650f7B1fc79443e905A64b235D0Ca556A7A6b620 (100 ETH)
(35) 0xd90257134B88E5B4771217e60b12d81d60F3988e (100 ETH)
(36) 0x0258fd708DBB0C0a8884B36034ff441157f3988e (100 ETH)
(37) 0xCf22EC0629b6F6551c9CeCc92FA889A374fe2249 (100 ETH)
(38) 0x3aB924D9dfb7E090844C8D764A438262DbD3Fd3a (100 ETH)
(39) 0x93FF64339E5C475E071EedA6Dd96383fc1E58f69 (100 ETH)
(40) 0xd229c17723C962AAa292F280d914f2F7A816229C (100 ETH)
(41) 0x77b8540662FB211Ec80186341A411aB311A422f3 (100 ETH)
(42) 0x642A80385C99825977dd1C3a22EF33A57EAc93C8 (100 ETH)
(43) 0x790f10906a29BcfA372914980F00d3FBA7397433 (100 ETH)
(44) 0xb0B97B5DeB4176BD66E0093a62a1Ac7fDe3f4788 (100 ETH)
(45) 0xfa6a789Ec73c249e598b0632168770E81daa4AF7 (100 ETH)
(46) 0xFd85177aD284B001951ce6eE88d3e61c4B71D2fc (100 ETH)
(47) 0xa230F8f6E8b86391A911727348da4fc09d370290 (100 ETH)
(48) 0xAfdA2cdC4564Fd3442765a6bd609b503ce3cd804 (100 ETH)
(49) 0xC8A757e8c92Df4e3961F42014cE5FCA38E583cf9 (100 ETH)

### Private Schlüssel

(0) 0x4f4b89dad9f18e85317b617d871b5c36d7e2ee8813934a01cc8e10e5b1d1af00
(1) 0x4250872a7b4e54337f645f8dc9b5647a18993404d36a310b7ddb7e4212955e23
(2) 0x16487dc8b13ca7bf3dfd546b9d7a0715f6c1de293e299f47f5fef0144bf4b435
(3) 0xe67b192cf5d5ded37d95d66ff95f583617e513fda2b076984ae428ca7cef4ac3
(4) 0x0a3822e4c2c07f5a0477f581b1f069d1000bf16dbd54d41f8f2d183b31c86081
(5) 0x9e83fba355815707667d0151769b4155ffd8364661609141a4c2987eb256dcff
(6) 0xeae10c60ba042608a8ed2d2c2f4aab2392e26bcc76200ff710a4782b4c97bf77
(7) 0xd18cd1c793e4b23487dc83ae03969f43c36671df68a9b8199c7402456a4de11e
(8) 0xf31b9470f4be23fa169131853bed7528aaa1b52077edd263b957369d68e8e1e2
(9) 0x2e173e5a4cfb1fc7a5e6340ebf02038bf90dd22361ec0856c9c47ea95929ab0b
(10) 0x9a98251cfcf17b7172d439cd2e00259c3b3cd334dec65984065b7b12cdf617db
(11) 0x2ec0e8442552cccff4524a4a6a2a328815a14ac04c289eecd3a3432ff53daabd
(12) 0xc3750f4c16b54ad7123a45b8c9cf0b1e3b7cafcf2999173217c0dc2ffe39ea89
(13) 0x1685487e2b9f4efe2287b6e39666dac99760d3f7ac59d0125ca16b152df81167
(14) 0xe2b02ce300f6aa07d133ac9bd95598fcde84a71a37fcd62af69f454b13ceadc1
(15) 0x288834885102b7212529e20be891d4e8da32a2d3643dee66be7ff1603cd2b838
(16) 0xa6f95357455c572bb000321ace8437dc816e068f075e144f08704d16b519ebe9
(17) 0x4eee80ec2f5ecc8d3ee828d7547dae2ab082809b88105e2095e8f687da84c229
(18) 0xa8527803ead1025878f45f7247185ddfb53df5f8783df64381475e4d5e0b0097
(19) 0xb25437af2376b6f95b930e693afc29a6b1939aa834252dd29321f8210196d1ed
(20) 0x2f81ec32d95eeff68ef2215df0cf129fe2cfc1fa05488bf5d795f5b7a827a2a0
(21) 0x3c0c1556cd40f15d7cb115db1dc4bd7fc6c99e8df6a1a5eb40d7b8bf1a5e45da
(22) 0x2fdb1baa08b1ba48428b3f799a8d2bba58df96014c9ef11194987baa03da976c
(23) 0x84309c454a10f77bf2cf70b36e5e77b853dcadb2e6aa308e76f3082d67795993
(24) 0x6dba10766ee9c1b22122e0702fbe7b21dcd0bee0aaa0732be13e3ddee78724c4
(25) 0x9ccbe971265ff62f9ba7626cb8dd5defde4cd41f31d5c8df6964e3a0cb0fee2d
(26) 0xce32915a6a7e9a24d9275a9bd6eb3447c245c9197512adaeb99ecd234aa82f44
(27) 0x9ad915264d96cda991a08c9be8922b3be51957baf45ba4eda46c1a762fea6c27
(28) 0xf764562e409485e7891696a3fea6dbe757787cfc8d5a79aea43d02b44c8e7899
(29) 0x8333b3ad7df5fcd784f88da0cbdbe1f1dad8d4d77c4a3ad75801127c5e98bd2b
(30) 0x0c783fb486cfc67c130907c6b832036ad22dab297739edbbf0656e3e30e38d61
(31) 0x7528d20b6eb6cf807bbc719bb86a37829804b845714d119251f58aa0f3bb4d69
(32) 0x3f5a217ca448dbfbf86e6cb052c759158e8ad86c67962aa4f26ec93313e76fe8
(33) 0xbe60ef29855671479cd46f856b69947624d4f8cdf50c852f9712b6dba75c864f
(34) 0xffedaf3ccc65b779f1560a32abdd9181952bd93c63a3a99a60c7dad9b01623d3
(35) 0x7bf5a471d1ebe9fd486e4461165c26d236432d233d294fbc0ce29f8f73523570
(36) 0xfb5b219f8d4dd8de70a8f6422ba1b832c671ce48310c83d5bbaf3cbb9d5a0faa
(37) 0x8450ffadf793499f11cc7122c82c5d34cb422dbc7de71c5468ad0b016f1ea5b9
(38) 0x03e28214b704aa49bdfa9021b000d78d04b301e236ad794ac2eef74cd4eacf5d
(39) 0x2c43ec420e9fdf2a7b4d36988038032ab1fc6dc2ae3a024725b5e2a181b60004
(40) 0xa158dbd8cbc6af152f4f099488de8b8d927884d460b4417fb54f1eeec2fabc6a
(41) 0x6a39f9afcef35a025b1591badfb11bf2df2c84f15b75eb72ab16f5ab204d69d5
(42) 0x8fbdf765a4a4c7ce6d37d3f787aa913458dfca5522ab5d4b6766f068033fc068
(43) 0x8be749b68079ae735e34660a9a6d2b430d2d64a42679ad4b5278e5d61b8a5ce3
(44) 0x05cf1e4b4a7657b043fa465b3beba23b9d530bdc0376206a404ac224f91dec3f
(45) 0x2e97caafcf0e6e86c2988445ce7ae972dd992a087d2564de0278f8173a2b50dd
(46) 0x6465bf3dd12bdc7ad8de618906fd38282c82ea94881d4d8e7dd93c838775a4a6
(47) 0x8af23f8cc7e08129fd1deaaeb93b2c16ad7f5c784cda3a31de96eb9624c33116
(48) 0x9899d371250f1c029df40b9ec0e5e2f3d8da9ebe92ecc905e15228d5d6ab8c68
(49) 0x0cdb5a9b311536eaffdcb58ce9fdcde6a680edf825024fc62359c1e7582e106c
