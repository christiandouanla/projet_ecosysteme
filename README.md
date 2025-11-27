#SIMULATEUR D'ECOSYSTEME

````un projet c++ utilisant SDL3 sur la simulation d'un ecosysteme virtuel intelligent````
 
##ARCHITECHTURE DU DEPOT
````
ecosystem_simulator/
├── include/
│   ├── Core/
│   │   ├── Structs.h
│   │   ├── Entity.h
│   │   ├── GameEgine.h
|   |   └── Ecosystem.h   
│   └── Graphics/
│       ├── Window.h
│       └── Renderer.h
├── src/                                    
│   ├── Core/
│   │   ├── Entity.cpp
        ├── Ecosystem.cpp
│   │   └── GameEngine.cpp
│   ├── Graphics/
│   │   ├── Window.cpp
│   │   └── Renderer.cpp
│   └── main.cpp
├── assets/
│   └── 
└── README.md
````

##PREREQUIS

````Windows (ou autre OS avec les ajustements appropriés).
Un compilateur C++ moderne (g++/MinGW, MSVC, clang).
SDL3 (bibliothèques de développement : headers et libs/dll). Assurez-vous d'avoir installé les fichiers de développement de SDL3 et de connaître les chemins d'inclusion et de bibliothèque.
````

##COMPILATION
````bash
g++ -std=c++17 -Iinclude -o ecosystem src/*.cpp src/Core/*.cpp src/Graphics/*.cpp -lSDL3
````
##EXECUTION

````.\ecosystem.exe````

##AUTEUR:
````bash
DOUANLA NGUEYO CHRISTIAN FRANCK    25P902
