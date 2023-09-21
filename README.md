# import turtle

# Configuración inicial
t = turtle.Turtle()
t.speed(1)  # Velocidad del dibujo
t.color("yellow")  # Color de la flor

# Dibuja un círculo amarillo
t.begin_fill()
t.circle(100)
t.end_fill()

# Dibuja los pétalos de la flor
t.color("red")  # Color de los pétalos
for _ in range(6):
    t.begin_fill()
    t.circle(50, 60)
    t.left(120)
    t.circle(50, 60)
    t.left(120)
    t.end_fill()

# Cierra la ventana al hacer clic
turtle.exitonclick()
