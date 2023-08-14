Практика с SELinux

Тренируем умение работать с SELinux: диагностировать проблемы и модифицировать политики SELinux для корректной работы приложений, если это требуется.
1) Запуск nginx на нестандартном порту 3-мя разными способами 
Дописал в Vagrantfile:  yum install policycoreutils-python (так как по умолчанию нет инструмента audit2why)

Способ 1
![Снимок экрана от 2023-08-14 15-23-14](https://github.com/otus-avi/dz17/assets/123792073/4ecacb1d-c5f4-43b2-9e02-7100df1daba1)

![Снимок экрана от 2023-08-14 15-30-46](https://github.com/otus-avi/dz17/assets/123792073/8b39eec3-8886-4286-9bf2-20af1ca213ae)

![Снимок экрана от 2023-08-14 15-33-47](https://github.com/otus-avi/dz17/assets/123792073/50316e33-fb20-4b23-81a1-af8c70a8ec02)

Способ 2
![Снимок экрана от 2023-08-14 15-38-36](https://github.com/otus-avi/dz17/assets/123792073/67efdb3b-ce5d-475f-8c9f-9a792fdaec4c)

Способ 3
![Снимок экрана от 2023-08-14 15-43-09](https://github.com/otus-avi/dz17/assets/123792073/daf3cf23-7219-4239-a2fd-4f1778aefa14)

2) Обеспечение работоспособности приложения при включенном SELinux
   
Client
![Снимок экрана от 2023-08-14 16-08-39](https://github.com/otus-avi/dz17/assets/123792073/6dde7c7d-6f11-484b-bf58-7f4e846d0442)

ns01

![image](https://github.com/otus-avi/dz17/assets/123792073/3ab28106-145f-4fef-8ee6-3fd9dc74e47b)
Шаг 2
![Снимок экрана от 2023-08-14 16-47-10](https://github.com/otus-avi/dz17/assets/123792073/b0656833-9059-442b-b053-8b05bb64ae7c)

Проверка работы 
![Снимок экрана от 2023-08-14 16-46-55](https://github.com/otus-avi/dz17/assets/123792073/4fd21123-d99b-4488-8811-72c45fa1dea2)

