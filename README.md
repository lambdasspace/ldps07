## Lenguajes de Programación
### Evaluación Semanal 7

#### 📝 Instrucciones

- El semanal podrá resolverse **en equipos de 3**.
- Se deberá entregar por medio de GitHub Classroom a más tardar a las **23:59:59 del martes 15 de octubre de 2024**. **No habrán prórrogas**. En caso de requerir más tiempo, se descontará un punto por cada día de entrega tardío.
- Cualquier duda podrá extenarse en la clase, por correo o por medio de Telegram en un horario de 8:00 a 18:00.
- Deberá entregarse en formato LaTeX.
- No es necesario que vuelvan a escribir los ejercicios completos, basta con que los numeren y entreguen **en orden**.

#### 🚀 Ejercicios

1. Dada la siguiente expresión en **MiniLisp**
   ```lisp
   (let (sum (lambda (n) (if0 n 0 (+ n (sum (- n 1))))))
      (sum 5))
   ```

   - Ejecutarla y explicar el resultado.
   - Modificarla usando el combinador de punto fijo Y, volver a ejecutarla y explicar el resultado.
  
2. Evaluar la siguiente expresión en **Racket**, explicar su resultado y dar la continuación asociada a evaluar usando la notación λ↑.

   ```racket
   > (define c #f)
   > (+ 1 (+ 2 (+ 3 (+ (let/cc k (set! c k) 4) 5))))
   > (c 10)
   
