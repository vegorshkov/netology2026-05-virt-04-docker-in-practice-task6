# Используем исходный образ
FROM hashicorp/terraform:latest

# Копируем бинарник terraform из образа в /output в новом контейнере
RUN mkdir /output
RUN cp /bin/terraform /output/

# Указываем рабочий каталог для вывода файла
WORKDIR /output

