# ECDH-AES Crypto 


**Funciton 1: Leave a secret message**

   Step 1: Share your secret link
   
        Open the link https://cghuisunshine.github.io/ecdh.html, click importMyKey if you already save it before, otherwise click exportMyKey to save it.
        
      Then click shareSecretChannel and paste it in WeChat, SMS or Email to someone. 
      
   Step 2: Send secret message 
   
        Someone open the secret link you sent to him, input words, click encrypt, click copyWithMyPubKey, and paste it in WeChat, SMS or Email to you.
        
   Step 3: You parse secret message
   
        Open the link of secret message, click importMyKey to import your key file(myKeys.json that you use exportMyKey saved before).
        
        Click decrypt to parse the secret message.
         
**Funciton 2: Chat to someone with your saved key**

    Similar to Leave a secret message, everyone use their saved key every time to chat with someone else: When you received the encrypted message that 
    
     encrypted with your public key, click the link that contains the encrypted message, click importMyKey to import your key file(myKeys.json that you 
     
     use exportMyKey saved before), click decrypt to parse the secret message.  



**Function 3: Chat to someone with temporary key**

   Step 1: Share your temporary secret link
   
        Open the link https://cghuisunshine.github.io/ecdh.html, click shareSecretChannel and paste it in WeChat, SMS or Email to someone. 
        
   Step 2: Send secret message 
   
        Someone open the secret link you sent to him, input words, click encrypt, click copyWithMyPubKey, and paste it in WeChat, SMS or Email to you.
        
   Step 3: You parse secret message
   
        Open the link of secret message, click importMyKey to import your key file(myKeys.json that you use exportMyKey saved before).
        
        Click decrypt to parse the secret message.
        
   Step 4: each party(you or someone) repeat Step 3 to continue the chat.
   
   
   **Pros:**
   
      1. Forget previous chat automatically
      
         Use temporary key and every time you open the link  https://cghuisunshine.github.io/ecdh.html, a new temporary key pair would generate and 
         
       replace the old temporary one, which means you would forget what you have said before.
       
      2. Easy of use
      
         You don't have to exportMyKey or importMyKey, just shareSecretChannel and send it to someone to start a chat.
         
         After that, each party would input words, click encrypt, click copyWithMyPubKey and send it to counterpart.
         
    **Cons:**
    
       1. You can chat with one person only at the same time.
       
       2. You must stick to one browser only during the chat, because the browser need to find keys to fill automatically.
       
