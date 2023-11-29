num_1 = 4
num_2 = 3
def my_shiny_new_decorator(function_to_decorate):
     # Внутри себя декоратор определяет функцию-"обёртку". Она будет обёрнута вокруг декорируемой,
     # получая возможность исполнять произвольный код до и после неё.
     def the_wrapper_around_the_original_function():
         summa = num_1 + num_2
         function_to_decorate() # Сама функция
         num_3 = summa*2
     # Вернём эту функцию
     return the_wrapper_around_the_original_function
