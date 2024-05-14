# **Gestoreit: Monitoreo de Biodigestor**

Monitoreo de sensores por el protocolo LoRa para el monitoreo de iodigestor en el Estado de Hidalgo

## Descripción

El proyecto consiste en el diseño, desarrollo e implementación de un biodigestor equipado con sensores para monitorear y optimizar el proceso de producción de biogás a partir de residuos orgánicos (de origen animal). El biodigestor aprovechará la descomposición anaeróbica de la materia orgánica para generar biogás, una fuente de energía renovable y limpia, mientras que los sensores permitirán controlar parámetros clave como la temperatura, nivel de humedad y concentración de gases de Co2 y Metano; garantizando una eficiencia óptima y una producción constante de biogás.

## Objetivo

Elaborar un biodigestor que integre tecnologías LoRa y sensores especializados para medir la temperatura, nivel de humedad y concentración de gases de Co2 y Metano; con el fin de monitorear los niveles de calidad del biogás producido, y mejorar su proceso.

## Problematica

La creciente demanda de energía y la necesidad de reducir las emisiones de gases de efecto invernadero han generado un interés creciente en fuentes de energía renovable. Sin embargo, la producción de biogás a partir de residuos orgánicos puede ser ineficiente y poco controlada, lo que limita su viabilidad como una alternativa energética sostenible. Además, la falta de monitoreo y control en los biodigestores tradicionales puede llevar a problemas de operación y mantenimiento, así como a una baja eficiencia en la producción de biogás.

## Visuales

Capturas de pantalla, videos o GIFs que demuestran lo que hace el proyecto y cómo usarlo.

## Empezando 🚀

Por ahora no hay alguna forma de tener nuestro proyecto ya que se encuentra alojado en una maquina virtual, proximamente en un contenedor para el acceso para todos

### Prerrequisitos 📋

Lista de software y herramientas, incluyendo versiones, que necesitas para instalar y ejecutar este proyecto:

- Sistema Operativo: Linux nativo o de forma virtualizada
- Lenguaje de programación: C+
- Base de datos: Mariadb o MySQL
- Zabbix: Frontend, server y agente 2
- PHP

### Instalación 🔧

Puedes ver el siguiente enlace para instalar zabbix y configurarlo de forma exitosa en tu entorno

## Ejecutando las Pruebas ⚙️

Los siguintes comandos son fundamentales para garantizar que esta funcionando de forma datisfactorio

### 1.- Establecer conexion con la maquina virtual, gateway o server de zabbix
```bash
ping 192.0.0.0
```
### 2.- Ver el archivo log de zabbix agent2
Es fundamental para asegurarse de que se configuró de forma satisfactoria el agente zabbix con el gateway, es importante conocer donde esta ubicado
```bash
cat *ubicacion del log de zabbix*
```

### Pruebas de Principio a Fin 🔩

Para la interpretacion de datos debes acceder al dashboard de zabbix desde el navegador de la maquina o de forma remota conectandote en la misma red del dashboard poniendo la ip del ordenador acompañada de /zabbix, ejemplo:
```navegador
192.0.0.1/zabbix
```

## Construido Con 🛠️

- [Ruby](https://www.ruby-lang.org/es/) - El lenguaje utilizado
- [Ruby on Rails](https://rubyonrails.org) - El framework web utilizado
- [Ruby gems](https://rubygems.org) - Gestión de dependencias
- [Postgresql](https://www.postgresql.org) - Sistema de base de datos
- [Bulma IO](https://bulma.io) - Framework de CSS

## Contribuyendo 🖇️

Las contribuciones son lo que hacen a la comunidad de código abierto un lugar increíble para aprender, inspirar y crear. Cualquier contribución que hagas es muy apreciada.

## Soporte

Si tienes algún problema o sugerencia, por favor abre un problema o envianos un correo electronico _______________________.

## Roadmap

Posibles implementaciones al proyecto

- Implementar automatizacion al proyecto
- Agregar mas sensores para el monitoreo
- Optimizacion de codigo de la placa
- Implementacion de big data para el analisis de datos
- implementacion de computo en la nube

## Autores ✒️

- **Alejandro Barrientos Escalante** - _Trabajo inicial_ - [Alejandro Barrientos](https://github.com/beofalejandro)
- **Ulises Porras Rosas** - _Trabajo inicial_ - [Ulises Porras](https://github.com/UlisesPR2101)
- **Elvis Jesus Martinez Lugo** - _Trabajo inicial_ - [Elvis Lugo](https://github.com/Elvis-Lugo)
- **Elizabeth Diaz Oropeza** - _Trabajo inicial_ - [Elizabeth Diaz](https://github.com/Elizabeth-Diaz-Oropeza)

Mira también la lista de [contribuidores]() que han participado en este proyecto.

## Expresiones de Gratitud 🎁

Estamos agradecidos por las contribuciones de la comunidad a este proyecto. Si encontraste cualquier valor en este proyecto o quieres contribuir, aquí está lo que puedes hacer:

- Comparte este proyecto con otros
- Muestra tu agradecimiento diciendo gracias en un nuevo problema.
- sigue al tarabjo de nuestros autores

---

Documentacion hecha con ❤️ por **ESCALIA**
