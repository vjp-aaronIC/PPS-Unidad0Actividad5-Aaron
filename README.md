# PPS-Unidad0Actividad5-Aaron

## Descripción de la actividad
En esta actividad voy a colaborar con compañeros a través de Github y de sus funcionalidades.
Voy a crear ramas en repositorios en los que me han dado permisos de colaborador, documentando todo el proceso.

## Visualización de repositorios remotos
Podemos visualizar los repositorios remotos configurados

```bash
git remote -v
```

![](imagenes/remote.png)

## Creación del profile
1. Voy a crear una carpeta llamada **img** dentro del repositorio y dentro añadiré una imagen que se llamará **aaron.png**.

```bash
mkdir img
```

![](imagenes/img_aaron.png)

2. Voy a crear la carpeta profile y dentro voy a crear un **HTML** (aaron.html). Este **HTML** va a contener una imagen que se llama **aaron.png**.

```bash
mkdir profile
echo "<img src="../img/aaron.png" />" >  aaron.html
```

![](imagenes/contenido_img.png)

3. Arranco el **servidor PHP** y en el navegador se muestra la imagen del **HTML**

![](imagenes/index_php.png)

## Colaboraciones
He conado el repositorio de mi compañero en un directorio local y luego he creado una rama con mi nombre (aaron) dentro de su repositorio. Me he situado sobre la rama con mi nombre y he comprobado el *estado* y revisado los repositorios remotos que tengo configurados.

```bash
git clone git@github.com:vjp-aimarMG/PPSUnidad0Actividad5Aimar.git
cd PPSUnidad0Actividad5Aimar
git branch aaron
git checkout aaron
git status
git remote -v
```

Después he creado en esta rama mi **foto** y mi **profile**.

![](imagenes/cp_colaboracion.png)

