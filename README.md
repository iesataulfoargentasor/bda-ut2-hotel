# Práctica Integradora de la UT2

Copia de trabajo del grupo hotelero de Cantabria para el módulo **BDA** (RA2). El enunciado está en la web del módulo:

https://iesataulfoargentasor.github.io/bda_2026_2027/ut2/practica-integradora/

Si estáis leyendo esto en `iesataulfoargentasor/bda-ut2-hotel`, esta carpeta es la **plantilla**. Cread vuestra copia en vuestra cuenta:

1. Abrid https://github.com/iesataulfoargentasor/bda-ut2-hotel/generate
2. En **Owner** elegid vuestro usuario, no `iesataulfoargentasor`.
3. Dejad el nombre **`bda-ut2-hotel`**.
4. Pulsad **Create repository**.

La dirección tiene que quedar `github.com/VUESTRO_USUARIO/bda-ut2-hotel`. Puede ser pública o privada. Si es privada, añadid como colaborador al usuario que indique el profesor y comprobad que acepta la invitación.

## Quién entrega

| Campo | Valor |
| --- | --- |
| Nombre | |
| Usuario de GitHub | |
| URL de este repositorio | |

## Qué hay que rellenar

| Archivo | Qué dejáis escrito |
| --- | --- |
| [diseno/combinacion.md](diseno/combinacion.md) | Qué pieza guarda, calcula, atiende recepción, copia y crece |
| [evidencias/](evidencias/) | Un archivo por bloque, con predicción, operación, salida e interpretación |
| [scripts/](scripts/) | Trabajos, consultas o programas que hayáis ejecutado |
| [datos/generar_cierre.py](datos/generar_cierre.py) | Genera el bruto en `datos/bruto/` con la semilla 2026 |
| [datos/totales_esperados.json](datos/totales_esperados.json) | Totales del perfil de aula. No los cambiéis para forzar una coincidencia |
| [avances/](avances/PLANTILLA.md) | Una nota al cerrar cada sesión |

Marcad el avance:

- [ ] La copia está en mi cuenta
- [ ] La combinación está escrita
- [ ] Bloque 1. Carga contrastada
- [ ] Bloque 2. Cierre local y repartido
- [ ] Bloque 3. Fallo en el histórico
- [ ] Bloque 4. Recepción con copias
- [ ] Bloque 5. Módulo añadido
- [ ] Bloque 6. Pregunta posterior
- [ ] URL y commit entregados en Moodle

## Qué no se sube

El bruto generado ronda 1 GB y se queda en el equipo, dentro de `datos/bruto/` o `datos/generado/`. Tampoco se suben salidas grandes, contraseñas ni un `.env`. Las evidencias llevan el extracto necesario para contrastar el total.

GitHub guarda el expediente. No ejecuta el clúster.

## Cómo entregar

En Moodle se entregan la **URL de este repositorio** y el **identificador completo del commit** que debe evaluarse. Comprobad en el navegador que ese commit está en GitHub. Un commit que solo exista en el portátil no queda entregado.

Al cerrar una sesión, copiad [avances/PLANTILLA.md](avances/PLANTILLA.md) a `avances/sesion-01.md`, `sesion-02.md`, etc., y registrad el cambio con un mensaje reconocible, por ejemplo `Bloque 1: carga contrastada con los totales esperados`.

## Organización

```text
bda-ut2-hotel/
├── README.md
├── diseno/combinacion.md
├── evidencias/bloque-01-dos-almacenes.md
├── evidencias/bloque-02-cierre-repartido.md
├── evidencias/bloque-03-fallo-historico.md
├── evidencias/bloque-04-recepcion.md
├── evidencias/bloque-05-crecimiento.md
├── evidencias/bloque-06-pregunta-posterior.md
├── scripts/
├── datos/                  # el bruto no se sube
├── salidas/                # las salidas grandes no se suben
└── avances/
```

La plantilla es material del IES Ataúlfo Argenta para el curso 2026/2027 y puede reutilizarse bajo [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). El trabajo que añadís en vuestra copia es vuestro.
