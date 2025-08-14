# Curso de Git y GitHub

git init                            # Inicia un nuevo repositorio local\n
git config --list                   # Muestra todas las configuraciones actuales
git config --global user.name "<nombre>"   # Configura tu nombre de usuario global
git config --global user.email "<email>"   # Configura tu correo electrónico global
git config --global -l              # Lista la configuración global

# Conexión con repositorio remoto
git remote add origin <url>         # Conecta el repositorio local con un repositorio remoto llamado 'origin'
git push -u origin master           # Sube el proyecto y vincula la rama local con la remota (rama master)

# Comandos más importantes
git add .                           # Agrega todos los archivos modificados al "staging area"
git commit -m "<mensaje>"           # Guarda los cambios agregados con un mensaje descriptivo
git push                            # Sube los commits confirmados al repositorio remoto

# Obtener cambios del remoto
git fetch                           # Descarga los cambios remotos SIN fusionarlos con tu rama actual
git pull                            # Descarga y fusiona los cambios del remoto con tu rama actual

# Ramas
git branch                          # Muestra todas las ramas locales
git branch <nombre>                 # Crea una nueva rama
git checkout <nombre-de-la-rama>   # Cambia a una rama existente
git checkout -b <nombre>            # Crea y cambia a una nueva rama (atajo)

# Repositorio remoto
git clone <url-del-repositorio>     # Clona un repositorio remoto a tu computadora
git remote -v                       # Muestra las URLs del repositorio remoto (fetch/push)
