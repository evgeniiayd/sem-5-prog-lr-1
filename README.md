# Яблонская Евгения, Лабораторная работа 1
## Импорт удаленного модуля

1. Размещение удаленного модуля myremotemodule в папке rootserver в следующей директории:

![image](https://github.com/user-attachments/assets/e375de14-6629-4424-beba-cf339a6753cb)

2. Код модуля:

![image](https://github.com/user-attachments/assets/1276c2a8-5133-40cf-831d-0f167cdc586e)

3. activation_script.py размещен в следующей директории:

![image](https://github.com/user-attachments/assets/af90cace-807f-4947-ba11-217ae6864828)

(код activation_script.py находится в этом репозитории в соответствующем файле).

4. Запуск сервера в директории rootserver с модулем.

![image](https://github.com/user-attachments/assets/36b93775-bd19-4b64-afe8-87b749b09414)

5. Добавление строчки ```sys.path.append("http://localhost:8000")``` в код activation_script.py:

![image](https://github.com/user-attachments/assets/ead20955-dafb-4447-8d4f-0e9e539e8d7a)

6. Успешный импорт модуля.

![image](https://github.com/user-attachments/assets/84bb2b98-3426-43bb-a8eb-78855d6efbf5)



