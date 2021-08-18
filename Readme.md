## Ejemplo de uso en colab

```sh
 !git clone https://github.com/camilousa/geek.git
 ```
```sh
 from geek.geek import  Agente, dibujar_ambiente, ejecutar
 ```
 ```sh
 out = dibujar_ambiente()
 acciones = ["rotar", "avanzar", "avanzar", "rotar"]
 valores = [0, 15, 5, 90]
 agente = Agente(out=out, x=50, y=50, angulo=180)
 ejecutar(agente, acciones, valores)
 ```
