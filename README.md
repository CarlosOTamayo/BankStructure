# BankStructure
En este codigo vamos a crear un sistema bancario.
-Requerimientos:
Escensiales = Toda cuenta va a tener sus respectivos nombres y apellido
de igual manera tambien se va a registrar la fecha en la que se creo
# 1. Cuentas:
    1.1. Usuario:
        1.1.1. Tendra titular por medio de cedula
            1.1.1.1. Se verificara el numero de la cedula para que no se repita
            1.1.1.2. Se le asignara una cuenta al usuario (numerica) 
        1.1.2. Se le dira al titular el saldo que tiene la cuenta
        1.1.3. El usuario tendra una moneda asignada, tendra 2 opciones:
            1.1.3.1. COP (Pesos colombiano)
            1.1.3.2. USD (Dolar)
        1.1.4. El usuario tendra la opcion de consignar dinero a la cuenta
        (El valor inicial de la cuenta va a ser 0)
        1.1.5. El usuario podra ver el saldo actual que tenga la cuenta
        1.1.6. El usuario podra depositar y retirar dinero
            1.1.6.1. Si la cantidad de dinero a retirar es mayor a la que se tiene se mostrara un mensaje de error
            1.1.6.2. Si el sueldo es 0 cuando se quiera realizar un retiro se mostrar un mensaje de error
            1.1.6.3. Si al momento de realizar una transaccion el monto es mayor al sueldo se mostrara un mensaje de error
        1.1.7. El usuario podra realizar transacciones a otras cuentas
            1.1.7.1. Se verificara si el numero de cuenta existe, si no se encuentra se dara un mensaje de error
            1.1.7.2. Se le preguntara al usuario si esta seguro del numero de cuenta
            1.1.7.3. Si el monto a mandar es mayor que el saldo que tiene la cuenta se dara un mensaje de error
    1.2.Funcionario:
        1.2.1. Tendra titular por medio de cedula
            1.2.1.1. Se verificara el numero de la cedula para que no se repita
            1.2.1.2. Se le asignara una cuenta al usuario (numerica)
        1.2.2. Se le asignaran al funcionario tareas con las cuales se dara un porcentaje de rendimiento
        1.2.3. Se le dira al titular el saldo que tiene la cuenta
        1.2.4. El usuario tendra una moneda asignada, tendra 2 opciones:
            1.2.4.1. COP (Pesos colombiano)
            1.2.4.2. USD (Dolar)
        1.2.5. El usuario tendra la opcion de consignar dinero a la cuenta
        (El valor inicial de la cuenta va a ser 0)
        1.2.6. El usuario podra ver el saldo actual que tenga la cuenta
        1.2.7. El usuario podra depositar y retirar dinero
            1.2.7.1. Si la cantidad de dinero a retirar es mayor a la que se tiene se mostrara un mensaje de error
            1.2.7.2. Si el sueldo es 0 cuando se quiera realizar un retiro se mostrar un mensaje de error
            1.2.7.3. Si al momento de realizar una transaccion el monto es mayor al sueldo se mostrara un mensaje de error
        1.2.8. El usuario podra realizar transacciones a otras cuentas
            1.2.8.1. Se verificara si el numero de cuenta existe, si no se encuentra se dara un mensaje de error
            1.2.8.2. Se le preguntara al usuario si esta seguro del numero de cuenta
            1.2.8.3. Si el monto a mandar es mayor que el saldo que tiene la cuenta se dara un mensaje de error
# 2. Calculos:
    2.1. Usuarios:
        2.1.1. Se le dara un bono de ahorro al usuario dependiendo del tiempo que haya tenido su sueldo en el sistema:
            2.1.1.1. Si el usuario a tenido su sueldo durante 6 meses se le da un bono del 0,2% del suedo actual
            2.1.1.2. Si el usuario a tenido su sueldo durante 1 año se le da un bono del 0,4% del sueldo actual
            2.1.1.3. Si el usuario a tenido su sueldo durante 2 años se le da un bono del 0,8% del sueldo actual
            2.1.1.4. Si el usuario a tenido su sueldo durante 4 o mas años se le da un bono del 0,10% del sueldo actual
    2.2. Funcionarios:
        2.2.1. Se le dara un bono de ahorro al usuario dependiendo del tiempo que haya tenido su sueldo en el sistema:
            2.2.1.1. Si el usuario a tenido su sueldo durante 6 meses se le da un bono del 0,2% del suedo actual
            2.2.1.2. Si el usuario a tenido su sueldo durante 1 año se le da un bono del 0,4% del sueldo actual
            2.2.1.3. Si el usuario a tenido su sueldo durante 2 años se le da un bono del 0,8% del sueldo actual
            2.2.1.4. Si el usuario a tenido su sueldo durante 4 o mas años se le da un bono del 0,10% del sueldo actual
        2.2.2. Se le dara un bono al funcionario conforme al rendimiento que tenga mensualmente:
            2.2.2.1. Rendimiento malo: no obtendra bono (0%)
            2.2.2.2. Rendimiento bajo: obtiene un bono del 5%
            2.2.2.3. Rendimiento medio: obtiene un bono del 10%
            2.2.2.4. Rendimiento bueno: obtiene un bono del 15%
            2.2.2.5. Rendimiento excelente: obtiene un bono del 20%