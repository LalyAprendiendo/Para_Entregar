"# Para_Entregar"  pero saltan estos errores
venv) C:\Users\Usuario\Desktop\ADA>python app.py
Traceback (most recent call last):
  File "C:\Users\Usuario\Desktop\ADA\app.py", line 20, in <module>
    lista_de_datos = proceso_cuentas.crear_cuentas()
                     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "C:\Users\Usuario\Desktop\ADA\proceso_cuentas.py", line 12, in crear_cuentas
    persona.crear_cuenta()
    ^^^^^^^^^^^^^^^^^^^^
AttributeError: 'Persona' object has no attribute 'crear_cuenta'