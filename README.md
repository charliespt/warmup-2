warmup-2
========
Name of the file: client.html

Instructions to install and run the code:

1. You can test in using the warmup1 if you tested using the sample front-end: first, copy client.html and replace it to the warmup1 directory where the client.html located, then you can test it.

2. Otherwise, add url(r'^client.html', 'yourAppName.views.showPage’) to the urlpatterns in the urls.py in your project's directory, then add 
def showPage(request):
	return render(request, 'client.html’)
in your view.py. Then, put the client.html in appName/templates/ of your project’s directory. It is better to set your  server in port 8000, then you can try and test the front-end by typing localhost:8000/client.html in a browser. If you use heroku, just go to heroku_link/client.html in order to test the front-end.
