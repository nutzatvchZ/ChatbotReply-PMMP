# ChatbotReply-PMMP
Chat bots interact with players.<br>
Features:
  ```
           Custom Reply Chat🤩
      Support 2 Language TH ENG🏳
      Support Custom Chat Execute Command💾
  ```
  <hr>
  <br>
API:
  ```php
  /*** Var $chatbot Chatbot **/
  $chatbot = ChatbotLoader::getInstance();
  $chatbot->addChatReply("Hello", "Reply Message");
  //Replay  Chat With Command
  /*** Var $chatbot Chatbot **/
  $chatbot = ChatbotLoader::getInstance();
  $chatbot->addChatReplyCommand("Hello", "Execute Command", false, "Hi");
  ```
