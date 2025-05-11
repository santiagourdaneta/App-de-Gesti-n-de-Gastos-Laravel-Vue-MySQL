# App-de-Gesti-n-de-Gastos-Laravel-Vue-MySQL
Una aplicación web para la gestión de gastos personales. Registra ingresos, gastos y categorías, y genera informes visuales.

## 🚀 Características

- 🔐 Autenticación de usuario (registro/inicio de sesión/reinicio)
- 🧾 Añadir, editar y eliminar gastos e ingresos
- 📂 Categorizar transacciones
- 📊 Informes mensuales con gráficos (Chart.js)
- 🔎 Buscar y filtrar por fecha/categoría/tipo
- 🌐 Interfaz de usuario responsiva con Vue.js y Bootstrap

## 🛠️ Pila tecnológica

- **Backend**: Laravel
- **Frontend**: Vue.js + Axios
- **Base de datos**: MySQL
- **Autenticación**: Laravel Breeze
- **Gráficos**: Chart.js
- **Estilo**: Bootstrap 

## 📦 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/santiagourdaneta/App-de-Gesti-n-de-Gastos-Laravel-Vue-MySQL/
cd App-de-Gesti-n-de-Gastos-Laravel-Vue-MySQL

# Instalar las dependencias del backend
composer install

# Modificar el archivo de entorno y configurar la base de datos(crear en phpmyadmin o terminal)

#Generar key y hacer migration+seeding

php artisan key:generate
php artisan migration --seed

# Instalar las dependencias del frontend(debes tener instalado Node.JS y npm) 
npm install
npm run dev

# Iniciar el servidor
php artisan serve

#Usar tu navegador para usar la app en la direccion que te indique la terminal
Voila!
