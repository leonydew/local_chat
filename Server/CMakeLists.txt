cmake_minimum_required(VERSION 3.25) # Проверка версии CMake.

set(PROJECT_NAME Server)				 # задать константу с именем проекта		 
project("${PROJECT_NAME}")			 # имя проекта	


set(CMAKE_CXX_STANDARD 17)			 # устанавливаем 17 стандарт языка
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)


add_executable("${PROJECT_NAME}" ServerS.cpp)	# добавить исполняемый файл
