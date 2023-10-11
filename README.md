# Как скачать репозиторий:

1. Зарегистрируйтесь на GitHub
2. Добавьте свой SSH ключ
   1. Сгенерируйте ключ у себя на ПК
   2. В терминале введите команду **ssh-keygen -t rsa -b 4096**
   3. Найдите в терминале папку .ssh в домашней директории, внутри папки будет файл id_rsa.pub - его содержимое и есть ваш ssh ключ
   4. В настройках GitHub найдите вкладку SSH and GPG keys
   5. Добавьте ключ по кнопке: Дайте ему название и вставьте ключ из буфера обмена
3. Задайте имя и рабочую почту для гита
   1. **git config --global user.name "Ваше имя"** задаст имя
   2. **git config --global user.email "ваша*электронная*почта@example.com"** задаст почту
4. В кодовом редакторе склонируйте репозиторий и откройте его
   - В стартовой вкладке VS Code найдите кнопку Clone Git Repository...
   - В нужном поле вставьте ссылку для открытия/клонирования
5. Воспользуйтесь лайвсервером и запустите index.html
6. Вуаля!

# Задание №1

## Сверстайте страницу, посвящённую вашим (или любыми чужим) увлечениям, по следующему техническому заданию:

1. В шапке страницы должна быть картинка logo.jpg с размером 50 на 50 пикселей, ваше ФИО и номер группы. У шапки есть нижняя прерывающаяся граница толщиной в 2 пикселя на всю ширину страницы

2. В основной части страницы добавьте 3 или более блоков о своих текущих, будущих (а может быть уже и прошлых) увлечениях
      Каждый блок должен иметь: 
    1. Заголовок с названием 
    2. Медиаэлемент, описывающий увлечение 
    3. Расскажите, почему вам интересно заняниматься/заняться в будущем этим 
    4. \*Расскажите о своих достижениях, знакачимых для вас событиях
3. Блоки размещаются друг под другом по центру экрана и занимают 900 пикселей
      Цветовая гамма страницы должна соответствовать схемам "Триада" или "Контрастная триада"
      При наведении на блок, у него должна появляться граница с закруглёнными краями. Закругление равно 24 пикселям
      
4. Футер странички должен содержать цветовые блоки с градиентом. Наклон градиента: 45 градусов, цвета на ваше усмотрение, ширина полосок не более 50 пикселей

## Как сохранить репозиторий у себя в аккаунте?
1. Создайте пустой репозиторий в вашем аккаунте GitHub
2. Найдите зелёную кнопку __Code__ и скопируйте ssh ссылку
3. Воспользуйтесь командой __git remote set-url origin <ссылка на ваш репозиторий>__

# Как сделать коммит:

1. Отредактируйте файлы
2. Добавьте файлы в отслеживание командой **git add -A**
3. Сделайте коммит с сообщением командой **git commit -m "your_commit_message"**
4. Отправьте изменения в удалённый репозиторий командой **git push**
5. \*Если вы сделали изменения с другого ПК, либо кто-то другой что-то изменил в вашем репозитории, то перед началом работы следует воспользоваться командой **git pull**, чтобы избежать конфликтов
#   H o w T o G i t  
 