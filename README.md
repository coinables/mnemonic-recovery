# mnemonic-recovery
 slow tool to brute force one missing word from a 12 word mnemonic phrase

Leave the word cell empty for the missing word you want to solve for. Considering this is client-side javascript, solving for one word (2048 combinations) is the maximum words you can solve for. This tool is slow and solves in alphabetical order, so if your missing word starts with the letter "a" it will not take as long to solve. Open your browser developer console to watch it work.

Provide a known address in the HD Key chain in "target address", and the depth to scan the keychain of each guess. A larger depth will take longer to find. For the fastest results use a depth of 1 and the first address in the key chain as the "target address".

Works with BIP44, BIP49 and BIP84 HD derivations.

![alt text](https://github.com/coinables/mnemonic-recovery/blob/master/1.png?raw=true)

![alt text](https://github.com/coinables/mnemonic-recovery/blob/master/2.png?raw=true)

![alt text](https://github.com/coinables/mnemonic-recovery/blob/master/3.png?raw=true)

![alt text](https://github.com/coinables/mnemonic-recovery/blob/master/4.png?raw=true)