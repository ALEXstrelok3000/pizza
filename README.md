pay = 0
pizza = int(input("выберите пиццу 1 - пеперони 2 - 4 сыра 3 - мясная "))
list_1 = ['Пикантная пепперони', 'увеличенная порция моцареллы', 'томаты', 'фирменный томатный соус']
list_2 = ['Сыр блю чиз', 'сыры чеддер и пармезан', 'моцарелла', 'фирменный соус альфредо']
list_3 = ['Цыпленок', 'ветчина', 'пикантная пепперони', 'острая чоризо', 'моцарелла', 'фирменный томатный соус']
if pizza == 1:
    print("состав пиццы: томатный соус, моцарелла, пеперонни, томаты")
    add = int(input('хотите добавить начинку? 1 - нет 2 - да '))
    if add == 2:
        print(list_1)
        ingridiens = int(input("что вы хотите добавить? 1 - сыры чеддер и пармезан 2 - лук 3 - грибы "))
        list_1.append(ingridiens)
        if ingridiens== 1:
            pay =+ 80
        elif ingridiens == 2:
            pay =+ 60
        elif ingridiens == 3:
            pay =+ 60
elif pizza == 2:
    print("состав пиццы: Сыр блю чиз, сыры чеддер и пармезан, моцарелла, фирменный соус альфредо")
    add = int(input('хотите добавить начинку? 1 - нет 2 - да '))
    if add == 2:
        print(list_1)
        ingridiens = int(input("что вы хотите добавить? 1 - сыры чеддер и пармезан 2 - лук 3 - грибы "))
        list_1.append(ingridiens)
        if ingridiens == 1:
            pay = + 80
        elif ingridiens == 2:
            pay = + 60
        elif ingridiens == 3:
            pay = + 60
elif pizza == 3:
    add = int(input('хотите добавить начинку? 1 - нет 2 - да '))
    if add == 2:
        print(list_1)
        ingridiens = int(input("что вы хотите добавить? 1 - сыры чеддер и пармезан 2 - лук 3 - грибы "))
        list_1.append(ingridiens)
        if ingridiens == 1:
            pay = + 80
        elif ingridiens == 2:
            pay = + 60
        elif ingridiens == 3:
            pay = + 60
if pizza == 1:
    pay =+ 290
elif pizza == 2:
    pay =+ 470
elif pizza == 3:
    pay =+ 470
how_pay = int(input("Выберете способ оплаты 1 - картой 2 - наличкой "))
if how_pay==1:
    print('спасибо за покупку средства сами снимуться с карты ')
else:
    pay_2 = int(input("оплатите наличкой "))
    pay_3 = pay_2 - pay
print(pay_3, 'ваша сдача ')
