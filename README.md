# spaceCalc · Aura Calculator

Calculadora web ultra-futurista (glassmorphism estilo Apple) en un único archivo HTML sin dependencias.

## Características

- **Motor propio**: tokenizer + shunting-yard → RPN (sin `eval`), con paréntesis, funciones, variable `x` y notación científica.
- **Científica**: trigonometría (+inversas e hiperbólicas con 2nd), ln/log, potencias, raíces, factorial, π, e, ans, memoria (MC/MR/M+/M−/MS), RAD/DEG.
- **Historial** persistente (localStorage) reutilizable con un clic.
- **Modo juego "Función Proyectil"**: escribe f(x) y lanza un proyectil sobre tu curva para alcanzar una estrella evitando obstáculos (torres, orbes y una barrera que impide el truco de la constante). Sin(x) oscila, x² vuela en parábola.
- Tema claro/oscuro, atajos de teclado completos, formato numérico español, copiar resultado con un clic.

## Uso

Abre `calculadora.html` en el navegador. No requiere build ni servidor.

## Atajos de teclado

`0-9 , . ( ) + - * / ^ ! %` · `Enter` igual/lanzar · `Esc` limpiar/cerrar · `Backspace` borrar · `s/c/t` trig · `l/g` ln/log · `r` √ · `x` variable · `p` π · `e` eˣ · `a` ans · `m` MR · `↑` última expresión
