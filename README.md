# 🛠️ Keylogger Educativo en Python

Este es un proyecto de ciberseguridad ofensiva que implementa un **keylogger básico** en Python.  
Fue desarrollado como parte de mi formación práctica en análisis post-explotación y desarrollo de herramientas personalizadas.

## ![Python](https://img.shields.io/badge/Python-3.9+-blue.svg) ![pynput](https://img.shields.io/badge/pynput-1.7+-green.svg) ![Security](https://img.shields.io/badge/Security-Penetration_Testing-8A2BE2) ![Educational](https://img.shields.io/badge/Educational-Lab_Only-FFA500) ![License](https://img.shields.io/badge/License-MIT-green.svg)

> ⚠️ **Uso exclusivo con fines educativos y en entornos controlados**.

---

## 📌 Funcionalidades

- Captura de pulsaciones del teclado en tiempo real
- Guarda el registro en un archivo local (`keylog.txt`)
- Puede ejecutarse en segundo plano

---

## 🚀 Instalación

Cloná este repositorio:

```bash
git clone https://github.com/Kronoscba/keylogger.git
cd keylogger
```

Creá y activá un entorno virtual (opcional pero recomendado):

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Instalá las dependencias:

```bash
pip install -r requirements.txt
```

> Si aún no tenés un `requirements.txt`, crealo con el contenido:
> ```txt
> pynput
> ```

---

## ⚙️ Uso

Ejecutá el script principal:

```bash
sudo python3 keylogger.py
```

Los logs se guardarán en un archivo local (`data.txt` o el que definas en el script).

---

luego ya podras ver el archivo data.txt: 
```bash
cat o bat data.txt
```
---

## ⚠️ Aviso de Uso Ético

Este proyecto fue creado con fines **exclusivamente educativos**, para entornos de laboratorio y pruebas controladas.  
**No debe usarse en sistemas reales sin autorización expresa.**  
El autor no se responsabiliza por el uso indebido de esta herramienta.

---

## 👨‍💻 Autor

- **Kronos**  

---

## 📝 Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo [LICENSE](LICENSE) para más información.
