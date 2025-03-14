<p align="center">
  <button onclick="openChatPopup()">Chat with AI</button>
</p>

<script>
  function openChatPopup() {
    let popup = window.open("https://your-username.github.io/ai-chatbot-ui/", "Chatbot", "width=400,height=600");
    if (!popup) {
      alert("Please allow pop-ups for this site!");
    }
  }
</script>
