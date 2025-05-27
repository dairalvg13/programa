# Navega al directorio de tu proyecto
cd ruta/a/tu/proyecto

# Inicializa un nuevo repositorio de Git
git init

# Agrega todos los archivos al área de preparación
git add .

# Realiza el primer commit
git commit -m "Primer commit de mi programa"

# Agrega la URL del repositorio remoto
git remote add origin https://github.com/dairalvg13/programa.git

# Verifica que el remoto se haya agregado correctamente
git remote -v

# Sube los cambios al repositorio en GitHub
git push -u origin main
