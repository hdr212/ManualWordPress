# ManualWordPress

1. mkdir (example)
2. cd example

3. vagrant init ubuntu/jammy64

4. vagrant up --provider=virtualbox

5. vagrant ssh

6. sudo -s

7. apt update

8. apt upgrade

9. apt install -y php libapache2-mod-php

10. apt install -y php-fpm php-common php-mbstring php-xmlrpc php-soap php-gd php-xml php-intl php-mysql php-cli php-ldap php-zip php-curl

11. php -v

12. apt install -y apache2

13. apt install -y mysql-server

14. systemctl restart apache2

15. mysql

16. CREATE DATABASE bbdd;

17. CREATE USER 'usuario'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';

18. GRANT ALL ON bbdd.* to 'usuario'@'localhost';

19. exit

20. https://wordpress.org/latest.zip

21. Mover el zip a la carpeta

22. mv /vagrant/wordpress….zip /var/www/html/

23. cd /var/www/html/

24. ls

25. apt install unzip

26. unzip wordpres….zip

27. ls

28. cd wordpress

29. cp -R * ..

30. ls

31. cd ..

32. ll

33. ls

34. rm -r wordpress

35. rm -r wordpress….zip

36. rm -r index.html

37. cd /var/www/html

38. chmod -R 775 .

39. chown -R root:www-data .

40. exit

41. logout

42. vi Vagrantfile

43. config.vm.network "forwarded_port", guest: 80, host: 8080

44. config.vm.network "public_network"

45. vagrant reload

46. vagrant ssh

47. logout

48. vagrant reload

49. vagrant ssh


INICIAR SESION

