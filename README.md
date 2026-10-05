# Restaurante App - Kerly Salazar - Semana 16

Proyecto POO Semana 16 - Manejo de eventos con Tkinter

## Características
- Roles: Administrador, Empleado, Cliente (ROLES_PERMITIDOS)
- 4 binds: <<TreeviewSelect>>, <Return>, <Escape>, <<ComboboxSelected>>
- Callbacks reutilizados: on_usuario_seleccionado, on_enter_presionado, on_escape_presionado, on_rol_cambiado
- Solo Administrador gestiona usuarios
- Contraseña con show="*"
- Rutas dinámicas con pathlib Path(__file__).resolve().parent / "datos"

## Acceso de prueba
- admin / admin123 (Administrador)
- cajero / cajero123 (Empleado)
- kerly / kerly123 (Administrador)

## Ejecución
```
python main.py
```
