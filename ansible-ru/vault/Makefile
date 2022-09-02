test:
	ansible-playbook -i inventory.ini playbook.yml
	test -e package.json || exit
	make lint

lint:
	ansible-lint playbook.yml

# BEGIN
install:
	npm install

start:
	npm start
# END

.PHONY: test
