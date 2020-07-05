# ija-app
- Autors: Patrik Tomov and Maroš Geffert
- Points earned: 60/80

# Folders info:
- src/          - (fold.) source files (package hierarchy)
- data/         - (fold.) prepared data files
- build/        - (fold.) translated class files
- doc/          - (fold.) generated program documentation
- dest/         - (fold.) location of the resulting jar archive (+ other necessary files)
                          after compiling the application,
                          this directory will be the executable application directory
- lib/          - (fold.) external files and libraries (third-party packages, images, etc.),
                          which your application uses
- build.xml     - (file) build file for ant application


# Application translation:
- in the root directory is executed with the ant compile command
- source texts are compiled, class files will be located in the build directory
- a jar archive named ija-app.jar is created in the dest directory; other necessary files and archives will be created / copied to this directory


# Launch the application:
- the created jar archive will be launched
- in the root directory is executed with the ant run command
