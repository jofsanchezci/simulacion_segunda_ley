# Segunda ley de Newton
Abre index.html en un navegador moderno. No requiere instalación ni conexión a internet.

- Ajusta masa, fuerzas y velocidad inicial; pulsa Iniciar.
- Pausa o avanza con pasos de 0,1 s.
- Reiniciar conserva los controles y aplica la velocidad inicial.
- Los casos de estudio cargan valores y reinician el ensayo.
- Se pueden modificar las fuerzas durante la marcha.
- Cambiar la masa representa una comparación idealizada.
- Selecciona posición, velocidad o aceleración para ver su historia temporal.
- Descarga CSV con los datos del ensayo (unidades SI, separador coma, decimal punto).

Modelo: F_neta = F_derecha - F_izquierda; a = F_neta/m.
En cada intervalo se integra exactamente la aceleración constante:
x_nuevo = x + v·dt + a·dt²/2; v_nueva = v + a·dt.
Pista sin rozamiento, peso y normal equilibrados; duración máxima 20 s.
La cámara acompaña al carrito en una pista ilimitada. No hay rebotes.
El tiempo se detiene al ocultar la pestaña; con baja tasa de fotogramas puede avanzar más lento que el reloj real.

Actividades: comparar 5 y 10 kg bajo 10 N; estudiar fuerzas equilibradas con v inicial no nula; predecir el instante de detención y la inversión del movimiento bajo una fuerza opuesta.
