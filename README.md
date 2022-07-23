# [AES Crypto](https://cghuisunshine.github.io/aes.html) 


**Use Cases 1: Fixed key encryption/decryption**

Step 1: Encrypt 
   
Open the link [AES Crypto](https://cghuisunshine.github.io/aes.html)

        Input words, click Encrypt, click CopyWithLink and paste it in WeCat, SMS, 
        
        or Email to someone. 
        
        Note: 1. If you click AutoDecrypt:off->on to change the auto decrpt switch on, the CopyWithLink would bring that switch, and the receiver would
        
               get plain text automatically when open the link without the need of click on decrypt.
              
              2. If you click CopyOnly -> CopyAndShare to change CopyAndShare switch on, the CopyWithLink would pop up Share menu, and you can share it.
              
              3. CopyWithLink only suitable for short words, for long words you should use Copy button.
        
   Step 2: Decrpt
        
        Open the link with encrypted message, click Decrypt.
        
   **Pros:**
   
       Easy for use.
   
   **Cons:**
   
       Not for serious securtiy usage, because everyone could use it to decrypt secret messages
       
 **Use Cases 2: Private shared key encryption/decryption**
 
   Step 1: Create and share shared key
   
   Open the link [AES Crypto](https://cghuisunshine.github.io/aes.html)
 
      Click ShowKeys, click generateKey, click copyKey, paste it somewhere for later usage and send it to someone secretly wiht who you want to talk with.
 
   Step 2: Encrypt 
   
   Open the link [AES Crypto](https://cghuisunshine.github.io/aes.html)
   
        Click showKeys, paste your saved shared key, input words, click Encrypt, click 
        
        Copy and paste it in WeCat, SMS, or Email to someone. 
        
   Step 3: Decrpt
   
   Open the link [AES Crypto](https://cghuisunshine.github.io/aes.html)
        
        Click showKeys, paste your saved shared key, paste encrypted message to input box, 
        
        click Decrpt. 
        
   **Pros:**
    
       Suitable for securtiy usage.
    
   **Cons:**
    
       1. Need to share shared key with secure channel first.
       
       2. Not easy for use.
        
    
        
        
        
        


# [ECDH-AES Crypto](https://cghuisunshine.github.io/ecdh.html)


**Use Cases 1: Leave a secret message**

   Step 1: Share your secret link
   
   Open the link [ECDH-AES Crypto](https://cghuisunshine.github.io/ecdh.html) 
   
        Click importMyKey if you already save it before, otherwise click exportMyKey to save it.
        
        Then click shareSecretChannel and paste it in WeChat, SMS or Email to someone. 
      
   Step 2: Send secret message 
   
        Someone open the secret link you sent to him, input words, click encrypt, click copyWithMyPubKey, and paste it in WeChat, SMS or Email to you.
        
   Step 3: You parse secret message
   
        Open the link of secret message received, click importMyKey to import your key file(myKeys.json that you use exportMyKey saved before).
        
        Click decrypt to parse the secret message.
         
**Use Cases 2: Chat to someone with your saved key**

    Similar to Leave a secret message, everyone use their saved key every time to chat with someone else: When you received the encrypted message that 
    
     encrypted with your public key, click the link that contains the encrypted message, click importMyKey to import your key file(myKeys.json that you 
     
     use exportMyKey saved before), click decrypt to parse the secret message.  



**Use Cases 3: Chat to someone with temporary key**

   Step 1: Share your temporary secret link
   
   Open the link [ECDH-AES Crypto](https://cghuisunshine.github.io/ecdh.html)
   
        Click shareSecretChannel and paste it in WeChat, SMS or Email to someone. 
        
   Step 2: Send secret message 
   
        Someone open the secret link you sent to him, input words, click encrypt, click copyWithMyPubKey, and paste it in WeChat, SMS or Email to you.
        
   Step 3: You parse secret message
   
        Open the link of secret message you received, click decrypt to parse the secret message.
        
   Step 4: each party(you or someone) repeat Step 3 to continue the chat.
   
   
   **Pros:**
   
      1. Forget previous chat automatically
      
         Use temporary key and every time you open the link(https://cghuisunshine.github.io/ecdh.html), a new temporary key pair would generate and 
         
         replace the old temporary one, which means you would forget what you have said before.
       
      2. Easy of use
      
         You don't have to exportMyKey or importMyKey, just shareSecretChannel and send it to someone to start a chat.
         
         After that, each party would input words, click encrypt, click copyWithMyPubKey and send it to counterpart.
         
   **Cons:**
    
       1. You can chat with one person only at the same time.
       
       2. You must stick to one browser only during the chat, because the browser need to find keys to fill automatically.
       
