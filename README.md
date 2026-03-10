m<!DOCTYPE html>
<html>
<head>
<title>My AI Solver</title>

<style>
body{
background:#0f172a;
font-family:Arial;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
color:white;
}

.chatbox{
width:400px;
height:500px;
background:#1e293b;
border-radius:10px;
display:flex;
flex-direction:column;
}

.messages{
flex:1;
padding:10px;
overflow-y:auto;
}

.user{
text-align:right;
margin:5px;
color:#38bdf8;
}

.ai{
text-align:left;
margin:5px;
color:#22c55e;
}

.inputbox{
display:flex;
border-top:1px solid #334155;
}

input{
flex:1;
padding:10px;
border:none;
outline:none;
}

button{
padding:10px;
background:#38bdf8;
border:none;
cursor:pointer;
}
</style>

</head>

<body>

<div class="chatbox">

<div class="messages">

<div class="ai">Hello, I am your AI Solver.</div>

<div class="user">Example Question</div>

<div class="ai">AI answer will appear here.</div>

</div>

<div class="inputbox">
<input type="text" placeholder="Ask a question...">
<button>Send</button>
</div>

</div>

</body>
</html>
