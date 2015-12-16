Chat app based on https://www.firebase.com/tutorial/#example/chat
	with added Math rendering via inclusion of the MathJax lib.
	Created during the the Firebase Hackatlon Google-NYC Nov 7,8 2015
	by Filip Babalievsky.

To use with own firebaseapp hosting see.

https://www.firebase.com/docs/hosting/quickstart.html

Get the firebaseapp name and replace in
firebase.json
and in index.html change the firebaseapp name:

var messagesRef = new Firebase('https://your-firebaseapp-here.firebaseio.com/'); 