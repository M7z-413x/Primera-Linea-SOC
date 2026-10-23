# Primera Línea SOC

Manual de campo para analistas SOC de nivel 1. Explica cómo leer y resolver alertas en CrowdStrike Falcon, Microsoft Defender XDR y Palo Alto Cortex XDR sin adivinar.

**Ver la guía:** https://m7z-413x.github.io/Primera-Linea-SOC/

## Qué incluye

- Qué ve un EDR, un XDR y un SIEM, y dónde buscar lo que a cada uno le falta.
- Cómo se ve una alerta en cada consola: qué campos leer primero, qué botones vas a usar y una consulta de ejemplo en CQL, KQL o XQL.
- 11 familias de alertas (ejecución sospechosa, robo de credenciales, persistencia, movimiento lateral, C2, ransomware, phishing, identidad, evasión, reconocimiento y exfiltración), cada una con qué revisar, cuándo huele a falso positivo y cuándo a ataque.
- Un método de triage en 6 pasos, para usar como checklist.
- Cómo descartar un falso positivo con evidencia, y la diferencia entre falso positivo y verdadero positivo benigno.
- Tabla de eventos de interés: Windows Security, Sysmon, códigos de SigninLogs de Entra ID y telemetría de cada EDR.
- 3 casos prácticos para resolver, con su explicación y consultas listas para copiar.
- 17 laboratorios recomendados según la consola con la que trabajes y el tema que quieras practicar.
- Herramientas de investigación, glosario y una plantilla de nota de cierre.

## Cómo usarla

Es una sola página HTML, sin instalación ni dependencias. Ábrela en el navegador y tenla a la mano durante el turno. El avance del checklist, las respuestas de los casos y tu selección de laboratorios se guardan solo en tu navegador.

Para verla en local, descarga `index.html` y ábrelo con doble clic.

## Datos de los casos

Los casos están basados en patrones que se ven en turno, pero todos los datos son ficticios. Las IPs son de los rangos de documentación del RFC 5737 y los dominios están desactivados con `[.]`. No contienen información de ningún cliente.

## Contribuir

Si encuentras un error, crees que falta un tema o tienes un caso que valga la pena agregar, abre un issue o escríbeme por LinkedIn. La guía crece con lo que se ve en turno.

## Autor

**Alejandro Martínez**
Threat Hunter · Equipo de Advanced Hunting
Security Operations Center · T-Systems México

[LinkedIn](https://www.linkedin.com/in/alejandro-martinez-acu%C3%B1a-321b9b225)

> Nadie nace sabiendo leer un árbol de procesos. Se aprende alerta por alerta, y se aprende más rápido cuando alguien comparte lo que ya sabe.
