# UTN-SIM-Final

Se desea simular el funcionamiento de una cantera de tierra y arena a granel. La cantera tiene una
retroexcavadora y una pala frontal.
La retroexcavadora tiene dos funciones, carga camiones de arena a granel desde el pozo (demora
2’±0,3’ por metro cúbico) o de tierra desde el pozo (demora 4’±0,3’ por metro cúbico) o saca arena a
granel desde el pozo (demora 0,4’±0,2’ por metro cúbico) y la coloca en montones para su uso por la
pala frontal.
Mientras haya arena en montones (para el uso de la pala frontal), la prioridad es cargar camiones, si
no hay arena en montones, la prioridad es generar montones, salvo que solo haya camiones que
quieren llevar tierra (en cuyo caso los carga).
La pala frontal se encarga de cargar camiones de arena a granel desde el montón (demora 0,4’±0,2’
por metro cúbico).
Siempre que puedan la retroexcavadora y la pala frontal, no interrumpen la carga de un camión que
han empezado a cargar.
Todos los camiones tienen igual prioridad. Los que quieren tierra solo pueden ser atendidos por la
retroexcavadora. La pala frontal reemplaza a la retroexcavadora, en las funciones de cargar arena a
granel, siempre que puede.
Un 75% de los camiones quiere arena. Las capacidades de los camiones son:

Porcentaje: 		20	40	30	10	
Metros cúbicos: 	4	5	6	7
 
Los camiones llegan a la cantera a intervalos de tiempo que responden a una distribución
exponencial negativa con lambda (λ) = 1.
Cantidad de arena en montones al iniciar: 12 metros cúbicos.
Estado inicial: la retroexcavadora terminará de extraer un metro cúbico dentro de 0,3 minutos. El
próximo camión llega en 1 minuto. No hay camiones en la cantera.
a) Calcular el número de metros cúbicos cargados en los camiones.
b) Determinar el tiempo promedio de espera en cola de los camiones.
c) Determinar el tiempo ocioso de la pala frontal, por falta de arena en montones, o por falta de
camiones.
