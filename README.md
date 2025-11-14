1. System prompt and user prompt
   --- System prompt : It is also known as develepor prompt it is a predefined instruction given to the system clearly instructs system role, tone, rules to perform on a particular task
   --- User prompt : It refers to input to the system like a message, instruction or a command to get the response
   EXAMPLE : system prompt - Assume that you're a proffesional BCCI board member and provide me the information only based on cricket by these defined rules :
            1. Domain - cricket
            2. Knowledge cutoff - 2024 december
            3. Tone should be professional and no personal opinion needed
            4. Only provide the response based on this domain only not rather than that
   User prompt - It is a prompt given by user to get the response the AI
                 1. who is more runs scorrer in IPL 2022
                 2. give me short summary on world cup 2011

 2. DEFINITIONS : LLM - Large language model, it is a advanced mode of (artificial intelligence) AI which is trained on large sets of data it can perform actions like classifying, prediction, generation like audio and video
       API - Application Programming Interface, It is a intermediate software to perform activities like communication, exchange of data between systems. For performing this activities we need an key API key, which act as a secret code for user or the system to interact with the API
       INFERENCE - It performs the action run the input to get the AI's response
       WORKFLOW - In context of n8n workflow term refers to the process of smooth and continous work by connecting nodes to one another

 3. n8n workflow                                     
          Step 1- Add the node manual trigger
          step 2- connect the AI agent  node 
          Step 3- at chat model connect the open AI node 
          Step 4- at tool connect the HTTP node
          Step 5- In the http node fill the details like method, URL and headers and back to canvas
          <img width="1365" height="583" alt="image" src="https://github.com/user-attachments/assets/f84ab6e2-6c21-4f8e-8090-24f19918cf9d" />

          
 4. Role based prompting - It is well defined prompt given to the system with the set of instructions, rules to particularly perform on a specific task
          EXAMPLE - Im new to this city so now assume that you're a tour guide and give me the list of famous places to visit based on the best preferable timings
         By declaring role to it. it will act as a professional in that specific domain and gives us the enhanced output

 5. OLLAMA installation - From the ollama website we need to download ollama for our PC, to know ollama running or not ? we need to search the port 11434 
         After ollama installation for loading the model we need to head towards the models in ollama website and in search bar we need to search ["llama3"] and after opening the page we need to copy the command               "[ollama run llama3"] and run it on our terminal or CMD 
         After entering this command and hitting enter the current model llama3 will pull into the system 
         so now we are ready to use that model in our local server

 6. PIP INSTALL OLLAMA
         IMPORT OLLAMA
         RESPONSE = OLLAMA.CHAT("what is AI")
         PRINT(RESPONSE)

 7. System role- In LLM's system role plays a vital role in perspective of giving responses 
      When we want a information regarding on specific domain we need to clearly instruct the system by providing the role, tone, domain, format and if needed knowledge cut-off also

8. step-1 open a workflow
        step-2 add the trigger node
        step-3 add the AI agent node
        step-4 With the connected node for AI agent just add the serpapi node 
      
      
9. You're an agent which needs to assist me by providing step by step clear response 
         Just give me bullet points only
         If needed provide me some short examples also
         Response should be as in same language 
         
10.  LIMITATIONS:
          - They might miss the information in the middle ("haluezination")
          - Knowledge cutoff 



      
      









         
