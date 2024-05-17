# Nombre de la Aplicación Flutter

Una aplicación Flutter que genera nombres que suenan bien como "newstay", "lightstream", "mainbrake" o "graypine". Los usuarios pueden solicitar otro nombre, marcar el actual como favorito y revisar la lista de nombres favoritos en una página independiente. La aplicación es responsiva y se adapta a distintos tamaños de pantalla.

## Características

- **Generación de Nombres**: Genera nombres únicos y atractivos.
- **Favoritos**: Marca nombres como favoritos y revisa la lista de nombres favoritos en cualquier momento.
- **Responsividad**: La aplicación se adapta a diferentes tamaños de pantalla para una mejor experiencia de usuario en móviles y tabletas.

## Capturas de Pantalla

![Pantalla de Inicio](screenshots/home.png)
![Pantalla de Favoritos](screenshots/favorites.png)

## Instalación

1. **Clonar el repositorio**
    ```sh
    git clone https://github.com/tu-usuario/tu-repositorio.git
    cd tu-repositorio
    ```

2. **Instalar dependencias**
    ```sh
    flutter pub get
    ```

3. **Ejecutar la aplicación**
    ```sh
    flutter run
    ```

## Uso

1. **Generar un nuevo nombre**: Al abrir la aplicación, se mostrará un nombre generado automáticamente. Puedes tocar el botón "Generar otro" para obtener un nuevo nombre.
2. **Marcar como favorito**: Si te gusta un nombre, puedes tocar el ícono de corazón para marcarlo como favorito.
3. **Ver favoritos**: Puedes acceder a la lista de nombres favoritos desde el menú principal.

## Estructura del Proyecto

```plaintext
├── android             # Archivos específicos de Android
├── ios                 # Archivos específicos de iOS
├── lib                 # Código fuente de la aplicación
│   ├── main.dart       # Punto de entrada de la aplicación
│   ├── home_page.dart  # Página principal de la aplicación
│   ├── favorites_page.dart # Página de favoritos
│   ├── name_generator.dart # Lógica para generar nombres
├── test                # Pruebas unitarias y de widget
├── pubspec.yaml        # Archivo de configuración de dependencias
└── README.md           # Documentación del proyecto
