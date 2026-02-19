# Propuesta de contenido para entrega

## Actores (AS-IS)
### Principales
- Conductor/Estudiante (inicia el proceso de salida)
- Personal de caseta / punto de venta
- Personal de Círculo K (si aplica)
- Policía/Seguridad en salida

### Soporte
- Terminal/sistema de cobro (entidad específica)
- Reglas institucionales de acceso/salida

## Flujo principal (sin fallas)
1. Inicia intención de salida.
2. Conduce hacia salida.
3. Verifica si ya cuenta con boleto.
4. Si no tiene, busca punto de venta y compra.
5. Conduce hacia salida.
6. Entrega boleto a seguridad.
7. Se valida boleto.
8. Sale del campus.

## Decisiones clave
- ¿Ya tiene boleto?
- ¿Punto de venta abierto?
- ¿Hay fila?
- ¿Aceptan método de pago?
- ¿Terminal/cobro funciona?
- ¿Hay fila en salida?
- ¿Boleto válido/legible?

## Pain points (con evidencia)
1. Dependencia de punto de venta abierto
   - Evidencia: nodo “¿Punto de venta abierto?”
   - Consecuencia: retraso/desvío

2. Congestión por filas en compra
   - Evidencia: “¿Hay fila?” -> “Esperar en fila”
   - Consecuencia: mayor tiempo de salida

3. Rechazo de método de pago
   - Evidencia: “¿Aceptan su método de pago?” / “Tarjeta rechazada”
   - Consecuencia: reproceso y demora

4. Falla de terminal/cobro
   - Evidencia: “¿Terminal/cobro funciona?”
   - Consecuencia: interrupción del flujo

5. Fila vehicular en salida
   - Evidencia: “¿Hay fila en la salida?”
   - Consecuencia: cuello de botella

6. Boleto no válido/no legible
   - Evidencia: “¿Boleto válido/legible?”
   - Consecuencia: incidencia y retrabajo
