## Bandit-Custom-CLI
* Step 1: Open terminal
* Step 2: Change directory

	 `cd /home/vagrant/Labs/Bandit-Custom-CLI`
* Step 3: Activate virtualenv 

	`source venv/bin/activate`
* Step 4: Run bandit 
	
	`bandit -f html -o bandit-result.html -x /home/vagrant/sources/Vulnerable-Flask-App/app/venv -r /home/vagrant/sources/Vulnerable-Flask-App/`
* Step 5: View report
	
	`firefox file://$PWD/bandit-result.html`
* Step 6: Deactivate virtualenv
	
	`deactivate`
