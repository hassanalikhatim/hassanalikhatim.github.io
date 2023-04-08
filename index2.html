{% load markup %}
<html>
	<head>
		<meta>
		<title>{% block title %}nugarum cesaris{% endblock %}</title>
		<link rel="stylesheet" type="text/css" href="{{STATIC_URL}}css/main.css">
		<script src="//ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
	</head>
	<body>
		<div id="container">
			<header>
				<h1><a href = "/">nugarum cesaris</a></h1>
				<nav id="menu">
					<ul>
						<li id="menu1"><a class="github" href="https://github.com/cesarvargas00">github</a></li>
						<li id="menu2"><a class="face" href="https://www.facebook.com/cesarvargas00">face</a></li>
						<li id="menu3"><a class="twitter" href="https://twitter.com/madasheila">twitter</a></li>
					</ul>
				</nav>
			</header>
			<section id="content">
				{% block content %}
					{% for p in ultimos_posts%}
					<h2>{{p.title}}</h2>
					<h3>Posted in {{p.data}} #<a href="/post/{{p.id}}/#disqus_thread"> 0 Comments</a></h3>
					{% if user.is_authenticated %}<a href="/apagar/{{p.id}}">remove</a>{% endif %}
					<div class="post">
						<p>
						{{p.conteudo|markdown:"safe"}}
						</p>
						<a href="/post/{{p.id}}" class="more">. . .more</a>
					</div>
					{%endfor%}
					<div class="navigation">&lt&nbsp&nbsp&nbsp&gt</div>
				{% endblock %}
			</section>
			<footer>
				<a href="#">about</a>
				<a href="/history">history</a>
				{% if user.is_authenticated %}<a href="/logout">logout</a>{% else %}<a href="/login">login</a>{% endif %}
			</footer>
		</div>
		{% block scripts %}
		<script type="text/javascript">
        /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
        var disqus_shortname = 'cesarblog'; // required: replace example with your forum shortname

        /* * * DON'T EDIT BELOW THIS LINE * * */
        (function () {
            var s = document.createElement('script'); s.async = true;
            s.type = 'text/javascript';
            s.src = 'http://' + disqus_shortname + '.disqus.com/count.js';
            (document.getElementsByTagName('HEAD')[0] || document.getElementsByTagName('BODY')[0]).appendChild(s);
        }());
        </script>
        {% endblock %}
	</body>
</html>
