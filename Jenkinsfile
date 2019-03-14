node {
	// download it
	git branch: 'example', url: 'https://github.com/bob-crutchley/python-http-server'
	// install it
	sh "sudo cp -r app.py public /home/python"	
	sh "sudo chown -R python:python /home/python"	
	// restart the application
	sh "sudo systemctl stop python-server"
	sleep(20)
	sh "sudo systemctl start python-server"
}

