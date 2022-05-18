# Tercer experimento con ozm
Este  es el respositorio que constitiuye el tercer experimento con ozm usando datos acoplados temporalmente. El acople temporal nos indica que  hay sincronizacion en el tiempo entre las diferentes medidas entre los diferentes medidores asociados a los electrodésticos de uso común y el medidor comun principal. En este experimento ademas de las medidas habituales usaremos los transitorios de tension , corriente y potencia

## Medidores
El OZM es un medidor monofásico de energía eléctrica (aunque ya existe una versión trifásica), que es además también analizador de calidad de la energía. Este dispositivo, es tanto de código abierto como de hardware abierto, y ha sido desarrollado conjuntamente entre las Universidades de Almería y Granada, contando además con capacidades de IoT, lo cual no sólo nos permite medir una amplia gama de variables eléctricas a una elevada frecuencia de muestreo de 15625 Hz (voltaje, intensidad, potencia activa, potencia reactiva, distorsión armónica total o THD, factor de potencia y armónicos tanto de intensidad [4] como de voltaje y potencia hasta el orden 50), sino que también nos permite capturar y tratar todas esas medidas.

Usamos 6 contadores tipo OZM aplicados  a 5 electromesticos de uso común.

Este es listado de dispositivos:

1- Mains ( contador principal)

2-Hervidor de agua

3-Ventilador

4-Congelador

5- TV

6-Aspiradora



## Medidas

En este experimento especificamos el número de medidas soportadas por los diferentes OZM, como son la potencia activa, aparente y reactiva, la frecuencia, el voltaje, la corriente y el factor de potencia.
En  este experimento añadimos ademas los transitorios de la tensión (50), corriente(50) y potencia (50). Es decir añadimos en total 150  valores más respecto al segundo experimento.

## Nota 
El DS al exceder de 25MB se ha subido comprimido con el winrar 
