# FrijArt

## Time lock encryption

Inside the folder timevault/. Node js application with UI showing the time locked encryption. The UI has a form with a birthday input, to showcase how our marketplace will keep the identity hidden given the age information. The countdown starts from the creation until the person's 18th birthday. The information regarding the identity can only be decrypted after the 18th birthday. Our database as well will not have the identity until then, and so it is purely anonymous till then.

## Smart Contract

Inside the folder nft_marketplace/. Smart contract code written in solidity. The contract has been compiled on Remix IDE and tested on a development blockchain environment. The biggest change made from the original contract code from OpenZepplin (https://www.openzeppelin.com/contracts) is the hash key added to the token creation stage. This hash key will be created from the text description, like a MD5 key (https://www.md5hashgenerator.com/), and this hash will be included in our token. This keeps a record of the item that was traded, and hence reduces the chance of duplicates/fraud.
