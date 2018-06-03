# XMLHttpRequest
1. Fork the Javascript 3 repo
2. Clone the repo to the local machine
3. Create a new branch
4. Create a file called steps.md
5. Write the steps to connect to the Github API:
	1. making an XHR object
	2. adding an event handler on the XHR object
	3. checking if the readystate is equal to 4 (done), and the status is 200 (successful) and excuting a function if the condition was met
	4. defining a function to create an HTML element and change its content to the xhr "responseText"
	5. another if statment to check if the status is 404 (not found), if so display something to tell the user that this page doesn't exist
	6. using the method open on the XHR object with the parameter "get", and the url
	7. using the method send() on XHR, to send the request to the server

