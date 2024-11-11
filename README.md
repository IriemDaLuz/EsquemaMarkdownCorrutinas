# Corrutinas

## 1. ¿Qué son las Corrutinas?
- Son funciones que pueden pausar su ejecución y reanudarla posteriormente.
- Permiten realizar tareas de manera concurrente sin crear múltiples hilos de ejecución.
- Utilizadas principalmente para mejorar la eficiencia y realizar tareas asíncronas.
  
- ## 2. Características Principales
- **Estado persistente**: Conservan su estado entre pausas.
- **Suspensión y reanudación**: Pueden suspenderse y continuar desde el punto donde se quedaron.
- **Concurrencia**: Permiten la concurrencia sin bloquear el hilo principal.

## 3. Ventajas de Usar Corrutinas
- **Eficiencia**: Ejecutan tareas concurrentes sin bloquear el programa.
- **Reducción de consumo de memoria**: Evitan el uso de múltiples hilos.
- **Código más limpio**: Simplifican el manejo de tareas asíncronas.
