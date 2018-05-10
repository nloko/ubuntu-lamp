# ubuntu-lamp
Simple Ubuntu based LAMP stack (Ubuntu Linux, Apache HTTP Server, MySQL, PHP / Python)

- Use 192.168.0.123 to access Apache served apps
- Use 192.168.0.123/phpmyadmin to access MySQL client
- mySQL root password is 12345678
- Put your project’s files in the “myproject” folder beneath the repo’s root

# Web Frameworks
The following frameworks are pre-installed:
- Django
- Symfony
    - create project using `symfony new my_project_name 2.7`
    - run using `php bin/console server:start 0.0.0.0:8080`
