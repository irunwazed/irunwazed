<html>

<head>


<style>

	@import url('https://fonts.googleapis.com/css?family=Source+Code+Pro');

body{
  padding: 40px;
  background-color: #121212;  
}

p {
  border-right: solid 3px rgba(0,255,0,.75);
  white-space: nowrap;
  overflow: hidden;    
  font-family: 'Source Code Pro', monospace;  
  font-size: 28px;
  color: rgba(255,255,255,.70);
}

/* Animation */
p {
  animation: animated-text 4s steps(29,end) 1s 1 normal both,
             animated-cursor 600ms steps(29,end) infinite;
}

/* text animation */

@keyframes animated-text{
  from{width: 0;}
  to{width: 472px;}
}

/* cursor animations */

@keyframes animated-cursor{
  from{border-right-color: rgba(0,255,0,.75);}
  to{border-right-color: transparent;}
}
	</style>
</head>
<body>
<p>Selamat Datang...</p>

<img src="https://github-readme-stats.vercel.app/api?username=irunwazed&show_icons=true&hide_border=true&hide=issues&title_color=5391FE&icon_color=000000&text_color=52057b" />

</body>

</html>


