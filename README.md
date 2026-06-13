# Sistema-de-Navegaci-n-Aut-noma-y-Mapeo-en-un-Robot-M-vil
Repositorio de diseño CAD, integración mecánica de sensores y análisis estructural para una plataforma de percepción 3D con LiDAR, cámara e IMU.
# Diseño CAD y análisis estructural de plataforma multisensor

## Descripción

Este repositorio contiene los avances relacionados con el diseño mecánico, modelado CAD, integración de sensores y análisis estructural de una plataforma de percepción tridimensional.

El sistema considera la integración física de sensores LiDAR, cámara e IMU. El diseño mecánico debe permitir que los sensores mantengan una posición y orientación definidas, debido a que la transformación y proyección de datos depende de la relación geométrica entre sus respectivos sistemas de coordenadas.

## Objetivo del repositorio

Mantener un registro organizado y actualizado de:

- Modelos CAD de piezas y ensambles.
- Diseño del chasis y estructura principal.
- Soportes para LiDAR, cámara e IMU.
- Distribución y orientación de sensores.
- Archivos para fabricación e impresión 3D.
- Planos de manufactura.
- Análisis estructurales.
- Cambios y versiones del diseño.
- Evidencias del avance del proyecto.

## Alcance personal

Mi participación en el proyecto se enfoca en:

- Diseño CAD de la plataforma.
- Diseño de soportes mecánicos para sensores.
- Integración física de LiDAR, cámara e IMU.
- Distribución de componentes.
- Revisión de interferencias entre piezas.
- Selección de materiales.
- Análisis de esfuerzos y deformaciones.
- Evaluación del factor de seguridad.
- Preparación de archivos para impresión 3D o manufactura.
- Elaboración de planos y documentación técnica.

El desarrollo de programación, procesamiento de datos y algoritmos no forma parte del alcance actual de este repositorio, salvo que se indique posteriormente.

## Sensores considerados

### LiDAR

El LiDAR se utiliza para obtener información tridimensional del entorno mediante nubes de puntos.

El soporte deberá:

- Mantener una orientación fija.
- Evitar obstrucciones en su campo de visión.
- Reducir vibraciones.
- Permitir desmontaje y ajuste.
- Proteger las conexiones eléctricas.

### Cámara

La cámara proporciona información visual del entorno.

El diseño del soporte deberá considerar:

- Campo de visión libre.
- Posición relativa respecto al LiDAR.
- Ajuste de inclinación.
- Rigidez estructural.
- Facilidad de calibración.

### IMU

La IMU registra aceleraciones y orientación de la plataforma.

Su soporte deberá:

- Ubicarse en una zona rígida.
- Reducir vibraciones.
- Mantener identificados sus ejes de referencia.
- Evitar movimientos relativos respecto al chasis.

## Consideraciones geométricas

La ubicación de los sensores debe documentarse mediante:

- Posición en los ejes X, Y y Z.
- Ángulos de orientación.
- Distancia entre sensores.
- Altura respecto a la base.
- Sistema de coordenadas de cada componente.
- Punto de referencia del ensamble.

Estas dimensiones son necesarias para relacionar los sistemas de coordenadas del LiDAR, la cámara y la IMU.

## Análisis estructural

Los análisis estructurales deberán incluir:

- Material asignado.
- Propiedades mecánicas.
- Cargas aplicadas.
- Restricciones.
- Tipo y tamaño de malla.
- Esfuerzo equivalente de von Mises.
- Desplazamiento máximo.
- Deformación.
- Factor de seguridad.
- Interpretación de resultados.

## Formatos de archivo

Se utilizarán los siguientes formatos:

- `.SLDPRT` para piezas de SolidWorks.
- `.SLDASM` para ensambles de SolidWorks.
- `.SLDDRW` para planos de SolidWorks.
- `.STEP` o `.STP` para intercambio de modelos.
- `.STL` para impresión 3D.
- `.PDF` para planos y reportes.
- `.DXF` o `.DWG` para corte o fabricación.

## Control de versiones

Cada modificación importante deberá registrarse indicando:

- Fecha.
- Número de versión.
- Pieza modificada.
- Motivo del cambio.
- Responsable.
- Resultado obtenido.

Ejemplo:

| Versión | Fecha | Modificación | Responsable |
|---|---|---|---|
| V0.1 | / | Modelo conceptual del chasis | Zuriel Espinosa |
| V0.2 | / | Diseño inicial del soporte LiDAR | Zuriel Espinosa |
| V0.3 | % | Ajuste de posición de la cámara | Zuriel Espinosa |

## Estado del proyecto

El proyecto se encuentra actualmente en la etapa de diseño conceptual y definición de la distribución mecánica de los componentes.

## Responsable CAD y análisis estructural

**Zuriel Abisai Espinosa Monroy**

Área de trabajo:

- Diseño CAD.
- Integración mecánica.
- Análisis estructural.
- Documentación para fabricación.
