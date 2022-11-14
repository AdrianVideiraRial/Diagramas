classDiagram
    Figuras geometricas <|-- Triangulo
    Figuras geometricas <|-- Rectangulo
    Figuras geometricas <|-- Pentagono
    Figuras geometricas <|-- Hexagono
    Figuras geometricas : -resultado String = mensaje
    Figuras geometricas: + Mostrar_resultado_area(String) float
    
    class Triangulo {
        -base:float
        -altura:float
        +area_triangulo():float
    }
    class Rectangulo {
         -base:float
        -altura:float
        +area_rectangulo ():float
    }
    class Pentagono {
         -lado:float
        -apotema:float
        +area_pentagono ():float
    }
    class Hexagono {
        -lado:float
        -apotema:float
        +area_hexagono ():float
    }