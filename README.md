# notes
Как развернpуть проект на yii
  1. Зайди в php контейнер по команде в консоли: docker exec -ti conteiner_name bash
  2. Добавить в контейнер гит: apt update, затем apt install git
  3. Установить композер: curl -s https://getcomposer.org/installer | php — —install-dir=/usr/local/bin/ —filename=composer
  4. Развернуть проект на yii: composer create-project --prefer-dist yiisoft/yii2-app-basic basic
