# cghuisunshine.github.io

ECDH-AES Crypto
https://cghuisunshine.github.io/ecdh.html

Funciton 1: Leave a secret message
   Step 1: Share you secret link
        Open the link https://cghuisunshine.github.io/ecdh.html, click importMyKey if you already save it before, otherwise click exportMyKey to save it. 
      Then click shareSecretChannel and paste it in WeChat, SMS or Email to your friends. 
   Step 2: Send secret message 
        Your friends open the secret link you sent to him, input words, click encrypt, click copyWithMyPubKey, and paste it in WeChat, SMS or Email to you.
   Step 3: You parse secret message
        Open the link of secret message, click importMyKey and import your key file(myKeys.json that you use exportMyKey saved before).
        Click decrypt to parse the secret message
         
Funciton 2: Chat to someone with your saved key
    Similar to Leave a secret message, 



Function 3: Chat to someone with temporary key
    Pros: key changed per session. Every time you open the link https://cghuisunshine.github.io/ecdh.html, a new key pairs would automatically generate, 
    
    Cons:
