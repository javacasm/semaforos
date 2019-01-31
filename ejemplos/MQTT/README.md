# Sincronización y control de varios semáforos vía MQTT

1. Semaforo de coches
    * 3 Led de colores

2. Semáfor de peatones 
    * 2 Led de colores
    * 1 Pulsador
    
    
## Secuencia

* Se activa el pulsador Sp -> se envia una petici'on de cambio

* Se activa el ambar en Sc  y un tiempo despu'es de que se active el rojo se envia un mensaje de Verde a Sp

* Se cambia a verde y cuando termina envia un mensaje de Fin
* Sc recibe el mensaje y cambia a Verde



